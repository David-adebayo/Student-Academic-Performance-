# Student Academic Performance Analysis

![Image](https://github.com/user-attachments/assets/c13f1a51-fe64-4cfe-b916-0775b3bae385)

## 1. Introduction
This project analyzes a student academic performance dataset to examine the factors that influence students’ academic outcomes. The dataset includes demographic information, attendance records, study habits, and subject scores. Statistical techniques such as multiple regression analysis and correlation analysis were applied using Microsoft Excel to identify significant predictors of academic performance and to explore relationships between key variables.

The project is intended for academic coursework, research practice, and data analysis learning purposes.

---

## 2. Research Questions
The study addresses the following research questions:

1. What factors significantly predict students’ academic performance?
2. Is there a relationship between students’ attendance rate and their grades?
3. How does academic performance differ between male and female students?
4. Which subjects show the greatest variation in academic performance among students?

---

## 3. Dataset Description
- File Name: `Final_Marks_Data.xlsx`
- Unit of Analysis: Individual student
- Data Type: Numerical and categorical variables

### Variables
- Gender (Male, Female)
- Attendance_Rate (Percentage)
- Daily_Study_Hours (Hours per day)
- Maths Score
- English Score
- Science Score
- Total_Marks
- Average_Score

Each row represents a single student, while each column represents a specific attribute or academic metric.

---

## 4. Analysis Conducted
The following analyses were conducted in this project:
1. Multiple Linear Regression Analysis
2. Correlation Analysis
3. Subject Performance Variation Analysis

All analyses were performed using Microsoft Excel.

---

## 5. Workings and Methodology

---

### 5.1 Multiple Regression Analysis

#### Objective
To determine whether gender, attendance rate, and daily study hours significantly predict students’ academic performance.

#### Model Specification
Dependent Variable:
- Average_Score

Independent Variables:
- Gender
- Attendance_Rate
- Daily_Study_Hours

Regression Model:

Average_Score = β₀ + β₁(Gender) + β₂(Attendance_Rate) + β₃(Daily_Study_Hours) + ε

---

#### Step-by-Step Workings in Excel

1. Data Preparation
   - Ensured all score and attendance columns were numeric.
   - Encoded Gender as:
     - Male = 1
     - Female = 0
   - Checked for missing or inconsistent values.

2. Enabling Analysis ToolPak
   - Navigated to File → Options → Add-ins
   - Enabled the Analysis ToolPak.

3. Running the Regression
   - Selected Data → Data Analysis → Regression.
   - Input Y Range: Average_Score column.
   - Input X Range: Gender, Attendance_Rate, Daily_Study_Hours columns.
   - Selected the Labels option.
   - Chose an output location.
   - Clicked OK to generate results.

4. Output Obtained
   - Regression coefficients
   - R-square and Adjusted R-square
   - Standard errors
   - t-statistics
   - p-values

---

#### Interpretation
- R-square measures how much variation in academic performance is explained by the independent variables.
- Attendance_Rate with a positive coefficient indicates that higher attendance improves academic performance.
- Daily_Study_Hours with a positive coefficient shows that increased study time leads to higher grades.
- Gender may show a smaller or statistically insignificant effect depending on its p-value.
- A variable is considered statistically significant if its p-value is less than 0.05.

---

### 5.2 Correlation Analysis

#### Objective
To examine the relationship between students’ attendance rate and academic performance.

---

#### Step-by-Step Workings in Excel

1. Selected an empty cell for the result.
2. Applied the Excel CORREL function:

   =CORREL(Attendance_Rate_Range, Average_Score_Range)

3. Recorded the correlation coefficient.

---

#### Visualization Steps
1. Highlighted Attendance_Rate and Average_Score columns.
2. Inserted a scatter plot.
3. Added a linear trendline.
4. Displayed the R-squared value on the chart.

---

#### Interpretation
- A positive correlation coefficient indicates that higher attendance is associated with higher grades.
- A value closer to +1 indicates a stronger positive relationship.
- The scatter plot visually supports the numerical correlation result.

---

### 5.3 Subject Performance Variation Analysis

#### Objective
To identify which subjects show the greatest variation in student performance.

---

#### Step-by-Step Workings in Excel

1. Calculated the standard deviation for each subject using:
   
   =STDEV(Maths_Range)  
   =STDEV(English_Range)  
   =STDEV(Science_Range)

2. Compared the standard deviation values across subjects.

---

#### Interpretation
- The subject with the highest standard deviation shows the greatest variation in performance.
- High variation indicates uneven performance among students in that subject.

---

## 6. Summary of Findings
- Attendance rate and daily study hours are significant predictors of academic performance.
- There is a positive relationship between attendance and students’ grades.
- Gender differences in performance exist but are generally weaker than behavioral factors.
- Some subjects exhibit greater variability in scores than others.

---

## 7. Conclusion
This analysis demonstrates that students’ academic performance is strongly influenced by attendance and study habits. Regression and correlation analyses provide consistent evidence that increased engagement leads to improved academic outcomes. The project highlights the effectiveness of Microsoft Excel as a tool for educational data analysis.

---



---



