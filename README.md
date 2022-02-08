# Stroke-Prediction: Project Overview
* Performance Comparison using Machine Learning Classification Algorithms on a Stroke Prediction dataset.
* using visualization libraries, ploted various plots like pie chart, count plot, curves, etc. 
* Used various Data Preprocessing techniques.
* Handle class imbalanced.
* Build various machine learning models
* Optimized SVM and Random Forest Classifiers using RandomizedSearchCV to reach the best model. 

## Pattern Recognition Project - B.Sc. in Computer Science and Engineering (CSE)

## Created by: - Mohammed Jawwadul Islam, Md Fahad Al Rafi, Pranto Podder

### Date of Completion: - Fall 2021 Trimester (Nov 2021 - Jan 2022)

### [Linkedin of Jawwadul](https://www.linkedin.com/in/jawwadfida/)  
### [Linkedin of Fahad](https://www.linkedin.com/in/md-fahad-al-al-rafi-14b968111/)
### [Linkedin of Pranto](https://www.linkedin.com/in/pranto-podder-b78b97162/)

## Code and Resources Used 
**Python Version:** 3.7.11  
**Packages:** numpy, pandas, sklearn, matplotlib, seaborn
**Dataset from:** [fedesoriano](https://www.kaggle.com/fedesoriano) <br>
**For Web Framework Requirements:**  ```pip install -r requirements.txt```  

## Features of the Dataset
Dataset contains 5111 rows. Each row in the data provides relevant information about the patient. 
* gender: "Male", "Female" or "Other"
* age: age of the patient
* hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has 
hypertension
* heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
* ever_married: "No" or "Yes"
* work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
* Residence_type: "Rural" or "Urban"
* avg_glucose_level: average glucose level in blood
* bmi: body mass index
* smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
* stroke: 1 if the patient had a stroke or 0 if not 

## Data Preprocessing
The data was cleaned it up to make it usable for the model. The following changes were made:

* replaced the null values by median using Sklearn Simple Imputer.
* converted the text features into numeric value using LabelEncoder from Sklearn.
* oversampled the dataset, i.e. increase the number of positive samples, by using RandomOverSampler from imblearn.


## Exploratory Data Analysis (EDA)
At first, using visualization libraries, we did some data visualizations by plotting various plots like pie chart, count plot, curves, etc. in order to understand the dataset better, and to find out the correlation between the attributes.. Below are a few highlights. 

![Count Plot - Job Type](https://user-images.githubusercontent.com/64092765/153050389-3dc5592f-3124-4abd-b615-19dff7f2160b.png)

![Pie Chart - Smoking Categories](https://user-images.githubusercontent.com/64092765/153050403-797bbcc7-fcf0-4830-933e-573beb29b2aa.png)

![Heat Map](https://user-images.githubusercontent.com/64092765/153050409-4de973ab-0d3a-4ef1-b4de-670248439bbb.png)

![No Stroke vs Stroke by BMI](https://user-images.githubusercontent.com/64092765/153050416-aff6dcb1-a406-417d-b060-dbd5056c1177.png)

![Categorical Plot](https://user-images.githubusercontent.com/64092765/153050427-1b13cf20-49fd-437f-991c-548ad32a65e9.png)

## Model Building 

The categorical variables were transformed into dummy variables. Dataset was split into train and tests sets with a test size of 20%.   
After our dataset was finally ready, we have used some machine learning classification algorithms on this dataset and observed their performances. 

The different models used are:
* Logistic Regression 
* Naive Bayes
* k Nearest Neighbors*. Support Vector Machine – Gaussian SVM
* Random Forest Classifier

## Model performance
We then compared these results based on various classification metrics. 
The metrics are: accuracy, precision, recall, f1 score and mcc score.

![image](https://user-images.githubusercontent.com/64092765/153050322-d2dca138-58d4-4bd1-9ac4-5927983b895a.png)






