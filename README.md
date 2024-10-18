# Case Study 

Employee attrition, or turnover, is a significant concern for many organizations, particularly in sectors where talent retention is critical for business success. A study by the Society for Human Resource Management (SHRM) reports that the average cost per hire is over $4,000, and replacing an employee can cost 6-9 months of their salary. This highlights the financial burden associated with high turnover, especially when attrition rates are unpredictable and not well-managed.

**Data Overview**

The  dataset used to identify here, includes information on 1,470 employees, covering important aspects like demographics, job satisfaction, work-life balance, and time spent with the company.

**Attrition Rate**: About 16% of the employees have left the organization, which highlights a substantial turnover issue.

**Job Satisfaction**: Employee satisfaction scores range from 1 to 4, with an average score of 2.7. This indicates that there may be concerns with employee contentment that need to be addressed.

**Years at Company**: The average employee stays with the company for 7 years, but many employees leave within the first 3 years, making early-stage turnover a key issue.

**The Need for Data Analysis and Classification**
Organizations often lack the capacity to accurately analyze employee data and predict potential attrition. This leaves HR teams reacting to turnover rather than proactively addressing it. Identifying employees at high risk of attrition can help organizations develop targeted retention strategies, thereby reducing turnover-related costs and improving workforce stability.

The dataset includes features such as:

- Employee satisfaction scores
- Business travel frequency
- Work-life balance
- Job performance metrics
- Years at the company
- These variables, when analyzed and classified using machine learning models, can predict which employees are most likely to leave. Machine learning can uncover complex patterns within these data points that human analysis may miss, enabling more effective retention strategies.

  **Data visualization**
  ![image](https://github.com/user-attachments/assets/b4431dbf-872a-45cd-965f-2c51318da7aa)


**Higher Attrition:** Employees with Education Level 2 (Blue) and Education Level 3 (Black) are more likely to leave the company.

**Higher Retention:** Employees with Education Level 3 (Black) and Education Level 4 (Orange) tend to stay longer, indicating better job satisfaction or security.
**No Significant Gender Impact** - Attrition patterns do not differ significantly by gender.

**Insights for Improvement:**

**Targeted Retention:** Focus on retaining employees with Education Levels 2 and 3, as they show higher attrition.

**Professional Development:** Offer development opportunities to employees with lower education levels to reduce turnover.

**No Immediate Gender-Specific Interventions: Retention strategies should be centered on educational background rather than gender.**

![image](https://github.com/user-attachments/assets/1f195fbe-88fa-4327-b2f9-4cf6843a81d2)

**Retention of High-Education, High-Income Employees:**
Employees with Education Level 3 and 4 in R&D appear to be a critical group in terms of total income contribution. To prevent attrition among these high-earning employees, HR teams should focus on ensuring job satisfaction, work-life balance, and growth opportunities for this group. Retaining these employees is essential to maintain the department's productivity and reduce turnover costs.

**Balancing Compensation Across Departments:**
The relatively low income distribution in Human Resources suggests that this department may have limited growth or salary opportunities, particularly for employees with higher education levels. This could lead to dissatisfaction and increased attrition risk. HR can address this by ensuring competitive salaries and providing career development programs for employees in this department.

**Tailored Retention Strategies by Department:**
R&D employees, especially those in higher education brackets, likely have complex job roles and higher expectations for job satisfaction. Personalized retention strategies, such as offering skill development opportunities or mentorship programs, can help mitigate turnover.
In Sales, where income distribution is more balanced across education levels, retention strategies might focus on incentives like performance-based bonuses or flexible work options to retain employees across different education levels.


**Statistics from the Data**
From the dataset, I observed the following relevant statistics:

**Business Travel**: Employees who frequently travel for work are 2 times more likely to leave the organization compared to those who travel rarely.
**Job Satisfaction**: Employees with lower job satisfaction scores (scores of 1 or 2) are 3 times more likely to leave the company than those with scores of 3 or 4.
**Overtime Work: Employees who regularly work overtime are 4 times more likely to leave, indicating that overwork might be contributing to burnout and eventual turnover.
Monthly Income: Interestingly, employees with lower monthly income (in the bottom 25th percentile) show a 25% higher likelihood of leaving compared to those in the higher income bracket.
By addressing these patterns and implementing retention efforts around job satisfaction, reducing frequent travel, and managing overtime, organizations can potentially reduce their attrition rate by a significant margin.

![image](https://github.com/user-attachments/assets/eb90130e-18a6-4cd3-887b-df6289de8925)

The comparison of machine learning models provides key insights into predicting employee attrition, enabling HR teams to develop targeted retention strategies. Here's how the models help:

**Logistic Regression (Accuracy: 0.867)**: Offers a balance of accuracy and simplicity. It quickly identifies high-risk employees by analyzing linear relationships, such as job satisfaction and overtime, providing actionable insights.

**Fast Large Margin (Accuracy: 0.831)**: While slightly less accurate, it’s computationally efficient, making it suitable for fast decision-making with minimal resource usage.

**Deep Learning (Accuracy: 0.876)**: Achieves the highest accuracy, effectively capturing complex patterns in data. This model is ideal for large companies requiring high precision in identifying at-risk employees.

The Gains metric highlights performance improvements, with Deep Learning showing a 42-point gain due to its ability to model non-linear relationships, and Logistic Regression with a 32-point gain for simplicity and ease of interpretation.

**Results and Impact:**

By identifying employees at high risk of leaving, these models enable proactive interventions, such as improving job satisfaction, managing overtime, or adjusting travel policies. These strategies can reduce turnover, improve retention, and minimize recruitment costs, directly addressing the organization's attrition challenges.
