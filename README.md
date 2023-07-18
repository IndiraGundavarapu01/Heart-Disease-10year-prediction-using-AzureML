# Heart-Disease-Indicator-using-AzureML
## SUMMARY
The project uses Azure ML Studio Designer to build a classification model to predict the likelihood of a patient developing Chronic Heart Disease (CHD) in the coming ten years. It follows data preparation, modeling, and assessment techniques to produce the best model. The process follows Exploratory Data Analysis, Model Development and Training, and Model Deployment.

## DATA DESCRIPTION
The data is obtained from the UCI Machine Learning Repository. The data has 18 attributes such as Age, Gender, Education, Income, Cigarettesperday, BP Meds, CurrentSmoker, Prevalent Stroke, Prevalent Hypertension, Total Cholestrol, Diabetes, Systolic BP, Diastolic BP, BMI, Heart Rate, Glucose, a1c, 10yearCHD (response variable)
## METHODOLOGY
1. **Exploratory Data Analysis**: In Tableau, visual representations of Measures and Category variables are generated through Univariate Analysis for each variable and Bivariate Analysis for each variable with the response variable to observe the patterns in the data.
2. **Data Cleansing**: Data is cleaned by methods such as filling the null values by mode, mean, and other columns, clipping values, normalizing and dropping the columns that show high correlation.
3. **Feature Engineering**: Different transformations (sqrt, ln, log10) are applied based on the varied intensity of skewness for each variable.
4. **Model exploration**: Various models, such as Logistic Regression, Boosted Decision Trees, etc., are explored, out of which Two-class boosted decision tree seemed to perform better than others.
pipeline ID - 8f837437-9052-4591-a55f-23fd21b3cb45
5. **Results Interpretation**: The model is evaluated on AUC and F1 Score, and the inference pipeline is generated to make predictions to the new data entered manually. The inference pipeline is deployed as an endpoint with an API to interact with the deployed model for real-time predictions.
inference pipeline ID - 27cbe4f9-215e-46d3-8e36-9c170b7d355e
