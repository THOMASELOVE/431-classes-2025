# Project B Materials

## Schedule for Project B Presentations

The schedule will be [posted here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md) on Friday 2025-11-14.

### Important Notes

1. In the **OK?** column, below...
    - ✔️ means I have approved your plan. If there is a check by your name, then you're all set. Go and do the rest of Project B.
    - ❓ means I am likely to approve your plan, but the footnote will tell you what further information or clarification I need (and how you should send it) before I formally approve your work.
    - **NO** means I will not approve your plan as currently listed, and you will have to edit your Registration form and resubmit it according to the requirements in my note to you.
2. In general, I am not going to let students use the **431 Favorite Movies** data. Other students *might* be allowed to use them, but only with my emailed permission **before** you submit the Project B Registration Form. Contact me by email now if you want me to consider letting you use these data. You will need to make a strong case to me that you are going to do something of interest to me that does not overlap with other projects in order to use these data.
3. The count of complete cases we ask for is across **ALL** your variables to be used in Study 2, not just the outcome and key predictor. Be sure to get this right, including properly treating Refused and Don't Know as missing in all variables before making your count.
4. Anyone working with NHANES data should have an age restriction, either to **adults** (which can be ages 21-79 or 18-79 or some smaller group within that range) or **children** (which should be determined depending on how the data are gathered, and include only people under a certain age - and perhaps above one, too, like 6 to 17 years old, for example) **or** provide me with a good reason as to why I should let you use some sort of mixed group including both adults and kids.
5. If you have more than the maximum allowable number of observations (10,000 for Non-NHANES studies, and 7,500 for NHANES studies), I encourage you to either (a) focus on a single sex (either females only or males only), or restrict the age range, or apply some other simply explained inclusion criterion that focuses your sample down below the maximum (maybe to about 4,000 subjects), or (b) *a less good solution* take a random sample of, say, 4,000 complete cases from your sample so that, again, you are well below the maximum possible sample size for your type of study.
6. For NHANES studies, if you get names instead of numbers in your categorical variables when using the `nhanes()` function in the **nhanesA** package, you can either work with those names, or try adding `translated = FALSE`, as in `demo <- nhanes("DEMO_L", translated = FALSE)` to your call to the `nhanes()` function.

## Registration Status

As each group's [Project B Registration Form](https://bit.ly/431-projB-registration-2025) is submitted, I will list the investigators below. 

- The deadline for the form is Wednesday 2025-11-12 at noon. If you are more than 59 minutes late, you will be assigned to the schedule last and lose some credit on Project B.

### Awaiting Submissions

- Alex Krammer
- Linda Chen

### Received but not yet reviewed

- Allison (Alli) Thirion-Blasius NHANES 8/2021 to 8/2023
- Arjun Chatterjee NHANES 8/2021 to 8/2023
- Emma Chio NHANES 8/2021 to 8/2023
- Isabela Drumond Fonseca (with Renu Madhuraj Jadhav) NHANES 8/2021 to 8/2023
- Josh Silalahi NHANES 8/2021 to 8/2023
- Simon Lynn NHANES 8/2021 to 8/2023

----

## Submitted Plans Not Yet Approved

### Non-NHANES Study Plans not yet approved

