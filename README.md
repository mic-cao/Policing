# Categorical Data Analysis - Policing

### Authors:
Michael Cao, Taren Daniels, Aristotle Kolefas  
**Net ID:** yc849, tbd33, aak99  

---

## Executive Summary

In this study, we investigate the factors influencing the treatment of individuals charged with possessing small amounts of marijuana after arrest. Through statistical analysis, we identify significant predictors affecting whether individuals are taken to court or detained. Our findings reveal race, employment status, citizenship, year of arrest, the number of databases individuals appear in, and age as crucial factors. We demonstrate that blacks are disproportionately held compared to whites, highlighting potential biases in law enforcement practices. Recommendations for policy implications and future research are provided.

## Introduction

The debate surrounding marijuana legality in the United States has raised questions about disparities in law enforcement treatment of offenders. Despite the severity of the offense being controlled, personal attributes may influence treatment post-arrest. We analyze a dataset containing various predictors, including race, sex, prior traffic violations, region, employment, citizenship, and age, to discern patterns in detention or court proceedings. Our goal is to identify biases and inform potential legislative changes.

## Data Cleaning

Before analysis, we preprocess the dataset by removing missing values, outliers, and duplicates. Certain predictors are transformed for meaningful interpretation, such as collapsing categories for databases and re-encoding the year variable. Through chi-square tests, we determine significant predictors associated with being held in jail, including race, employment status, citizenship, and year.

## Results

Our logistic regression model, incorporating significant predictors and interactions, provides insights into detention probabilities. Key findings include:

- Blacks are more likely to be held than whites, even when controlling for other variables.
- Unemployment and non-citizenship increase the likelihood of detention.
- The number of databases positively correlates with the probability of being held.
- Arrests between 2001-2003 are associated with higher detention rates compared to 2004-2006.
- Age influences detention probabilities, with younger individuals more likely to be detained.

## Discussion

Our analysis reveals disparities in the treatment of marijuana offenders, suggesting potential racial profiling and systemic biases. Future research avenues include examining additional predictors such as income, police presence, and officer demographics. Legislative changes informed by our findings could mitigate unjust detention practices and their impact on affected communities.

---

For more details, refer to the [full report](https://github.com/mic-cao/Policing/blob/main/Written%20Report.pdf).
