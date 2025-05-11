# English Premier League Variable Prediction

This project analyzes the 2018/2019 English Premier League season to identify which team performance metrics significantly impact final league position. The analysis is performed using multiple linear regression in R, with a focus on model diagnostics and transformation.

## 🔍 Project Summary

- Cleaned a dataset containing 268+ variables to focus on 6 statistically meaningful predictors
- Conducted exploratory data analysis using scatterplots, residual plots, and QQ plots
- Detected violations of normality and corrected them using a square root transformation and Box-Cox diagnostics
- Improved adjusted R² from **0.76 to 0.85**, indicating stronger explanatory power in the transformed model

## 📊 Tools & Technologies

- **Language**: R
- **Libraries**: `tidyverse`, `dplyr`, `car`, `ggplot2`
- **Output Format**: R Markdown (`.Rmd`) and PDF/HTML (optional)

## 📁 Files

- `Title.rmd`: The full R Markdown file containing all analysis and code
- `Title.md`: Markdown render of the report
- `Title_files/`: Folder containing plot images generated from the `.Rmd`

## 📎 Data Source

- EPL team performance data for the 2018/19 season sourced from:  
  [https://footystats.org/download-stats-csv](https://footystats.org/download-stats-csv)

## 🧠 Key Takeaways

- **Average Possession** and **Expected Goals (xG)** are statistically significant predictors of league performance
- Model diagnostics and transformation steps (Box-Cox, residual analysis) play a critical role in model validity
- Demonstrates practical skills in regression modeling, EDA, and report writing in R

---

