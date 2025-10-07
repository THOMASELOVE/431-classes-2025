# Project A Plan Examples and General Comments

- [How I scored the Project A Plans](#scoring-the-plans) including how to interpret key rows in the grid I emailed to you on 2025-10-06.
- [General Advice on Titles](#general-advice-on-titles)
- A note on [Variable Names](#on-variable-names)
- Reminder that the Project A instructions provide the [2024, not 2025 elements](#reminder-about-the-review-elements-list-from-2024-that-i-provided).
- What should this section look like?
  - Every section in the Project A Plan (except 1, 9, and 15) needs complete sentences in text explaining what you're doing.
  - [Section 1](#section-1) R Packages
  - [Section 2](#section-2) Data Ingest
  - [Section 3](#section-3) State Selection
  - [Section 4](#section-4) Variable Selection
  - [Section 5](#section-5) Variable Cleaning and Renaming
  - [Section 8](#section-8) Arranging and Saving the Analytic Tibble
  - [Section 9](#section-9) Print the Tibble
  - [Section 11](#section-11) The Codebook
  - [Section 14](#sections-14-and-15) AI Usage
  - [Section 15](#sections-14-and-15) Session Information
- [Trivia](#trivia)

## Scoring the Plans

Look at the grid of material I emailed you on Monday 2025-10-06.

1. There are 16 rows highlighted in yellow. Count the number of those which say "OK" as opposed to something else (usually "Problem") and multiply that total by 2.5 points. (The count of the # of OKs is shown in the grid.)
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

## On Variable Names

**Many** people developed variable names that were excellent in terms of clearly indicating what was going on. However, some of those names were so long that they will be really problematic down the line as you work on the portfolio. Ideally, all of your variable names in your codebook other than `county_clustered` will be **no more than 12 characters long**, while still describing what the reader needs to know effectively. Please try to accomplish this for the portfolio, as you move forward. For instance, the name `income_inequality` is 17 characters long.

## Reminder about the Review Elements List from 2024 that I provided

The [review elements list in the Project A Plan](https://thomaselove.github.io/431-projectA-2025/plan.html#checklist-review-elements-for-the-project-a-plan) specifically mentions (twice) that it refers to **2024**, and not 2025, and I also mentioned this in class. Yours will be similar but not identical, naturally. For example, you should be using R 4.5.1. and your dates should be something like 2025-10-01, etc.

## General Advice on Titles

Titles are difficult to build, but are also very important, and I'd like to see your work start out as effectively as possible. I believe that each of you can create a more effective title (which meets the maximum 80 characters limit) and subtitle (which should not exceed 150 characters) than you have submitted, so I'll expect a new title and subtitle when you submit the Project A Portfolio. A few tips (which you will also find in our feedback, coming early next week.)

1. Your title needs to distinguish your project well from the other 44 project A submissions.
2. A good strategy is to focus on one of your research questions in which you think your readers can be enticed (in a brief title of no more than 80 characters) to be actively interested in your results. This may be easier when you have completed your analyses in the portfolio.
3. Information like the fact that you're using data from CHR 2025 (and CHR 2019) in your work or that you are using six states, or which six states they are can all be safely moved to a subtitle.
4. Avoid the use of words like "Exploring" or "Assessing how" or "An Analysis of" or "A Study of" or "Relationships between" or "Associations between" or "Correlations between" or "Impact of" or any other "throat clearing" phrases[^1] that don't actually communicate any meaningful information in your title or subtitle. They don't belong.

## Section 1

Here's an example of an excellent Section 1 of the HTML for the Project A Plan.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section1.png)

## Section 2

Here's an example of an excellent Section 2 of the HTML for the Project A Plan.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section2.png)

## Section 3

Here's an example of an excellent Section 3 of the HTML for the Project A Plan.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section3.png)

## Section 4

Here's an example of an excellent Section 4 of the HTML for the Project A Plan.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section4.png)

## Section 5

Here's an example of an excellent Section 5 of the HTML for the Project A Plan.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section5.png)

## Section 8

Here's an example of a very good Section 8 of the HTML for the Project A Plan. It would be even better if it started with a complete sentence describing what Section 8 is doing. Note that if you're going to use `droplevels()`, this should happen **before** you save the .Rds file.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section8.png)

## Section 9

Here's an example of an excellent Section 9 of the HTML for the Project A Plan.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section9.png)

## Section 11

Here's an example of the start of an excellent Section 11 of the HTML for the Project A Plan. 

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section11.png)


## Sections 14 and 15

Here's an example of an excellent Section 14 and start of Section 15 of the HTML for the Project A Plan.

![](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectA/plans/projA_plan_section14.png)

## Trivia

### States Selected

```
45 OH
20 PA
19 CA
18 MI
17 IL IN
14 NY
10 FL
 9 MN TX WI
 8 GA WV
 7 KY MD
 6 CO
 4 IA NJ OR WA
 3 ID KS
 2 AL LA MT NC NE NM OK UT
 1 AR AZ CT MA MO ND SC VA WY
```

### County Counts

Mean = 492, Median = 505, SD = 90

- 505 Counties: IN KY MI PA WV OH
- 524 Counties: IL IN	MI MN WI OH 

```
6 50 77 79
6 20 48
5 56 64 69 73
5 04 05 05 05 05 05 06 11 24 24 24 24 24 27 36 39
4 73 76 81 87 90 94 97
4 10 21 22 28 49
3 52 62 64 86 91
3 02 20 33
```

### Variables Selected

#### Analysis 1 Outcomes

```
8 v042
6 v002
5 v001 v011 v127
4 v060
3 v009
2 v155
1 v049 v050 v070 v125 v136 v140 v143
```

#### Analysis 1 Predictors

```
6 v023
4 v063 v085
3 v011 v058 v155
2 v009 v067 v070 v125 v139 v143
1 v001 v036 v044 v049 v057 v059 v060 v168

Two (v037 and v190) that will need to change (see my email to you this AM)
```

#### Analysis 2 Outcomes

```
6 v042
4 v011 v036 v049
3 v002 v127 v155
2 v009 v139 v143 
1 v001 v034 v044 v050 v060 v067 v070 v125 v128 v136 v140 v166

One (v226) that will need to change (see my email to you this AM)
```

#### Analysis 2 Predictors

```
6 v063 v168
4 v023
3 v058 v085 v136 v139 v140
2 v049 v070
1 v042 v044 v057 v059 v060 v067 v125 v143 v151 v155
```

#### Analysis 3 Outcomes

```
10 v143
 6 v042
 5 v070
 4 v060
 3 v009 v011 v036 v049 v139
 2 v127
 
Three (v001, v063 and v201) that will need to change (see my email to you this AM)
```


[^1]: In writing, "throat-clearing" refers to unnecessary words or phrases at the beginning of a sentence or text that delay the main point. The best approach in scientific writing is to cut this material and build a stronger, more direct sentence.

