# Heart-Disease-Classification
Evaluating the performance of multiple (almost ALL!) supervised machine learning algorithms on a Heart Disease dataset

## <u>Overview</u>
The main objective of this project is to develop a classification algorithm that identifies individuals with heart disease based on some of their health condition and other relevant attributes. To achieve that several classifiers were trained on a labelled dataset of patients, as well as ensemble methods, boosting and stacking methods. Results from all these methods were thoroughly analysed and the advantages and disadvantages of each of the methods used were rigorously discussed. The classifier that was ultimately selected was the one that achieved the best balance between performance and interpretability.

## <u>Context</u>
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

## <u>About the dataset</u>
The dataset has around 900 rows and 12 features as follows:
1. Age: age of the patient [years]
1. Sex: sex of the patient [M: Male, F: Female]
1. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
1. RestingBP: resting blood pressure [mm Hg]
1. Cholesterol: serum cholesterol [mm/dl]
1. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
1. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
1. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
1. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
1. Oldpeak: oldpeak = ST [Numeric value measured in depression]
1. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
1. HeartDisease: output class [1: heart disease, 0: Normal]

## <u>Source</u>
The dataset was obtained from Kaggle.
This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

- Cleveland: 303 observations
- Hungarian: 294 observations
- Switzerland: 123 observations
- Long Beach VA: 200 observations
- Stalog (Heart) Data Set: 270 observations
- Total: 1190 observations
- Duplicated: 272 observations

*Final dataset: 918 observations*

## <u>Supervised Machine Learning, Classification </u>

