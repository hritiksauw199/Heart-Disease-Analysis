# Heart-Disease-Analysis

**In this project, we analyze different attributes/parameters that indicate heart disease among men and women.**

We prepared, transformed, and performed Exploratory Data Analysis on the data to answer questions like:
1. What is the mean age of patients?
2. Which gender is more prone to heart disease?
3. What parameters are highly correlated with heart disease?
4. Does a particular chest pain indicate heart disease?

, and gain insights into which different attributes/parameters indicate heart disease among patients.
****
### Real-world applications

In rural places or hospitals lacking specialized medical pieces of equipment, patients usually have to wait a long time to
get their test reports and diagnosis, which prevents early treatment and could risk a patient's life.

In such situations, a more-refined version of this analysis could help in the early detection of heart disease.
The medical team could conduct only those tests (like chest pain, thalach, etc.) which are highly correlated with heart disease and help 
provide early treatment to patients. 

****

## About Dataset

This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. 
It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. 

The `target` field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease. 

Dataset Link: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

### Attribute information

1. `age`
2. `sex` : (1: male; 0; female)
3. `cp`: chest pain type (0: typical angina; 1: atypical angina; 2: non-anginal pain; 3: asymptomatic)
4. `trestbps`: resting blood pressure (in mm Hg)
5. `chol`: serum cholestoral in mg/dl
6. `fbs`: fasting blood sugar 120 mg/dl (1: True; 0: False)
7. `restecg`: resting electrocardiographic results (0: normal; 1: having ST-T wave abnormality; 2: showing probable or definite left ventricular hypertrophy)
8. `thalach`: maximum heart rate achieved
9. `exang`: exercise induced angina (1: yes; 0: no)
10. `oldpeak`: ST depression induced by exercise relative to rest
11. `slope`: the slope of the peak exercise ST segment (1: upsloping; 2: flat; 3: downsloping)
12. `ca`: number of major vessels (0-3) colored by flourosopy
13. `thal`: (0: normal; 1: fixed defect; 2: reversable defect)
14. `target`: (0: no heart disease; 1: heart disease)
****

## Libraries Used

`numpy`, `pandas`, `seaborn`, `matplotlib`, `plotly`

## Dashboard

Dashboard Link : https://public.tableau.com/views/HeartDiseaseAnalysis_16708396459530/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

![](heart%20db.png)
