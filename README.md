# HR-Analytics-Problem
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.


## 📊 Dataset Description

This dataset includes demographic, performance, and training-related data for employees at a multinational corporation. The objective is to predict whether an employee will be promoted.

| **Variable**           | **Definition**                                                                 |
|------------------------|--------------------------------------------------------------------------------|
| `employee_id`          | Unique identifier for each employee                                            |
| `department`           | Department in which the employee works                                         |
| `region`               | Employment region (categorical, unordered)                                     |
| `education`            | Education level attained by the employee                                       |
| `gender`               | Gender of the employee                                                         |
| `recruitment_channel`  | Channel through which the employee was recruited                               |
| `no_of_trainings`      | Number of additional trainings completed by the employee in the past year      |
| `age`                  | Age of the employee                                                            |
| `previous_year_rating` | Performance rating given in the previous year                                  |
| `length_of_service`    | Total number of years the employee has been with the organization              |
| `KPIs_met >80%`        | Indicates if more than 80% of the employee’s KPIs were met (1 if yes, else 0)  |
| `awards_won?`          | Indicates if the employee won any awards in the previous year (1 if yes, else 0)|
| `avg_training_score`   | Average score obtained by the employee in training evaluations                 |
| `is_promoted`          | **Target** — Whether the employee was promoted (1) or not (0)                  |

---
 
### Evaluation Metric
The evaluation metric for this competition is F1 Score.

## Public and Private Split
Test data is further randomly divided into Public (40%) and Private (60%) data.
- Your initial responses will be checked and scored on the Public data.
- The final rankings would be based on your private score which will be published once the competition is over.
