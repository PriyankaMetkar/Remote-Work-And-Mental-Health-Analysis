# Remote Work And Mental Health Analysis Dashboard and Report

As a part of this project I have created two types of visualizations as listed below: 

* In first part of project I have created Visualizations using Power BI
* Second part of project consists of Visualizations and analysis using Python

## Project Overview

With remote work becoming more prevalent, it is essential to understand how it impacts employees' mental well-being. This project explores a dataset of 5,000 records collected from employees worldwide, providing insights into stress levels, work-life balance, and mental health conditions across various industries and regions. The aim is to help researchers, HR professionals, and businesses assess how remote work affects productivity, job satisfaction, and mental health.

The dataset contains key features like work location (remote, hybrid, onsite), stress levels, mental health resources, and job satisfaction, allowing for in-depth analysis of trends and patterns in employee well-being.

## Dataset Information

- **Source**: [Kaggle - Remote Work and Mental Health Dataset](https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health)
- **Records**: 5,000 employees across various industries and regions
- **Features/Columns**:
  - `Employee_ID`: Unique identifier for each employee.
  - `Age`: Age of the employee.
  - `Gender`: Gender of the employee (Male, Female, Non-binary).
  - `Job_Role`: The role the employee is performing.
  - `Industry`: The industry they work in.
  - `Work_Location`: Whether they work remotely, hybrid, or onsite.
  - `Stress_Level`: Self-reported stress level.
  - `Mental_Health_Condition`: Reported mental health condition (e.g., Anxiety, Depression).
  - `Social_Isolation_Rating`: A self-reported rating (1-5) of social isolation.
  - `Satisfaction_with_Remote_Work`: Level of satisfaction with remote work (Satisfied, Neutral, Unsatisfied).

## Project Objectives

The project is divided into two parts: **Power BI Visualizations** and **Python Analysis**.

### 1. Power BI Visualizations

The following Power BI visualizations are included to analyze the Remote Work and Mental Health dataset:

1. **Stress Level by Age**: Analyze how stress levels vary across different age groups of employees working remotely, onsite, or in hybrid settings.
2. **Gender and Work Satisfaction**: Explore if there are significant differences in satisfaction with remote work between male, female, and non-binary employees.
3. **Industry Stress Comparison**: Compare stress levels across different industries to determine which sectors experience the most or least stress in remote work settings.
4. **Social Isolation by Work Location**: Investigate whether employees working remotely, onsite, or hybrid feel more socially isolated.
5. **Mental Health Condition and Job Role**: Examine the relationship between specific job roles and reported mental health conditions such as anxiety or depression.
6. **Satisfaction vs. Stress Levels**: Assess whether satisfaction with remote work correlates with lower stress levels across all employees.
7. **Stress Levels by Work Location**: Compare stress levels of employees working remotely, hybrid, and onsite to understand how location affects mental well-being.
8. **Age and Social Isolation**: Analyze the relationship between age groups and their self-reported social isolation ratings.
9. **Work Satisfaction by Industry**: Investigate job satisfaction levels across various industries for remote workers.
10. **Gender and Social Isolation**: Explore whether there are differences in social isolation ratings among different gender groups.
11. **Stress Levels in Different Job Roles**: Compare the stress levels reported by employees in different job roles, such as managers vs. non-managers.
12. **Mental Health Conditions by Age**: Analyze the prevalence of mental health conditions like anxiety and depression across different age groups.
13. **Stress Levels and Work Location Preferences**: Investigate if employees who prefer working remotely report lower stress levels compared to those working onsite or hybrid.
14. **Job Role and Remote Work Satisfaction**: Analyze the level of satisfaction with remote work for various job roles.
15. **Age and Mental Health Condition**: Explore how mental health conditions vary across different age groups.
16. **Gender and Mental Health Condition**: Investigate if there are significant differences in reported mental health conditions based on gender.
17. **Work Location and Mental Health Condition**: Analyze how different work locations (remote, hybrid, onsite) influence the occurrence of mental health conditions.
18. **Industry and Work Satisfaction**: Assess the level of satisfaction with remote work arrangements across different industries.
19. **Satisfaction by Gender**: Compare the satisfaction levels with remote work between male, female, and non-binary employees.
20. **Social Isolation and Satisfaction Correlation**: Explore the relationship between social isolation ratings and overall satisfaction with remote work.
21. **Work Location and Social Isolation**: Determine whether remote workers feel more isolated than hybrid or onsite workers.
22. **Stress by Gender**: Compare stress levels reported by different genders in remote, hybrid, and onsite work settings.
23. **Job Role and Stress Levels**: Investigate whether employees in managerial roles report higher stress levels compared to non-managers.
24. **Industry and Social Isolation**: Explore if employees in certain industries report higher social isolation in remote or hybrid work.
25. **Age and Remote Work Satisfaction**: Analyze whether older or younger employees are more satisfied with remote work arrangements.
26. **Industry and Mental Health**: Determine which industries have the highest incidence of mental health conditions among remote and hybrid workers.
27. **Work Location Preference by Age**: Investigate how work location preferences (remote, hybrid, onsite) differ by age group.
28. **Job Role and Social Isolation**: Examine the relationship between an employee's job role and their social isolation rating.
29. **Stress Level and Mental Health Conditions**: Analyze whether higher stress levels correlate with a higher prevalence of mental health conditions.
30. **Work Satisfaction and Industry Stress**: Compare the stress levels and job satisfaction rates for employees in high-stress vs. low-stress industries.
31. **Social Isolation by Gender**: Determine if gender influences the level of social isolation felt by remote workers.
32. **Satisfaction by Work Location**: Compare the satisfaction with remote work among employees working in remote, hybrid, and onsite settings.
33. **Mental Health by Work Location**: Explore whether employees working remotely report more mental health conditions than those onsite or hybrid.
34. **Work-Life Balance and Stress Levels**: Analyze how work-life balance impacts self-reported stress levels in different work locations.
35. **Satisfaction and Age Group Analysis**: Compare how satisfaction with remote work varies across different age groups.
36. **Mental Health and Social Isolation**: Investigate the relationship between mental health conditions and self-reported social isolation levels.
37. **Satisfaction by Job Role**: Analyze the satisfaction levels with remote work for different job roles.
38. **Gender and Stress Levels**: Explore how stress levels vary among male, female, and non-binary employees in different work settings.
39. **Social Isolation by Industry**: Investigate which industries report the highest levels of social isolation among remote workers.
40. **Work Satisfaction and Mental Health Conditions**: Assess whether employees who are satisfied with remote work report fewer mental health conditions.
41. **Work Satisfaction and Work Location**: Compare satisfaction levels of employees based on their work locations (remote, hybrid, onsite).
42. **Job Role and Mental Health Condition**: Analyze the prevalence of mental health conditions in different job roles.
43. **Age and Stress Levels**: Compare stress levels across various age groups in remote, hybrid, and onsite work settings.
44. **Industry and Remote Work Preferences**: Explore if certain industries prefer remote or hybrid work more than others.
45. **Social Isolation and Age**: Investigate how social isolation ratings differ across age groups in remote and hybrid work settings.
46. **Satisfaction and Mental Health Correlation**: Examine the correlation between remote work satisfaction and the occurrence of mental health conditions.
47. **Mental Health Condition by Industry**: Analyze the prevalence of mental health conditions across different industries.
48. **Gender and Work Location Preferences**: Compare work location preferences (remote, hybrid, onsite) across gender groups.
49. **Work-Life Balance and Job Role**: Analyze the relationship between job roles and perceived work-life balance in remote and hybrid work settings.
50. **Age and Work Location Preferences**: Explore how age impacts preferences for remote, hybrid, or onsite work.

