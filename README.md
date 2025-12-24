# Student Academic Performance Dataset

## 📌 Overview
This dataset contains information on students’ demographic characteristics, attendance, study habits, and academic performance.  
It is designed for educational data analysis using tools such as **Microsoft Excel** and **Power BI**, and supports statistical techniques including **regression analysis**, **correlation analysis**, and **data visualization**.

The dataset can be used to answer questions such as:
- What factors significantly predict students’ academic performance?
- Is there a relationship between attendance rate and grades?
- How does academic performance differ by gender or grade level?
- Which subjects show the greatest variation in performance?

---

## 📁 File Information
- **File name:** `Final_Marks_Data.xlsx`
- **File format:** Excel Workbook (.xlsx)
- **Unit of analysis:** Individual student
- **Data type:** Mixed (Numerical and Categorical)

---

## 🧾 Dataset Structure
Each row represents **one student**, and each column represents a **specific attribute or performance metric**.

### 🔢 Variables Description

| Column Name | Description | Data Type | Example |
|------------|------------|----------|---------|
| Student_ID | Unique identifier for each student | Numeric / Text | 101 |
| Gender | Student gender | Categorical | Male, Female |
| Attendance_Rate | Percentage of classes attended | Numeric (%) | 85 |
| Daily_Study_Hours | Average study hours per day | Numeric | 3.5 |
| Maths | Mathematics score | Numeric | 72 |
| English | English language score | Numeric | 68 |
| Science | Science score | Numeric | 75 |
| Total_Marks | Sum of subject scores | Numeric | 215 |
| Average_Score | Mean score across subjects | Numeric | 71.7 |
| Grade_Level | Academic grade or class level | Categorical | SS1, SS2, SS3 |

> Note: Column names may vary slightly depending on analysis requirements.

---

## 🛠 Data Preparation Notes
- Attendance rate is recorded as a **percentage (0–100)**.
- Subject scores are on a **0–100 scale**.
- `Total_Marks` and `Average_Score` can be computed if not provided.
- For regression analysis, categorical variables such as **Gender** may be encoded numerically  
  (e.g., Male = 1, Female = 0).

---

## 📊 Recommended Analyses

### 1️⃣ Regression Analysis
- **Dependent Variable:** Average_Score or Total_Marks  
- **Independent Variables:**  
  - Gender  
  - Attendance_Rate  
  - Daily_Study_Hours  
- **Tool:** Excel Data Analysis ToolPak

### 2️⃣ Correlation Analysis
- Examine the relationship between **Attendance_Rate** and **Average_Score**
- **Tool:** Excel `CORREL()` function or Data Analysis ToolPak

### 3️⃣ Visualization
- Scatter plot: Attendance Rate vs Grades
- Column chart: Performance by Gender
- Box plot: Subject score variation
- Dashboard: Power BI–style academic performance overview

---

## 🎯 Intended Use
This dataset is suitable for:
- Academic assignments and projects
- Excel and Power BI dashboards
- Introductory statistics practice
- Educational data analysis demonstrations

---

## ⚠️ Limitations
- Dataset size may be limited.
- Results should not be generalized beyond the dataset.
- External factors (e.g., socioeconomic status, teaching quality) are not included.

---

## 👤 Author / Prepared By
Prepared for academic analysis and learning purposes.

---

## 📜 License
This dataset is provided strictly for **educational and non-commercial use**.

