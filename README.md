# Tracking User Engagement with SQL, Python, and Excel

## Project Overview
This project analyzes student engagement on an online learning platform by comparing user behavior in Q2 2021 and Q2 2022. The objective is to evaluate whether newly introduced platform features (courses, career tracks, and exams) led to increased student engagement.

The analysis uses SQL for data preparation, Python for preprocessing and modeling, Excel for statistical analysis, and machine learning to study the relationship between engagement and learning outcomes.

---

## Tools & Technologies
- SQL (MySQL)
- Python (Pandas, Seaborn, Matplotlib, Scikit-learn)
- Excel (Statistical Analysis)
- Jupyter Notebook
- GitHub

---

## Project Workflow

### 1. Data Preparation with SQL
- Calculated subscription start and end dates based on plan types
- Adjusted subscription periods for refunded purchases
- Classified students as paid or free in Q2 2021 and Q2 2022
- Aggregated minutes watched per student for both quarters
- Linked engagement data with certificates issued

---

### 2. Data Preprocessing with Python
- Visualized engagement distributions using KDE plots
- Identified right-skewed distributions
- Removed extreme outliers using the 99th percentile
- Saved cleaned datasets for further analysis

---

### 3. Data Analysis with Excel
- Calculated mean and median engagement values
- Constructed 95% confidence intervals for engagement metrics
- Performed hypothesis testing to evaluate feature impact
- Analyzed correlation between minutes watched and certificates issued

---

### 4. Probability & Event Analysis
- Assessed dependency between watching lectures in Q2 2021 and Q2 2022
- Calculated conditional probabilities to measure retention behavior

---

### 5. Machine Learning Modeling
- Built a linear regression model to predict certificates issued
- Used minutes watched as the predictor variable
- Evaluated model performance using R-squared
- Predicted certificate outcomes for new engagement values

---

## Key Insights
- Student engagement increased from Q2 2021 to Q2 2022
- Paid users consistently showed higher engagement
- Engagement and certificates issued exhibit a positive correlation
- Regression analysis confirms minutes watched as a meaningful predictor of learning outcomes

---

## Conclusion
The project demonstrates an end-to-end data analytics pipeline, transforming raw data into actionable insights. The results suggest that new platform features positively influenced student engagement and learning outcomes.

---

## Author
Ayush Mohan Tripathi  
Data Scientist
 
