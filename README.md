# Heart_disease_prediction

Kaggle contest (https://www.kaggle.com/competitions/heart-disease-prediction-tfug-chd-oct-2022)

## Source
This dataset has been synthetically cured from the original data source using CTGAN, as acknowledged in brief.

## Files
train.csv - the training set  
test.csv - the test set  
sample_submission.csv - a sample submission file in the correct format


## Columns
This dataset is composed of various parameters namely,

age: age of the patient [years]  
sex: (0: Male, : Female)  
chest pain type: chest pain type [0: Typical Angina, 1: Atypical Angina, 2: Non-Anginal Pain, 3: Asymptomatic]  
	Recoded to [0: No chest pain, 1: Typical Angina, 2: Atypical Angina, 3: Non-Anginal Pain, 4: Asymptomatic]
resting bp s: resting blood pressure [mm Hg]  
cholesterol: serum cholesterol [mm/dl]  
fasting blood sugar: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]  
resting ECG: resting electrocardiogram results [0: Normal, 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), 2: showing probable or definite left ventricular hypertrophy by Estes' criteria]  
max heart rate: maximum heart rate achieved [Numeric value between 60 and 202]  
exercise angina: (0: No, 1: Yes)  
oldpeak: ST [Numeric value measured in depression]  
ST slope: the slope of the peak exercise ST segment (1—upsloping; 2—ﬂat; 3—downsloping)
target: [0: Normal, 1: Heart disease]  
