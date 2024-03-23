# Loan-Approval-Model-
Model using Machine Learning to check if loan will be approved or not

![images](https://github.com/10guptapallavi/Loan-Approval-Model-/assets/157853035/e71fb7a6-7a26-48ec-88a3-1e73c0ddeaad)

Introduction
In this notebook, a machine learning model is formed to check the applicant's profile eligibility for the approval of loan using Python.

Following Approah will be implemented:

Problem definition
Data Exploration
Data Cleaning
Data Preprocessing
Evaluation
Features
Modelling
Experimentation
1. Problem Defination
Based on the applicants loan amount, applicant income, coapplicant income, marital status, education, property area, number of dependents, Gender, type of employement, will it be possible to predict the status of loan if it is approved or not?

2. Data Exploration
The raw data has 13 attributes which effect the loan aproval chance. The attributes are of two type- categorical and numeric. Explored raw data in terms of different attributes and draw very common conclusions for the chance of loan approval.

3. Data cleaning
Raw data has many null values, so data cleaning is done to fill those null values.

4. Data Preprocessing
Numeric data such as loan amount and applicant and coapplicant income has many outliers showing in their the boxplot and hist plots. I tried to remove the skeweness to get a better model. Rescale the numeric attributes to enhance the model predictions.

7. Evaluation
After modelling, main motive is to find the category of the Iris Flower

8. Data Features or Data Attributes
Information of different attributes of data is given below:

Create data dictionary sepal length in cm sepal width in cm petal length in cm petal width in cm class: -- Iris Setosa

-- Iris Versicolour

-- Iris Virginica

Important Libraries
I imported several libraries for the project:

numpy: To work with arrays
pandas: To work with csv files and dataframes
matplotlib: To create charts
seaborn: To create different category charts
train_test_split: To split the dataset into training and testing data
Approach
Data Wrangling

Exploratory Data Analysis (EDA) on the data set.

For modeling, I have identified 7 models to try:

I will be using different models to study our data:

Logistic Regression
SVM- Support Vector Machine
KNeighbors
Naive Bayes
DecisionTreeClassifier
RandomForestClassifier
GradientBoostingClassifier
Test size of Train-Test-Split is set to 20%

