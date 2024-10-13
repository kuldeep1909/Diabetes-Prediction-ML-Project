# **Diabetes Prediction Project**

## **Overview**
This project aims to predict whether a person has diabetes based on key health parameters such as glucose levels, BMI, insulin levels, and more. It uses a **Support Vector Machine (SVM)** model to classify patients as diabetic or non-diabetic. The dataset used consists of health data from over 700 individuals.

## **Dataset**
The dataset contains the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function that scores the likelihood of diabetes based on family history
- **Age**: Age in years
- **Outcome**: 0 for non-diabetic, 1 for diabetic

## **Steps in the Project**
1. **Importing Libraries**: 
   - Libraries like `pandas`, `numpy`, `scikit-learn` were used for data processing, model building, and evaluation.
   
2. **Data Collection and Preprocessing**:
   - The data was loaded and analyzed using basic exploratory data analysis (EDA).
   - Standardization was applied to bring all feature values to a similar scale.
   
3. **Splitting the Data**:
   - The dataset was split into training and testing sets with a ratio of 80:20.
   
4. **Modeling**:
   - The **SVM (Support Vector Machine)** with a linear kernel was chosen to classify the patients.
   - The model was trained using the training set and evaluated using the test set.

5. **Prediction System**:
   - A prediction system was built to classify a new set of input features as diabetic or non-diabetic.

6. **Model Saving**:
   - The trained model was saved using **Pickle** for future use and easy deployment.

## **Usage**

### 1. Clone the repository:
```bash
git clone https://github.com/kuldeep1909/Diabetes-Prediction-ML-Project
```

## **Technologies Used**
- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Scikit-learn** for model building and evaluation
- **Pickle** for saving and loading the model




