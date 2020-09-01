# Heart-Disease-Analysis

Analysing the heart-disease-uci from kaggle datasets.
In particular, the Cleveland database is the only one that has been used by ML researchers to this
date. The "target" field refers to the presence of heart disease in the patient. It is integer valued
from 0 (no presence) and 1 (presence) and it will get stored in the target column. Target is the
dependent variable and rests all the variable are the independent variable. We are analysing the
data to see the gender bifurcation for the patient having the heart diseases. As we are analysing
the clinical data set so, we are dealing with some of the clinical abbreviations.

1) age: The person's age in years
2) sex: The person's sex (1 = male, 0 = female)
3) cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
4) trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)
5) chol: The person's cholesterol measurement in mg/dl
6) fbs: The person's fasting blood sugar (if > 120 mg/dl, 1 = true; 0 = false)
7) restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
8) thalach: The person's maximum heart rate achieved
9) exang: Exercise induced angina (1 = yes; 0 = no)
10) oldpeak: ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot)
11) slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
12) ca: The number of major vessels (0-3)
13) thal: A blood disorder called thalassemia (1 = normal; 2 = fixed defect; 3 = reversable defect)
14) target: Heart disease (0 = no, 1 = yes)

Looking at information of heart disease risk factors led me to the following: high cholesterol,
high blood pressure, diabetes, weight, family history and smoking 3. According to another source 4,
the major factors that can't be changed are: increasing age, male gender and heredity. Note that thalassemia,
one of the variables in this dataset, is heredity. Major factors that can be modified are: Smoking,
high cholesterol, high blood pressure, physical inactivity, and being overweight and having diabetes.
Other factors include stress, alcohol and poor diet/nutrition.
