# Project B Materials

Project B Registration status is [now available here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/registration.md).

## Schedule for Project B Presentations

The schedule will be [posted here](https://github.com/THOMASELOVE/431-classes-2025/blob/main/projectB/schedule.md) on Friday 2025-11-14.

---

## Important Notes

1. The count of complete cases we ask for is across **ALL** your variables to be used in Study 2, not just the outcome and key predictor. Be sure to get this right, including properly treating Refused and Don't Know as missing in all variables before making your count.
2. If you have more than the maximum allowable number of observations (10,000 for Non-NHANES studies, and 7,500 for NHANES studies), I encourage you to either (a) focus on a single sex (either females only or males only), or restrict the age range, or apply some other simply explained inclusion criterion that focuses your sample down below the maximum (maybe to about 4,000 subjects), or (b) *a less good solution* take a random sample of, say, 4,000 complete cases from your sample.
3. Anyone working with **NHANES** data should have an age restriction, either to **adults** (which can be ages 21-79 or 18-79 or some smaller group within that range) or **children** (which should be determined depending on how the data are gathered, and include only people under a certain age - and perhaps above one, too, like 6 to 17 years old, for example) **or** provide me with a good reason as to why I should let you use some sort of mixed group including both adults and kids.
4. For **NHANES** studies, if you get names instead of numbers in your categorical variables when using the `nhanes()` function in the **nhanesA** package, you can either work with those names, or try adding `translated = FALSE`, as in `demo <- nhanes("DEMO_L", translated = FALSE)` to your call to the `nhanes()` function.

---