OK? | Investigator(s) | Data Source | S2 Outcome | S2 Key Predictor | Subjects
:--: | :-------------------------------------: | :-----------------------------: | :-----------------: | :-----------------: | ----:
❓ | Dayanna Bohorquez[^Dayanna] | [Medical Expenditure Panel Survey 2023](https://meps.ahrq.gov/data_stats/download_data_files_detail.jsp?cboPufNumber=HC-247) | Out-of-pocket burden | Insurance type (2 levels) | 791 *subjects with cancer*
**NO** | Johnathan Huff[^Johnathan] | [NFL Statistics: Career_Stats_Defensive](https://www.kaggle.com/datasets/kendallgillies/nflstatistics?select=Career_Stats_Defensive.csv) | Tackles made in a season | Defensive Position | *will change*
❓ |  Scout Osborne[^Scout] | PROTECT (Predicting Response to Standardized Colitis Therapy) Study: [Table 6 in this article](https://doi.org/10.1016/j.chom.2018.09.009) | fecal calprotectin levels | relative abundance of the bacterial species H. parainfluenzae | 368

### NHANES Study Plans not yet approved

OK? | Investigator(s) | Survey Dates | S2 Outcome | S2 Key Predictor | Subjects
:--: | :-------------------------------------: | :------------------: | :--------------------: | :--------------------: | ----:
❓ | Jiakun Wang[^Jiakun] | 2017 to 3/2020 | mean of `BPXOSY1`, `BPXOSY2`, `BPXOSY3` systolic blood pressure (mm Hg) | `BMXBMI` body mass index (kg/m2) | 7,007
❓ | Leland Metheny[^Leland] | 8/2021 to 8/2023 | `LBDNENO` Segmented neutrophils (1000 cell/μL) | *to be clarified* | 2,242
❓ | Sadia Ahmed[^Sadia] and Erin San Valentin | 2017 to 3/2020 | `SLD012` and `SLD013` to calculate average hours of weekly sleep debt | `OCQ180` work hours last week | 4,015 

----

## Approved Study Plans

### Approved Non-NHANES Study Plans

OK? | Investigator(s) | Data Source | S2 Outcome | S2 Key Predictor | Subjects
:--: | :-------------------------------------: | :-----------------------------: | :-----------------: | :-----------------: | ----:
✔️ | Andrew Crawford | [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/) | ICU length of stay | average hemoglobin level during ICU stay | 6,899 ICU patients with a single stay
✔️ | Dana Kleinman | [National Health Interview Survey](https://www.cdc.gov/nchs/nhis/documentation/2024-nhis.html), 2024 Adult Sample | average hours of sleep per night | cardiovascular physical activity (3 levels) | 1,074
✔️ | Fai Albuainain & Avianna Thompson | [National Health Interview Survey](https://www.cdc.gov/nchs/nhis/documentation/2024-nhis.html), 2024 Adult Sample | days missed work  in past 12m | asthma episode/attack  in past 12m | 450
✔️ | Fangzhou (Eric) Liu | [Environmental Justice Index](https://www.atsdr.cdc.gov/place-health/php/eji/eji-data-download.html) | % of tract residents ages 16+ who are unemployed | % of racial/ethnic minority residents | 7,000 *US census tracts*
✔️ | Hana Sato | [National Health Interview Survey](https://www.cdc.gov/nchs/nhis/documentation/2024-nhis.html) | Family income ratio (vs. poverty) | Race in the household (4 levels) | 3,825 *people representing Midwest households*
✔️ | Moses Fleischman | [Behavioral Risk Factor Surveillance System](https://www.cdc.gov/brfss/annual_data/annual_2024.html), 2024 | Days in past 30 when mental health was not good | Adult made the respondent feel safe/protected during childhood (5 levels) | 10,000
✔️ | Noni Pinales & Swati Jha | [National Survey of Family Growth](https://www.cdc.gov/nchs/nsfg/nsfg-2022-2023-puf.htm), 2022-2023 - Female Respondent File | Lifetime count: use of emergency contraception | Male parental figure status (3 levels) | 1,460 women ages 15-49
✔️ | Phia Ribeiro & Annabelle Elsner Pacheco | [Portuguese student performance](https://archive.ics.uci.edu/dataset/320/student+performance) | Final grade in Mathematics | Final grade in Portuguese | 382
✔️ | Pooja Madan Mohan and Noha Orabi | ([Global Coral Bleaching Database (NCEI Accession 0228498)](https://www.ncei.noaa.gov/archive/archive-management-system/OAS/bin/prd/jquery/accession/download/228498)) | Percent bleached | Depth of site | 2,427 coral reef sites
✔️ | Subin Lee | [2025 Annual Social and Economic Supplements Data](https://www.census.gov/data/datasets/time-series/demo/cps/cps-asec.html) | Total medical out-of-pocket expenditure ($) in 2024 | Total family earnings ($) in 2024 |  1,354
✔️ | Vennila Ramasubramanian and Paulina Gonzalez | [BRFSS 2023](https://www.cdc.gov/brfss/annual_data/annual_2023.html) | Body Mass Index | Educational Attainment (4 levels) | 8,859

### Approved NHANES Study Plans

OK? | Investigator(s) | Survey Dates | S2 Outcome | S2 Key Predictor | Subjects
:--: | :-------------------------------------: | :------------------: | :--------------------: | :--------------------: | ----:
✔️ | Alex Bergendorf | 8/2021 to 8/2023 | `LBXHSCRP` HS C-reactive protein (mg/dl) | `PUQ100` Are products used in the home to control insects? (yes/no) | 2,268
✔️ | Amanda Barabas | 8/2021 to 8/2023 | `LBXSATSI` Alanine Aminotransferase (ALT) (IU/l) | `PUQ100` Are products used in the home to control insects? (yes/no) | 6,366
✔️ | Amjad Samara | 8/2021 to 8/2023 | `LBDLDL` LDL cholesterol (mg/dl) | `BMXBMI` body mass index (kg/m2) | 3,192
✔️ | Andrew Morris | 8/2021 to 8/2023 | `BPXOSY1` systolic blood pressure (mm Hg), 1st reading | `HUQ042` Place most often go for health care (5 levels) | 532
✔️ | Ben Kwiatkowski | 8/2021 to 8/2023 | `SLD012` Weekday sleep hours | `KIQ481` Times per night waking to urinate (0-4 or 5+) | 4,843
✔️ | Cher Yuan | 8/2021 to 8/2023 | `BMXBMI` Body Mass Index | `DMDMARTZ` Marital Status (3 levels) | 5,000
✔️ | Hannah-Beth Iqbal and Comelia Soltanirad | 8/2021 to 8/2023 | `LBXTC` Total cholesterol (mg/dl) | `INDFMPIR` Ratio of family income to poverty | 4,337
✔️ | Helena Zhao | 8/2021 to 8/2023 | `BPXOSY1` systolic blood pressure (mm Hg), 1st reading | `BMXBMI` body mass index (kg/m2) | 3,000
✔️ | Janetta Brundage and Leah Nez | 8/2021 to 8/2023 | `SLD012` Weekday sleep hours | `DMDMARTZ` Marital Status (3 levels) | 1,074
✔️ | Jiayi Sun | 8/2021 to 8/2023 | `LBXVIDMS` Vitamin D: 25OHD2 + 25OHD3 (nmol/L) | `INDFMPIR` Ratio of family income to poverty | 518 *age 4 to 19*
✔️ | Kuangtsan (Wilson) Hsu & Ching-Wen Mai | 8/2021 to 8/2023 | `LBXVIDMS` 25OHD2+25OHD3 (nmol/L) | `PAD680` Minutes of Sedentary Activity per day | 1,584 <br> *age 50-64*
✔️ | Lauren Sapienza | 8/2021 to 8/2023 | `SLD012` Weekday sleep hours | `DPQ020` feeling down, depressed, hopeless in past 2 weeks (4 levels) | 1,896
✔️ | Lily Zhang | 8/2021 to 8/2023 | `SLD012` Weekday sleep hours | `PAD790Q` & `PAD790U` Times engaged in moderate leisure-time physical activity per week (4 groups) | 1,531
✔️ | Madison Albert | 8/2021 to 8/2023 | `LUXSMED` Median Liver Stiffness (kPa) | `BMXWAIST` Waist circumference (cm) | 3,226
✔️ | Shufei Fang & <br> Ruoying Chen | 8/2021 to 8/2023 | `LBXTC` Total cholesterol (mg/dl) | `LBXWBCSI` White blood cell count (1000 cells / μl) | 1,994
✔️ | Valerie Lam | 2017 to 3/2020 | `LBXIN` insulin (μU/mL) | `BMXHIP` hip circumference (cm) | 1,795 *women*

----

[^Dayanna]: Dayanna: Two questions: (1) Is the outcome describing out-of-pocket costs in 2023, or in some other year? (2) Is the insurance information only binary or are there more than two categories, like public, private, uninsured? It would be better if there were 3 or more categories for your key predictor. Please email me your response to these questions, ideally before noon Wednesday.
[^Johnathan]: Johnathan: This is a problem in several ways. (1) The data are old. Newer information on the same subject is available elsewhere. (2) The data are from Kaggle, which I didn't expressly forbid here, but I probably should have. The Kaggle data are already pre-canned for you, and I don't love that. (3) You cannot use multiple years of the same player for this project, so you must filter the data to look at either all of the players in one specific season, or maybe all players in one season and then one other season far enough away in time that there is no overlap in players, so, for example, data on 2000 and 2024 (where the year would become one of your predictors.) (4) You would need to specify which position categories you plan to study (since many players in the Kaggle set have missing data in the Position column) (5) You also need tell me what other predictors are that you are planning to include in Study 2 in order for me to approve this. So that's a lot to deal with here, but if you still want to try with these data, or (better) a combination of multiple data sets from the Kaggle site, or (better still) getting the data yourself from NFL's statistics site or something like football-reference.com, I am willing to consider it. In the meantime, though, you will need to email me about how you'd like to proceed, ideally by the noon Wednesday deadline.
[^Scout]: Scout: Can you email me both the units of measurement and the range you observe (minimum and maximum) for your outcome and key predictor, ideally by the noon Wednesday deadline?
[^Jiakun]: Jiakun: Either (a) take a random sample of 4,000 of these subjects between the ages of 21 and 79 for your Project B, please, or, if you prefer, (b) focus on a single sex, or a smaller age range, or some other inclusion criterion that focuses your sample on less than 4,000 subjects. Personally, I would prefer you to choose option (b). Please email me to let me know you've seen this and what you will do, so I can correct the size above and then remove this note.
[^Leland]: Leland: You need to specify for me (1) exactly what variable you will use as your key predictor to describe alcohol use, and tell me (if it is categorical) how many levels it has (outside of things that should be treated as missing) or (if it is quantitative) what the range is, and how this affects your number of subjects. Then (2) You also need to be more accurate about what you present in the subjects section. If you are using data from one cycle of NHANES, you shouldn't be talking about every year since 1960, and you should also be specifying the age range for the subjects you intend to study. Please email me your response to these thoughts, ideally before noon Wednesday.
[^Sadia]: Sadia and Erin: You need to (1) tell me exactly how you will calculate average hours of sleep debt in detail, including what "recommended number of sleep hours" you are planning to use, and the source of that recommendation, (2) specify much more than you did in the "Subjects, and selected how?" section of the form, in particular specifying what age range you will limit your NHANES subjects to in this work, and (3) tell me how you're going to deal with the fact that so many of your key predictor values are going to be 40 (with many of the rest being 20, 30, 35, 45, 50 and 60) *and* what you're going to do about people who worked less than 6 or more than 78 hours. Please email me your responses to each of these thoughts, ideally before noon Wednesday.
