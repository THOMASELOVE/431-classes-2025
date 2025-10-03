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

