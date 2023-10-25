# Emission_Prediction_and_Classification

This project addresses multiclass classification and regression task, aiming to predict vehicle emissions and classify CO2 rating based on various vehicle characteristics. 

This project leveraged Pandas and NumPy libraries for exploratory data analysis and data cleaning, along with visualizations using seaborn, matplotlib, and plotly.

Statistical techniques like ANOVA and Pearson's correlation were applied, and principal component analysis with Mutual Information was used for feature selection. 

## Data Exploration and Preprocessing:

Load the CO2 Emission dataset and perform initial data exploration.
Handle missing values, specifically in the 'CO2 Rating' and 'Smog Rating' columns.
Conduct data visualization and analysis to understand the relationships between variables.
Identify and remove outliers, focusing on true outliers.
Regression Task (Predicting CO2 Emissions):

## Use various regression models to predict CO2 emissions.
Models used: Multiple Linear Regression, Decision Tree Regressor, Support Vector Regressor, Random Forest Regressor, and GridSearchCV for hyperparameter tuning.
Evaluate model performance using metrics like R-squared, RMSE, MSE, and MAE.
Classification Task (Predicting CO2 Ratings):

## Perform classification for CO2 ratings.
Models used: Support Vector Classifier, Multinomial Naive Bayes, Random Forest Classifier, and XGBoost Classifier.
Use ROC analysis for multiclass classification, including micro-average and class-specific ROC curves.
Evaluate classification performance using metrics like accuracy, precision, recall, F1-score, and the ROC curve.

Evaluation metrics including accuracy, precision recall, F1 score, ROC curve, RMSE, MSE, R2 score were utilized for evaluating the model.

