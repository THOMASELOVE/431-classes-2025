# How the Project A Plans Were Evaluated

## Scoring the Plans

Look at the grid of material I emailed you on Monday 2025-10-06.

1. There are 16 rows highlighted in yellow (and shown in bold below). Count the number of those which say "OK" as opposed to something else (usually "Problem") and multiply that total by 2.5 points. (The count of the # of OKs is shown in the grid.)
2. The three research questions are each graded on a scale from 0 = Poor to 3 = OK to 5 = Excellent. Sum those three to get the RQ Score (out of 15) shown near the bottom of the grid.
3. The Reflection is scored on three elements (identified issue, how they overcame, and writing quality) at 5 points each. Those are summed to get a score out of 15, shown as the Reflection Score near the bottom of the grid.
4. Add up the points from 1-3 above to get a score out of a possible 70 points.
5. The "Total % Satisfactory" is the percentage out of 70 points you received in the previous line.
6. The ACCEPT or REDO decision is not made solely on the basis of these scores.

If your first version was **ACCEPT**ed, then your actual score (out of 20 points) for Project A on the Proposal will be:
- 20, if your "Total % Satisfactory" was 78% or higher.
- 19, if your "Total % Satisfactory" was 67% or higher, but lower than 78%.
- 18, if your "Total % Satisfactory" was 55% or higher, but lower than 67%.
- 17, if your "Total % Satisfactory" was below 55%.

If your first version requires a **REDO**, then your actual score (out of 20 points) for Project A on the Proposal will fall somewhere between 14 and 18 points, and that will be determined after that revision is complete.

## Describing "The Grid"

Label | Description
:------------ | :--------------------------------------------------------------------------------------
Project A Group | Code (A-xx) for this project
Submitted by | Project Plan submitter
Partner Name  | Partner's name (if any)
Title | Plan title (as submitted)
Subtitle | Plan subtitle (as submitted)
Dr. Love's | Comments on Your Submitted Title and Subtitle
More General | Comments from Dr. Love
Comments | (more from TAs than from Dr. Love but equally important) mostly focusing on Plan Sections 10-14
Submission Date | Date
Submission Time | Time
**A. Submitted On Time?** | OK if On Time
Author Names | Are author names formatted properly in HTML?
Date Format | Is date formatted properly in HTML?
Code Tools | Are code tools functioning properly in HTML?
15 sections | Does Table of Contents show 15 sections, as required?
T of C functions? | Do the links in the Table of Contents function properly?
**B. Working HTML?** | OK if the basics of HTML (previous five lines) are all fine.
Quarto Date Setup | Does the Quarto file identify the date properly, with last-modified?
Quarto Theme | What [Quarto theme](https://quarto.org/docs/output-formats/html-themes.html) was used?
Love-431 Sourcing | Is Love-431.R sourced, and if it is, is it sourced in properly?
Quarto Spell Check | How many problems were identified by running Spell Check in RStudio on your Quarto file? OK if 0.
Quarto Blank Lines | Did you have trouble including blank lines before and after each code chunk, paragraph and heading?
Quarto Line Count | Lines of Quarto Code
**C. Quarto Overall** | OK if Quarto file (previous lines here) are all OK
comment = NA | Is `comment=NA` correctly set with `knitr` options in Section 1?
library only | We want to be sure that no packages are loaded after Section 1
R package count | Count of R packages loaded
loads main 5 packages | Does project load janitor, naniar, xfun, easystats, tidyverse?
other packages loaded | Other loaded packages, (things that are in [easystats](https://easystats.github.io/easystats/) or [core tidyverse](https://www.tidyverse.org/packages/) are problems)
tidyverse loaded last | Is tidyverse the last package loaded?
ggplots theme | ggplots theme chosen (most picked `theme_bw()`)
package messages | Are these silenced properly in Section 1?
**1. R Packages** | OK if Section 1 looks OK overall (see [Example](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/examples.md#section-1))
**2. Data Ingest** | OK if Section 2 looks OK overall (see [Example](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/examples.md#section-2)
state 1 | First state (alphabetically by [two-letter abbreviation](https://www.youtube.com/watch?v=dLECCmKnrys)) chosen other than OH
state 2 | Second state (alphabetically by [two-letter abbreviation](https://www.youtube.com/watch?v=dLECCmKnrys)) chosen other than OH
state 3 | Third state (alphabetically by [two-letter abbreviation](https://www.youtube.com/watch?v=dLECCmKnrys)) chosen other than OH
state 4 | Fourth state (alphabetically by [two-letter abbreviation](https://www.youtube.com/watch?v=dLECCmKnrys)) chosen other than OH
state 5 | Fifth state (alphabetically by [two-letter abbreviation](https://www.youtube.com/watch?v=dLECCmKnrys)) chosen other than OH
state 6 | OH
Section 3 county count | How many counties are specified in Section 3?
Why these states? | Is this described in complete sentences in Section 3?
**3. State Selection** | OK if Section 3 looks OK overall (see [Example](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/examples.md#section-3)
A1 outcome | Analysis 1 outcome
A1 predictor | Analysis 1 predictor
A2 outcome | Analysis 2 outcome
A2 predictor | Analysis 2 predictor
A3 outcome | Analysis 3 outcome
Name of Rds file | Name of your Rds file
Rds file: rows | Rows in your Rds file
Rds file: columns | Columns in your Rds file
**4, 5, 8: Variables** | OK if Sections 4, 5 and 8 look OK overall (see Example [Section 4](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/examples.md#section-4), [Section 5]((https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/examples.md#section-5) and [Section 8](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/examples.md#section-8))
**9 Print Tibble** | OK if Section 9 looks OK overall (see [Example](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/examples.md#section-9)
10.1 `tabyl` | OK if you've run code successfully to do what is asked of you (Table of States by Binary Factor). In particular, you’ve used `tabyl()` properly, and shown row and column marginal totals, including for missing values of your binary predictor. Explanatory text is welcome but not required in this section. 
10.2 `describe_distribution` | OK if you've run `describe_distribution()` properly on the entire tibble. For all variables except the two factors, this will allow us to see (among other things) that the minimum and maximum values that make sense, and also that each of your variables shows the appropriate number of counties. 
10.3 `data_codebook` | OK if you've run `data_codebook()` properly on the whole data set, using the settings max_values = 6, range_at = 15) without any errors or warnings happening, [as detailed here](https://thomaselove.github.io/431-projectA-2025/plan.html#section-10.3-data_codebook-results), AND you also included at least one English sentence to verify the issues described there, specifically regarding whether the minimum and maximum values of the quantitative data elements make sense, and that the amount of missingness meets our requirements for each variable.
10.4 distinct check | OK if you've provided counts of distinct values, as requested and we can see the results for all eleven variables. You also have a sentence or two showing that you have checked for distinct `fipscode`s (a unique code for each row) and that you have at least 15 unique values for each outcome and the quantitative predictor. 
**10 Numerical Summaries** | If rows for 10.1, 10.2, 10.3, and 10.4 are all OK, then this is OK.
**11 Codebook** | OK if the submission meets these requirements: (1) The student(s) have a sentence stating the number of counties (should be 300-800) and variables (should be eleven) in your tibble. This should match what's in the printout of the tibble in section 9. and (2) You have an attractively formatted, readable codebook that looks nice in your HTML which contains each variable’s (1) name in your tibble, (2) its role, (3) its original vXXX code, (4) the definition (including units) and (5) the year(s) in which the variable was measured. 
12.1 Research Question 1 | Your first research question, verbatim.
**12.1 RQ 1 matches Task 1?** | Is the first research question proposed here something you will be able to answer (or at least respond to effectively) after your Analysis 1 is complete?
**12.1 RQ Pre-Analysis Direction OK?** | OK if student(s), after listing the first Research Question, provided some brief speculation in complete sentences as to the nature of the relationship they anticipate finding based on their hypotheses about their Analysis 1 variables. 
12.1 Score (0-5) on RQ1 | If we were unable to identify any problems in Section 12.1 (including the Research Question, matching the task and pre-analysis direction and anything else they wrote) we gave a score of 5 here. If there was one minor problem, we gave a 4. If there are two minor problems or one major problem, we gave a 3. If there are more problems, we gave a score of 1 or 2. We gave a score of 0 if they left out something important completely in completing Research Question 1.
12.2 Research Question 2 | Your second research question, verbatim.
**12.2 RQ 2 matches Task 2?** | Is the second research question proposed here something you will be able to answer (or at least respond to effectively) after your Analysis 2 is complete?
12.2 Score (0-5) on RQ2 | If we were unable to identify any problems in Section 12.2 (including the Research Question and matching the analysis) we gave a score of 5. If there was one minor problem, we gave a 4. If there are two minor problems or one major problem, we gave a 3. If there are more problems, we gave a score of 1 or 2. We gave a score of 0 if they left out something important completely in completing Research Question 2.
12.3 Research Question 3 | Your third research question, verbatim.
**12.3 RQ 3 matches Task 3?** | Is the third research question proposed here something you will be able to answer (or at least respond to effectively) after your Analysis 3 is complete?
12.3 Score (0-5) on RQ3 | If we were unable to identify any problems in Section 12.3 (including the Research Question and matching the analysis) we gave a score of 5. If there was one minor problem, we gave a 4. If there are two minor problems or one major problem, we gave a 3. If there are more problems, we gave a score of 1 or 2. We gave a score of 0 if they left out something important completely in completing Research Question 3.
Reflection Word Count | Number of words in your reflection (this should have been at least 100: if it wasn't, your score on the reflection was affected.)
13 Identified Issue (0-5) | Score for how clearly they identified at least one meaningful issue they confronted in preparing the Plan. We used 0 = not acceptable or skipped, 1 = Poor, 2 = Fair 3 = OK, 4 = Good, 5 = Excellent.
13 How they overcame (0-5) | Score for how clearly they explained how they overcame that issue in preparing the Plan. We used 0 = not acceptable or skipped, 1 = Poor, 2 = Fair 3 = OK, 4 = Good, 5 = Excellent.
13 Writing Quality (0-5) | Score for how well section 13 is written. We used 0 = not acceptable or skipped, 1 = Poor, 2 = Fair 3 = OK, 4 = Good, 5 = Excellent.
13 Reflection Score (0-15) | Sum of three previous (marked 13) rows.
**14 AI Usage** | OK if what is written is in complete sentences with appropriate use of grammar and syntax, and appropriately describes their AI usage. If you claimed not to have used AI, we reminded you that "spell check" and "using RStudio to suggest completions for code" are likely to have been used by everyone and should be indicated. 
15 R version | R Version you're running (should be 4.5.1)
15 Running System... | System you are running according to your session information
**15 Session Information** | OK if Session Information section is correct and complete.
OKs  | Count of OKs out of a possible 16 in the yellow rows on the grid (indicated **in bold** in this table)
RQ Score | Research Question score out of 15 points, summing the 0-5 scores for each of the three Questions
Reflection Score | Reflection Score, out of 15 points, from above
Total Score | from previous three rows: 2.5 for each OK (out of 16) + RQ Score + Reflection Score (maximum possible score = 70)
Total % Satisfactory | Total Score from previous row, expressed as a percentage of those 70 maximum points
Plan version 1 Status | ACCEPT or REDO

Repeating: If your first version was **ACCEPT**ed, then your actual score (out of 20 points) for Project A on the Proposal will be:
- 20, if your "Total % Satisfactory" was 78% or higher.
- 19, if your "Total % Satisfactory" was 67% or higher, but lower than 78%.
- 18, if your "Total % Satisfactory" was 55% or higher, but lower than 67%.
- 17, if your "Total % Satisfactory" was below 55%.

If your first version requires a **REDO**, then your actual score (out of 20 points) for Project A on the Proposal will fall somewhere between 14 and 18 points, and that will be determined after that revision is complete.

