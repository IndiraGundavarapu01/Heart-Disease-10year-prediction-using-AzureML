### Project Title
**Predicting Coronary Heart Disease Using Machine Learning**

### Executive Summary

**Objective:** The main goal of this project is to develop a machine learning model to predict the likelihood of a patient developing coronary heart disease (CHD) within 10 years based on various health and demographic factors.

**Context:** The project utilizes Azure Machine Learning for building and deploying the pipeline. The analysis is performed using Python, and the exploratory data analysis (EDA) is conducted using Tableau. Data preprocessing includes filling missing values and feature selection.

### Business Problem

**Problem Identification:** The specific business challenge addressed in this project is the need to accurately predict the risk of coronary heart disease in patients to enable timely medical interventions.

**Business Impact:** Accurate prediction of CHD risk can lead to better patient outcomes by enabling early diagnosis and personalized treatment plans, thereby reducing the overall healthcare costs and improving patient quality of life.

### Methodology

**Data Cleaning & Transformation:**
- **Data Cleaning:** Removed patient IDs, changed the `cigsPerDay` variable to double, and filled missing values using Python scripts.
- **Transformation:** Clipped outlier values for `totChol`, filled missing binary values with mode and non-binary values with mean, normalized data, and removed highly correlated variables like `a1c`.

**Analysis Techniques:**
- **Univariate Analysis:** Detailed examination of individual variables.
- **Bivariate Analysis:** Analysis of relationships between two variables.
- **Feature Engineering:** Skewness reduction using mathematical transformations such as square root, logarithmic, and log10 transformations.
- **Model Evaluation:** The model pipeline includes data preprocessing, training, and evaluation phases using various machine learning algorithms.

### Skills

**Tools, Languages, & Software:**
- **Languages:** Python
- **Tools & Platforms:** Azure Machine Learning, Tableau
- **Libraries:** Scikit-learn, Pandas, NumPy

### Results & Business Recommendation

**Business Impact:** The findings from the predictive model can guide healthcare providers in making data-driven decisions regarding patient care. The model's metrics indicate its effectiveness in predicting CHD, providing a basis for proactive medical interventions.

**Insights:**
- The model identified key risk factors for CHD, including age, systolic blood pressure, and cholesterol levels.
- Visualizations from the EDA phase highlighted significant correlations between certain variables and the likelihood of developing CHD.

### Next Steps

**Future Work:**
- **Model Improvement:** Further refine the model by incorporating additional health metrics and demographic data.
- **Deployment:** Implement the model in a clinical setting to assist healthcare professionals in real-time decision-making.
- **Monitoring & Maintenance:** Continuously monitor the model's performance and update it with new data to maintain its accuracy and relevance.
