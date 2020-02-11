# Salary-Analysis


## Problem Statement:
To build a model that will predict if the income of any individual in the US is greater than or less than USD 50,000 based on the data available about that individual.We are taking the position of a consultancy company hired by the government to study the relationship between income in the US versus various factors related to education, gender etc. The study's objective is to support the government in formulate different policy based on the model that we build.

## Key files

Link here : Presentation in Google Slides format

salary_census : Presentation in PDF format
salary_census.ipynb : Jupyter notebook file with Python codes + commentaries
salary_census.py : local Python functions source file for Jupyter notebook
adult.data : Raw data source file in CSV format

#### Data Set Description: 
This Census Income dataset was collected by Barry Becker in 1994andgiventothe public site http://archive.ics.uci.edu/ml/datasets/Census+Income. This data set will help you understand how the income of a person varies depending on various factors such as the education background, occupation, marital status, geography, age, number of working hours/week, etc.
Here’s a list of the independent or predictor variables used to predict whether an individual earns more than USD 50,000 or not
### 1. Categorical Attributes

workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.


marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
Individual marital status

occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black

sex: Female, Male.

native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

### 2. Continuous Attributes

age: continuous.Age of an individual

fnlwgt: final weight, continuous.
The weights on the CPS files are controlled to independent estimates of the civilian noninstitutional population of the US. These are prepared monthly for us by Population Division here at the Census Bureau.

capital-gain: continuous.

capital-loss: continuous.

hours-per-week: continuous.Individual's working hour per week

