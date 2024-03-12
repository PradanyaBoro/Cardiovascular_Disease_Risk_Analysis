# Cardiovascular Disease Risk Analysis

## Overview
This project focuses on analyzing the UCI Heart Disease dataset, which consists of 14 attributes including age, sex, chest pain type, blood pressure, cholesterol levels and more. The primary objective is to predict the presence of heart disease based on patient attributes and derive insights to aid in diagnosis and understanding of the problem.

## Process Flow
- **Data Loading and Exploration:** Load dataset into pandas DataFrame, handle missing values, and explore data structure.
- **Descriptive Statistics:** Compute basic statistics for numerical columns and analyze the distribution of age and gender.
- **Correlation Analysis:** Calculate correlation matrix and visualize using a heatmap.
- **Gender-based Analysis:** Explore heart disease distribution by gender and average age of patients with/without heart disease.
- **Age Distribution:** Create age bins and visualize heart disease distribution across different age groups.
- **Chest Pain Type Analysis:** Analyze distribution of chest pain types and its relationship with heart disease.
- **Blood Pressure and Cholesterol Analysis:** Visualize distribution of blood pressure and cholesterol levels and their relationship with heart disease.
- **Heart Rate Analysis:** Analyze distribution of maximum heart rates achieved and its correlation with heart disease.
- **Angina and Exercise Analysis:** Explore relationship between exercise-induced angina and heart disease, and analyze ST depression induced by exercise.
- **Visualization:** Create visualizations (e.g. bar charts, histograms) to represent key insights.

## Conclusion
- There is no correlation among numeric columns.
- Majority of heart patients are male.
- Patients with asymptomatic chest pain have the highest chance of heart disease.
- Males achieve higher maximum heart rates during exercise.
- Patients with exercise-induced angina are more likely to have heart disease.

## Language and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Future Improvements
- Explore advanced predictive modeling techniques.
- Conduct further feature engineering for better insights.
- Enhance visualization techniques for clearer representation.
