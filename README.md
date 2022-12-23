<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img1.png">

## INTRODUCTION

Rapid Finance handles all types of house loans. They have a presence in all metropolitan, semi-urban, and rural regions. The customer initially applies for a house loan through ICAM - a standardized application, following which the firm verifies the customer's loan eligibility manually. Because of the unpredicted growth that the business experienced last quarter, there is a shortage of staff who can go through the documents and come up with a verdict on the approval. The company wishes to automate the loan eligibility procedure (in real-time) based on the information supplied by the applicant. Not only will automation of the loan approval help the company reduce its expenses, but it will also enhance the scalability of the business in the longevity of their procedures.

This is a classic supervised classification problem, a task in which we must predict whether or not a loan will be approved. The data set we will be using could be found here: https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset


## DATA SET DESCRIPTION

There is a total of 614 rows and 13 columns in our data set of which 8 are categorical variables, 4 continuous, and 1 unique loan ID identifier.

The dataset attributes are listed below along with their descriptions.

<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img2.png">


## GETTING STARTED
The purpose of the following analysis is to predict whether an applicant is approved for a loan provided the required information.

For this we will be looking at the following machine learning models:
* Logistic Regression
* K-Nearest Neighbour (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* Gradient Boost

## IMPORTING MODULES

<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img3.JPG">

## PROPRIETARY ANALYSIS
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img4.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img5.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img6.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img7.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img8.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img9.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img10.png">
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img11.png" /></p>
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img12.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img13.png">
<img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img14.png">

<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img15.png" /></p>
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img16.png" /></p>
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img17.png" /></p>

## PREPROCESSING THE DATA
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img18.JPG" /></p>
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img19.png" /></p>

## BEFORE SKEWNESS REDUCTION TREATMENT

<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img20.png" /></p>

## AFTER SKEWNESS REDUCTION TREATMENT

<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img21.png" /></p>

## CORRELATION MATRIX

<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img22.JPG" /></p>

## FEATURE SEPARATION

<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img23.JPG" /></p>

## Logistic Regression
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img24.JPG" /></p>

## K-Nearest Neighbour (KNN)
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img25.JPG" /></p>

## Support Vector Machine (SVM)
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img26.JPG" /></p>

## Decision Tree
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img27.JPG" /></p>

## Random Forest
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img28.JPG" /></p>

## Gradient Boosting
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img29.JPG" /></p>

## Model Performance Comparison
<p align="center"><img src="https://raw.githubusercontent.com/JoexTitan/RFLP-Prediction-Model/main/Visuals/img30.JPG" /></p>
