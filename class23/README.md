# 431 Class 23: 2025-11-20

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
23 | 2025-11-20 | **[Slides 23](https://thomaselove.github.io/431-slides-2025/class23.html)** | **[Word 23](https://thomaselove.github.io/431-slides-2025/class23w.docx)** | **[Code 23](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class23.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

![](https://imgs.xkcd.com/comics/paper_title.png)  [Source](https://xkcd.com/2703)

## Announcements

1. Several students have now [completed Lab X](https://github.com/THOMASELOVE/431-labs-2025/blob/main/labX/websites_2025.md). Here are [the instructions](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX). Don't leave this to the last couple of days!
2. The [Project B Presentation Schedule is here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md).
3. Feedback on the Minute Paper after Class 22 will be **available by class time**.

---

## Thinking through a problem

[How is it that this problem, with its 21 data points, is so much easier to handle with 1 predictor than with 16 predictors?](https://statmodeling.stat.columbia.edu/2025/11/14/how-is-it-that-this-problem-with-its-21-data-points-is-so-much-easier-to-handle-with-1-predictor-than-with-16-predictors/) by Andrew Gelman

> One week, a pair of students reported that someone had shown up who was studying the efficiency of industrial plants. The researcher had data on 21 factories, and for each of them she had a measure of efficiency and 16 predictors—different variables that might be predictive of that outcome. She wanted to use these data to see which of these factors was most important.

> When this example came up in our consulting class years ago, one of the other students said that he remembered that researcher from the previous semester: she’d come by with 15 data points and 16 predictors, and he and his partner had told her that, with fewer data points than predictors, they couldn’t help her. In the meantime this researcher had gathered data from 6 more plants and was emboldened to return.

> The first problem here is to ask what can be done with these data. It’s not an easy question. Indeed, it might seem ridiculous to suppose that you could tease out a regression relationship among so many predictors with so few observations. And this is without even getting into potential interactions (16*15/2 two-way interactions and so forth) or the difficulties of causal identification from observational data. If students cannot come up with any ideas, the instructor should push them in another way, by asking what decisions they might make based on these data, if they were designing this sort of industrial plant.

> Fine. Laugh all you want. But . . . there are things that can be done even using this small dataset. Think about it this way: suppose the researcher had come in with 21 factories and just one predictor. Then you could do something, right? You can make a scatterplot of the outcome vs. the predictor, you could run a regression predicting the outcome from this one variable. You can potentially learn a lot from 21 data points, or even from 15.

---

## One Last Thing

[A database of every mound-charging we've found in Major League Baseball](https://www.patreon.com/posts/database-of-weve-142735794). Also see [this FlowingData post](https://flowingdata.com/2025/11/14/database-of-mound-charging-in-baseball/) which alerted me to these data.

---

# Reminders of things I have shared previously

## There are 6 Remaining Deliverables for 431 This Semester

As things stand, here is the complete list. See the [Course Calendar](https://thomaselove.github.io/431-2025/calendar.html) for more details, and updates will appear there, if needed. All dates are **WEDNESDAYS**, unless indicated otherwise.

Deadline | Item(s)
:-----------------: | :----------------------------------------------------------------------------------------------------------
2025-12-03 at noon | (1) [Quiz 2](https://github.com/THOMASELOVE/431-quizzes-2025/tree/main/quiz2) is due (Google Form). <br> [Quiz 2](https://github.com/THOMASELOVE/431-quizzes-2025/tree/main/quiz2) will be made available to you by 3 PM on Thursday 2025-11-20.
~30 minutes on <br> December <br> 3, 4, 5, 8 or 9 | (2) [Project B](https://thomaselove.github.io/431-projectB-2025/) presentation with me (either in person or over Zoom) <br> The [Project B presentation schedule is here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md).
2025-12-10 at noon | (3) **Final Deadline**: All [Project B](https://thomaselove.github.io/431-projectB-2025/) Materials are due. <br> (4) [Lab X](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX) is due. <br> (optional) (5) [Lab Regrade Request Form](https://bit.ly/431-2025-lab-regrade-request) is due.
Around December 10 | (6) Course Evaluation of 431 for CWRU (exact date and web link TBA)

**Note**: There are three remaining opportunities for bonus credit this semester - each has deadlines between December 2 and 4. So far, one has been published, another [is right here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/class21/extra.md), and the final one will also be published before Thanksgiving Break.

## Taking Other Courses With Me

In addition to 431, I teach two other semester-long courses, called **PQHS 432** and **PQHS 500**. I will teach both 432 and 500 in Spring 2026. My advice on these courses is found [in the Class 18 README](https://github.com/THOMASELOVE/431-classes-2025/tree/main/class18#taking-other-courses-with-me).

## Missing Data in Project B

- In Project B, study 1: for each analysis, filter to complete cases on the variables used in that individual analysis.
- In Project B, study 2: filter to complete cases on your outcome and key predictor, then single imputation on all other predictors to determine final model choice, then (ideally) show multiple imputation results (`model_parameters()` and `glance()` are sufficient) across all of the data.
