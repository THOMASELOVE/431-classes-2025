# 431 Class 20: 2025-11-11

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
20 | 2025-11-11 | **[Slides 20](https://thomaselove.github.io/431-slides-2025/class20.html)** | **[Word 20](https://thomaselove.github.io/431-slides-2025/class20w.docx)** | **[Code 20](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class20.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

![](https://imgs.xkcd.com/comics/health_stats.png)  [Source](https://xkcd.com/2581)

## Announcements

1. I sent **431 Project A Feedback** to you at your CWRU email between 3 and 4 PM on Friday 2025-11-07. Thanks for your patience.
2. My [feedback on your questions and comments](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/self_eval_questions.md) from the **Project A Self-Evaluation** is available [here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/self_eval_questions.md).
3. The [Lab 5](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab5) Answer Sketch and Grading Rubric is now on our Shared Drive.
4. **Feedback on Lab 5 will be posted to our Shared Drive soon.**
5. **Lab X**: Several students have now [completed Lab X](https://github.com/THOMASELOVE/431-labs-2025/blob/main/labX/websites_2025.md). Here are [the instructions](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX). Don't leave this to the last couple of days!
6. **Project B instructions**: Thanks to an alert student, I corrected a mistake in [this part of the "Using NHANES data" section](https://thomaselove.github.io/431-projectB-2025/data2.html#which-variables-subjects-should-i-use) of the [Project B instructions](https://thomaselove.github.io/431-projectB-2025/). That location now accurately reflects the number of NHANES 8/2021 - 8/2023 subjects who are **below** the age of 80, as 8,335, while 525 subjects are 80 years or older.
7. **Course Book**: I updated the [Course Book](https://thomaselove.github.io/431-book/) to include a more complete Chapter 21, which will be the last Chapter this year. If you find any typos, or have any questions about the Book, please let me know.
8. **New R and RStudio Versions**: I upgraded R to version **4.5.2.** We will accept work done with either 4.5.1 or 4.5.2 for the rest of 431. I also upgraded RStudio to version **2025.09.2+418**. We will accept work done with any 2025 version of RStudio for the rest of 431.
    - See [our software page](https://thomaselove.github.io/431-2025/software.html) for reminders on how to install of R and RStudio.
9. **New (to us) R package** I added [the gtExtras package](https://jthomasmock.github.io/gtExtras/index.html) to our [list of packages to install](https://github.com/THOMASELOVE/431-packages/tree/main). I will use this next time, I believe.

## Due Tomorrow (Wednesday 2025-11-12) at noon

1. There is a [Minute Paper after Class 20](https://bit.ly/431-2025-minute-20) due **tomorrow** (Wednesday 2025-11-12) at noon.
2. The [Project B Registration Form](https://bit.ly/431-projB-registration-2025) is also due **tomorrow** (Wednesday 2025-11-12) at noon. Please get this in on time. Here are [instructions for Registering Project B](https://thomaselove.github.io/431-projectB-2025/register.html).
    - Dr. Love responds to these forms as they are submitted, and [tracks submissions here](https://github.com/THOMASELOVE/431-classes-2025/tree/main/projectB).
    - The schedule for Project B presentations will be available [here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md) on Friday 2025-11-14.

---

## References from Today's Slides (Class 20)

- [The naniar package](https://naniar.njtierney.com/) documentation includes [this `replace_with_na()` vignette](https://cran.r-project.org/web/packages/naniar/vignettes/replace-with-na.html).
- The [tidyr package on `replace_na()`](https://tidyr.tidyverse.org/reference/replace_na.html). The [tidyr package](https://tidyr.tidyverse.org/) is part of [the core tidyverse](https://tidyverse.org/packages/).
- The [broom](https://broom.tidymodels.org/) package, which is part of [the tidymodels framework](https://www.tidymodels.org/) we will see in 432
- Bayesian modeling references, from Slides Set 20
    - [Probability of Direction](https://easystats.github.io/bayestestR/reference/p_direction.html)
    - [Rhat and ESS diagnostics](https://mc-stan.org/rstan/reference/Rhat.html)
    - [Bayesian R-squared](https://easystats.github.io/performance/reference/r2_bayes.html)
    - [Performance of Bayesian models](https://easystats.github.io/performance/reference/model_performance.stanreg.html)

## References from Slides in Class 19 (also now in [Class 19 README](https://github.com/THOMASELOVE/431-classes-2025/tree/main/class19))

- [Reflection on modern methods: Statistics education beyond ‘significance’: novel plain English interpretations to deepen understanding of statistics and to steer away from misinterpretations](https://academic.oup.com/ije/article/49/6/2083/5876177?login=false) by Hilary Watt
- [Compare performance of different models](https://easystats.github.io/performance/reference/compare_performance.html) from the easystats framework.
- Main page for [Posit Cheat Sheets](https://rstudio.github.io/cheatsheets/)
    - [Posit's Data Transformation Cheat Sheet](https://rstudio.github.io/cheatsheets/html/data-transformation.html)
    - The [Joins chapter](https://r4ds.hadley.nz/joins) of R for Data Science
- [Technical Writing](https://quarto.org/docs/visual-editor/technical.html) in Quarto, including information on including equations, citations, cross-references, footnotes, embedded code, and LaTeX, especially using Quarto's Visual Editor.
- Were I to want to learn a little bit about informative priors, I'd look at places like the following:
    - https://xcelab.net/rm/
    - https://github.com/rmcelreath/stat_rethinking_2024?tab=readme-ov-file
    - https://vincentarelbundock.github.io/rethinking2/
    - https://mdsr-book.github.io/mdsr2e/
    - https://bookdown.org/content/4857/
    - https://torkar.github.io/BDA_in_ESE/

---

## Taking Other Courses With Me

In addition to 431, I teach two other semester-long courses, called **PQHS 432** and **PQHS 500**. I will teach both 432 and 500 in Spring 2026. My advice on these courses is found [in the Class 18 README](https://github.com/THOMASELOVE/431-classes-2025/tree/main/class18#taking-other-courses-with-me).

---

## There are 10 Remaining Deliverables for 431 This Semester

As things stand, here is the complete list. See the [Course Calendar](https://thomaselove.github.io/431-2025/calendar.html) for more details, and updates will appear there, if needed. All dates are **WEDNESDAYS**, unless indicated otherwise.

Deadline | Item(s)
:-----------------: | :----------------------------------------------------------------------------------------------------------
2025-11-12 at noon | (1) [Project B registration and scheduling form](https://thomaselove.github.io/431-projectB-2025/register.html) is due. (Google Form) <br> (2) [Minute Paper after Class 20](https://bit.ly/431-2025-minute-20) is also due.
2025-11-19 at noon | (3) [Lab 6](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab6) is due to [Canvas](https://canvas.case.edu/). <br> (4) [Minute Paper after Class 22](https://github.com/THOMASELOVE/431-minute-2025) (*to appear*)
2025-12-03 at noon | (5) [Quiz 2](https://github.com/THOMASELOVE/431-quizzes-2025/tree/main/quiz2) is due (Google Form). <br> [Quiz 2](https://github.com/THOMASELOVE/431-quizzes-2025/tree/main/quiz2) will be available by 3 PM on Thursday 2025-11-20.
~30 minutes on <br> December <br> 3, 4, 5, 8 or 9 | (6) [Project B](https://thomaselove.github.io/431-projectB-2025/) presentation with me (either in person or over Zoom) <br> You will express your schedule preferences in the [Project B registration form](https://thomaselove.github.io/431-projectB-2025/register.html). <br> The presentation schedule will be posted on 2025-11-14.
2025-12-10 at noon | (7) **Final Deadline**: All [Project B](https://thomaselove.github.io/431-projectB-2025/) Materials are due. <br> (8) [Lab X](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX) is due. <br> (optional) (9) [Lab Regrade Request Form](https://bit.ly/431-2025-lab-regrade-request) is due.
Around December 10 | (10) Course Evaluation of 431 for CWRU (exact date and web link TBA)

**Note**: There will also be at least two more opportunities for bonus credit this semester - each of which will have deadlines after the Thanksgiving Break. So far, one has been published, and the other will be published before Thanksgiving Break.

--- 

## One Last Thing

[What They Forgot to Teach You About R](https://rstats.wtf/) by Jennifer Bryan, Jim Hester, Shannon Pileggi and E. David Aja (The stuff you need to know about R, besides data analysis.) - this is *work in progress*...
