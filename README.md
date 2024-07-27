# Project 5: Group Project - Opioid Abuse


## Problem Statement

Can we build a model that predicts the likelihood of a patient abusing prescribed pain medication?

## Questions

1. Can we predict the likelihood of a patient abusing prescription pain medication based on past addiction history?
2. How do different characteristics correlate to our predictions?
3. How accurate of a model can we build and how could it be improved upon?
4. What type of model gets us the best result?

## Data Dictionary


| Feature             | Type   | Dataset | Description                                                                       | Note |
|---------------------|--------|---------|-----------------------------------------------------------------------------------|------|
| **PRLMISAB**        | *int*  | All     | Abused prescription medications (Binary).                       | **TARGET VARIABLE** |    
| **YEAR**            | *int*  | All     | Year of survey (Integer).                                                         |   15=2015, 16=2016, 17=2017   |
| **AGECAT**          | *int*  | All     | Age category (Categorical).                                                       | 1=12-17 years, 2=18-25, 3=26-35, 4=36-49, 5=50 and older |
| **SEX**             | *int*  | All     | Gender (Categorical).                                                             |   0=Male, 1=Female   |
| **MARRIED**         | *int*  | All     | Marital status (Categorical).                                                     |  0=unmarried, 1=divorced, 2=widowed, 3=married     |
| **EDUCAT**          | *int*  | All     | Education level (Categorical).                                                    |   1=h.s. or Less, 2=h.s. grad., 3=some college, 4=college grad.    |
| **EMPLOY18**        | *int*  | All     | Employment status (Categorical).                                                  |  1=not employed, 2=part-time, 3=full-time    |
| **CTYMETRO**        | *int*  | All     | City or metropolitan area (Categorical).                                          |    1=rural, 2=small, 3=large |
| **HEALTH**          | *int*  | All     | Self-reported health (Categorical).                                               |   Likert scale: 1-10   |
| **MENTHLTH**        | *int*  | All     | Self-reported mental health (Categorical).                                        |   Likert scale: 1-10   |
| **PRLMISEVR**       | *int*  | All     | Ever misused prescription medication (Binary).                                    |       |
| **PRLANY**          | *int*  | All     | Misused or abused minimum prescription medications (Binary).                      |       |
| **HEROINEVR**       | *int*  | All     | Ever used heroin (Binary).                                                        |       |
| **HEROINUSE**       | *int*  | All     | Used heroin in past year (Binary).                                                |   Likert scale: 0-5   |
| **TRQLZRS**         | *int*  | All     | Used tranquilizers in past year (Binary).                                         |   Likert scale: 0-5    |
| **SEDATVS**         | *int*  | All     | Used sedatives in past year (Binary).                                             |   Likert scale: 0-5    |
| **COCAINE**         | *int*  | All     | Used cocaine in past year (Binary).                                               |   Likert scale: 0-5    |
| **AMPHETMN**        | *int*  | All     | Used amphetamines in past year (Binary).                                          |  Likert scale: 0-5   |
| **HALUCNG**         | *int*  | All     | Used hallucinogens in past year (Binary).                                         |  Likert scale: 0-5    |
| **TRTMENT**         | *int*  | All     | Received treatment for substance use (Binary).                                    |    Likert scale: 1-10    |
| **MHTRTMT**         | *int*  | All     | Received treatment for mental health (Binary).                                    |   Likert scale: 0-5   |
| **AGE_MARRIED**         | *int*  | All     | Interaction (*) of AGECAT and MARRIED.                                               |       |
| **AGE_EMPLOY**        | *int*  | All     | Interaction (*) of AGECAT and EMPLOY18.                                          |     |
| **REPORTED_HEALTH**         | *int*  | All     | Interaction (*) of HEALTH and MENTHLTH.                                         |      |
| **HISTORY**         | *int*  | All     | Interaction (*) of HEROINEVR and PRLMISEVR                                    |        |
| **UPPERS**         | *int*  | All     | Use of uppers in last year (Cocaine and Amphetamines).                                    |      |
| **DOWNERS**         | *int*  | All     | Use of downers in the last year (Sedatives, Tranqs, Heroin).    

## Data Used
1. prlmis-data-full.csv
2. pain_clean.csv


Links to outside resources used:
1. Opioid Crisis in Young Americans https://murphy.house.gov/media/press-releases/murphy-fentanyl-killing-more-young-americans-covid-19
2. 


---

## Requirements
- Python, Jupyter
- Pandas, Numpy, Matplotlib, Seaborn
- Scikit Learn Libraries:
   - StandardScaler, Train Test Split, Metrics, LogisticRegression
   - Pipeline
- Tensorflow, Keras
   - Conv2D, MaxPooling2D, Flatten, Dense, Dropout
   - VGG16, TensorBoard
---
## Executive Summary
 This project aims to develop a machine learning model to predict the likelihood of a patient abusing pain medications. This information would allow doctors to make decisions on what types of pain meds to give, how much to give at a time, prevent cases of addiction and/or relapse and
intervene early, create treatment plans and overall improve quality of care for all patients.

 
#### Objectives
1. Data Processing: Clean and preprocess the text data to ensure it is suitable for model training.
2. Data Exploration: Explore data for correlations to our target variable and create interaction terms.
3. Model Development: Develop and train machine learning models to predict the likelihood of a patient abusing prescription pain medications.
4. Evaluation: Assess the performance of the models using various metrics to ensure their accuracy and reliability.


#### Methods
  - 
  

#### Findings
  - 

#### Next steps
  -  