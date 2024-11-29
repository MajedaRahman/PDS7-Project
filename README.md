About this file

Dataset size : 554KB Rows: 15000 columns: 10

Employee Turnover is the measurement of the total number of employees who leave an organization in a particular year. Employee Turnover Prediction means to predict whether an employee is going to leave the organization in the coming period.

A Company uses this predictive analysis to measure how many employees they will need if the potential employees will leave their organization. A company also uses this predictive analysis to make the workplace better for employees by understanding the core reasons for the high turnover ratio.

1.satisfaction_level: Level of satisfaction {0–1}.
2.last_evaluationTime: Time since last performance evaluation (in years).
3.number_project: Number of projects completed while at work.
4.average_montly_hours: Average monthly hours at workplace.
5.time_spend_company: Number of years spent in the company.
6.Work_accident: Whether the employee had a workplace accident.
7.left: Whether the employee left the workplace or not {0, 1}.
8.promotion_last_5years: Whether the employee was promoted in the last five years.
9.sales: Department the employee works for.
10.salary: Relative level of salary {low, medium, high}.

Dependent variable : 'left'

Independent variable : 'satisfaction_level', 'last_evaluation', 'number_project', 'average_montly_hours', 'time_spend_company', 'Work_accident', 'promotion_last_5years', 'sales', 'salary'

As we know left is dependent variable and its is discrete value . like 0 & 1 and T & F

as for the prediction we have model options as :
@Logistic Regression
@Support vector Classifier
@Random forest Classifier
@K Neighbours Classifier
@Ada Booost Classifier
@Gradient Boosting Classifier
@XGBoost Classifier

From the above mentioned model as per the basis of f1 score Random Forest Classifier has been working efficiently and more accurately.

Summary: With all of this information, this is what employer should know about his company and why his employees probably left:

Employees generally left when they are underworked (less than 150hr/month or 6hr/day)
Employees generally left when they are overworked (more than 250hr/month or 10hr/day)
Employees with either really high or low evaluations should be taken into consideration for high turnover rate
Employees with low to medium salaries are the bulk of employee turnover
Employees that had 2,6, or 7 project count was at risk of leaving the company
Employee satisfaction is the highest indicator for employee turnover.
Employee that had 4 and 5 years at company should be taken into consideration for high turnover rate 8 .Employee satisfaction, yearsAtCompany, and evaluation were the three biggest factors in determining turnover.
