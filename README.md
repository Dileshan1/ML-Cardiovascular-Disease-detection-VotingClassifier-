# Cardiovascular disease prediction

* The task is to predict the presence or absence of cardiovascular disease (CVD) using the patient examination results.
* predict Cardiovascular disease using 11 idependent variables.
* use kaggle dataset for predict Cardiovascular disease
* use VotingClassifier to predict Cardiovascular disease

## dataset
[kaggle-Cardiovascular disease](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)

The dataset consists of 70 000 records of patients data in 12 features, such as age, gender, systolic blood pressure, diastolic blood pressure, and etc. The target class "cardio" equals to 1, when patient has cardiovascular desease, and it's 0, if patient is healthy.

## About Dataset

Data description
There are 3 types of input features:

Objective: factual information;
Examination: results of medical examination;
Subjective: information given by the patient.
Features:

1. | Age | Objective Feature | age | int (days)
2. | Height | Objective Feature | height | int (cm) |
3. | Weight | Objective Feature | weight | float (kg) |
4. | Gender | Objective Feature | gender | categorical code |
5. | Systolic blood pressure | Examination Feature | ap_hi | int |
6. | Diastolic blood pressure | Examination Feature | ap_lo | int |
7. | Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
8. | Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
9. | Smoking | Subjective Feature | smoke | binary |
10. | Alcohol intake | Subjective Feature | alco | binary |
11. | Physical activity | Subjective Feature | active | binary |
12. | Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

All of the dataset values were collected at the moment of medical examination.
