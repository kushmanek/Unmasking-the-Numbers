# Unmasking-the-Numbers
COVID-19’s Effect on Jobs, Markets, and Growth Analyzing the Economic Impact of COVID-19 in the US Through Statistics

A statistical exploration of the economic impact of the COVID-19 pandemic in the United States, analyzing its effects on employment, financial markets, and public health using data visualization, modeling, and interactive tools.

Instructor: Professor Arjun Banik

Institution: University of Victoria

Date: April 4th, 2025

👩‍💻 Team Members
Thamy Soares

Kush Manek

Sarah Sandmeier

Xueying Lin

🎯 Project Objective
To statistically analyze and visualize how COVID-19 influenced:

U.S. unemployment trends and initial claims

Stock market movements in tech (VGT) and healthcare (VHT)

Case and death rates across age, gender, region, and race/ethnicity

🧠 Research Questions
How did COVID-19 affect jobs, financial markets, and economic growth in the US?

Are there demographic disparities in COVID-19 outcomes?

What predictive insights can we derive from historical data?

🧼 Data Sources & Cleaning
Data Sources

Stock data from Yahoo Finance

Unemployment and claims data from FRED

COVID-19 data from CDC Open Data Portal

Cleaning Methods

Converted and normalized date formats

Removed suppressed/missing values

Created new features (e.g., average_movement)

Region-based encoding for states

Stored cleaned datasets in .csv format

📈 Visualizations & Tools
ggplot2 used to plot:

Time-series of stock indices VGT & VHT

Unemployment claims and rates

COVID-19 cases and deaths by sex, age, race, and region

Shiny App:
Live interactive map of COVID-19 cases and deaths by U.S. state
▶️ Try the app

📊 Statistical Analysis
Time Series Modeling: SARIMA models for stock forecasts

Linear Regression:

Unemployment rate vs claims

COVID death rate by age and sex

Multiple Linear Regression:

COVID-19 case rate by age, sex, race

Significance Testing:
T-tests, Mann-Whitney U, and ANOVA for demographic comparisons

📌 Key Findings
Stock Markets: Tech (VGT) and Healthcare (VHT) showed initial dips followed by strong post-COVID recovery.

Unemployment: Peaked around April 2020 (~15%) with over 6 million claims in one week.

Demographics:

Males had higher death rates despite fewer total cases.

Older adults (75+) had the highest mortality.

Hispanics had the highest case rates; Whites and Asians had the lowest.

🧠 Insights
The economic recovery was gradual but strong, especially in key sectors.

Death and case rates varied significantly across demographic groups.

Data modeling can be a powerful tool for guiding policy decisions and emergency preparedness.

References
All sources are listed in the final report. Key data was obtained from:

CDC Open Data Portal

FRED Economic Data

Yahoo Finance

Published economic research on COVID-19
