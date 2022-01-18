## DataScience_Capstone_Project  
**Industry area: Healthcare.**  
**Hands-on Experience demonstrated:**  
_Data Analytics_  
_Missing data analytics using `heatmap` and `dendogram`_  
_Data augmentation techniques_  
_Choosing appropriate data modeling algorithm using `Scikit-Learn`_  
_Parameter tuning using `XGBoost`, `Random Forest` and `ExtraTrees`_  
_Reporting using `Python` libraries and `Jupyter nb`._ 
### Problem Statement

    The dataset used in this project is originally from NIDDK. 
	The objective of the project is to:  
    (a) Predict whether or not a patient has diabetes , based on certain diagnostic measurements included in the dataset.
    (b) Build a model to accurately predict whether the patients in the dataset have diabetes or not.  
    NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases) research creates  
    knowledge about and treatments for the most chronic, costly, and consequential diseases.  

**Dataset Description**
  
The datasets consists of several medical predictor variables and one target variable (Outcome). Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and more.  

| Variables                | Description                                    |
| :----------------------- |:---------------------------------------------- |
| Pregnancies              | Number of times pregnant                       |
| Glucose                  | Plasma glucose concentration in an oral glucose tolerance test|
| BloodPressure            | Diastolic blood pressure (mm Hg)               |
| SkinThickness            | Triceps skinfold thickness (mm)                |
| Insulin                  | Two hour serum insulin                         |
| BMI                      | Body Mass Index                                |
| DiabetesPedigreeFunction | Diabetes pedigree function                     |
| Age                      | Age in years                                   |
| Outcome                  | Class variable (either 0 or 1). 268 of 768 values are 1, and the others are 0|

_The dataset can be found in the following zip:_  
[HealthCareDiabetes](https://raw.githubusercontent.com/Simplilearn-Edu/Data-Science-Capstone-Projects/master/Project_2.zip)  

**Project Task 1 : Data Exploration:**

1. Perform descriptive analysis. Understand the variables and their corresponding values. On the columns below, a value of zero does not make sense and thus indicates missing value:  
   Glucose, BloodPressure, SkinThickness, Insulin, BMI

2. Visually explore these variables using histograms. Treat the missing values accordingly.

3. There are integer and float data type variables in this dataset. Create a count (frequency) plot describing the data types and the count of variables. 

**Project Task 2: Data Exploration:**  

1. Check the balance of the data by `plotting` the count of outcomes by their value. 
Describe your findings and plan future course of action.

2. Create scatter charts between the pair of variables to understand the relationships. Describe your findings.

3. Perform `correlation analysis`. Visually explore it using a heat map.

**Project Task 3: Data Modeling:**  

1. Devise strategies for model building. It is important to decide the right validation framework. Express your thought process.

2. Apply an appropriate classification algorithm to build a model. Compare various models with the results from KNN algorithm.

**Project Task 4: Data Modeling/Data Reporting with Tableau Dashboard**  

1. Create a `classification` report by analyzing sensitivity, specificity, AUC (ROC curve), etc. Please be descriptive to explain what values of these parameter you have used.

2. Create a `dashboard in tableau` by choosing appropriate chart types and metrics useful for the business. The dashboard must entail the following:

    2.a  Pie chart to describe the diabetic or non-diabetic population

    2.b Scatter charts between relevant variables to analyze the relationships

    2.c Histogram or frequency charts to analyze the distribution of the data

    2.d Heatmap of correlation analysis among the relevant variables

    2.e Create bins of these age values: 20-25, 25-30, 30-35, etc. Analyze different variables for these age brackets using a bubble chart.  
**[My Solution](https://github.com/samuel-ntsua/DataScience_Capstone_Project/blob/d2c013a2a40d243cb612168a82b3ce3c5789424f/DS_capstone_proj_newrun_sntsua.ipynb)**
