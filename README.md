# BI Programming - Final Project on Diabetes Analysis
---------------
## Context
---------------

Diabetes is one of the most frequent diseases worldwide and the number of diabetic patients are growing over the years. The main cause of diabetes remains unknown, yet scientists believe that both genetic factors and environmental lifestyle play a major role in diabetes.

A few years ago research was done on a tribe in America which is called the Pima tribe (also known as the Pima Indians). In this tribe, it was found that the ladies are prone to diabetes very early. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients were females at least 21 years old of Pima Indian heritage. 

-----------------
## Objective
-----------------

Here, we are analyzing different aspects of Diabetes in the Pima tribe by doing Exploratory Data Analysis.

-------------------------
## Data Dictionary
-------------------------

The dataset has the following information:

* Pregnancies: Number of times pregnant
* Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test
* BloodPressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skin fold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body mass index (weight in kg/(height in m)^2)
* DiabetesPedigreeFunction: A function which scores likelihood of diabetes based on family history.
* Age: Age in years
* Outcome : Class variable (0: person is not diabetic or 1: person is diabetic)

-------------------------
## Process
-------------------------
Step 1: We have done Exploratory Data Analysis (EDA) on our dataframe. 
<br>Step 2: Train and Test Data split.
<br>Step 3: Model Training (Models used: Logistic Regression and Random Forest Models).
<br>Step 4: Model Evaluation and Analysis.

-------------------------
## Conclusion
-------------------------
* From the observation of **Accuracy** and **Confusion Matrix** scores, we can see that the **Random Forest** model has **higher accuracy** of **82%** and **79%** on the **train and test sets**, respectively.
* Also while comparing the scores along with the **Confusion Matrix** we can see that the **Random Forest** model has low False Negatives comparitively with **Logistic Regression** model.
* In future, we can also perform hyperparameter tuning to our **Random Forest** model and increase its accuracy scores even higher.