These Power BI visualizations help to answer key questions about the relationship between remote work, stress levels, mental health, and job satisfaction across various demographic groups and work settings.

---

### 2. Python Visualizations

The following Python visualizations are included to analyze the Remote Work and Mental Health dataset:

1. **Descriptive Analysis of Stress Levels**: Perform a descriptive analysis (mean, median, mode) of the stress levels of employees.
2. **Age Group Distribution Analysis**: Analyze the distribution of age groups in the dataset.
3. **Gender Distribution Analysis**: Analyze the gender distribution across different industries and job roles.
4. **Work Location Distribution**: Identify the distribution of work locations (remote, hybrid, onsite) across different job roles.
5. **Stress Levels and Work Location**: Compare the stress levels of employees based on their work location (remote, hybrid, onsite).
6. **Mental Health Conditions by Age**: Analyze how mental health conditions vary across different age groups.
7. **Stress Levels by Gender**: Compare the stress levels between different genders.
8. **Job Role and Stress Levels**: Analyze which job roles report higher stress levels.
9. **Industry-wise Mental Health Conditions**: Compare the prevalence of mental health conditions (e.g., anxiety, depression) across different industries.
10. **Social Isolation and Work Location**: Analyze the relationship between social isolation ratings and work location.

### Correlation and Causal Analysis:
11. **Correlation Between Stress Levels and Age**: Calculate the correlation between stress levels and the age of employees.
12. **Correlation Between Social Isolation and Stress Levels**: Examine the relationship between social isolation ratings and stress levels.
13. **Work Satisfaction and Mental Health Conditions**: Analyze how mental health conditions affect satisfaction with remote work.
14. **Correlation Between Work Satisfaction and Stress Levels**: Identify the correlation between satisfaction with remote work and stress levels.
15. **Social Isolation and Mental Health**: Explore the correlation between social isolation ratings and mental health conditions.
16. **Effect of Work Location on Social Isolation**: Investigate how different work locations affect feelings of social isolation.
17. **Stress Levels and Job Satisfaction**: Explore whether employees with higher stress levels report lower satisfaction with remote work.
18. **Impact of Gender on Mental Health**: Analyze how gender affects mental health conditions (e.g., anxiety, depression).
19. **Industry and Stress Levels**: Investigate the relationship between industry and self-reported stress levels.
20. **Impact of Age on Job Satisfaction**: Analyze how age affects satisfaction with remote work.

---

## Tools and Technologies Used
- **Power BI**: Data visualizations for understanding trends across stress levels, work locations, and mental health conditions.
- **Python**: For performing data analysis, statistical computations and Visualizations.
  - Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
- **Jupyter Notebooks**: For analysis and documentation.
  
---


## How to Run the Project

1. **Power BI**: Open the provided `.pbix` file to explore visualizations.
2. **Python**: Run the Jupyter Notebook file (`Remote_Work_Mental_Health_Analysis.ipynb`) to execute the analysis.


## Conclusion
This project aims to provide insights into how remote work affects employee well-being. Through both Power BI and Python visualizations, the project helps businesses and HR professionals better understand the mental health challenges posed by remote work and how to enhance employee satisfaction and productivity.

## Author
  - Priyanka Metkar
