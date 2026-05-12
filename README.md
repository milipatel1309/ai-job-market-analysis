# AI Job Market Analysis

## Analyzing Skill Demand and Salary Trends in the Artificial Intelligence Job Market

### Author Information
- **Name:** Mili Patel
- **University:** Rutgers University
- **Course:** Introduction to Data Science (01:198:439)
- **NetID:** mp2173

---

# Project Overview

This project analyzes salary trends and skill demand in the Artificial Intelligence job market using data science and machine learning techniques.

The project studies how factors such as:
- Experience level
- Company size
- Industry
- Remote work ratio
- Technical skills

influence salary in AI-related jobs.

The dataset contains approximately **15,000 AI job postings** collected from Kaggle.

---

# Objectives

The main goals of this project were:
- Identify the most demanded AI skills
- Analyze salary trends across different job categories
- Study the impact of experience and remote work on salary
- Build machine learning models to predict salary
- Group similar AI jobs using clustering techniques

---

# Methods Used

The project followed a complete data science workflow:

## 1. Data Cleaning
- Removed duplicates
- Checked missing values
- Standardized columns
- Cleaned skills data
- Prepared dataset for modeling

## 2. Exploratory Data Analysis (EDA)
Created visualizations for:
- Salary distribution
- Top AI skills
- Top job titles
- Salary by experience level
- Salary by company size
- Salary by remote work ratio
- Correlation analysis

## 3. Feature Engineering
- Encoded categorical variables
- Processed experience levels
- Prepared features for machine learning

## 4. Machine Learning Models
Implemented:
- Linear Regression
- Random Forest Regression

## 5. Clustering
Used K-Means clustering to identify groups of similar AI jobs.

---

# Key Results

## Most Demanded Skills
Top skills found in AI job postings:
- Python
- SQL
- TensorFlow
- Kubernetes
- PyTorch
- Linux
- Git
- Java
- GCP

---

## Salary Findings

### Average Salary by Experience Level

| Experience Level | Average Salary |
|---|---|
| Entry Level | $63,133 |
| Mid Level | $87,955 |
| Senior Level | $122,187 |
| Executive Level | $187,724 |

The analysis showed that **experience level is the strongest salary predictor**.

---

## Model Performance

| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | 37,351 | 0.6175 |
| Random Forest | 21,408 | 0.8743 |

The **Random Forest model performed best**, explaining about **87% of salary variation**.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Project Structure

```bash
ai-job-market-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_modeling.ipynb
│
├── outputs/
│   ├── figures/
│   └── models/
│
├── report/
│
├── README.md
└── requirements.txt
```

---

# Dataset

Dataset Source:
https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025

---

# Project Files

- `01_data_cleaning.ipynb` → Data cleaning and preprocessing
- `02_eda.ipynb` → Exploratory Data Analysis
- `03_modeling.ipynb` → Machine learning and clustering
- `report/DSProjMiliPatel.pdf` → Final project report

---

# Conclusion

This project demonstrates how data science and machine learning can be used to analyze real-world AI job market trends.

The results show that:
- Experience strongly affects salary
- AI jobs require both programming and cloud/deployment skills
- Random Forest is effective for salary prediction
- Clustering helps identify meaningful job market segments

---
