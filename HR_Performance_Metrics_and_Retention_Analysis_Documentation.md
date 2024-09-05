# Documentation

1. Data Preparation and Feature Engineering:
   - Handled missing values and converted date columns
   - Created new features: Age, AgeAtHiring, Tenure, YearsSinceLastReview
   - Additional feature: SalaryToPerformanceRatio

2. Exploratory Data Analysis (EDA):
   - Analyzed distributions of key metrics (Salary, EngagementSurvey, EmpSatisfaction)
   - Examined relationships between age, gender, salary, and departments
   - Explored employee distribution, tenure, and performance scores

3. Machine Learning Models:
   - Implemented Logistic Regression, Random Forest, Gradient Boosting, and SVM
   - Used cross-validation for model evaluation
   - Logistic Regression performed best (mean CV F1 score: 0.975, test F1 score: 0.951)

4. Key Findings:
   a) Salary and Compensation:
      - Right-skewed distribution (mean: $69,020, median: $62,810)
      - Highest salaries in Executive Office, IT/IS, and Software Engineering
      - No significant gender-based salary differences, but highest earners tend to be female

   b) Demographics:
      - 56.5% female employees, male-dominated in IT and Sales
      - Most common hiring age: 24-29 years

   c) Tenure and Performance:
      - Highest concentration: 9.5-10.45 years tenure
      - 78.1% "Fully Meets", 11.9% "Exceeds", 5.8% "Needs Improvement", 4.2% on PIP
      - "Exceeds" performers have longest average tenure (9.86 years)

   d) Departments:
      - Largest: Production (209 employees), IT/IS (50 employees)
      - Highest average tenure: Sales (10.06 years)

   e) Performance Reviews:
      - Time since last review: 6.68 years ("Exceeds") to 7.67 years ("Needs Improvement")

5. Machine Learning Insights:
   - Top predictors of employee retention:
     1. PerformanceScore_Numeric
     2. YearsSinceLastReview
     3. SalaryToPerformanceRatio
     4. EngagementSurvey
     5. EmpSatisfaction

6. Areas for Improvement:
   - Develop retention strategies for 9.5-10.45 year tenure employees
   - Address lower engagement scores
   - Implement more frequent performance reviews, especially for underperformers
   - Focus on career development for long-term employees (14+ years)
   - Investigate decreased high earners among employees over 63

7. Strengths:
   - Good overall gender balance
   - High percentage of employees meeting/exceeding expectations
   - Stable tenures across most departments

8. Recommendations based on combined insights:
   - Prioritize performance management and regular reviews, as PerformanceScore is the top predictor of retention
   - Implement a structured review schedule to address the YearsSinceLastReview factor
   - Develop a fair and transparent compensation strategy that aligns with performance (SalaryToPerformanceRatio)
   - Focus on improving employee engagement and satisfaction, as these are key retention factors
   - Create targeted retention programs for high-performing employees and those in critical tenure ranges
   - Develop career progression paths, especially in departments with high average tenure
   - Address potential age discrimination concerns for employees over 63

9. Next Steps:
   - Conduct further analysis on the relationship between engagement, satisfaction, and performance
   - Implement the predictive model to identify employees at risk of leaving
   - Develop department-specific retention strategies based on the unique characteristics of each group
   - Regular monitoring and updating of the model with new data to maintain its accuracy

This combined analysis provides a holistic view of the company's workforce dynamics, highlighting key areas for HR interventions and strategic decision-making to improve employee retention and performance.
