## About dataset:

The heart disease dataset consists of 918 records across 12 columns, covering the important feature variable and target value. The dataset includes various sale categories and attributes such as:

1. **Age:** age of the patient [years]
2. **Sex:** sex of the patient [M: Male, F: Female]
3. **ChestPainType:** chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. **RestingBP:** resting blood pressure [mm Hg]
5. **Cholesterol:** serum cholesterol [mm/dl]
6. **FastingBS:** fasting blood sugar [1: if FastingBS > 120 mm/dl, 0: otherwise]
7. **RestingECG:** resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes criteria]
8. **MaxHR:** maximum heart rate achieved [Numeric value between 60 and 202]
9. **ExerciseAngina:** exercise-induced angina [Y: Yes, N: No]
10. **Oldpeak:** oldpeak = ST [Numeric value measured in depression]
11. **ST_Slope:** the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. **HeartDisease:** output class [1: heart disease, 0: Normal]

This dataset contains a mix of textual and numerical (float) values, which can be challenging to manage, analyze, and predict the new values' outcomes manually.

## Problem Statement and Approach

To predict whether a patient will have a heart attack, I will use Python and its data science libraries, along with Microsoft Excel.

**Data Preparation**

Python libraries like NumPy and Pandas will be used for data cleaning and manipulation, while Excel will assist with preliminary data inspection.

**Exploratory Data Analysis (EDA)**

Visualization tools such as Matplotlib and Seaborn will help uncover patterns and insights.

**Model Building**

Scikit-learn will be employed to develop and evaluate classification models, aiming to predict heart attack risk based on the provided features.

This combined approach will facilitate thorough data analysis, feature engineering, and model development to accurately predict heart attack likelihood.
