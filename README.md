
![Hr-employee Attrition Dashboard](https://github.com/user-attachments/assets/f0ba0732-3051-4890-8e7c-e1f98dbc3c40)

# -HR-Employee-Attrition-Dashboard
This repository contains a dashboard designed to analyze and visualize key metrics (KPIs) from an HR Employee Attrition dataset. The goal is to provide actionable insights for HR professionals by exploring employee data and meeting specific client requirements.

## Problem Statement
The primary objective of this project is to analyze HR employee attrition data to identify key trends, uncover insights, and visualize metrics that aid in decision-making. By leveraging the dataset, the dashboard aims to address client requirements, such as employee attrition rates, performance reviews, and workforce distribution, through meaningful visualizations and metrics.

## Dataset Overview
The dataset contains detailed information about employees, including demographic, job-related, and performance data. Below is a summary of the key columns:

| Column Name                | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| AGE                       | Age of each employee                                                       |
| ATTRITION                 | Whether the employee has left the company (YES/NO)                         |
| BUSINESS TRAVEL           | Employee travel category (e.g., Rarely, Frequently, Non-Travel)            |
| DEPARTMENT                | Department where the employee works                                         |
| DISTANCE FROM HOME        | Travel distance from home to office                                         |
| EDUCATION FIELD           | Employee's educational background                                           |
| EMPLOYEE NUMBER           | Employee identifier (not used for analysis)                                |
| ENVIRONMENT SATISFACTION  | Rating for satisfaction with the work environment                          |
| GENDER                    | Gender of the employee                                                     |
| HOURLY RATE               | Hourly pay rate of the employee                                             |
| JOB ROLE                  | Employee's job title or role                                               |
| JOB SATISFACTION          | Job satisfaction rating (scale of 1 to 4)                                  |
| MARITAL STATUS            | Employee's marital status (Single, Married, Divorced)                      |
| MONTHLY INCOME            | Employee's monthly salary                                                  |
| MONTHLY RATE              | Monthly pay rate of the employee                                           |
| NO. OF COMPANIES WORKED FOR | Number of companies the employee has previously worked for                |
| OVER TIME                 | Whether the employee works overtime (Yes/No)                               |
| % SALARY HIKE             | Percentage of salary hike received                                         |
| PERFORMANCE RATING        | Employee's annual performance rating (1 to 4)                              |
| STANDARD HOURS            | Standard working hours                                                     |
| TOTAL WORKING YEARS       | Total years of work experience                                             |
| YEARS @ COMPANY           | Years of experience in the current company                                 |
| YEARS IN CURRENT ROLE     | Years of experience in the current job role                                |
| YEARS SINCE LAST PROMOTION | Years since the employee's last promotion                                 |
| YEARS WITH CURRENT MANAGER| Years of experience working with the current manager                       |

## Dashboard Objectives
The dashboard aims to fulfill the following Key Performance Indicators (KPIs):

1. **Employee Distribution:**
   - Number of employees by department and gender.
   - Total percentage of male and female employees (calculated using measures).

2. **Employee Attrition and Overtime:**
   - Total employees working overtime (Yes/No).
   - Number of employees who have left the company.

3. **Performance and Satisfaction:**
   - Job satisfaction analysis (1-2 as BAD, 3-4 as GOOD).
   - Identification of top and bottom performers based on performance ratings (3 and 4 stars).

4. **Travel and Demographics:**
   - Employee count by business travel category.
   - Count of marital status across three categories (Single, Married, Divorced).

5. **Compensation Analysis:**
   - Average hourly rate of employees displayed using a chart.

6. **Job Roles and Managerial Insights:**
   - Total employees by job roles.
   - Number of employees working with their current manager for more than 5 years.

## Visualizations Used
The following visualizations are used to display the insights clearly and effectively:

- Cards
- Funnel Chart
- Column Chart
- Pie Chart
- Donut Chart
- Multi-row Card
- Bar Chart
- Other relevant charts as needed

## Files Included
- `dashboard.pbix`: Power BI dashboard file containing all the visualizations and KPIs.
- `HR_Attrition.csv`: Raw dataset used for analysis.
- `scripts/`: Python or SQL scripts (if any) for preprocessing the data.

## Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hr-employee-attrition-dashboard.git
   ```

2. Open the `dashboard.pbix` file using Power BI Desktop to view or edit the dashboard.

3. Explore the `HR_Attrition.csv` dataset to understand the raw data structure.



## Dashboard Preview
Add a screenshot or GIF preview of the dashboard here to give viewers a quick glance at the visualizations.

## Contributing
Contributions are welcome! If you have suggestions or additional KPIs to include, feel free to open an issue or submit a pull request.

