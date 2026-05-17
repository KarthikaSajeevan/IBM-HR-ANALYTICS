# IBM HR Analytics — Employee Attrition Analysis using Pandas, Matplotlib, and Seaborn

---

## 1. Project Overview

This project focuses on analysing employee attrition data from IBM's HR dataset using Pandas for data cleaning and analysis, and Matplotlib and Seaborn for data visualization. The goal is to identify the key factors driving employee attrition and generate insights to help organizations make data-driven HR decisions.

---

## 2. Tools Used

- **Pandas** – Data cleaning and manipulation
- **Matplotlib** – Basic data visualization
- **Seaborn** – Advanced and statistical visualizations
- **Google Colab** – Development environment

---

## 3. Dataset

- **Source**: IBM HR Analytics Employee Attrition & Performance Dataset (available on Kaggle)
- **Records**: 1,470 employees | **Features**: 35 columns
- **Key columns include**:
  - Age, Gender, Marital Status
  - Department, Job Role, Job Level
  - Monthly Income, Salary Slab
  - Job Satisfaction, Environment Satisfaction, Work-Life Balance
  - OverTime, Years at Company, Years Since Last Promotion
  - Attrition (Target Variable)

---

## 4. Steps Followed

1. Imported the dataset using Pandas.
2. Cleaned the data by:
   - Checking for null values and duplicates
   - Dropping redundant columns (`EmployeeCount`, `Over18`, `StandardHours`)
   - Converting columns to appropriate data types
3. Performed Exploratory Data Analysis (EDA) using Pandas.
4. Created visualizations using Matplotlib and Seaborn, such as:
   - Count plots for attrition distribution across departments, job roles, and gender
   - Box plots and violin plots for income vs. attrition
   - Bar charts for satisfaction scores and overtime analysis
   - Heatmap for correlation between numerical features
5. Extracted key insights and business recommendations from the analysis.

---

## 5. Key Insights

- Overall attrition rate is approximately **16.1%**.
- Employees working **overtime** have nearly 3× higher attrition risk.
- **Sales Representatives** and **Laboratory Technicians** are the most attrition-prone roles.
- Employees with **low monthly income** and **low job satisfaction** are significantly more likely to leave.
- Attrition is highest among employees with **less than 2 years** of tenure.
- **Single employees** show higher attrition compared to married or divorced employees.
- Poor **work-life balance** and **low environment satisfaction** are strong attrition indicators.

---

## 6. Visualizations

- Count plot showing overall attrition distribution
- Bar charts for department-wise and job-role-wise attrition
- Box plot comparing monthly income by attrition status
- Count plot for overtime vs. attrition
- Heatmap displaying correlation between numerical features

---

#### 7. Files Included

- `IBM_HR_Analytics.ipynb` — Main Jupyter Notebook with data cleaning, EDA, visualizations, insights, and recommendations
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` — The raw HR dataset
- `README.md` — Project description and usage instructions
---

## 8. How to Use

1. Download or clone this repository.
2. Open `IBM_HR_Analytics.ipynb` using **Google Colab** or **Jupyter Notebook**.
3. The dataset is already included in this repository. Simply load it directly in the notebook.
4. Run the notebook cells step by step to view data cleaning, analysis, and visualizations.
5. Modify the code to explore additional insights if needed.

---

## 9. Conclusion

This project demonstrates how Python libraries such as Pandas, Matplotlib, and Seaborn can be used to perform meaningful HR data analysis. By identifying the key drivers of employee attrition — including overtime, low compensation, poor satisfaction, and limited career growth — this analysis provides actionable recommendations that HR teams can use to improve employee retention and organizational performance.
