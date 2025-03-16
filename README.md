# Heart Attack Classification Model

This repository contains the code and resources for a Heart Attack Classification Model (Neural Network, Logistic Regression, kNN, and Randomforest) developed to predict the likelihood of a heart attack based on various medical and lifestyle factors.

## 🤎Dataset
The dataset used for this model is available on Kaggle and can be found at this [Heart Attack Dataset](https://www.kaggle.com/datasets/waqi786/heart-attack-dataset).

- **Age**: Patient's age  
- **Sex**: Patient's sex  
- **exng**: Exercise-induced angina (1 = yes, 0 = no)  
- **ca**: Major vessels count (0-3)  
- **cp**: Chest pain type  
  - **1**: Typical angina  
  - **2**: Atypical angina  
  - **3**: Non-anginal pain  
  - **4**: Asymptomatic  
- **trtbps**: Resting blood pressure (mm Hg)  
- **chol**: Cholesterol (mg/dl) from BMI sensor  
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)  
- **rest_ecg**: Resting ECG results  
  - **0**: Normal  
  - **1**: ST-T wave abnormality  
  - **2**: Left ventricular hypertrophy (Estes' criteria)  
- **thalach**: Max heart rate achieved  
- **Target**:  
  - **0** = Less chance of heart attack  
  - **1** = More chance of heart attack  

## 🤎Evaluation
The model is evaluated using Classification Report and Confusion Matrix.

Initial results from Logistic Regression and Random Forest show promising recall score and reliable identification of patients at risk of a heart attack, though further tuning and validation may improve performance.
