# Heart Disease Prediction - Exploratory Data Analysis (EDA)

## Project Overview
This project analyzes a heart disease dataset to identify patterns, risk factors, and clinical indicators associated with heart disease. The analysis includes data cleaning, exploratory analysis, statistical comparisons, and predictive modeling to derive actionable healthcare insights.

## Objective
The objective of this project is to:

- Understand the distribution of patient demographics and clinical measurements.
- Identify major risk factors associated with heart disease.
- Compare clinical characteristics between heart disease and non-heart disease patients.
- Build a predictive Logistic Regression model.
- Generate business recommendations for healthcare providers.

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Dataset Features

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate (thalach)
- Exercise-Induced Angina (exang)
- Oldpeak
- Slope
- Major Vessels (ca)
- Thalassemia (thal)
- Target (Heart Disease Presence)

## Project Workflow

### 1. Data Cleaning
- Checked missing values
- Removed invalid records
- Verified data types
- Created age group categories

### 2. Basic Analysis (10 Questions)
- Gender distribution
- Average age
- Chest pain distribution
- Blood pressure analysis
- Cholesterol analysis
- Heart disease prevalence
- ECG distribution
- Major vessel distribution
- etc.

### 3. Mid-Level Analysis (10 Questions)
- Age vs Cholesterol relationship
- Chest pain patterns across age groups
- Exercise-induced angina analysis
- Blood pressure by gender
- Fasting blood sugar vs heart disease
- Major vessel impact
- Oldpeak by chest pain type
- Thalassemia analysis
- Risk factor combinations
- Pairwise clinical comparisons

### 4. Advanced Analysis (5 Questions)
- Combined risk factor effects
- Correlation analysis
- Logistic Regression modeling
- ECG slope vs chest pain analysis
- Thalassemia and heart disease prevalence analysis

## Logistic Regression Results

### Model Accuracy

Accuracy: 81.97%

### Top Positive Predictors

| Feature | Coefficient |
|----------|-----------:|
| Chest Pain Type (cp) | 0.944 |
| Slope | 0.428 |
| Resting ECG | 0.369 |

### Top Negative Predictors

| Feature | Coefficient |
|----------|-----------:|
| Sex | -1.575 |
| Exercise-Induced Angina | -0.914 |
| Thalassemia | -0.820 |
| Major Vessels (ca) | -0.717 |

## Key Insights

### Heart Disease Indicators

- Chest pain type showed the strongest positive relationship with heart disease.
- Maximum heart rate was significantly higher among heart disease patients.
- Exercise-induced angina was strongly associated with heart disease.
- Patients with fewer major vessels tended to have higher heart disease prevalence.
- Thalassemia type showed a notable association with heart disease status.

### Clinical Observations

- Average cholesterol level was approximately 246.5 mg/dL.
- Most patients belonged to the 50–60 age group.
- Typical Angina was the most common chest pain category.
- Most patients had normal fasting blood sugar levels.

## Business Impact

### Early Risk Detection
The identified risk factors can help healthcare organizations detect high-risk patients earlier.

### Personalized Treatment Plans
Clinical measurements such as chest pain type, exercise-induced angina, and ECG results can be used to tailor treatment recommendations.

### Resource Optimization
Hospitals can prioritize screening and intervention efforts toward patients exhibiting high-risk profiles.

### Preventive Healthcare
Understanding common risk-factor combinations enables targeted awareness campaigns and preventive programs.

## Conclusion

The analysis identified several important factors associated with heart disease, including chest pain type, maximum heart rate, exercise-induced angina, thalassemia type, and major vessel count. The Logistic Regression model achieved an accuracy of approximately 82%, demonstrating that patient clinical measurements can effectively support heart disease prediction and risk assessment.

The findings can assist healthcare providers in improving diagnostic accuracy, patient monitoring, and preventive care strategies.
