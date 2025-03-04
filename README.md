# heart-attack-sa
Heart Disease Prediction - Jupyter Notebook
Overview
This Jupyter Notebook is designed to analyze and predict the presence of heart disease using machine learning techniques. The dataset used contains various medical attributes that serve as predictors for heart disease. The notebook walks through data exploration, preprocessing, model training, and evaluation, providing insights into the factors contributing to heart disease.

Dataset
The dataset used in this project contains medical attributes such as:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol Level
Fasting Blood Sugar
Resting ECG Results
Maximum Heart Rate Achieved
Exercise-Induced Angina
ST Depression Induced by Exercise
Slope of the Peak Exercise ST Segment
Number of Major Vessels Colored by Fluoroscopy
Thalassemia
Target (Presence of Heart Disease: 0 = No, 1 = Yes)

The Libraries used were :
1. Pandas
2. Nummpy
3. matplotlib
4. seaborn
5. scikit-learn

Data loaded using pandas to read the csv file.
Missing data was handeled using:
-Handling Missing Values:
  Missing values (if any) are handled using df.dropna() or df.fillna().
-Encoding Categorical Variables:
  Categorical variables such as "Sex" and "Chest Pain Type" are converted into numerical format   using pd.get_dummies() or LabelEncoder.
-Feature Scaling:
  Standardization of numerical values using StandardScaler() ensures all features are on the       same scale, improving model performance.
The classification model used was RandomForestClassifier

Conclusion:
-The model effectively predicts the presence of heart disease based on medical attributes.
-Feature importance analysis reveals key contributing factors to heart disease risk.
-Future improvements could include hyperparameter tuning and trying other machine learning       models like Logistic Regression, SVM, or Neural Networks.
