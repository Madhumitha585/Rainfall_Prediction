# Rainfall_Prediction
A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset This project is tested over lot of ml models like logistic regression,decision tree clasifier,random forest. Out of these models catboost performed very well giving an AUC score around and ROC score of 89 far better than others. Here due to my system compatibility is very low. So I havent done hyperparameter tuning. But it is highly recommended to do it if possible.

Tech Stack
Back-End: Gradio
IDE: Google Colab

Data Collection:
Rainfall Prediction in Australia dataset from Kaggle

Data Preprocessing:
Missing Values Handled by Random Sample imputation to maintain the variance
Categorical Values like location, wind direction are handled by using Target guided encoding
Outliers are handled using IQR and boxplot
Feature Selection and was done it can be seen in RainPrediction.ipynb

Model Creation:
Different types of models were tried like random forest, logistic regression, decision tree.
Out of these random forest was top 
