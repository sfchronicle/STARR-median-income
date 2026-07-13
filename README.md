# STAAR-median-income

Critics of standardized testing have long argued that wealthier students have a distinct advantage.

Academic research has largely focused on the SAT and ACT, with a study by the Brookings Institution finding that students whose household income is greater than $200k outscore students whose household income is less than $20k by almost 300 points.

I could not find any publicly available research connecting wealth to STAAR scores. 

Texas students are required to pass 5 EOC STAAR tests to graduate high school. Elementary and middle school students may be held back for failing.

At the district level, consistently poor performance may lead to state intervention or even takeover.

The 2020-2024 ACS survey provides median household income by Unified School District. The Texas Education Agency recently released detailed results for the Spring 2026 STAAR administrations by district. Though both these datasets are imperfect (see notebooks for details), we can build a pretty strong OLS regression model using income to predict passing-rate statewide.

From there, we can also isolate districts that overperform and underperform based on their income level. We can also focus on trends in the San Antonio-area and Austin metro.

This analysis can be repurposed for any market in Texas.

# Sources

NHGIS (IPUMS). 2020–2024 American Community Survey (ACS) 5-Year Estimates, Table B19013 (Median Household Income), Texas Unified School District geography.
Dataset: nhgis0001_ds272_20245_sd_uni.csv
Available from: https://data2.nhgis.org/ (IPUMS account required)

Texas Research Portal. Texas STAAR assessment results (End-of-Course and Grades 3–8).
https://txresearchportal.com/

Texas Education Agency (TEA). Texas school district directory and district identification numbers.
https://tealprod.tea.state.tx.us/TEA.AskTED.TSD/TSDfiles/tsd2000/psdlasbo.pdf

Brookings Institution. "Students need more than an SAT adversity score—they need a boost in wealth."
https://www.brookings.edu/articles/students-need-more-than-an-sat-adversity-score-they-need-a-boost-in-wealth/
