# How the Project A Plans Were Evaluated

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
comment = NA in Section 1 | Is `comment=NA` correctly set with `knitr` options in Section 1?
library only in Section 1 | Are any packages loaded after Section 1?
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
A1 outcome
A1 predictor
A2 outcome
A2 predictor
A3 outcome
Name of Rds file
Rds file: rows
Rds file: columns
4, 5, 8: Variables Setup
9. Print Tibble
10.1 tabyl
10.2 describe_distribution
10.3 data_codebook
10.4 distinct check
10. Numerical Summaries
11. Codebook
12.1 Research Question 1
12.1 RQ 1 matches Task 1?
"12.1 RQ Pre-Analysis
Direction OK?"
12.1 Score (0-5) on RQ1
12.2 Research Question 2
12.2 RQ 2 matches Task 2?
12.2 Score (0-5) on RQ2
12.3 Research Question 3
12.3 RQ 3 matches Task 3?
12.3 Score (0-5) on RQ3
Reflection Word Count
13. Identified Issue (0-5)
13. How they overcame (0-5)
13. Writing Quality (0-5)
13. Reflection Score (0-15)
14. AI Usage
15. R version
15. Running System...
15. Session Information
# of OKs (out of 16) in the yellow columns
RQ Score (out of 15)
Reflection Score (out of 15)
Total Score (out of 70)
Total % Satisfactory
Plan version 1 Status (ACCEPT or REDO)
