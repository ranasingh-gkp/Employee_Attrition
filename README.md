# Employee_Attrition
Predicting Employee Attrition in the Dawn of Recession
https://www.kaggle.com/c/summeranalytics2020/overview

As the COVID-19 keeps unleashing its havoc, the world continues to get pushed into the crisis of the great economic recession, more and more companies start to cut down their underperforming employees. Companies firing hundreds and thousands of Employees is a typical headline today. Cutting down employees or reducing an employee salary is a tough decision to take. It needs to be taken with utmost care as imprecision in the identification of employees whose performance is attriting may lead to sabotaging of both employees' career and the company's reputation in the market.

###Aim of The Competition
To predict Employee Attrition by the given data about his/her past history.

###Acknowledgements
We thank IBM for providing us with the dataset.


###Evaluation
The evaluation metric for this competition is AUC score under ROC. AUC - ROC curve is a performance measurement for classification problem at various thresholds settings. ROC is a probability curve and AUC represents degree or measure of separability. It tells how much model is capable of distinguishing between classes. Higher the AUC, better the model is at predicting 0s as 0s and 1s as 1s. By analogy, Higher the AUC, better the model is at distinguishing between patients with disease and no disease.


##File descriptions
train.csv - the training set
test.csv - the test set
Sample submission.csv - a sample submission file in the correct format


###Data fields
Id - an anonymous id given to an Employee
Age - Age of an Employee
Attrition - Did the Employee leave the company, 0-No, 1-Yes
BusinessTravel - Travlling frequency of an Employee
Department - Work Department
DistanceFromHome - Distance of office from home
EducationField - Field of Education
EmployeeNumber - Number of Employees in the division of a given Employee
EnvironmentSatisfaction - Work Environment Satisfaction
Gender - Gender of Employee
MartialStatus - Martial Status of an employee
MonthlyIncome - Monthly Income of Employee in USD
NumCompaniesWorked - Number of Companies in which Employee has worked before joining this Company
OverTime - Does The person work overtime
PercentSalaryHike - Average annual salary hike in percentages
StockOptionLevel - Company stocks given to an Employee
TotalWorkingYears - Total working experience of an employee
TrainingTimesLastYear - No. of trainings an employee went through last year
YearsAtCompany - Number of years worked at this company
YearsInCurrentRole - Number of years in current role
YearsSinceLastPromotion - Number of years since last promotion
YearsWithCurrManager - Number of years with the current manager
Education

1 'Below College'
2 'College'
3 'Bachelor'
4 'Master'
5 'Doctor'

EnvironmentSatisfaction

1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobInvolvement

1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobSatisfaction

1 'Low'
2 'Medium'
3 'High'
4 'Very High
'
PerformanceRating

1 'Low'
2 'Good'
3 'Excellent'
4 'Outstanding'

Behaviour

1 'Good'
2 'Bad'
3 'Not Rated'

CommunicationSkill

1 'Bad'
2 'Average'
3 'Good'
4 'Better'
5 'Best'
StockOptionLevel

0 'No stocks'
1 'Less Stocks'
2 'Moderate Stocks'
3 'A lot of Stocks'
