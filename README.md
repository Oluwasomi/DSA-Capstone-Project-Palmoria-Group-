### DSA-Capstone-Project-Palmoria-Group-Analysis 

#### Project Topic: Palmoria Group HR Analysis 

#### Project Overview

This project was conducted as part of the DSA Capstone Program to evaluate and apply data analysis skills using real-world data. The focus is on analyzing HR data from Palmoria Group, a manufacturing company with branches in Lagos, Abuja, and Kaduna.

Palmoria has been accused of gender bias, particularly against its female workforce. This analysis explores the employee dataset to determine the validity of those claims.

#### Data source
The primary source of data used here is the Palmoria Group emp data csv and also the bonus rule excel data, which was probided by DSA(The incubator hub)

###  Tools and Techniques Employed

- Power BI[Download here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
  - For data cleaning
  - For data transformation
  - For visualization
- Microsoft Excel
  - For preliminary data preview

 ### Data cleaning and preparation 

1. Removed inactive employees (null or missing salary)
2. Replaced missing genders with "Unspecified"
3. Dropped rows with null departments
4. Created a conditional column to convert performance rating to numerical form
5. Merged bonus rules with employee data via a left join
6. Created a custom column to calculate total salary = base + bonus
7. Used bar charts, cards, pie charts, and slicers for visual storytelling



