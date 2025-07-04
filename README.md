### DSA-Capstone-Project-Palmoria-Group-Analysis 
This project was executed as part of the DSA Capstone to demonstrate analytical thinking and real-world application of data transformation, visualization, and storytelling.
#### Project Topic: Palmoria Group HR Analysis 

#### Project Overview

The focus is on analyzing HR data from Palmoria Group, a manufacturing company with branches in Lagos, Abuja, and Kaduna.

Palmoria has been accused of gender bias, particularly against its female workforce. This analysis explores the employee dataset to determine the validity of those claims.

#### Data source
The primary source of data used here is the Palmoria Group emp data csv and also the bonus rule excel data, which was probided by DSA(The incubator hub)

#### Tools and Techniques Employed

- Power BI[Download here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
  - For data cleaning
  - For data transformation
  - For visualization
- Microsoft Excel
  - For preliminary data preview

 #### Data cleaning and preparation 

1. Removed inactive employees (null or missing salary)
2. Replaced missing genders with "Unspecified"
3. Dropped rows with null departments
4. Created a conditional column to convert performance rating to numerical form
5. Merged bonus rules with employee data via a left join
6. Created a custom column to calculate total salary = base + bonus
7. Used bar charts, cards, pie charts, and slicers for visual storytelling

#### Exploratory Data Analysis
1. What is the gender distribution in the organization?

2. Show insights on performance ratings based on gender.

3. Analyze the company's salary structure.

4. Compliance with new salary regulation
A new law mandates a minimum salary of \$90,000 for manufacturing workers.
  
5. Calculate the annual bonus pay for each employee based on their performance rating and department.

6. The total amount to be paid to each employee (salary + bonus).
7. The total amount to be paid out per region, and the total company-wide payout.

#### Data Analysis

![image](https://github.com/user-attachments/assets/173a46c9-df94-4172-b631-e89f53fa1833)

![image](https://github.com/user-attachments/assets/f1f3e453-c6c8-4011-8993-fc68f9fbfb5b)



#### Summary of Key Findings

- Gender pay gaps exist, particularly in Kaduna
-  Female employees are rated higher but earn less
- Bonus allocation appears fair and performance-driven
- Legal and Accounting departments need equity reviews as there is a clear gap between the numbers of male employees and female employees and also in payments
- Non-compliance with the N90,000 salary regulation is evident

#### Recommendations

1. Investigate and address salary imbalances, especially where female employees outperform male peers but are paid less especially in Kaduna 
2. Continue using performance-based bonuses, but ensure transparency
3. Consider implementing gender pay equity audits periodically
4. Improve HR data completeness (e.g., gender disclosure, exit tracking)
5. Ensure compliance with minimum wage regulations

#### Limitations

- Missing Data: Some employees had missing gender or department entries and were removed, which may slightly skew results.
- No Role or Seniority Info: The dataset lacks job titles or experience levels, so salary gaps can’t be fully explained.
- Static Snapshot: No time-based data, so trends in promotion or salary growth couldn’t be analyzed.


