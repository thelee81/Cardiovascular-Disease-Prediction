# Cardiovascular Disease (Heart disease) Prediction

Heart disease describes a range of conditions that affect your heart. Diseases under the heart disease umbrella include blood vessel diseases, such as coronary artery disease; heart rhythm problems (arrhythmias); and heart defects you're born with (congenital heart defects), among others.

The term "heart disease" is often used interchangeably with the term "cardiovascular disease." Cardiovascular disease generally refers to conditions that involve narrowed or blocked blood vessels that can lead to a heart attack, chest pain (angina) or stroke. Other heart conditions, such as those that affect your heart's muscle, valves or rhythm, also are considered forms of heart disease.

<img src=https://www.mayoclinic.org/-/media/kcms/gbs/patient-consumer/images/2014/09/22/12/43/mcdc7_theheart.jpg, width="300" height="300">

More refrence:
https://www.mayoclinic.org/diseases-conditions/heart-disease/symptoms-causes/syc-20353118

# Objective of this notebook 

To show how Machine Learning and Deep Learning methods can be used on tabular data to build models that predicts the disease.

For Machine Learning Random Forest was used to build model
For Deep Learning TensorFlow Keras was used to build model

# Data description
There are 3 types of input features:

1. Objective: factual information;
2. Examination: results of medical examination;
3. Subjective: information given by the patient.


**Features:**

|Feature Name | Objective Feature | Column Name | Data Type|
|------|------|------|------|
|Age | Objective Feature | age | int (days)|
|Height | Objective Feature | height | int (cm) |
|Weight | Objective Feature | weight | float (kg) |
|Gender | Objective Feature | gender | categorical code |
|Systolic blood pressure | Examination Feature | ap_hi | int |
|Diastolic blood pressure | Examination Feature | ap_lo | int |
|Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
|Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
|Smoking | Subjective Feature | smoke | binary |
|Alcohol intake | Subjective Feature | alco | binary |
|Physical activity | Subjective Feature | active | binary |
|Presence or absence of cardiovascular disease | Target Variable | cardio | binary |
| | | | |
