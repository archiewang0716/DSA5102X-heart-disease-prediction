# DSA5102X-heart-disease-prediction
DSA5102X Project: Heart Disease Prediction

Codes can be seen in `heart-disease-prediction.ipynb`.

We use Heart Disease UCI dataset (link: https://archive.ics.uci.edu/ml/datasets/Heart+Disease) for this project. This dataset contains 76 attributes, but all published experiments refer to using a subset of 14 of them. Brief description of its attributes are shown below:

```
1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
 -- Value 1: typical angina
 -- Value 2: atypical angina
 -- Value 3: non-anginal pain
 -- Value 4: asymptomatic
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
 -- Value 0: normal
 -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST 
             elevation or depression of > 0.05 mV)
 -- Value 2: showing probable or definite left ventricular hypertrophy
             by Estes' criteria
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
-- Value 1: upsloping
-- Value 2: flat
-- Value 3: downsloping
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14. target: diagnosis of heart disease (angiographic disease status)
-- Value 0: < 50% diameter narrowing
-- Value 1: > 50% diameter narrowing
```

With the help of this dataset, we aim to predict the presence of heart disease with these 13 features for the patients. Our goal is to use the machine learning models to help predict the variable target. 
