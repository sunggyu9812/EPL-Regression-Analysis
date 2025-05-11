# ⚽ English Premier League Variable Prediction

This project analyzes the 2018/2019 English Premier League season to identify which team performance metrics significantly impact final league position. The analysis is performed using multiple linear regression in R, with a focus on exploratory data analysis, model diagnostics, and transformation techniques.

---

## 🔍 Project Summary

- Cleaned a dataset containing **268+ variables**, narrowing down to 6 statistically meaningful predictors  
- Conducted exploratory data analysis using scatterplots, residual plots, and QQ plots  
- Identified and addressed violations of normality using **square root transformation** and **Box-Cox diagnostics**  
- Improved adjusted R² from **0.76** to **0.85**, enhancing the model’s explanatory power  

---

## 📊 Tools & Technologies

- **Language**: R  
- **Libraries**: `tidyverse`, `dplyr`, `car`, `ggplot2`  
- **Output Formats**: `.Rmd` (source), `.md` (rendered), PDF (optional)  

---

## 📁 Repository Contents

| File                  | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `epl_analysis.rmd`    | Full R Markdown file with code, analysis, and narrative                     |
| `epl_analysis.md`     | 📄 **Rendered version of the report** (best viewed on GitHub — like a PDF)   |
| `epl_analysis_files/` | Auto-generated folder containing plots and figures                          |

---

## 📎 Data Source

- [FootyStats EPL Team Stats (2018/19)](https://footystats.org/download-stats-csv)

---

## 🧠 Key Takeaways

- **Average Possession** and **Expected Goals (xG)** are statistically significant predictors of final league position  
- Model diagnostics and transformation steps (e.g., Box-Cox) are critical for valid regression modeling  
- Demonstrates hands-on skills in **regression**, **EDA**, and **technical report writing** using R and R Markdown

Average Possession and Expected Goals (xG) are statistically significant predictors of final league position

Model diagnostics (residuals, QQ plots, Box-Cox) are essential for validating assumptions

Demonstrates practical skills in regression modeling, EDA, statistical correction, and professional report writing in R
