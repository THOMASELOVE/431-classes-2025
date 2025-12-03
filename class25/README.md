# 431 Class 25: 2025-12-04

[Main Website](https://thomaselove.github.io/431-2025/) | [Calendar](https://thomaselove.github.io/431-2025/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2025/) | [Text](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2025/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

![](https://imgs.xkcd.com/comics/compact_graphs.png) from <https://xkcd.com/2864/>

## Announcements

1. We'll do today's slides last. That's why [they are found below](#todays-slides).
2. The [Project B Presentation Schedule is here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md).
3. Here's a [video from The GRAPH Courses](https://www.youtube.com/watch?v=OlvO-EG-P60) on creating a personal website that some people found helpful in doing Lab X.

## Bonus Opportunities

1. Check out [this YouTube Playlist](https://youtube.com/playlist?list=PL1WkTI58HjciC-FdKZkwiVet-Iar6u7wm&si=UvpdygUuUBFO_2kH) of favorite songs from students in 431 this year.
2. I've prepared this list of [your favorite R functions](https://github.com/THOMASELOVE/431-classes-2025/blob/main/extra/favorite-R-function.md).
3. There **will be information here by class time** about the third bonus opportunity, listed in Quiz 2, and due at 9 AM Thursday 2025-12-04.

-------

## Quiz 2

**Details to come**.

-------

## There are at most 5 remaining deliverables for 431

See the [Course Calendar](https://thomaselove.github.io/431-2025/calendar.html) for more details, and updates will appear there, if needed. 

Deadline | Item(s)
:-----------------: | :----------------------------------------------------------------------------------------------------------
~30 minutes on <br> December 4, 5, 8 or 9 | (1) [Project B](https://thomaselove.github.io/431-projectB-2025/) presentation with me (either in person or over Zoom) <br> The [Project B presentation schedule is here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md).
Wednesday <br> 2025-12-10 at noon | (2) **Final Deadline**: All [Project B](https://thomaselove.github.io/431-projectB-2025/) Materials are due. <br> (3) [Lab X](https://github.com/THOMASELOVE/431-labs-2025/tree/main/labX) is due. <br> (optional) (4) [Lab Regrade Request Form](https://bit.ly/431-2025-lab-regrade-request) is due.
Once your presentation <br> is complete | (5) Course Evaluation of 431 for CWRU at <https://webapps.case.edu/courseevals/>

-------


## Some Other Things To Look At Over Break

1. Alex Reinhart's book [Statistics Done Wrong](https://www.statisticsdonewrong.com/index.html) is well worth your time.
2. Need some motivation to work with public health data and don't mind that the subject matter is horribly depressing? Here's the [Gun Violence Archive](https://www.gunviolencearchive.org/).
3. Looking for a video to watch over the break? Check out the work of [David Robinson](https://www.youtube.com/@safe4democracy), [Frank Harrell](https://www.youtube.com/channel/UC-o_ZZ0tuFUYn8e8rf-QURA) or [Julia Silge](https://www.youtube.com/@JuliaSilge).
    - One good option is David's [Tidy Tuesday screencast: analyzing student/teacher ratios and other country statistics](https://www.youtube.com/watch?v=NoUHdrailxA)
    - Another is Julia's [Resampling to understand gender in art history textbooks](https://www.youtube.com/watch?v=Ac7V848uBuo) with this [accompanying blog post](https://juliasilge.com/blog/art-history/).
4. Need a break? Perhaps you'll enjoy these [10 GIFs for Stats/Data People](https://graphpaperdiaries.com/2017/03/15/7-gifs-for-statsdata-people/) from BS King.



![](figures/cox1.png)

## One "Last Thing" in the middle of class

Frank Harrell posted this [Biostatistical Modeling Plan](https://hbiostat.org/blog/post/modplan/), most recently on 2023-01-26. This is the kind of thing we will work towards in 432.

> This is an example statistical plan for project proposals where the goal is to develop a biostatistical model for prediction, and to do external or strong internal validation of the model.

-------------

## Today's Slides

Class | Date | Slides | Word .docx | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
25 | 2025-12-04 | **[Slides 25](https://thomaselove.github.io/431-slides-2025/class25.html)** | **[Word 25](https://thomaselove.github.io/431-slides-2025/class25w.docx)** | **[Code 25](https://github.com/THOMASELOVE/431-slides-2025/blob/main/class25.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## References from Today's Slides

- [Get Started with Tidymodels](https://www.tidymodels.org/start/). The sea urchins example comes from [Build a Model](https://www.tidymodels.org/start/models/).
- [TidyTuesday and tidymodels](https://juliasilge.com/blog/intro-tidymodels/) by [Julia Silge](https://juliasilge.com/).
- I have a semi-surprise visualization example, which (after the surprise has been revealed) might interest you in reading more from [Alberto Cairo](http://www.thefunctionalart.com/2016/08/download-datasaurus-never-trust-summary.html), [Steph Locke](https://cran.r-project.org/web/packages/datasauRus/vignettes/Datasaurus.html), [Tomas Westlake](https://r-mageddon.netlify.com/post/reanimating-the-datasaurus/), [Julia Silge](https://juliasilge.com/blog/datasaurus-multiclass/) and [Justin Mareika and George Fitzmaurice](https://www.autodesk.com/research/publications/same-stats-different-graphs) in addition to what you've already read about it in Spiegelhalter. 

## Ten of the Most Important Ideas from 431 (discussed in today's slides)

1. You have to visualize and count data to understand it.
2. 90% of statistical work could be described as data management.
3. Quarto and the tidyverse make it easier to do the right thing.
4. Statistical significance is not a helpful concept.
5. Point estimates and confidence intervals are useful ideas.
6. Most statistical procedures are in fact regression models.
7. All statistical methods involve assumptions worth checking.
8. The bootstrap is a very useful, and somewhat underused tool.
9. Prediction models need to predict well in new situations.
10. Statistical thinking is far too important to be left to statisticians.

## Advertising

I am singing with the [Chagrin Falls Studio Orchestra](https://thecfso.com/) on Monday 2025-12-22 and Tuesday 2025-12-03 at their annual Wassail Christmas Concert. The 40 piece orchestra is backed by four singers (no solos for me this time) for a family-friendly concert of holiday favorites performed at the [Chagrin Valley Little Theatre](https://app.arts-people.com/index.php?show=290422) in Chagrin Falls, Ohio. If you're interested, tickets can be purchased in advance at <https://app.arts-people.com/index.php?show=290422>. Please feel absolutely no obligation to attend.
