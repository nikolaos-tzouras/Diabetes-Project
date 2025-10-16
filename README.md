🩺 Factors Affecting Diabetes – Data Analysis Project

Author: Nikolaos Tzouras
Date: October 2025

🧠 About This Project

This project investigates how demographic, behavioral, and clinical factors influence the likelihood of having diabetes, using data from the NHANES (National Health and Nutrition Examination Survey).
The analysis explores how variables like Age, Gender, BMI, Smoking Status, Total Cholesterol and Self-Rated Health are associated with diabetes, using descriptive statistics and logistic regression modeling.

The work combines data cleaning, exploratory data analysis, predictive modeling, and model validation, resulting in a comprehensive and reproducible research report built entirely in R Markdown.

📊 Key Highlights

Age and BMI are the strongest and most consistent predictors of diabetes.

Individuals who rate their general health as “Poor” have 6× higher odds of diabetes.

Gender and Smoking Status show smaller, non-significant effects.

Including Total Cholesterol improves model performance slightly but its inverse association likely reflects treatment or behavior effects.

All models achieved AUC > 0.80, demonstrating strong predictive accuracy.

The Adjusted Model (with Cholesterol) and Stepwise Model were the most robust and stable specifications.

📁 What You Will Find
File	Description
Diabetes_Project_Analysis.Rmd	R Markdown source file with all code, analysis, tables, and plots
Diabetes_Project_Analysis.html	Rendered report (HTML format)

⚙️ Tools & Methods
🧩 Tools
R packages:
NHANES, ggplot2, dplyr, tidyr, pROC, car, ResourceSelection, kableExtra, tidyverse

🧮 Methods
-Data preprocessing & missing value handling
-Descriptive statistics (categorical & continuous variables)
-Visualization using ggplot2
-Binary Logistic Regression models
-Sensitivity Analysis: Core, Adjusted, and Stepwise models

Model Diagnostics:
-Odds Ratios (OR) with 95% CI
-Variance Inflation Factor (VIF) for multicollinearity
-Hosmer–Lemeshow goodness-of-fit test
-ROC curves and AUC metrics for predictive performance

🔍 Methodology Summary
Five logistic regression models were compared to evaluate stability and robustness:
Model	Description:
-Core (No Cholesterol)	Includes Age, Gender, BMI, and Smoking Status
-Core (With Cholesterol)	Adds Total Cholesterol
-Adjusted (No Cholesterol)	Adds Race, Education, Physical Activity, Depression, Self-Rated Health
-Adjusted (With Cholesterol)	Includes Total Cholesterol
-Stepwise Adjusted (With Cholesterol)	AIC-based selection of optimal predictors

All models were evaluated using Likelihood Ratio Tests, VIF, Hosmer–Lemeshow Tests, and ROC–AUC.
The Adjusted Model (With Cholesterol) achieved the best balance between simplicity and predictive power (AUC ≈ 0.851).

🚀 How to Explore
Install Dependencies
install.packages(c("NHANES", "ggplot2", "dplyr", "tidyr", "scales",
                   "gridExtra", "pROC", "knitr", "tidyverse",
                   "ResourceSelection", "car", "kableExtra"))
Open and Run
Open Diabetes_Project_Analysis.Rmd in RStudio.

Click Knit → Knit to HTML to reproduce the full report.

View Results

Plots: Distributions, proportions, and ROC curves.

Tables: Summary stats, Odds Ratios, and model diagnostics.

📈 Key Insights
Older, heavier, and less physically active individuals are significantly more likely to have diabetes.

Self-rated poor health is a strong indicator of diabetes presence.

Including Total Cholesterol refines model fit but doesn’t change overall trends.

The Stepwise Model confirms that simplifying the model retains predictive strength.

🧾 Interpretation Notes

This analysis is cross-sectional — associations should not be interpreted as causal.

The inverse link with cholesterol likely reflects diabetes management (medication or diet), not protective effects.

All findings are statistically valid but should be contextualized within broader clinical research.

🧰 Skills Demonstrated

Data wrangling and preprocessing

Statistical modeling and interpretation

Advanced visualization in R

Reproducible reporting with R Markdown

Model evaluation and diagnostic interpretation

📬 Contact

Author: Nikolaos Tzouras
📧 tzourasnikos@gmail.com

📜 License
Feel free to use, adapt, and share with proper attribution.
