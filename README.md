**Name:** Heart Health Classifier

**Author:** Sharome Burton

**Date:** 07/16/2021

**Description:** Machine learning model used to classify whether a patient has heart disease based on structured data. This notebook looks into using various Python-based machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

Approach:
1. Problem definition
2. Data (source: https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Definition

> Given clinical parameters about a patient, are we able to predict whether they have heart disease?

## 2. Data

The original data came from Cleveland data from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Heart+Disease

Data is also available on Kaggle: https://www.kaggle.com/ronitf/heart-disease-uci

## 3. Evaluation

> Goal: Reach 95% accuracy at predicting whether a patient has heart disease during proof of concept

## 4. Features

Information about each feature in the dataset:

* age: age in years
* sex: sex (1 = male; 0 = female)
* cp: chest pain type
    - Value 1: typical angina
    - Value 2: atypical angina
    - Value 3: non-anginal pain
    - Value 4: asymptomatic 
* trestbps: resting blood pressure (in mm Hg on admission to the hospital)
* chol: serum cholestoral in mg/dl
* fbs: fasting blood sugar > 120 mg/dl
* restecg: resting electrocardiographic results (values 0,1,2)
* thalach: maximum heart rate achieved
* exang: exercise induced angina
* oldpeak: ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
* ca: number of major vessels (0-3) colored by flourosopy
* thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

Guidance from data science and machine learning course: https://github.com/mrdbourke/zero-to-mastery-ml

