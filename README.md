# HR_Attrition_Project


## Overview
This project repository is designed to analyze HR Attrition Data, offering insights into employee demographics, job satisfaction, and attrition trends. By leveraging Excel for data preparation and Power BI for advanced visualization, this project delivers actionable insights for HR teams to improve employee engagement and retention.

## Objectives
- **Attrition Analysis**: Examine factors contributing to employee attrition.
- **Satisfaction Ratings**: Evaluate employee and job satisfaction scores across roles and departments.
- **Employee Demographics**: Analyze demographic data (age, gender, marital status, educational field) to identify trends.
- **Overtime Impact**: Understand how overtime influences attrition rates.
- **Departmental Overview**: Summarize employee distribution and attrition by department.

## Project Structure

### Data Columns
- **Attrition**: Indicates whether an employee has left the company.
- **Business Travel**: Frequency of business travel.
- **CF_age_band**: Age bands categorized for easy analysis.
- **CF_Attrition Label**: Label indicating attrition status (e.g., "Active," "Exited").
- **Department**: Department where the employee works.
- **Educational Field**: Employee's field of education.
- **Employee Number**: Unique identifier for each employee.
- **Gender**: Gender of the employee.
- **Job Role**: Employee's job role.
- **Marital Status**: Marital status.
- **Overtime**: Indicates whether the employee works overtime.
- **CF_Current Employee**: Current employment status.
- **Employee Count**: Total number of employees.
- **Employee Satisfaction**: Self-reported satisfaction score.
- **Job Satisfaction Rating**: Job-specific satisfaction rating.

## Data Preparation and Cleaning (Excel)
- **Remove duplicates and empty rows** to ensure data accuracy.
- **Ensure consistency** in categorical data (e.g., Gender, Department).
- **Calculate new metrics** as needed, such as attrition rate per department.
- **Create additional columns**, including tenure in age bands, to aid in analysis.

### Data Analysis (Excel)
#### Key Metrics
- **Attrition Rate**: Calculated by department, age band, and job role.
- **Average Satisfaction Ratings**: Analyzed for both job-specific and overall satisfaction.
- **Employee Distribution**: Breakdown by department, gender, and marital status.

#### Formulas and Calculations
- **Attrition Rate**: `(Attrition Count / Total Employees) * 100`
- **Satisfaction Averages**: Use `AVERAGEIF` formulas for each satisfaction metric by job role and department.

### Data Transformation (Power BI)
- **Import Data**: Load cleaned data from Excel into Power BI.
- **Data Modeling**: Set up calculated columns and measures, such as Attrition Rate, Average Satisfaction, and Employee Count, to enhance data analysis.

## Visualization and Dashboard Creation (Power BI)

### Dashboard Elements
- **Attrition Overview**:
  - Attrition rate by department, age band, and gender.
  - Visualizations: Bar charts for attrition rates, donut chart for attrition by gender, line chart for attrition over time.
- **Satisfaction Analysis**:
  - Job satisfaction and employee satisfaction by department and role.
  - Visualizations: Heatmap for satisfaction scores, bar chart comparing departments.
- **Employee Demographics**:
  - Breakdown of employees by age band, marital status, and educational field.
  - Visualizations: Pie chart for marital status, stacked bar chart for educational field.
- **Overtime Analysis**:
  - Dual bar chart for overtime vs. non-overtime attrition to analyze overtime’s impact on employee retention.

### Interactive Features
- **Slicers**: Enable filtering by Department, Age Band, Gender, Marital Status, and Job Role for dynamic data exploration.
- **Drill-Down Options**: Allow deeper analysis into department-specific or job role-specific attrition and satisfaction rates.

---

## Key Insights & Findings
- **Attrition Trends**: Identified departments and roles with the highest attrition, providing guidance for targeted HR strategies.
- **Satisfaction Insights**: Highlighted satisfaction trends by role and department, pinpointing areas for engagement improvement.
- **Demographic Patterns**: Identified attrition trends based on age, marital status, and gender.
- **Overtime Impact**: Significant correlation found between overtime and higher attrition, suggesting the need for review of overtime policies.

## Visualization on Power BI
![Screenshot (70)](https://github.com/user-attachments/assets/ab984fe7-79e2-423f-9ceb-71fd70ae4c57)
![Screenshot (71)](https://github.com/user-attachments/assets/0e91332f-5ee6-484e-90db-cf7d5996c3e4)
![Screenshot (72)](https://github.com/user-attachments/assets/91b1aef0-5715-49c7-b03d-365515692e3d)

## Conclusion
This HR Data Attrition Repository enables data-driven decision-making in HR departments by providing comprehensive insights into employee attrition, satisfaction, and demographics. The Excel-prepared data, alongside interactive Power BI visualizations, offers a complete view of the organization's HR health, enabling informed actions to improve retention and engagement.
