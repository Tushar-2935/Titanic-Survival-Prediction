# Titanic Survival Prediction using Machine Learning
This project builds and evaluates a classification model to predict passenger survival from the Titanic dataset. It includes data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation using a Random Forest classifier.
The Titanic dataset is a classic from Kaggle, containing data about passengers such as age, gender, class, and more

#Dataset Overview
The dataset used is the classic Titanic dataset from Kaggle and includes the following columns:

#Feature	Description
Pclass -Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex - Gender
Age	- Age of the passenger
SibSp	- Number of siblings/spouses aboard
Parch	- Number of parents/children aboard
Fare - Fare paid
Cabin	- Cabin number (dropped due to many missing values)
Embarked	- Port of embarkation (also dropped due to missing data)
Survived	- Target variable (0 = No, 1 = Yes)

#Exploratory Data Analysis (EDA)
Visualizations show more males than females, yet females had higher survival rates.
Passengers in 1st class had the highest chance of survival.
People with no family onboard had a higher survival rate.
Key insights:
% of women who survived: 0.742
% of men who survived: 0.188

#Model Building
Model Used: RandomForestClassifier from sklearn
Train-Test Split: 80% training, 20% testing
Evaluation Metrics:

Accuracy: ~79%

Confusion Matrix:
TN = 90, FP = 12
FN = 22, TP = 52
Precision = TP / (TP + FP)
Recall = TP / (TP + FN)
Accuracy = (TP + TN) / Total

#Author
Tushar
Undergraduate in Economics | Aspiring Data Scientist

