# Salary-Analysis


## Problem Statement:
To build a model that will predict if the income of any individual in the US is greater than or less than USD 50,000 based on the data available about that individual.We are taking the position of a consultancy company hired by the government to study the relationship between income in the US versus various factors related to education, gender etc. The study's objective is to support the government in formulate different policy based on the model that we build.

## Key files

1.Link here : Presentation in Google Slides format

2.salary_census : Presentation in PDF format
3.salary_census.ipynb : Jupyter notebook file with Python codes + commentaries
4.salary_census.py : local Python functions source file for Jupyter notebook
5.adult.data : Raw data source file in CSV format

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

## Methodology
1. **Data Import**
2. **Data Cleansing**  
  2.1 Clean-up columns and data  
  2.2 Remove outliers  
3. **Data Exploration**  
  3.1 Overview of all data via plots  
  3.2 Overview of target  
  3.3 Split and transform training and test data
4. **Feature Selection (Part 1): Evaluate predictors**  
  4.1 Baseline model : logistic regression model with all predictors  
  4.2 Baseline model : logistic regression with SMOTE 
  4.3 Model1: Decesion tree model   
  4.4 Model2: KNN model 
  4.5 Model3: SVM model
  4.6 Model4: Random Forest
  4.7 Model5: ADABoost
  4.8 Model6: XGBoost
 
5. **Model Selection (Part 2) s**  
  5.1 Determine Best model on basis of AUC 
   
6. **Final Model**  
  6.1 Prepare final training and test data  
  6.2 Final model : run with training and test data

