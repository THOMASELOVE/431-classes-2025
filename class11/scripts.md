## The `twobytwo()` function from [the `Love-431.R` script](https://github.com/THOMASELOVE/431-data/blob/main/data/Love-431.R)

The `twobytwo()` function is designed to take information from an existing 2x2 table and run [the Epi package's](https://bendixcarstensen.com/Epi/) **twoby2()** command to summarize key analytic results. Given a table (in *standard epidemiological format*) that looks like this:

-- | Outcome 1 | Outcome 2
-----: | :----:  | :----:
Exposure 1 | A | B
Exposure 2 | C | D

the `twobytwo()` function would be called, generically, with: 

```
twobytwo(A, B, C, D, "Exposure 1 Name", "Exposure 2 Name", "Outcome 1 Name", "Outcome 2 Name", conf.level = 0.95)
```

Note that the **Epi package** must be loaded for this function to work.

As an illustration, consider the following table:

-- | Outcome 1 | Outcome 2
-----: | :----:  | :----:
Exposure 1 | 100 | 50
Exposure 2 | 40 | 30

```
> twobytwo(100, 50, 40, 30, "Exp1", "Exp2", "Out1", "Out2", conf.level = 0.95)

2 by 2 table analysis: 
------------------------------------------------------ 
Outcome   : Out1 
Comparing : Exp1 vs. Exp2 

     Out1 Out2    P(Out1) 95% conf. interval
Exp1  100   50     0.6667    0.5875   0.7374
Exp2   40   30     0.5714    0.4537   0.6816

                                   95% conf. interval
             Relative Risk: 1.1667    0.9248   1.4717
         Sample Odds Ratio: 1.5000    0.8377   2.6858
Conditional MLE Odds Ratio: 1.4971    0.8008   2.7915
    Probability difference: 0.0952   -0.0394   0.2315

             Exact P-value: 0.1791 
        Asymptotic P-value: 0.1725 
------------------------------------------------------
```

The script follows:

```
`twobytwo` <-
  function(a,b,c,d, 
           namer1 = "Row1", namer2 = "Row2", 
           namec1 = "Col1", namec2 = "Col2", 
           conf.level = 0.95)
  {
    .Table <- matrix(c(a, b, c, d), 2, 2, byrow=T, 
                     dimnames=list(c(namer1, namer2), 
                                   c(namec1, namec2)))
    Epi::twoby2(.Table, alpha = 1 - conf.level)
  }
```

## The `saifs_ci()` function from [the `Love-431.R` script](https://github.com/THOMASELOVE/431-data/blob/main/data/Love-431.R)

The `saifs_ci()` function calculates a *single augmentation with one failure and one success* estimated confidence interval for a proportion, based on a sample of size *n* which contains *x* successes. Useful references include:

- Reed JF (2007) [Better Binomial Confidence Intervals](https://digitalcommons.wayne.edu/cgi/viewcontent.cgi?article=1132&context=jmasm) J Modern Applied Stat Methods 6:1.
- Gelman A (2007) [(y+2)/(n+4) instead of y/n](https://statmodeling.stat.columbia.edu/2007/05/15/y1n2_instead_of/)

As an illustration, suppose we have 20 "successes" in a sample of 100 observations.

```
> saifs_ci(x = 20, n = 100, conf.level = 0.95)
# A tibble: 1 × 6
  sample_x sample_n sample_p lower upper conf_level
     <dbl>    <dbl>    <dbl> <dbl> <dbl>      <dbl>
1       20      100      0.2 0.119 0.288       0.95
```

Estimates with and without the augmentation will be generally comparable, so long as:
- the sample size is more than, say, 30 subjects, and/or
- the sample probability of the outcome is between 0.1 and 0.9

```
`saifs_ci` <- 
  function(x, n, conf.level=0.95, dig=3)
  {
    p.sample <- round(x/n, digits=dig)
    
    p1 <- x / (n+1)
    p2 <- (x+1) / (n+1)
    
    var1 <- (p1*(1-p1))/n
    se1 <- sqrt(var1)
    var2 <- (p2*(1-p2))/n
    se2 <- sqrt(var2)
    
    lowq = (1 - conf.level)/2
    tcut <- qt(lowq, df=n-1, lower.tail=FALSE)
    
    lower.bound <- round(p1 - tcut*se1, digits=dig)
    upper.bound <- round(p2 + tcut*se2, digits=dig)
    tibble(
      sample_x = x,
      sample_n = n,
      sample_p = p.sample,
      lower = lower.bound,
      upper = upper.bound,
      conf_level = conf.level
    )
  }
```

The Agresti-Coull method, for example, uses a similar scheme, but with a varying size of augmentation (adding Z successes and Z failures to the data, where Z is the appropriate quantile for a standard Normal distribution (1.96 for a 95% CI)). There's an argument that Agresti-Coull is now the best choice for estimating a proportion based on a single sample, and as a result, it's the main one I use. One way to get that CI uses the **mosaic** package's `binom.test()` function:

```
mosaic::binom.test(x = 20, n = 100, p = 0.5, conf.level = 0.95, ci.method = "agresti-coull")

	Exact binomial test (Agresti-Coull CI)

data:  20 out of 100
number of successes = 20, number of trials = 100, p-value = 1.116e-09
alternative hypothesis: true probability of success is not equal to 0.5
95 percent confidence interval:
 0.1326077 0.2895884
sample estimates:
probability of success 
                   0.2 
```
