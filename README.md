# Task 3: Heart Disease Prediction

## Task Objective
The goal of this task is to build a model that predicts whether a person is at risk of heart disease based on their health data. This helps in early detection and decision-making for preventive healthcare.

## Dataset Used
- **Heart Disease UCI Dataset** (available on Kaggle)  
- Contains features such as Age, Sex, Chest Pain Type, Blood Pressure, Cholesterol, Maximum Heart Rate, and more.  
- Target variable: `Heart Disease` (0 = Absence, 1 = Presence)

## Models Applied
1. **Logistic Regression**  
   - Provides interpretable linear relationships between features and heart disease risk.
2. **Decision Tree Classifier**  
   - Captures non-linear patterns and identifies important features for splitting data.

## Key Results and Findings
- Both models achieved high accuracy in predicting heart disease.  
- ROC-AUC scores indicate strong ability to distinguish between patients with and without heart disease.  
- Confusion matrices show how many patients were correctly or incorrectly classified.  
- **Important features** affecting prediction:
  - Age
  - Chest Pain Type
  - Cholesterol
  - Maximum Heart Rate
- Logistic Regression highlights linear relationships, while Decision Tree captures non-linear patterns, providing complementary insights for risk assessment.  

## Conclusion
The models can assist healthcare professionals in identifying high-risk patients and focusing on key health indicators for preventive care. Combining multiple models can improve prediction robustness.
