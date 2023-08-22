# Improving Employee Retention by Predicting Employee Attrition

### Introduction

Improving Employee Retention by Predicting Employee Attrition Using Machine Learning. In this Mini Project, the role is as a member
of the Data Scientist team in a technology start-up company. The company is currently facing a significant issue, with many employees submitting their resignations, yet the company has not made decisions regarding this matter. Help the company understand its current employee situation and identify the underlying issues causing these resignations. The aim is to reduce the resignation rate and devise a strategy to enhance employee retention. Findings can be presented descriptively using data visualization and data storytelling, and inferential insights can be drawn using statistical analysis or machine learning approaches, incorporating frameworks like Interpretable & Explainable AI to translate model findings into a narrative.

### Step-by-step Analysis
1. **Import Package**: At the beginning, the necessary packages are imported. This is the initial step in most data analyses.
2. **Exploratory Data Analysis (EDA)**: EDA is conducted to understand the data and extract vital insights from it.
3. **Employee Trend Analysis**: An analysis of the trend in the number of employees hired and those who have resigned over the years is performed.
4. **Data on Employees Who Have Resigned and Those Who Remain**: Differences between employees who have resigned and those who remain are analyzed based on various variables, such as their position.

### Data Modelling

| Model              | Metrics       | Value       |
|--------------------|---------------|-------------|
| Logistic Regression| Accuracy      | 0.16        |
|                    | F1-Score      | 0.20        |
|                    | Confusion Matrix| See Below  |
| Random Forest      | Accuracy      | 0.43        |
|                    | F1-Score      | 0.36        |
|                    | Confusion Matrix| See Below  |
| SVM                | Accuracy      | 0.41        |
|                    | F1-Score      | 0.36        |
|                    | Confusion Matrix| See Below  |
| Gradient Boosting  | Accuracy      | 0.48        |
|                    | F1-Score      | 0.42        |
|                    | Confusion Matrix| See Below  |

**Confusion Matrices**:
1. **Logistic Regression**:
\[
\begin{matrix}
0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & 0 & 0 \\
0 & 2 & 0 & 3 & 0 & 2 & 2 & 0 & 1 & 0 & 3 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & 0 & 0 & 0 & 1 \\
\end{matrix}
\]

2. **Random Forest**:
\[
\begin{matrix}
0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & 0 & 0 & 2 & 0 & 0 & 0 \\
\end{matrix}
\]

3. **SVM**:
\[
\begin{matrix}
0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & 0 & 0 & 2 & 0 & 0 & 0 \\
\end{matrix}
\]

4. **Gradient Boosting**:
\[
\begin{matrix}
0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 2 & 0 & 0 & 0 \\
\end{matrix}
\]

### Interpretation:
- From 2006 to 2010, the company experienced stable growth in the number of employees.
- In 2010, there was a massive recruitment with 76 new employees joining.
- Although initially stable in 2012-2013, from 2014 onwards, many employees began to resign.
- 2018 became a critical point where more employees resigned than were hired.

### Business Recommendation:
1. **Assessment of Internal Conditions**: The increase in employee resignations might reflect internal company issues, such as financial problems, work culture, or low employee satisfaction. An internal survey or interviews with employees should be conducted to understand the root cause.
2. **Improving the Recruitment Process**: Considering the high resignation rate, there might be a mismatch between the employees and the company. The recruitment process should be updated to ensure that the recruited employees match the company's culture and needs.
3. **Employee Retention Program**: The company should consider implementing an employee retention program, such as training and development, improving workplace facilities, or award programs for high-performing employees.
