
# Heart Health Data Analysis

This project analyzes a heart health dataset to predict the likelihood of heart disease using various clinical features. The dataset includes attributes such as age, sex, cholesterol levels, and exercise-induced factors. The goal is to identify patterns that could help in diagnosing heart disease.

## Project Overview
This project aims to analyze a dataset related to heart health and predict the presence of heart disease based on various clinical and personal features. The analysis focuses on exploring relationships between these features and their impact on heart health.

## Dataset
The dataset includes the following attributes:
- **age**: Age of the patient (in years)
- **sex**: 1 = male, 0 = female
- **cp (chest pain type)**:
  - 0: Typical angina
  - 1: Atypical angina
  - 2: Non-anginal pain
  - 3: Asymptomatic
- **trestbps**: Resting blood pressure (mm Hg)
- **chol**: Serum cholesterol (mg/dL)
- **fbs**: Fasting blood sugar > 120 mg/dL (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results
  - 0: Nothing to note
  - 1: ST-T Wave abnormality
  - 2: Possible or definite left ventricular hypertrophy
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise
- **slope**: Slope of the peak exercise ST segment
  - 0: Upsloping
  - 1: Flat
  - 2: Downsloping
- **ca**: Number of major vessels (0-3) colored by fluoroscopy
- **thal**: Thalium stress test result (1,3 = normal; 6 = fixed defect; 7 = reversible defect)
- **target**: Presence of heart disease (1 = yes, 0 = no)

## Technologies Used
- **Python**
- **NumPy**: For numerical operations
- **pandas**: For data manipulation
- **seaborn**: For visualizations

## Installation
To run this project, install the necessary libraries:

```bash
pip install numpy pandas seaborn
```

## Data Attributes
The heart health data includes important features like:
- **Chest pain type**: Differentiating typical and atypical angina from non-anginal or asymptomatic cases.
- **Blood pressure and cholesterol**: Key indicators of heart health.
- **Exercise-induced factors**: Data such as exercise-induced angina, ST depression, and the slope of the peak ST segment offer insights into how the heart handles stress.

## Exploratory Data Analysis
The analysis includes:
- Distribution of patients by age and sex.
- Correlation between cholesterol, blood pressure, and heart disease.
- Relationship between chest pain types and the presence of heart disease.
- Impact of exercise-induced factors on heart health.



## Conclusion
The analysis reveals key factors that contribute to heart disease, such as high cholesterol, exercise-induced angina, and resting blood pressure. Understanding these patterns can aid in early detection and treatment.

 Future ScopeBased on our analysis, the Random Forest Classifier model demonstrated the highest accuracy score among the tested models (KNN, Logistic Regression, Random Forest).
 However, it's crucial to consider the context of medical diagnosis and the potential consequences of misclassification.

 The confusion matrix and classification report provide insights into the model's performance on different classes. It's important to analyze metrics like precision, recall, and F1-score,
 especially for imbalanced datasets, to understand the trade-offs between false positives and false negatives.

 Cross-validation helps assess the model's generalizability and robustness. The mean cross-validated accuracy provides a more reliable estimate of the model's performance on unseen data.

Further improvements could involve hyperparameter tuning using techniques like GridSearchCV or RandomizedSearchCV to optimize the model's performance.
 Additionally, exploring other algorithms and feature engineering techniques might lead to better result.


