# HR Analytics Dashboard

## 📊 Project Overview
This project contains an **HR Analytics Dashboard** (Power BI template) and the dataset used for analysis.  
The goal of the dashboard is to analyze **employee attrition** within the company, identify key trends, and provide actionable insights through meaningful KPIs.

## 🗂 Files in Repository
- `HR ANAYLTICS_DASHBOARD.pbit` → Power BI dashboard template  
- `HR_Analytics.csv` → Dataset used for the dashboard  

## 🚀 Dashboard Highlights
The dashboard provides:  
- **Overall Attrition Rate** → % of employees who left the company  
- **Attrition by Age Group, Department, and Education Field**  
- **KPIs such as:**
  - Average Age of employees
  - Average Salary / Daily Rate
  - Attrition split by Business Travel, Job Role, Distance from Home
- **Visualizations**:
  - Attrition trends across demographics
  - Department-level attrition comparison
  - Employee distribution by age, education, and job satisfaction  

This helps HR and management identify **key risk areas** and take **data-driven retention strategies**.

## 🔎 Exploratory Data Analysis (EDA)

### 📌 Dataset Summary
- **Rows:** 1480  
- **Columns:** 38  
- **Target Variable:** `Attrition` (Yes/No)  

### 📌 Key Columns
- **Employee Info:** `EmpID`, `Age`, `Gender`, `MaritalStatus`  
- **Job-Related:** `Department`, `JobRole`, `BusinessTravel`, `JobLevel`, `JobSatisfaction`, `YearsAtCompany`  
- **Compensation & Performance:** `DailyRate`, `MonthlyIncome`, `PerformanceRating`  
- **Attrition Indicator:** `Attrition`  

### 📌 Data Types
- **Numerical:** Age, DailyRate, DistanceFromHome, MonthlyIncome, YearsAtCompany, etc.  
- **Categorical:** Attrition, AgeGroup, Department, BusinessTravel, EducationField, JobRole, etc.  

### 📌 Missing Values
- No missing values found in the dataset.

- ### 📌 Key Insights
- **Attrition Distribution:** Out of 1480 employees, **1242 (84%) stayed** and **238 (16%) left**.  
- **Age Group:** Most employees are between **26-35 years (611 employees)**.  
- **Department:** Majority work in **Research & Development (967 employees)**.  
- **Education Field:** Top field is **Life Sciences (607 employees)**.  
- **Business Travel:** Most employees **Travel Rarely (1042 employees)**.  
- **Distance From Home:** Average = **9.2 km**, with employees living as far as 29 km.

- ## 🏆 Insights for HR
- Younger employees (26–35) form the largest workforce segment but also show higher attrition.  
- Attrition is concentrated in certain **departments and job roles**, highlighting the need for role-specific retention strategies.  
- Employees with **frequent travel requirements** tend to have higher attrition rates.  
- Distance from home appears to influence employee satisfaction and attrition.  

## ⚙️ How to Use
1. Download both the `.pbit` (dashboard) and `.csv` (dataset).  
2. Open the `.pbit` file in **Power BI Desktop**.  
3. Load the dataset (`HR_Analytics.csv`) into the dashboard.  
4. Explore and interact with the KPIs and visuals.  

---

## 📌 Future Improvements
- Add predictive modeling for **attrition risk scoring**.  
- Create interactive HR recommendations.  
- Automate data refresh pipelines.  
