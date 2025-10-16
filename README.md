🩺 Factors Affecting Diabetes – Data Analysis Project

- Author: Nikolaos Tzouras
- Date: October 2025


🧠 About this Project

- This project examines how demographic, behavioral, and clinical factors influence the likelihood of having diabetes, using data from the NHANES (National Health and Nutrition Examination Survey).

- The analysis explores the effects of Age, Gender, BMI, Smoking Status, Total Cholesterol, Physical Activity, Self-Rated Health, and other variables to understand their association with diabetes.

- The work combines data cleaning, descriptive statistics, and logistic regression modeling with a detailed sensitivity analysis to evaluate the stability and accuracy of results.


📊 Key Highlights

- Age and BMI are the strongest and most consistent predictors of diabetes.

- Participants who rated their health as “Poor” were around six times more likely to have diabetes.

- Gender and Smoking Status showed smaller, mostly non-significant effects.

- Adding Total Cholesterol slightly improved model performance but likely reflects treatment or lifestyle adjustments.

- All models achieved AUC > 0.80, demonstrating strong predictive accuracy.


📁 What You Will Find

- Diabetes_Project_Analysis.Rmd → The complete R Markdown file containing the data cleaning, analysis, models, and visualizations.

- Diabetes_Project_Analysis.html → The rendered report with all plots, tables, and results, viewable in any browser.


⚙️ Tools & Methods

🧩 Tools

- Language: R

Key Packages:
- NHANES, ggplot2, dplyr, tidyr, pROC, car, ResourceSelection, kableExtra, tidyverse


🧮 Methods

- Descriptive statistics and exploratory visualizations

- Logistic regression models (Core, Adjusted, and Stepwise)

- Sensitivity analysis with model comparison

Model diagnostics:

- Odds Ratios (OR)

- Variance Inflation Factor (VIF)

- Hosmer–Lemeshow Goodness-of-Fit Test

- ROC–AUC evaluation


🚀 How to Explore

- Open Diabetes_Project_Analysis.Rmd in RStudio to view or run the full analysis.

- Knit the file to HTML to reproduce the complete report.

Or simply open Diabetes_Project_Analysis.html in your web browser to explore the final output.



💡 Project Motivation

This project was developed to explore how everyday health and lifestyle indicators contribute to diabetes risk. It demonstrates how data-driven approaches can be used to identify key public health insights and evaluate predictive models in a transparent, reproducible way.



🧾 Contact

📧 [tzourasnikos@gmail.com]
🔗 [www.linkedin.com/in/
nikolaos-tzouras]

