# HR Attrition Dashboard

## Project Summary

The Goal of this project is to determine the reasons for the high employee **Turnover Rate** and come with the solutions increase the **Retention Rate** through corrective measures taken by the data analysis and visualization. The dataset contains detail data about the employees such as **Age, Gender, YearSinceLastPromotion, Overtime, Department, etc.** I have consolidated the visuals in the dashboard with the reasons which affect the employee turnover rate the most from the data of the firm.     

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Executive Summary

In this descriptive analysis, I conducted a comprehensive Data Cleaning process to ensure data quality and integrity. This involved identifying and removing duplicate records from the dataset to eliminate redundancy. Additionally, missing values were addressed through imputation, where blank entries were replaced using the mode (modal values) to maintain consistency and accuracy.

Following the data preprocessing phase, I performed an Exploratory Data Analysis (EDA) leveraging Pivot Table Analysis in Excel. This allowed for in-depth insights into key trends, patterns, and relationships within the dataset. By summarizing and segmenting the data effectively, I was able to derive meaningful business insights that can support data-driven decision-making.    

![Dashborad-Page-1](https://github.com/user-attachments/assets/c0bff371-1804-4ca9-9492-3c6a95c8c868)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## **Summary of Insights**

### Age Group

The Firm has the large count of employees in 28-38 age group.

| **Age Group** | **No. of Employees** | **Percentage of Total** |  
|--------------|----------------------------|---------------------|  
| **18-28**    | 260                        | 17.7%               |  
| **29-39**    | 696                        | 47.3%               |  
| **40-50**    | 381                        | 25.9%               |  
| **51-61**    | 133                        | 9.1%                |  
| **Grand Total** | 1,470                     | 100%                |  

Age Group - **29-39** Contributes 47.3% of the Total workforce of the firm.

### Marital Status

The employees who are single have the high turnover rate. 

| **Marital Status** | **No. of Employees Left** | **Attrition Rate** |  
|--------------------|------------------------------|-------------------|  
| **Single**        | 120                          | 9.74%            |  
| **Married**       | 84                           | 6.82%            |  
| **Divorced**      | 34                           | 2.76%            |  

### Job Role By Overtime

| **Job Role**                 | **Overtime - No** | **Overtime - Yes** |  
|------------------------------|------------------|------------------|  
| **Research Scientist**       | 14               | 33               |  
| **Sales Executive**          | 26               | 32               |  
| **Laboratory Technician**    | 31               | 31               |  
| **Sales Representative**     | 17               | 16               |  
| **Human Resources**          | 7                | 5                |  
| **Manager**                  | 1                | 4                |  
| **Manufacturing Director**   | 6                | 4                |  
| **Healthcare Representative** | 7               | 2                |  
| **Research Director**        | 1                | 1                |  

We can clearly see the **Research Scientist** are leaving due to frequent Overtime.

### Salary Slab

| **Salary Slab**   | **No. of Employees Left** |  
|------------------|--------------------------|  
| **Upto 5K**     | 163                        |  
| **5K - 10K**    | 49                         |  
| **10K - 15K**   | 21                         |  
| **15K+**        | 5                          |  

The lower income range shows high turnover rate

### Salary Hike and Promotions

| **Percent Salary Hike** | **No. of Employees Left** |  
|------------------------|--------------|  
| **11%**               | 41           |  
| **12%**               | 33           |  
| **13%**               | 35           |  
| **14%**               | 24           |  
| **15%**               | 18           |  
| **16%**               | 14           |  
| **17%**               | 14           |  
| **18%**               | 13           |  
| **19%**               | 9            |  
| **20%**               | 7            |  
| **21%**               | 5            |  
| **22%**               | 12           |  
| **23%**               | 6            |  
| **24%**               | 6            |  
| **25%**               | 1            |  

The employees with the Salary Hike (%) of 11% - 13% have high numbers

Similarly,

The employees with the recent promotions within few months, a year or two have high count. 

| **Years Since Last Promotion** | **No. of Employees Left** |  
|-------------------------------|--------------------------|  
| **0**                         | 110                      |  
| **1**                         | 49                       |  
| **2**                         | 28                       |  
| **3**                         | 9                        |  
| **4**                         | 5                        |  
| **5**                         | 2                        |  
| **6**                         | 6                        |  
| **7**                         | 16                       |  
| **8**                         | 0                        |  
| **9**                         | 4                        |  
| **10**                        | 1                        |  
| **11**                        | 2                        |  
| **12**                        | 0                        |  
| **13**                        | 2                        |  
| **14**                        | 1                        |  
| **15**                        | 3                        |  

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Recommendations

The employees in R&D department has the high turnover.

The reason is clearly that they are leaving due to the overtime therefore the overtime should be reduced.

The Employees with the salary upto 5k and percent salary hike of 11% to 13% are leaving.

Also the Employees who are recently promoted within few months, a year or two are leaving in search of higher salaries.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

