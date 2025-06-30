# Stroke_Predictor_ML_with_Python

The purpose of this project is to create a stroke prediction machine learning model to predict the likelihood that a person will experience a stroke based on their health and their lifestyle.
This enables early intervention, preventive care, and better resource allocation in healthcare.

If you're using Anaconda or Miniconda, follow these steps to create and activate a virtual environment:

### Create virtual environment
You can name it stroke_env (or choose your own name):

```shell
conda create --name stroke_env python=3.10
```

### Activate the environment
```shell
conda activate stroke_env
```

### Install required packages
```shell
pip install jupyter pandas numpy matplotlib seaborn scikit-learn xgboost
```
or
```shell
conda install jupyter pandas numpy matplotlib seaborn scikit-learn xgboost
```

## Dataset

The dataset contains information such as:

- Age
- Gender
- Hypertension
- Heart Disease
- Marital Status
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke (Target)

The data is cleaned, preprocessed, and encoded for training and evaluation.

## Project Steps

1. **Data Cleaning**  
   Handling missing values, encoding categorical variables.

2. **Exploratory Data Analysis (EDA)**  
   Correlation analysis and data visualization to understand key predictors of stroke.
   
3. **Model Training**  
   - Logistic Regression  
   - Random Forest  
   - XG Boost
   - SVM

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix

5. **Model Optimization**  
   Hyperparameter and threshold tuning.

## Files

- `ML_Python_exam.ipynb` – Main notebook with code and results
- `stroke_data.csv` – Input dataset
- `README.md` – Project overview

