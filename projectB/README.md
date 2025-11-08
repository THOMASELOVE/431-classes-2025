# Project B Materials

## Schedule for Project B Presentations

The schedule will be [posted here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md) on Friday 2025-11-14.

## Registration Status

As each group's [Project B Registration Form](https://bit.ly/431-projB-registration-2025) is submitted, I will list the investigators below. 

### Non-NHANES Study Plans

OK? | Investigator(s) | Data Source | S2 Outcome | S2 Key Predictor | Subjects
:--: | :-------------------------------------: | :-----------------------------: | :-----------------: | :-----------------: | ----:
❓ | Fai Albuainain[^Fai]. | [National Health Interview Survey](https://www.cdc.gov/nchs/nhis/documentation/2024-nhis.html), 2024 Adult Sample | days missed work  in past 12m | asthma episode/attack  in past 12m | 1392
❓ | Dana Kleinman[^Dana]. | [National Health Interview Survey](https://www.cdc.gov/nchs/nhis/documentation/2024-nhis.html), 2024 Adult Sample | # of diagnosed health conditions | cardiovascular physical  activity (3 levels) | 1106
**NO** | Subin Lee[^Subin] | [National Hospital Care Survey](https://www.cdc.gov/nchs/nhcs/data/index.html), 2021 | *needs to change* | *needs to change* |  TBD

### NHANES Study Plans

OK? | Investigator(s) | Survey Dates | S2 Outcome | S2 Key Predictor | Subjects
:--: | :-------------------------------------: | :------------------: | :--------------------: | :--------------------: | ----:
✔️ | Cher Yuan[^Cher] | 8/2021 to 8/2023 | `BMXBMI` Body Mass Index | `DMDMARTZ` Marital Status (3 levels) | 5000
❓ | Lily Zhang[^Lily] | 8/2021 to 8/2023 | `SLD012` Weekday sleep hours | `PAD790Q` Times engaged in moderate leisure-time physical activity per week | 1099
✔️ | Ben Kwiatkowski[^Ben] | 8/2021 to 8/2023 | `SLD012` Weekday sleep hours | `KIQ481` Times per night waking to urinate (0-4 or 5+) | 4843
✔️ | Shufei Fang[^Shufei] & <br> Ruoying Chen | 8/2021 to 8/2023 | `LBXTC` Total cholesterol (mg/dl) | `LBXRBCSI` Red blood cell count (million cells / μl) | 5669


[^Fai]: Fai: (a) Does the count of 1392 subjects refer specifically to 1392 subjects with a diagnosis of asthma? (b) I want to see a tabyl of the outcome variable and the key predictor (2 levels) before I'll give final approval.
[^Dana]: Dana: (a) Diagnosed health conditions is a count, which for most people in your sample of 1106 will be either 0, 1, or 2. We need more variation than that in an outcome for this project, so I am concerned. (b) I want to see a tabyl of the outcome variable and the key predictor (3 levels) within your sample before I'll give final approval.
[^Subin]: Subin: You suggest the data describe individual people, but the outcome you propose (in-hospital mortality) is binary if it is about individual people, and you need a quantitative outcome, not a categorical one. Also, your proposed key predictor is age, which you propose to categorize. You want a quantitative predictor if at all possible. So I cannot accept this, as you've planned it, and you'll need to try again.
[^Cher]: (a) There are only three meaningful levels in your cardiovascular physical activity variable: levels 4 (Refused) and 5 (Don't Know) should be recoded as missing. (b) I assume your sample will be restricted to those with both a known `BMXBMI` and a `DMDMARTZ` in levels 1 (Married) 2 (No Longer Married) or 3 (Never Married). If that is correct, then I approve your project. If not, please contact me.
[^Lily]: You suggested that all `PAD790Q` values are 1 or more, but what about the zeros? Are you excluding them, and if so, why?
[^Ben]: I would treat the predictor as quantitative here, and assign 5 to all of the 5+ people. When possible, a quantitative key predictor is appealing for a variety of reasons.
[^Shufei]: Since you didn't specify the NHANES variable names, I am assuming I have the right ones here. If I do not, then please let me know immediately.
