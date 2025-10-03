# 431 Class 11: 2025-10-07

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
11 | 2025-10-07 | **[Slides 11](https://thomaselove.github.io/431-slides-2025/class11.html)** | **[Word 11](https://thomaselove.github.io/431-slides-2025/class11w.docx)** | **[Code 11](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class11.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. There will be a Minute Paper after Class 11. Details to come.
2. I fixed the [Class 10 slides, Word and Quarto files](https://github.com/THOMASELOVE/431-classes-2025/tree/main/class10#todays-slides) to correct the sample size (*n* = 847, not 846) after dropping cases with missing data.
3. More to come.

## The `twobytwo()` function from the `Love-431.R` script

```
`twobytwo` <-
  function(a,b,c,d, 
           namer1 = "Row1", namer2 = "Row2", 
           namec1 = "Col1", namec2 = "Col2", 
           conf.level = 0.95)
    # build 2 by 2 table and run Epi library's twoby2 command to summarize
    # from the row-by-row counts in a cross-tab
    # upper left cell is a, upper right is b, 
    # lower left is c, lower right is d
    # names are then given in order down the rows then across the columns
    # use standard epidemiological format: 
    # outcomes in columns, treatments in rows
  {
    .Table <- matrix(c(a, b, c, d), 2, 2, byrow=T, 
                     dimnames=list(c(namer1, namer2), 
                                   c(namec1, namec2)))
    Epi::twoby2(.Table, alpha = 1 - conf.level)
  }
```

## The `saifs_ci()` function from the `Love-431.R` script

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

