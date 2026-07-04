# Capstone-Project
Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning models. It is a binary classification problem built using the famous Kaggle Titanic dataset.

 Objective
Analyze Titanic passenger data
Perform data preprocessing and feature engineering
Build ML models to predict survival
Compare model performance
Dataset Information

Source: Kaggle Titanic Dataset

Features:
PassengerId
Pclass (Ticket class)
Name
Sex
Age
SibSp (Siblings/Spouses aboard)
Parch (Parents/Children aboard)
Fare
Embarked
Target:
Survived (0 = No, 1 = Yes)
 Technologies Used
Python 
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
 Data Preprocessing
Handled missing values (Age, Embarked, Cabin)
Encoded categorical variables (Sex, Embarked)
Dropped unnecessary columns (Name, Ticket, Cabin)
Feature scaling applied where required
 Exploratory Data Analysis (EDA)
Survival rate by gender
Survival rate by passenger class
Age distribution analysis
Correlation heatmap
Data visualization using graphs
 Machine Learning Models Used
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
 Model Evaluation

Models were evaluated using:

Accuracy Score
Confusion Matrix
Precision, Recall, F1-score

 Best performing model: Random Forest Classifier

 Key Insights
Females had higher survival chances
Higher passenger class had better survival rate
Children were more likely to survive
Project Structure
capstone-project/
│
├── data/raw_data  and cleaned_titanic
├── notebooks/capstone_final
├── images/
|-- report/
|--presentation/
├── README.md

Future Improvements
Hyperparameter tuning
Advanced models (XGBoost, Neural Networks)
Deploy using Flask / Streamlit
Improve feature engineering
