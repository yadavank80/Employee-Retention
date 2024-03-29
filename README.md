# Employee Retention (Classification using ML)  
Given some data about employees working in an organization, we are interested in predicting if an employee is likely to leave the organization or not.  
* We have **14249 observations** from past/present employees having 9 different features.  
  
## Target Variable:  
* **status** - Current employment status  

## Features given:  
* **department** – Department employees belong(ed) to  
* **salary** – Salary level relative to rest of their department  
* **tenure** – Number of years at the company  
* **recently_promoted** – Was promoted in last 3 yrs?  
* **n_projects** – No. of projects employee is staffed on  
* **avg_monthly_hrs** – Average number of hours worked per month  
* **satisfaction** – Employee’s satisfaction score  
* **last_evaluation** – Recent evaluation score  
* **filed_complaint** – Has the employee filed a formal complaint in the last 3 years?

## Model performance:
Best performing model was Random Forest.  
Receiver Operating Characteristic curve for all the models is as below:  
  
![alt text](https://github.com/yadavank80/Employee-Retention/blob/master/RoC%20Curve.PNG "RoC Curve")
