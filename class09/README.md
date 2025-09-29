# 431 Class 09: 2025-09-30

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
09 | 2025-09-30 | **[Slides 09](https://thomaselove.github.io/431-slides-2025/class09.html)** | **[Word 09](https://thomaselove.github.io/431-slides-2025/class09w.docx)** | **[Code 09](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class09.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Changes and fixes made since last class (with my thanks to the relevant alert students):
    - I updated the [Class 08 Slides](https://thomaselove.github.io/431-slides-2025/class08.html) including [the Quarto code](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class08.qmd) and [the Word version](https://thomaselove.github.io/431-slides-2025/class08w.docx) in two main ways:
        - **I have edited** Slides 34-41 and 45-46 from the [Class 08 Slides](https://thomaselove.github.io/431-slides-2025/class08.html) to reflect correct simultaneous CIs for the Bonferroni method as well.
        - We have new slides 43-46, to use `stan_glm()` for the Bayesian fit. This changes results shown in slides 43-44 and 46, and also requires the addition of a line of code to the `mutate()` statement in defining the `con_bay` tibble in slide 45.
    - I updated the [Project A Plan instructions](https://thomaselove.github.io/431-projectA-2025/plan.html) to consistently indicate **3089** (not 3088) rows and **95** (not 90) columns as the size of the original `chr_2025_raw` tibble in [Section 5.2](https://thomaselove.github.io/431-projectA-2025/plan.html#section-2.-data-ingest) and [Section 7.1.4.](https://thomaselove.github.io/431-projectA-2025/plan.html#element-d.-plan-section-2.-data-ingest)
    - **I have edited** [Section 9.9 of the Course Book](https://thomaselove.github.io/431-book/09_transmore.html#pairwise-comparisons-of-means) to reflect correct simultaneous CIs for the Bonferroni and Tukey methods as will be presented in today's slides
    - I have edited the [Calendar page's descriptions](https://thomaselove.github.io/431-2025/calendar.html) of classes 8-10 to better reflect what we're actually doing.
2. Your Project A Plan is due tomorrow (Wednesday 2025-10-01) at noon. Please ensure that you submit all required elements to [Canvas](https://canvas.case.edu/).
3. There is no [Minute Paper](https://github.com/THOMASELOVE/431-minute-2025) this week. The next Minute Paper is after Class 11.
4. [Lab 3](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab3) is the next assignment after the Project A Plan. It's due next Wednesday 2025-10-08. You have everything you need from me to do it now.

## Theming ggplots

1. The main ggplot2 themes are demonstrated at <https://ggplot2.tidyverse.org/reference/ggtheme.html>. I use `theme_bw()` and `theme_light()`, mostly.
2. The `see` package within the **easystats** ecosystem adds [several other plot themes](https://easystats.github.io/see/reference/index.html#themes). I like `theme_modern()` and `theme_lucid()`, personally.
3. If you want to go even further, the [ggthemr package](https://github.com/Mikata-Project/ggthemr), the [ggthemes package](https://jrnold.github.io/ggthemes/) and the [hrbrthemes package](https://github.com/hrbrmstr/hrbrthemes) each provide attractive options.

------

## Reminders

1. Your Project A Plan is due tomorrow (Wednesday 2025-10-01) at noon. Please ensure that you submit all required elements to [Canvas](https://canvas.case.edu/).
2. [Lab 3](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab3) is the next assignment after the Project A Plan.
3. We hope that by Class 11 (next Tuesday 2025-10-07) you'll have caught up on your reading, including Chapter 8 of Spiegelhalter.
