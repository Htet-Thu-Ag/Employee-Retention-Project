# Employee Turnover Analysis for Salifort Motors

## Project Title
Predictive Modeling for Employee Turnover at Salifort Motors

## Project Overview
This project involves building and evaluating predictive models to analyze a dataset and generate insights into employee turnover at Salifort Mortors. The goal is to predict whether an employee will leave the company based on various factors, such as job title, department, number of projects, and average monthly hours. The results aim to assist Salifort Motors in increasing retention, enhancing job satisfaction, and optimizing resource allocation.

## Business Understanding
Salifort Motors is currently facing a high rate of employee turnover, impacting both financial resources and the company's efforts to foster a supportive corporate culture. The leadership team is concerned about the cost associated with recruiting, training, and upskilling employees who leave. To address the issue, they surveyed to understand the factors driving turnover. As a data professional, the task is to analyze the survey and design a predictive model to identify key factors influencing employee departure.

## Data Understanding
The analysis utilizes data collected through an employee survey, including variables such as satisfaction level,  number of projects, time spent in the company, Department, salary, and promotion in the last 5 years with 14999 rows and 10 columns.

![employee stayed or left by department](https://drive.google.com/drive/u/1/my-drive/stay-or-left-by-department.png)


## Modeling and Evaluation
After conducting feature engineering, the decision tree model achieved AUC of 93.8%, precision of 87.0% and recall of 90.4%, f1-score of 88.7%, and accuracy of 96.2%, on the test set. The random forest modestly outperformed the decision tree model.

The following figure is feature importance of employee leaving.
![feature importance for employee leaving](https://drive.google.com/drive/u/1/my-drive/feature-importance)


## Conclusion

The models and the feature importances extracted from the models confirm that employees at the company are overworked.

To retain employees, the following recommendations could be presented to the stakeholders:

- Cap the number of projects that employees can work on.-
- Consider promoting employees who have been with the company for at least four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.
- Either reward employees for working longer hours, or don't require them to do so.
- If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear.
- Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.
- High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort.
