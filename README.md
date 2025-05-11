# CODSOFT_TASK_01
# Titanic Survival Prediction

This project uses machine learning to predict the survival of passengers aboard the Titanic. The dataset contains information about passengers, including their age, gender, ticket class, and whether they survived or not. The goal is to build a predictive model that can accurately predict survival.

## Project Overview

In this project, we perform the following steps:
1. *Data Preprocessing:* Clean the data by handling missing values, converting categorical variables to numeric, and dropping unnecessary columns.
2. *Model Building:* Use a *Random Forest Classifier* to train a model using the cleaned data.
3. *Model Evaluation:* Evaluate the model's performance using accuracy and confusion matrix.

## Dataset

The dataset used in this project is the *Titanic dataset*, which is publicly available from sources like Kaggle. The data includes the following columns:
- *PassengerId*: ID of the passenger
- *Pclass*: Passenger class (1st, 2nd, or 3rd)
- *Name*: Name of the passenger
- *Sex*: Gender of the passenger
- *Age*: Age of the passenger
- *SibSp*: Number of siblings/spouses aboard
- *Parch*: Number of parents/children aboard
- *Ticket*: Ticket number
- *Fare*: Fare the passenger paid
- *Cabin*: Cabin number
- *Embarked*: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
- *Survived*: Whether the passenger survived (0 = No, 1 = Yes)

## Steps to Run the Code

1. *Clone this repository* to your local machine.
2. *Install necessary libraries* by running:
   ```bash
   pip install pandas numpy scikit-learn

3. Upload the Titanic dataset (train.csv) to your working directory or adjust the file path in the notebook.


4. Run the code in the notebook to train the model and evaluate its accuracy.



Model

Random Forest Classifier is used for prediction.

The model is trained on the preprocessed dataset, and the prediction accuracy is evaluated.


Results

The model's accuracy and confusion matrix will be printed after running the code, which helps evaluate the performance.

This is the content for the *README.md* file. Just copy and paste this into your GitHub repository’s README.md file.
