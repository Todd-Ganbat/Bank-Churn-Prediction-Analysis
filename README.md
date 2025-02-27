# Bank Churn Prediction Analysis - README

## Project Overview
This project, **Bank Churn Prediction Analysis**, was developed as part of the group assignment for the ETF5912 course. The primary objective was to predict customer churn using machine learning techniques implemented in R, focusing on classification trees and logistic regression. The findings aim to guide customer retention strategies with data-driven insights.

### Authors:
- Tuguldur Ganbat (33762740)
- Tran Hoang Phuong Le (34044396)
- Chaoyan Yu (32815719)

### Submission Date:
October 17, 2024

---

## Objectives
- To perform exploratory data analysis (EDA) and prepare the dataset for modeling.
- To build predictive models using:
  - Classification Trees
  - Logistic Regression
- To evaluate model performance and recommend the best-performing approach.
- To derive actionable insights into customer churn.

---

## Key Components

### Exploratory Data Analysis (EDA):
- Visualizations and statistical summaries of features.
- Detection of missing values and outliers.
- Exploration of correlations to identify significant variables.

### Data Preprocessing:
- Imputation of missing data.
- Feature engineering to enhance model performance.
- Data splitting into training and test sets.

### Model Development:
- **Classification Trees**: Applied to capture complex, nonlinear relationships in the data.
- **Logistic Regression**: Used as a benchmark for comparison.
- Evaluation based on metrics like accuracy, precision, recall, and F1-score.

### Results & Insights:
- Analysis of model performance and key influencing factors.
- Recommendations for targeted customer retention efforts.

---

## Methodology

### Tools Used:
- **Programming Language**: R
- **Libraries**: `tidyverse`, `caret`, `rpart`, `ggplot2`, and others.

### Dataset:
- Includes customer demographic, account, and transactional data.

### Statistical Techniques:
- Feature correlation analysis.
- Model evaluation using confusion matrices and AUC scores.

---

## How to Run

1. **Ensure R and required packages are installed**:
   - Use the `install.packages()` function to install any missing libraries.

2. **Download or clone the repository**:
   - Ensure the repository contains the `.Rmd` or `.R` scripts along with the dataset.

3. **Open the files in RStudio**:
   - Open the `ETF5912 Assignment 2.Rproj` file in RStudio to set the working directory.
   - Load the `Assignment 2.Rmd` file in RStudio.

4. **Execute the analysis**:
   - Run each chunk in the R Markdown file sequentially or render the entire document using the "Knit" button.
   - The results, including visualizations and summaries, will be displayed in the knitted output (e.g., an HTML or PDF file).

5. **Output**:
   - The final report will be saved in the project directory with a name like `Assignment-2.html`.

---

## Conclusion
The analysis successfully identified key features influencing customer churn and demonstrated that the classification tree model outperformed logistic regression. These insights can inform effective customer retention strategies.

---
