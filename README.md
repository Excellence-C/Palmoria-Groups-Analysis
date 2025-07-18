# HR Analysis
## Project Topic: Palmoria Groups Gender Analysis 
## Brief 
The Palmoria Group, a manufacturing company based in Nigeria, was embroiled in issues bordering on gender inequality in its 3 regions. I have been recruited as an HR Analytics expert to analyse the company’sHR data and come up with recommendations for management’s attention. This Power BI dashboard project visualizes gender-based employee insights within Palmoria Groups. It includes regional and departmental breakdowns of salaries, bonuses, performance ratings, and gender distribution. The dashboard highlights key findings such as gender pay gaps, regional disparities, and performance trends, aiding decision-making toward diversity and inclusion.

## Data Source
-Excel.CSV 
  - Dataset: Employee data with demographics, salaries, ratings
## Tools used:
 - Excel: For initial data cleaning.
 - Power BI: Final data cleaning and visualization.
  
## Objective
  - Drive inclusive compensation and HR insights

View interactive visuals and insights in the full dashboard screenshots provided below:

## Data Summary & Insights
This dashboard provides a comprehensive gender-based analysis of employee distribution, salary structure, performance ratings, and bonus allocation across departments and regions within Palmoria Groups. 

### Top-Level Metrics
- Number of Employees: The total number of employees in the organization is 874.                                            
- Total Salary Paid: Aggregate salary disbursed to employees is ₦70M   
- Average Salary by Gender: Average salary per employee across all genders is ₦73.7K
- Employees Below Minimum Salary: A total of 654 employees earn below the minimum salary threshold (90, 000).
   - The measure/calculation used to determine this was:
     
- Salary Count by Department: Sum of salary records categorized by department is 946.
Measure used to determine this:

### Gender Distribution by Region
Kaduna, Abuja, Lagos regions analyzed.
Male employees slightly outnumber females in most regions. 
A small portion of the entire population is marked as N/A. This indicates unspecified gender data.

### Rating Distribution by Gender
Most employees are rated “Average”, and with females leading in count. Very few employees are rated “Very Poor” or “Not Rated”.
Undisclosed Gender N/A still appears in very low portion which indicates that not a large number of the total employees did not disclose their gender and so this information doesn’t really affect the analysis as quite a majority of employees’ data can be worked with to determine an outcome.
### Count of Name by Rating and Gender
This shows how many employee names fall into each rating level and gender. Reinforcing the dominance of average performance ratings and female representation in this segment.
### Regional Gender Pay Gap 

| Region | Female         | Male             | N/A               |
| Lagos   | ₦74,163.47  | ₦76,680.65 | ₦86,860       |
| Abuja   | ₦70,452.05  | ₦73,254.55 | ₦73,378.89 |
| Kaduna | ₦72,297.58 | ₦74,849.95 | ₦78,642.86 |
Males consistently earn more than females across all regions. Lagos has the highest pay gap.
The employees with undisclosed gender have unusually high salaries, which may indicate data quality issues or special cases.
### Total Bonus Allocation: 
Annual Bonus:  ₦2.20M
Total Pay (Salary + Bonus): ₦71.92M
Bonuses are likely awarded based on performance ratings.
### Salary Count by Department and Region
‘Product Management’, ‘Legal’, ‘Human Resources’, and ‘Business Development’ show the highest salary counts.
‘Kaduna’ dominates in salary distribution, followed by ‘Abuja’, then ‘Lagos’.
### Pay Band Distribution
This Reflects how salary bands are distributed across regions.
Kaduna employees appear to have the most entries in upper salary bands. Regional imbalance may signal uneven compensation practices.
### Total Company Bonus by Region
Visualized in a “donut chart”. Kaduna region again takes the lead in total bonus payout. Lagos appears to have received the least bonus amount overall.
### Count of Name by Gender
A gender split of the employees:
Female: 441, Male: 405, N/A: 28
This confirms a slight female majority in the organization.
### Slicers
Interactive slicers are available for: Gender, Department, Region. Allowing for filtering through the data set and more interaction with the data set
## Recommendations
1. Address Gender Pay Gaps – Males earn consistently more than females even though there is a majority of female employees in the company. Equity should be evaluated.
2. Data Cleanup Needed – The presence of “N/A” in gender and pay fields suggests incomplete data. According to the initial handler of this data set, it was confirmed that some employees intentionally didn’t put in their genders. This should be looked in to by the management especially with the pay gap that exists in the salaries as compared with other genders.
3. Revisit Minimum Salary Policies – Over ‘650 employees’ earn below the expected minimum—this should be investigated.
4. Performance Review Culture – Many employees rated “Average”—could signal lack of differentiation or robust evaluation methods.

