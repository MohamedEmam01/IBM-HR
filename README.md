# IBM HR Analytics Employee Attrition & Performance

## Overview

This project aims to analyze employee attrition and performance using a fictional dataset created by IBM data scientists. The dataset provides insights into various factors influencing employee attrition, such as age, education, job satisfaction, and more.

## Dataset

The dataset used in this project consists of 1470 rows and 35 columns. Here are some key columns and their descriptions:

- **Age:** The age of the employee.
- **Attrition:** Whether the employee has left the company (Yes/No).
- **BusinessTravel:** Frequency of business travel.
- **DailyRate:** Daily rate of pay.
- **Department:** The department where the employee works.
- **DistanceFromHome:** Distance of the employee's home from the workplace.
- **Education:** Level of education.
- **EducationField:** Field of education.
- **EmployeeCount:** Always 1 for all records.
- **EmployeeNumber:** Unique identifier for each employee.
- **EnvironmentSatisfaction:** Satisfaction with the work environment.
- **Gender:** Gender of the employee.
- **HourlyRate:** Hourly rate of pay.
- **JobInvolvement:** Level of job involvement.
- **JobLevel:** Job level or rank.
- **JobRole:** Role of the employee in the company.
- **JobSatisfaction:** Satisfaction with the job.
- **MaritalStatus:** Marital status of the employee.
- **MonthlyIncome:** Monthly income of the employee.
- **MonthlyRate:** Monthly rate of pay.
- **NumCompaniesWorked:** Number of companies the employee has worked for.
- **Over18:** Always 'Y' for all records.
- **OverTime:** Whether the employee works overtime (Yes/No).
- **PercentSalaryHike:** Percentage increase in salary.
- **PerformanceRating:** Performance rating.
- **RelationshipSatisfaction:** Satisfaction with relationships at work.
- **StandardHours:** Standard working hours (always 80 for all records).
- **StockOptionLevel:** Level of stock options.
- **TotalWorkingYears:** Total years of work experience.
- **TrainingTimesLastYear:** Number of training times last year.
- **WorkLifeBalance:** Satisfaction with work-life balance.
- **YearsAtCompany:** Years at the current company.
- **YearsInCurrentRole:** Years in the current role.
- **YearsSinceLastPromotion:** Years since the last promotion.
- **YearsWithCurrManager:** Years with the current manager.

## Data Preprocessing

- Duplicates were checked and removed from the dataset.
- Label encoding was applied to categorical columns to convert them into numerical values.
- Exploratory data analysis (EDA) was performed to understand the data distribution.

## Data Visualization

Several data visualizations were created to gain insights from the dataset. Some examples include:

- A pie chart showing the percentage of attrition.
- A pie chart showing the gender distribution.
- Count plots for business travel and department distribution.
- ECDF (Empirical Cumulative Distribution Function) and histogram plots for various features.
- Box plots and strip plots to analyze factors like age, income, and job satisfaction.

## Conclusion

The analysis of the IBM HR Analytics Employee Attrition & Performance dataset provides valuable insights into the factors that influence employee attrition. This information can be used to make informed decisions and take actions to reduce attrition rates and improve overall employee performance.

## Dependencies

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn
- Plotly Express
## Requirements
To run this project, you will need to install the following Python libraries. You can install them using pip and the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
```
## Usage

You can use this project to:

- Analyze employee attrition and performance in your organization.
- Gain insights into the factors contributing to attrition.
- Create data visualizations for better understanding.

## License

This project is licensed under the [MIT License](LICENSE.md).

## Acknowledgments

- IBM for providing the dataset.
- The open-source community for developing the libraries used in this project.
