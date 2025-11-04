# 431 Class 18: 2025-11-04

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
18 | 2025-11-04 | **[Slides 18](https://thomaselove.github.io/431-slides-2025/class18.html)** | **[Word 18](https://thomaselove.github.io/431-slides-2025/class18w.docx)** | **[Code 18](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class18.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

![](https://imgs.xkcd.com/comics/effect_size.png) [Source](https://xkcd.com/2755)

## Announcements

1. [Lab 5](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab5) is due tomorrow (Wednesday 2025-11-05) at noon. I repaired the [PDF of the Lab instructions](https://github.com/THOMASELOVE/431-labs-2025/blob/main/lab5/431-lab5.pdf) on Sunday evening (specifically Question 1) to fix two broken links to descriptions of questionnaires in NHANES 2001-02.
2. There is a [Minute Paper after Class 18](https://bit.ly/431-2025-minute-18), also due tomorrow at noon.
3. **Project A evaluations** You can track your Project A [evaluation details as we review them here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/portfolio_evaluation.md).
4. **Lab 6 Data** I added the `lab6_lindner800.csv` data set that you need to do [Lab 6](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab6) to [our 431-data page]((https://github.com/THOMASELOVE/431-data)). Sorry it wasn't there earlier.
5. **Taking 432** I've started permitting people into 432 (and 500). If you're in 431 now, and get an A or B, then you'll get into 432 this Spring.

## Reminder to Dr. Love

Don't forget to incorporate a **standing break** today.

## Project B

1. The [Project B registration](https://thomaselove.github.io/431-projectB-2025/register.html) Google Form due 2025-11-12 is now open.
2. **NHANES: Insurance in Project B**. 
    - A problem is that you will have people who are listed as covered by multiple types of insurance, so you'll have to decide on what to do about that, since your categories need to be collectively exhaustive and mutually exclusive. I encourage you to create a four-level categorical variable for insurance type.
    - I built [a small example (PDF)](nhanes_insurance.pdf) to create this variable using the 2017-18 NHANES data, and then also ran it for 2017-March 2020 and for 8/21 - 8/23 data so you can check your work should you decide to use NHANES data for Project B.

## Taking Other Courses With Me

In addition to 431, I teach two other semester-long courses, called **PQHS 432** and **PQHS 500**. I will teach both 432 and 500 in Spring 2026. Here's my advice, for what it's worth ...

- **432** is the continuation of this course (widely regarded as the "better" half.) I think **everyone** in this class should be planning to take 432 this Spring (i.e. Spring 2025), **unless** you don't feel you've received sufficient value from this course and don't need to take 432 to finish your program at CWRU, **or** you have an unshakable conflict in Spring 2026 (especially if you plan to instead take 432 in Spring 2027.)
    - I will provide the 432 website and syllabus to everyone enrolled in 432 in mid-January. The Spring 2025 syllabus for 432 is [here](https://thomaselove.github.io/432-syllabus-2025/) but of course, things will change, in ways I will start to think about after Christmas. The 432 class is held on Tuesdays and Thursdays from 1:00 to 2:15 PM.
- **500** is a project-based and more advanced course covering specific topics in the design and analysis of observational studies. 
    - This Spring (2026) will be the **last** time that I will teach 500 as I have in the past.
        - In Spring 2027 and beyond, the way I will teach it will be different in important ways.
        - I'm not sure yet if these changes will be for the better or worse for students. I hope generally better, but cannot guarantee that will be the case.
    - I think everyone in this class who is interested in taking 500 should do so at some point. The course is mostly about using propensity scores well to help design (and analyze) data from observational studies where we want to estimate a causal effect.
    - A revised syllabus for the Spring 2026 version of the course will be available in mid-January. The Spring 2025 syllabus for 500 is [here](https://thomaselove.github.io/500-syllabus-2025/), but of course, things will change in ways I will start to think about after Christmas.
    - The Spring 2026 version of the 500 course will be held on Thursdays from 8:30 to 11 AM.
    - I especially think MS and PhD students (in any department) interested in applications of health research in real world situations should take it, as well as people looking for jobs in fields related to health care analytics.
    - For some people, it's better to complete 432 before taking 500 for several reasons, most especially ...
        1. percolation time for some of the ideas in 431/432
        2. too much of me at one time can be overwhelming
    - If Spring 2026 is your best opportunity to take 500, then I will certainly permit you to do so. Send me an email anytime if you want to discuss this.

## Taking Other Courses about Statistics/Data Science and related fields

Our TAs are a better resource than I am for advice on this issue. We have created a Google Doc called "TA Advice on Other Courses" posted to your Shared Drive. Take a look.

-------

## References That Might Interest You

1. From Andrew Gelman's blog:
    - 2017-03-04: [How to interpret confidence intervals?](https://statmodeling.stat.columbia.edu/2017/03/04/interpret-confidence-intervals/)
    - 2022-04-05: [Confidence intervals, compatability intervals, uncertainty intervals](https://statmodeling.stat.columbia.edu/2022/04/05/confidence-intervals-compatability-intervals-uncertainty-intervals/)
    - 2024-03-14: [Abraham Lincoln and confidence intervals](https://statmodeling.stat.columbia.edu/2024/03/14/abraham-lincoln-and-confidence-intervals/)
2. Chapter 2 on [Data and measurement (pdf)](https://statmodeling.stat.columbia.edu/wp-content/uploads/2021/01/raos_chapter2.pdf) from [Regression and Other Stories](https://avehtari.github.io/ROS-Examples/) by Andrew Gelman, Jennifer Hill and Aki Vehtari.
    - Chapter 16 on [Design and sample size decisions (pdf)](https://statmodeling.stat.columbia.edu/wp-content/uploads/2021/01/raos_chapter16.pdf) is also available, and this is a substantial part of the 432 class.

-----------------

## Next to Last Thing (reminders of remaining deliverables are below)

[Source](https://x.com/StatisticUrban/status/1982995821655405017/photo/1)

![](male_heights_2025-10-27.png)

## One Last Thing

[The Ultimate Halloween Candy Power Ranking](https://fivethirtyeight.com/videos/the-ultimate-halloween-candy-power-ranking/) from FiveThirty Eight in 2017.

- Data available [on Github](https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking)
- Check out the survey at [What's the best Halloween candy?](https://walthickey.com/2017/10/18/whats-the-best-halloween-candy/)

-----------------

## There are 12 Remaining Deliverables for 431 This Semester

As things stand, here is the complete list. See the [Course Calendar](https://thomaselove.github.io/431-2025/calendar.html) for more details, and updates will appear there, if needed. All dates are **WEDNESDAYS**, unless indicated otherwise.

Deadline | Item(s)
:-----------------: | :----------------------------------------------------------------------------------------------------------
2025-11-05 at noon | (1) [Lab 5](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab5) is due to [Canvas](https://canvas.case.edu/). <br> (2) [Minute Paper after Class 18](https://bit.ly/431-2025-minute-18)
2025-11-12 at noon | (3) [Project B registration and scheduling form will be due.](https://thomaselove.github.io/431-projectB-2025/register.html) (Google Form) <br> (4) [Minute Paper after Class 20](https://github.com/THOMASELOVE/431-minute-2025) (*to appear*)
2025-11-19 at noon | (5) [Lab 6](https://github.com/THOMASELOVE/431-labs-2025/tree/main/lab6) is due to [Canvas](https://canvas.case.edu/). <br> (6) [Minute Paper after Class 22](https://github.com/THOMASELOVE/431-minute-2025) (*to appear*)
2025-12-03 at noon | (7) [Quiz 2](https://github.com/THOMASELOVE/431-quizzes-2025/tree/main/quiz2) is due (Google Form). <br> [Quiz 2](https://github.com/THOMASELOVE/431-quizzes-2025/tree/main/quiz2) will be made available to you by 3 PM on Thursday 2025-11-20.
~30 minutes on <br> December <br> 3, 4, 5, 8 or 9 | (8) [Project B](https://thomaselove.github.io/431-projectB-2025/) presentation with me (either in person or over Zoom) <br> You will express your schedule preferences in the [Project B registration form](https://thomaselove.github.io/431-projectB-2025/register.html). <br> The presentation schedule will be posted on 2025-11-14.
2025-12-10 at noon | (9) **Final Deadline**: All [Project B](https://thomaselove.github.io/431-projectB-2025/) Materials are due. <br> (10) [Lab X](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX) is due. <br> (optional) (11) [Lab Regrade Request Form](https://bit.ly/431-2025-lab-regrade-request) is due.
Around December 10 | (12) Course Evaluation of 431 for CWRU (exact date and web link TBA)

**Note**: There will also be at least two more opportunities for bonus credit this semester - each of which will have deadlines after the Thanksgiving Break. So far, one has been published.
