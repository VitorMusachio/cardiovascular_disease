# Cardiovascular Disease

Project from [Kaggle](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset?resource=download) for predicting cardio disease.

Work in Progress...

## About Dataset

There are 3 types of input features.

Feature type | Description |
| :---: | :---: |
Objective | factual information |
Examination | results of medical examination |
Subjective | information given by the patient |

### Features

Feature | Feature Type | Feature Name in Dataset | Datatype |
| :---: | :---: | :---: | :---: |
Age | Objective Feature | age | int (days) |
Height | Objective Feature | height | int (cm) |
Weight | Objective Feature | weight | float (kg) |
Gender | Objective Feature | gender | categorical code |
Systolic blood pressure | Examination Feature | ap_hi | int |
Diastolic blood pressure | Examination Feature | ap_lo | int |
Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
Smoking | Subjective Feature | smoke | binary |
Alcohol intake | Subjective Feature | alco | binary |
Physical activity | Subjective Feature | active | binary |
Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

All of the dataset values were collected at the moment of medical examination.
