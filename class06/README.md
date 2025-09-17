# 431 Class 06: 2025-09-18

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
06 | 2025-09-18 | **[Slides 06](https://thomaselove.github.io/431-slides-2025/class06.html)** | **[Word 06](https://thomaselove.github.io/431-slides-2025/class06w.docx)** | **[Code 06](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class06.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

![](https://imgs.xkcd.com/comics/assigning_numbers.png) [Source](https://xkcd.com/2610)

## Announcements

1. If you are asking for help from us through **431-help**, provide your **complete Quarto file**, as well as a description (and screenshot) of the problem you're having.
    - We cannot diagnose a problem outside of Zoom without a Quarto file, and often we'll want to see the Quarto file on Zoom, too.
    - Don't just show us the piece of your Quarto file where you think the problem is - we need the whole thing so we can try to duplicate your problem as exactly as possible.
2. Things I've updated since last class...
    - I've updated [the Love-431.R script](https://raw.githubusercontent.com/THOMASELOVE/431-data/refs/heads/main/data/Love-431.R) on our 431-data page and everywhere else to address an extra comma.
    - [Slide 41 from Class 05](https://thomaselove.github.io/431-slides-2025/class05.html#/bayesian-fit) is, I think, fixed online now. I emailed you all a copy if it's still an issue for you.
    - I changed a phrase in [Section 5.4.1 of the Course Text](https://thomaselove.github.io/431-book/05_paired.html#using-a-linear-model) which was poorly edited previously, abnout the t statistic and p value, which we're not yet interested in.
3. To get access to the **Robbins Building**:
    - If you are affiliated with a degree program in PQHS, emailing the appropriate admin is a quick way to address ID access issues too.
        - Epi/Bio PhD, Informatics MS and PhD, MS biostatistics: Kim Krajcovic (kxk917@case.edu)
        - CTS PhD, CRSP: Lauren Mazzagatti (lxm565@case.edu)
        - MPH: Tara Hannum (tmh123@case.edu).
    - Or visit the Security Office on the ground floor of the BRB building.
5. The **Answer Sketch for Lab 1** will go live on our Shared Google Drive in the early afternoon on Friday. I will alert you by email when it is live. The Answer Sketch includes a grading rubric.
    - If I ask you to (for example) report a result to one decimal place, that doesn't mean you have to produce output which is limited to one decimal place. You could, for example, have output with more decimals, but your sentence describing your answer should list a correctly rounded result.
6. "[See 2025 Ohio school report card grades for every district in the state](https://www.cleveland.com/news/2025/09/see-2025-ohio-school-report-card-grades-for-every-district-in-the-state.html)" published 2025-09-15 at [Cleveland.com](https://www.cleveland.com/news/2025/09/see-2025-ohio-school-report-card-grades-for-every-district-in-the-state.html)

## Minute Paper after Class 05 Feedback

I **will add a link here** to my feedback on the Minute Paper after Class 05.

## Ten More Interesting/Fun Facts about Students in this semester's 431 class

1. I love to work out and I have my personal training and barre certification!
2. I moved to Cleveland a month ago and already got 5 stitches :))
3. I name my pets after [cnidarians](https://en.wikipedia.org/wiki/Cnidaria).
4. I recently started brewing my own [kombucha](https://en.wikipedia.org/wiki/Kombucha).
5. I somehow manage to run cancer research projects, study for [Step exams](https://www.usmle.org/step-exams), and raise a Boston Terrier puppy who thinks she’s my boss. Honestly, the puppy is the toughest project.
6. I started skiing when I was 2 and a half years old.
7. I studied in Ireland for a semester in undergrad.
8. I used to practice [aerial dancing](https://en.wikipedia.org/wiki/Aerial_dance).
9. I was on [CWRUbotix](https://www.cwrubotix.org/)'s product demo team for the [MATE ROV (underwater drone) World Championship](https://materovcompetition.org/) a couple of months ago when we won first overall in the university class.
10. I work at Case, primarily dissecting fresh cadavers.

These come from the Welcome to 431 survey - some more results from that survey [can be found here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/class02/welcome_report.md).

## Reminders (see [the Calendar](https://thomaselove.github.io/431-2025/calendar.html) for the final word on all deadlines)

- Attend [TA office hours](https://thomaselove.github.io/431-2025/contact.html#ta-office-hours) or email us at `431-help at case dot edu` if you need help. Send your entire Quarto file **and** a description of your problem if you're asking a question about R via email.     
- Before Class 7 (2025-09-23)
    - Work on [Lab 2](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab2), which is due Wednesday 2025-09-24 at noon.
    - Finish the [Project A data work](https://thomaselove.github.io/431-projectA-2025/) and get started on the [Project A Plan](https://thomaselove.github.io/431-projectA-2025/).
    - Read *The Art of Statistics* by David Spiegelhalter, Chapter 5 (we'll read Chapter 4 later, you can read it now if you like)
    - Read [R for Data Science](https://r4ds.hadley.nz/), the "Visualize" sections, focusing on sections 10-11
    - Review the [Lab X instructions](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX) and perhaps get started.
- Next Week
    - [Minute Paper](https://github.com/THOMASELOVE/431-minute-2025/tree/main) after Class 07 will be posted in time for Class on Tuesday, and is due Wednesday at noon.
    - Remember that [Lab 2](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab2) is also due on Wednesday 2025-09-24 at noon.
