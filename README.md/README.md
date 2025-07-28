# Predicting Coronary Heart Disease (CHD)

## Overview
This project applies classification models to predict the likelihood of coronary heart disease (CHD) using clinical and behavioral data from the SAHeart dataset. The goal is to identify key predictors and assess which modeling approach is most suitable in a healthcare context.

## Dataset
The dataset contains medical and lifestyle features for individuals, including:
- Age
- LDL cholesterol
- Adiposity (body fat)
- Tobacco and alcohol use
- Family history of CHD
- Type A behavior
- Blood pressure and obesity indicators

## Objectives
- Identify important risk factors associated with CHD
- Train and evaluate multiple classification models
- Interpret model outputs for clinical relevance

## Tools and Libraries
- Python, pandas, NumPy
- scikit-learn
- seaborn, matplotlib

## Modeling Summary

We trained and evaluated three models:

### Logistic Regression
- Accuracy: 0.74
- Precision: 0.63
- Recall: 0.63
- F1 Score: 0.63
- ROC AUC: 0.82

**Key Points:**
- Highest ROC AUC of all models
- Most interpretable model
- Age, family history, LDL, and Type A behavior were major contributors

### Decision Tree
- Accuracy: 0.54
- ROC AUC: 0.56
- Struggled with overfitting and poor generalization

### Random Forest
- Accuracy: 0.68
- ROC AUC: 0.72
- Balanced performance, less interpretable
- Top features: Age, LDL, tobacco, adiposity, type A behavior

## Key Takeaways

- **Age**  
  Risk of CHD increases naturally with each passing year. This is a reminder to cherish every day and prioritize both physical and mental health.

- **Type A Behavior**  
  More reactive, high-stress individuals may be at increased risk. Learning to manage stress, slow down, and cultivate emotional balance can offer real protection.

- **Family History**  
  A significant predictor of CHD. Take time to understand your family’s medical background — it could inform preventative decisions and screenings.

- **Lifestyle Modifications**  
  Classic advice remains powerful:
  - Reduce body fat and manage adiposity
  - Improve LDL cholesterol through diet and activity
  - Avoid tobacco
  - Limit alcohol consumption

**In summary:**  
Small, consistent lifestyle choices can meaningfully reduce the risk of CHD.  
The data supports it — and now, so do you.
