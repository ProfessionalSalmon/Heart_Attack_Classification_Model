# Heart Attack Classification Model

This repository contains the code and resources for a Heart Attack Classification Model (Logistic Regression, kNN, and, Randomforest) developed to predict the likelihood of a heart attack based on various medical and lifestyle factors.

## Dataset
The dataset used for this model is available on Kaggle and can be found at this [Heart Attack Dataset](https://www.kaggle.com/datasets/waqi786/heart-attack-dataset).

- Age: Age of the patient

- Sex: Sex of the patient

- exng: exercise induced angina (1 = yes; 0 = no)

- ca: number of major vessels (0-3)

- cp: Chest Pain type
    - Value 1: typical angina
    - Value 2: atypical angina
    - Value 3: non-anginal pain
    - Value 4: asymptomatic

- trtbps: resting blood pressure (in mm Hg)

- chol: cholestoral in mg/dl fetched via BMI sensor

- fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

- rest_ecg: resting electrocardiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

- thalach: maximum heart rate achieved

- Target variable: 0 = less chance of heart attack, 1 = more chance of heart attack

## Usage
To run the notebook locally, ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Evaluation
The model is evaluated using various metrics such as:

Accuracy: How often the model makes the correct prediction.
Precision & Recall: To assess the balance between false positives and false negatives.
Confusion Matrix: For a breakdown of true vs. false predictions.
Initial results show promising accuracy and reliable identification of patients at risk of a heart attack, though further tuning and validation may improve performance.