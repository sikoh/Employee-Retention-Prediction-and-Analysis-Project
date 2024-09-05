# HR Performance Metrics and Retention Analysis Report

## 1. Introduction
This project focused on analyzing and predicting employee retention to assist the organization in enhancing its HR strategies and reducing turnover.
## 2. Workforce Demographics

### 2.1 Gender Distribution
<br>

![image](https://github.com/user-attachments/assets/dc317cf4-f4b0-424d-bd08-193193ea3f87)

<br>

![image](https://github.com/user-attachments/assets/a3c0155b-14fc-4bfc-90e9-8205aacc4839)
<br>

**Key Finding:** 
The company's workforce is predominantly female, with women making up 56.5% of the total employees. However, in departments like IT and Sales, there are more male employees than female ones. This shows that, although females make up the majority company-wide, men are more prevalent in these specific departments.

<br>
<br>

### 2.2 Age Distribution
<br>


![image](https://github.com/user-attachments/assets/39d4eaac-8f2a-4ab4-a5f1-80632a9ea5ed)


**Key Finding:** 
The age distribution at hiring shows a broad range with some notable patterns. The majority of hires fall between 24 and 29 years old. A significant number of hires occur in the age range of 27 to 29 years, with 33 hires recorded.

The age at hiring ranges from a minimum of 19 years to a maximum of 63 years. Notably, the median age is 32 years, and 75% of hires are 39 years old or younger, indicating that most employees are hired within a relatively young age range.



## 3. Salary Analysis

### 3.1 Overall Salary Distribution
<br>

![image](https://github.com/user-attachments/assets/963495cd-35bc-4cce-aa99-3606a8b877bf)


**Key Finding:** 
The salary distribution in the dataset shows considerable variation, with a right-skewed distribution. This skew implies that a portion of employees earn significantly higher salaries, pulling the mean (69,020.68) upwards compared to the median(62,810.00). Specifically, the presence of a maximum salary as high as $250,000.00 indicates outliers or high earners in the dataset. This distribution should be considered when evaluating salary equity and making compensation decisions.

<br>

### 3.2 Salary by Department

<br>

![image](https://github.com/user-attachments/assets/21883e2b-0a11-4188-b85f-d3b2fc8f9c22)


**Key Findings:** 
Production salaries are relatively close to the median (59,472.00) with a broad range at the upper end. The average (59,953.55) is slightly higher than the median, suggesting that higher salaries are pulling up the average. The maximum salary (170,500) is considerably higher than the 75th percentile (64,066.00), indicating possible outliers or specialized roles with high compensation.

The IT/IS department exhibits a high average salary (97,064.64) with significant variability. The maximum salary (220,450.00) is notably higher than the 75th percentile (106,844.50), suggesting the presence of high earners or potential outliers . The wide range between the 25th (77,417.75) and 75th percentiles indicates a diverse salary structure.

Software Engineering shows high average (94,989.45) and median (95,660.00) salaries with a relatively narrow range between the 25th (89,601.50) and 75th (100,807.50) percentiles, suggesting consistent compensation levels. The maximum salary (108,987.00) is higher than the 75th percentile, indicating the presence of high earners.

The Admin Offices show a considerable salary range with a maximum salary ($106,367.00) that is significantly higher than the median (63,003.00). The average salary (71,791.89) is higher than the median, suggesting a few high earners could be skewing the average. The gap between the 25th (55,000.00) and 75th (93,046.00) percentiles indicates variability within this department.

Sales department salaries are fairly balanced with the average (69,061.26) close to the median (65,310.00). The maximum salary (180,000.00) is significantly higher than the 75th percentile (70,506.50), suggesting a few high earners. The relatively narrow range between the 25th (61,561.50) and 75th percentiles indicates moderate variability.

The Executive Office currently has a single employee in the dataset, therefore the salary data reflects only one individual’s compensation (250000.00). As a result, there is no variation or outliers in the pay structure for this department.

<br>
<br>

### 3.3 Salary by Gender and Age
<br> 

![image](https://github.com/user-attachments/assets/17f13ef3-ff5f-4dfb-ba66-46297f208af5)

**Key Findings:** 
The scatterplot analysis reveals that earnings do not vary significantly by gender across the dataset. However, it is notable that the highest earners are predominantly female. Additionally, there is a marked decrease in high earners among employees older than 63, indicating that high earnings are concentrated within younger age groups.


## 4. Employee Tenure and Performance

### 4.1 Tenure Distribution
<brr>
  
![image](https://github.com/user-attachments/assets/af86bd71-b6be-4370-be74-14a0316ed2a0)


**Key Finding:** 
The tenure range from 9.50 to 10.45 years has the highest number of employees, with 56 employees, indicating that this is a common tenure range among employees.There may be a need to focus on retention strategies and career development for employees around this tenure, as they represent a significant portion of the workforce.

Ranges with very low employee counts include 14.25 to 15.20 years (1 employee), and 17.10 to 18.05 years and 18.05 to 19.00 years (0 and 1 employee respectively). These ranges have fewer employees, indicating they are less common. The low count of employees in the higher tenure ranges indicates potential opportunities for developing strategies to retain long-term employees and provide career growth opportunities to extend tenure.

<br>

### 4.2 Performance Scores
<br>

![image](https://github.com/user-attachments/assets/601d0ad1-1151-440d-bdd5-2e32596c7bf9)


**Key Findings:**
The performance score distribution within the organization reveals that 78.1% of employees are classified as Fully Meets, indicating that a significant majority are meeting their performance expectations. 11.9% of employees are in the Exceeds category, representing high achievers who perform above expectations. Meanwhile, 5.8% of employees fall under Needs Improvement, suggesting areas where additional support may be required. Lastly, 4.2% of employees are currently under a Performance Improvement Plan (PIP), reflecting a small group facing more serious performance challenges.


### 4.3 Performance vs Tenure
[Box plot of tenure for each performance category]

**Key Finding:** "Exceeds" performers have the longest average tenure (9.86 years).

**Suggestion:** Investigate factors contributing to high performance and long tenure to replicate across the workforce.

## 5. Retention Risk Analysis

### 5.1 Top Predictors of Employee Retention
[Bar chart of feature importance from ML model]

1. Performance Score
2. Years Since Last Review
3. Salary to Performance Ratio
4. Engagement Survey Score
5. Employee Satisfaction

**Key Finding:** Performance and timely reviews are crucial for retention.

**Suggestions:**
- Implement regular performance reviews
- Ensure fair compensation aligned with performance
- Focus on improving employee engagement and satisfaction

## 6. Department-Specific Insights

[Stacked bar chart of employee counts by department and gender]

**Key Findings:**
- Production has the most employees (209)
- Sales department has the highest average tenure (10.06 years)

**Suggestions:**
- Develop department-specific retention strategies
- Investigate and replicate positive factors from the Sales department

## 7. Recommendations

1. Prioritize regular performance reviews and feedback
2. Develop a structured career progression framework
3. Implement targeted retention programs for high performers
4. Address engagement and satisfaction through tailored initiatives
5. Review and adjust compensation strategies to align with performance
6. Focus on diversity and inclusion across all departments
7. Create mentorship programs to transfer knowledge from long-tenured employees

## 8. Next Steps

1. Conduct deeper analysis on engagement and satisfaction factors
2. Implement predictive model to identify at-risk employees
3. Develop action plans for each department based on their unique characteristics
4. Establish a system for regular workforce analytics updates
