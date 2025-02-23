# Predicting Unemployment Rates in Australia: A Machine Learning Approach

[![View Analysis](https://img.shields.io/badge/View-Full_Analysis-blue)](https://htmlpreview.github.io/?https://github.com/yourusername/australian_covid_unemployment/blob/main/index.html)

## Project Overview
The goal of this project was to develop models to predict unemployment rates in Australia by analyzing various economic indicators. This project covered data from 1980 to 2020, including the initial impact of the COVID-19 pandemic.

### 1. The Challenge
The goal was to predict Australia's unemployment rate using economic data. Achieving this could have several positive impacts across different areas:
- Business planning for hiring strategies
- Governments policy development
- Greater understanding of economic trends

### 2. The Data
I worked with quarterly data from the Australian Bureau of Statistics that included:
- Consumer Price Index (CPI)
- Population estimates
- Job vacancy numbers
- Government spending figures
- Trade information
- Overall economic growth rates

### 3. The Approach
I tested two different machine learning methods:

1. Support Vector Regression (SVR):
   - Think of this like drawing the best possible line through complex data points
   - Good at handling curves and patterns in data
   - Generally easier to understand how it makes decisions

2. Neural Network:
   - Works similarly to how our brain processes information
   - More complex but potentially more powerful
   - Better at catching subtle patterns in data

### 4. Key Findings
- The Neural Network performed significantly better:
  - Training accuracy: 95% (compared to 70% for SVR)
  - Testing accuracy: 73% (compared to 20% for SVR)
  - Could better predict unusual events like COVID-19's impact

- Trade-offs:
  - Neural Network took about 2 seconds to process (vs 0.08 seconds for SVR)
  - Neural Network was harder to interpret but gave better results

### 5. Real-World Impact
The project demonstrated that:
- Complex economic predictions are possible with machine learning
- Neural networks can spot patterns that simpler models miss
- We can predict unemployment trends with reasonable accuracy, even during unusual events like COVID-19

### 6. Future Improvements
I identified several ways to make the predictions even better:
- Include more historical data
- Add international economic indicators
- Use monthly instead of quarterly data to catch trends sooner
- Include more data about government policies and spending

This project combined economic analysis with cutting-edge machine learning techniques to tackle a real-world problem that affects millions of people's lives.

## Repository Structure
```
.
├── README.md
├── index.html          # Full analysis with visualizations
├── Unemployment Prediction Portfolio.Rmd                 # R scripts for analysis
└── data/              # Data files
```

## Technologies Used
- R
- neuralnet
- e1071 (SVR)
- ggplot2
- tidyverse

## How to View
Click the "View Analysis" badge at the top of this README or [click here](https://htmlpreview.github.io/?https://github.com/yourusername/australian_covid_unemployment/blob/main/index.html) to see the full analysis with interactive visualizations.