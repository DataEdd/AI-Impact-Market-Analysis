# AI Automation Risk Analysis 🚀

This project, part of the STA141A course at UC Davis, explores whether certain job sectors are at higher risk of automation by AI. Using statistical tests and the K-Nearest Neighbors (KNN) algorithm, we built models to predict automation risk.

## Project Overview
- **Dataset**: [AI-Powered Job Market Insights](https://www.kaggle.com/datasets/uom190346a/ai-powered-job-market-insights/data)
- **Goal**: Understand which industries are at higher risk of automation and the relationship between AI adoption, salaries, and automation risks.

## Key Findings
- High AI adoption correlates with **lower salaries**.
- No statistically significant relationship between **AI adoption and automation risk** across industries (Chi-Square test, p = 0.4772).
- KNN model achieved **86.58% accuracy**.

## Project Structure
- **Data Summary and Exploratory Analysis**: [See notebook](notebooks/data_analysis.ipynb)
- **Modeling**: KNN classification with optimized `k` values and evaluation metrics.
- **Results**: Confidence intervals for salary, confusion matrices, and Chi-Square test outcomes.

## Visuals
![Salary Distribution by Automation Risk](results/salary_distribution.png)
![Confusion Matrix](results/confusion_matrix.png)

## How to Run the Code
