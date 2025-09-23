# 431 Class 07: 2025-09-23

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
07 | 2025-09-23 | Coming soon | Coming soon | Coming soon | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

<!-- 

07 | 2025-09-23 | **[Slides 07](https://thomaselove.github.io/431-slides-2025/class07.html)** | **[Word 07](https://thomaselove.github.io/431-slides-2025/class07w.docx)** | **[Code 07](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class07.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

-->

## Announcements

1. There is a Minute Paper after Class 07, due Wednesday 2025-09-24 at noon, and which I will link to as soon as it's available.
2. [Lab 2](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab2) is also due Wednesday 2025-09-24 at noon.
3. Corrections since last time:
    - I added material to [Project A Data Task 6](https://thomaselove.github.io/431-projectA-2025/data.html#data-task-6.-re-order-variables-drop-extraneous-factor-levels-then-save-the-final-chr_2025-tibble) about applying the `droplevels()` function to your tibble just before you save it. We apply the `droplevels()` function to a tibble to remove all unused levels from your factors, so, for instance, instead of R thinking your tibble has 51 different `state` values (including `DC`), it will correctly understand that you have only 6.
    - Somehow, I'd deleted the [`431-projectA-chr_2019.csv`](https://raw.githubusercontent.com/THOMASELOVE/431-data/refs/heads/main/data/431-projectA-chr_2019.csv) file from our [431-data page](https://github.com/THOMASELOVE/431-data), which you need for Project A. It's back now.
    - I fixed the [Project A Plan section 5.2](https://thomaselove.github.io/431-projectA-2025/plan.html#section-2.-data-ingest) to indicate that the initial tibble should have 3089 rows and 95 columns.
    - I fixed Task 2.2b in [Lab 2](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab2) to indicate that there are four approaches, not three, as I'd originally written.
    - I fixed the typo in [slide 15 from Class 06](https://thomaselove.github.io/431-slides-2025/class06.html#/what-to-do-about-outliers-13) to show the correct bootstrap confidence interval (0.19, 0.47).
    - I fixed a broken link on the [main page for Lab X](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX), and then some broken links within the [Lab X instructions](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX).
    - I fixed errors in the [Course Text, Chapter 8](https://thomaselove.github.io/431-book/08_moregroups.html), specifically in [section 8.3.2](https://thomaselove.github.io/431-book/08_moregroups.html#estimate-means-at-each-level-from-model) and in [section 8.3.5](https://thomaselove.github.io/431-book/08_moregroups.html#pairwise-comparisons-using-holm-method) where the numbers in the text didn't match the numbers in the output. They should, now.
5. Because conversion of Quarto files to Word does not allow the use of `kable()`, I have deliberately deleted `kable()` calls when building the Word documents for Class Slides this semester. Sorry about that.
6. MediaVision will be video-taping (at least some of) our Class 09 on 2025-09-30 for use in a video about our MS program in Biostatistics.
7. Brief introductory videos (from Task 5 in Lab 1) from each of you are now posted to our Shared Google Drive. Please feel encouraged to learn a little more about the very talented people who are also in this room.
8. **More to come**.

## Reminders to Dr. Love

1. We will discuss Section 12 of the Project A Plan - building your research questions today.
2. We will discuss how to interpret confidence and credibility intervals today in more detail.

## Final Ten Interesting/Fun Facts about Students in this semester's 431 class

1. I'm a former nutritionist. I enjoy rock climbing!
2. I’m a passionate Manchester United fan and often stayed up until 3 AM to watch live matches while growing up in India.
3. I’m always curious. I genuinely enjoy learning new things, even if they seem small. It keeps life exciting, and I think there’s always something new to explore.
4. I'm from Connecticut.
5. I've been playing tennis since I was 5 years old and played on my collegiate team in undergrad.
6. I’ve gone skydiving twice; for my next thrill, I’m taking PQHS 431.
7. My favorite hobby is knitting and I've been doing that for almost 20 years at this point. During the early days of the pandemic I picked up quilting as another hobby and have been enjoying that as well.
8. My go-to fun fact about myself is that in 2011 I bicycled from Portland, Maine to Santa Barbara, California. I was part of a group and for a charity cause, but I rode every inch!
9. My house has six refrigerators.
10. I dance in my free time.

These come from the Welcome to 431 survey - some more results from that survey [can be found here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/class02/welcome_report.md).

## Reminders (see [the Calendar](https://thomaselove.github.io/431-2025/calendar.html) for the final word on all deadlines)

- Attend [TA office hours](https://thomaselove.github.io/431-2025/contact.html#ta-office-hours) or email us at `431-help at case dot edu` if you need help.     
- [Lab 2](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab2) is also due on Wednesday 2025-09-24 at noon.
- [Minute Paper](https://github.com/THOMASELOVE/431-minute-2025/tree/main) after Class 07 will be posted in time for Class on Tuesday, and is due Wednesday at noon.
