# SAT-Scores-and-Loan-Repayment-Rates

# Overview

This analysis investigates the relationship between SAT average scores at colleges and the three-year loan repayment rates. The study aims to explore how SAT scores correlate with graduates' financial reliability post-education.

# Dataset

The dataset includes various educational statistics, but this analysis focuses on:

SAT_AVG: Average SAT score.
COMPL_RPY_3YR_RT: Three-year loan repayment rate.
LOCALE: Geographical location of the colleges.
Tools and Libraries Used

R Language: Used for data manipulation and analysis.
Libraries: dplyr, ggplot2, broom.
Methods

# Data Preprocessing
Simplification of the dataset to three columns and recoding of location data into categorical types (City, Suburb, Town, Rural).
# Exploratory Data Analysis
Visual examination using scatter plots and histograms to understand the distribution and correlation of the data.
# Statistical Analysis
Linear Regression: To model the relationship between SAT scores and repayment rates.
# Summary Statistics
Calculation of mean, median, and standard deviation for key variables.

# Key Findings

A positive correlation exists between SAT scores and loan repayment rates, suggesting that higher academic scores are indicative of better financial reliability post-graduation.
The location does not significantly influence the repayment rate except in suburbs, where it tends to be lower regardless of SAT scores.
Files Structure

Data/: Contains the dataset used for analysis.
Scripts/: R scripts for preprocessing, analysis, and visualization.
Output/: Generated plots and model summaries.

# Conclusion

The project concludes that SAT scores are a significant predictor of loan repayment rates, which could help in assessing the financial risk associated with lending to students from different academic backgrounds.

