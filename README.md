# Portfolio 4 - Analysis of Analysis of Heart disease prediction
This portfolio uses the dataset from [Kaggle](https://www.kaggle.com/datasets/mexwell/heart-disease-dataset/data). The perpose of this project is to help predicting if an individual has heart disease. Use two different machine learning models to bulid the models, evaluate the models and make comparsion. 
# Description
This profolio compares the two models bulit by logistic regression and KNN classification, hoping to make predection about heart health condition of an individual and using descriptive data to answer some quesions.
Here is question that will be answered along with:
1. Which gender is more likely to have heart disease?
2. Which types of chest pain is more likely to leading to heart disease?
3. Which factors or attrbutes are much important to predict heart disease?

Structure of this portfolio:
1. Import and explore dataset
2. Clean the dataset
3. Answer question 1
4. Answer question 2
5. Answer question 3
   * Study correlation and selecting features 
6. Bulid logistic regression model
   * Explain and evaluate the model performance
7. Bulid KNN classification model
    * Tunning hyper-parameter K
    * Explain and evaluate the model performance
8. Evaluate and compare two models using confusion matrix
# Data overview
* Age
* gender (1 = male, 0 = female)
* Chest pain types ( 1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
* resting bp s: resting blood pressure
* cholesterol: serum cholesterol
* Fasting blood sugar: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* resting ecg: Resting electrocardiogram results ( 0 = normal, 1 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) , 2 = showing probable or definite left ventricular hypertrophy by Estes criteria)
* max heart rate: Maximum heart rate achieved
* exercise angina: Exercise induced angina (1 = Yes, 0 = No):
* ST slope: The slope of the peak excerise ST segment ( 1 = upsloping, 2 = flat, 3 = downsloping)
* Target < Target variable > (1 = heart disease, 0 = Normal)
# Version History

0.1 Initial Release
