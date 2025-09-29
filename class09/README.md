# 431 Class 09: 2025-09-30

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
09 | 2025-09-30 | **[Slides 09](https://thomaselove.github.io/431-slides-2025/class09.html)** | **[Word 09](https://thomaselove.github.io/431-slides-2025/class09w.docx)** | **[Code 09](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class09.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

![](https://imgs.xkcd.com/comics/data_trap.png) Source: [XKCD](https://xkcd.com/2582/)

## Announcements

1. Changes and fixes made since last class (with my thanks to alert students as applicable):
    - I have edited the [Calendar page's descriptions](https://thomaselove.github.io/431-2025/calendar.html) of classes 8-10 to better reflect what we're actually doing.
    - I added the `DescTools` package to our [R packages installation list](https://github.com/THOMASELOVE/431-packages/tree/main). We'll use it today.
        - See <https://andrisignorell.github.io/DescTools/> for more. In particular, [this material on post-hoc tests](https://andrisignorell.github.io/DescTools/reference/PostHocTest.html) after ANOVA.
    - I also added today's `eurocare.csv` data file to the [431-data page](https://github.com/THOMASELOVE/431-data).
    - I updated (and shortened) the [Class 08 Slides](https://thomaselove.github.io/431-slides-2025/class08.html) including [the Quarto code](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class08.qmd) and [the Word version](https://thomaselove.github.io/431-slides-2025/class08w.docx). Specifically, I edited Slides 34-42 from the [Class 08 Slides](https://thomaselove.github.io/431-slides-2025/class08.html) to reflect correct simultaneous CIs for the Bonferroni method, and to use `stan_glm()` for the Bayesian ANOVA fit now found in slide 42. 
    - I have edited [Section 9.9 of the Course Book](https://thomaselove.github.io/431-book/09_transmore.html#pairwise-comparisons-of-means) to reflect correct simultaneous CIs for the Bonferroni and Tukey methods as will be presented in today's slides. I also added the `DescTools` package to [Appendix A](https://thomaselove.github.io/431-book/package_info.html) in the Book.
    - I updated the [Project A Plan instructions](https://thomaselove.github.io/431-projectA-2025/plan.html) to consistently indicate **3089** (not 3088) rows and **95** (not 90) columns as the size of the original `chr_2025_raw` tibble in [Section 5.2](https://thomaselove.github.io/431-projectA-2025/plan.html#section-2.-data-ingest) and [Section 7.1.4.](https://thomaselove.github.io/431-projectA-2025/plan.html#element-d.-plan-section-2.-data-ingest)
2. Your [Project A Plan](https://thomaselove.github.io/431-projectA-2025/plan.html) is due tomorrow (Wednesday 2025-10-01) at noon. Please ensure that you submit all required elements to [Canvas](https://canvas.case.edu/).
    - [What you should be sending](https://thomaselove.github.io/431-projectA-2025/plan.html#the-deliverables) is
        - the analytic tibble (as an `.Rds` data file) you developed following the Data page instructions,
        - a Quarto (`.qmd`) file containing your data management work, and the other elements required in the Project A Plan, and
        - the HTML result of rendering your Quarto file. The resulting HTML document will have 15 sections.        - 
    - If you are working with a **partner**, then **exactly one** of you should submit the materials listed above to Canvas, **and the other partner** should submit a text document (Word or PDF is fine) uploaded to Canvas that reads: "My name is [YOUR NAME]. I am working on Project A with [INSERT FULL NAME OF YOUR PARTNER], and they will submit the materials for the Plan."
    - Be sure to use spell check (just hit F7) on your Quarto file before rendering it, and review the HTML result carefully to ensure that no residual warnings or error messages remain in the document.
    - Be sure that your Plan includes your name (names if you are working with a partner) as the author in Quarto, and thus in HTML, as well as a [proper title](https://thomaselove.github.io/431-projectA-2025/plan.html#project-a-plan-title).
    - Again, [here are the details](https://thomaselove.github.io/431-projectA-2025/plan.html#grading-the-project-a-plan) on what we will be checking when we assess your [Project A Plan](https://thomaselove.github.io/431-projectA-2025/plan.html).
3. There is no [Minute Paper](https://github.com/THOMASELOVE/431-minute-2025) this week. The next Minute Paper is after Class 11.
4. [Lab 3](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab3) is the next assignment after the Project A Plan. It's due next Wednesday 2025-10-08. You have everything you need from me to do it now.

## Favorite Movies

Here's our [second breakout activity](https://github.com/THOMASELOVE/431-classes-2025/blob/main/movies/class09.md). It uses the `movies_2025-09-30` version of the data found on our Shared Drive.

## Theming ggplots

1. The main ggplot2 themes are demonstrated at <https://ggplot2.tidyverse.org/reference/ggtheme.html>. I use `theme_bw()` and `theme_light()`, mostly.
2. The `see` package within the **easystats** ecosystem adds [several other plot themes](https://easystats.github.io/see/reference/index.html#themes). I like `theme_modern()` and `theme_lucid()`, personally.
3. If you want to go even further, the [ggthemr package](https://github.com/Mikata-Project/ggthemr), the [ggthemes package](https://jrnold.github.io/ggthemes/) and the [hrbrthemes package](https://github.com/hrbrmstr/hrbrthemes) each provide attractive options.

------

## Reminders

1. Your [Project A Plan](https://thomaselove.github.io/431-projectA-2025/plan.html) is due tomorrow (Wednesday 2025-10-01) at noon. Please ensure that you submit all three required elements (.Rds, .qmd and .html) to [Canvas](https://canvas.case.edu/) by that deadline.
2. [Lab 3](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab3) is the next assignment after the Project A Plan.
3. We hope that by Class 11 (next Tuesday 2025-10-07) you'll have caught up on your reading, including Chapter 8 of Spiegelhalter.
