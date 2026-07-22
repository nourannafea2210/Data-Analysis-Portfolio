# Project Goals
he primary goal of this project is to analyze and quantify the relationship between digital habits—specifically screen time and notification frequency and 
key mental health indicators across a diverse dataset of 7,000 participants.


# Stages
 - Data Cleaning & Preprocessing
 - Exploratory Data Analysis (EDA) & Pattern Identification
 - Feature Engineering & Target Encoding
 - Predictive Modeling & Evaluation
 - Insights & Data-Driven Recommendations
# Data Cleaning & Preprocessing
 - Handled missing values by imputing missing sleep hours and cleaning incomplete demographics
 - Applied the Interquartile Range (IQR) method across numeric features to effectively identify and manage outliers
# Exploratory Data Analysis (EDA) & Pattern Identification
 - Analyzed screen time metrics against mental health indicators,
   revealing a strong positive correlation between screen hours, anxiety, life satisfaction, and sleep
   
   ![plot1](https://github.com/nourannafea2210/Data-Analysis-Portfolio/blob/main/Screenshot%202026-07-22%20004350.png)
   
 - Identified platform-specific usage trends, highlighting Instagram, TikTok, and YouTube as primary drivers of high engagement
# Feature Engineering & Target Encoding
 - Encoded wellbeing categories (At-risk, Moderate, Good) into numeric targets to evaluate behavioral differences across user segments
 - Selected anxiety score as the primary predictor for wellbeing risk based on feature correlation strength
# Predictive Modeling & Evaluation
 - Trained and evaluated a Simple Linear Regression model to predict wellbeing tiers based on anxiety levels
 - Achieved a strong $R^2$ score of 0.74, demonstrating high predictive accuracy for user mental health risk
# Insights & Data-Driven Recommendations
 - Demonstrated how high daily notifications and late-night usage directly correlate with reduced sleep and lower life satisfaction
 - Provided clear recommendations for digital detox limits and platform usage awareness to promote mental wellbeing
