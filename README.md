[README.md](https://github.com/user-attachments/files/35083975/README.md)
# Student-Learning-Analytics
Analysis of student learning habits and academic performance using Excel, including formulas, data sorting, filtering, conditional formatting, statistical analysis, and visualizations to identify factors influencing examination marks.
# Student Learning Analytics and Academic Performance

## 1. Case Study Title
**Student Learning Analytics – Relationship Between Learning Habits and Academic Performance**

## 2. Problem Statement
A college wants to understand how students' learning habits relate to academic performance. The dataset records daily study hours, assignment completion, attendance percentage and examination marks for 12 students. The analysis identifies patterns and students who may need additional academic support.

## 3. Objectives
- Organize student learning data in a spreadsheet.
- Calculate descriptive statistics using spreadsheet functions.
- Classify students according to examination marks.
- Sort and filter records to identify useful patterns.
- Visualize student performance and relationships between variables.
- Interpret findings and suggest improvements to learning outcomes.

## 4. Dataset Description
The dataset contains 12 student records and these fields:
| Column | Description |
|---|---|
| Student ID | Unique student identifier |
| Study Hours/Day | Average daily study hours |
| Assignments Completed | Number completed, out of 10 |
| Attendance % | Attendance percentage |
| Exam Marks | Examination score out of 100 |
| Performance | Formula-based category |

## 5. Spreadsheet Functions Used
- `AVERAGE()` – calculates average study hours and examination marks.
- `MAX()` / `MIN()` – finds the highest and lowest examination marks.
- `COUNT()` – counts numeric examination scores.
- `IF()` – classifies students as Excellent, Good or Needs Improvement.
- `COUNTIF()` – counts students in each performance category.
- `COUNTIFS()` / `AVERAGEIFS()` – summarizes results by study-hour groups.
- `CORREL()` – measures the linear association between two numerical variables.

### Performance classification
- Excellent: marks >= 85
- Good: marks from 50 to 84
- Needs Improvement: marks < 50

## 6. Data Analysis Techniques
- Data validation for study hours, assignments, attendance and marks.
- Sorting by examination marks (highest to lowest).
- Filtering students studying more than four hours per day.
- Identifying students who completed all 10 assignments.
- Conditional formatting for marks below 50.
- Summary of average marks by study-hour group.

## 7. Charts and Visualizations
- Bar chart: compares examination marks by student.
- Line chart: displays study hours and examination marks across students.
- Histogram: shows the distribution of examination marks.
- Scatter plot: examines the relationship between study hours and examination marks.
- Heat map: compares study hours, attendance and examination marks.

## 8. Important Observations
- Average study time: **3.67 hours/day**.
- Average examination mark: **69.25/100**.
- Highest mark: **96**; lowest mark: **38**.
- Study hours and marks correlation: **0.981** (strong positive association in this sample).
- Assignment completion and marks correlation: **0.993**.
- Students scoring below 50: **S205, S212**.
- Students completing all 10 assignments: **S204, S208**.

## 9. Conclusion
The sample suggests that students who spend more time studying and complete more assignments tend to achieve higher examination marks. Attendance also shows a positive association with marks. Students scoring below 50 should receive timely academic support. Since the dataset contains only 12 students, the results are preliminary and do not establish causation.

## 10. Google Sheets Sharing Link
**Add your Google Sheets link here after uploading the workbook to Google Drive.**

## Repository Contents
- `Student_Learning_Analytics.xlsx` – workbook containing student data, formulas, analysis and dashboard charts.
- `Student_Data.csv` – raw dataset in CSV format.
- `Observations_and_Conclusion.md` – findings, interpretation and recommendations.
- `Screenshots/` – dashboard and heat-map images.

## How to Use
1. Download `Student_Learning_Analytics.xlsx`.
2. Open it in Microsoft Excel or upload it to Google Sheets.
3. Review the **Student Data**, **Analysis** and **Dashboard** sheets.
4. Use the table filters to explore the dataset.
5. Replace the Google Sheets placeholder above with your own shareable link before publishing.
