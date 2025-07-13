# Titanic Survival Prediction using Machine Learning
This project builds and evaluates a classification model to predict passenger survival from the Titanic dataset. It includes data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation using a Random Forest classifier.
The Titanic dataset is a classic from Kaggle, containing data about passengers such as age, gender, class, and more

# Dataset Overview
The dataset used is the classic Titanic dataset from Kaggle and includes the following columns:

# Feature	Description
Pclass -Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)<br>
Sex - Gender<br>
Age	- Age of the passenger<br>
SibSp	- Number of siblings/spouses aboard<br>
Parch	- Number of parents/children aboard<br>
Fare - Fare paid<br>
Cabin	- Cabin number (dropped due to many missing values)<br>
Embarked	- Port of embarkation (also dropped due to missing data)<br>
Survived	- Target variable (0 = No, 1 = Yes)<br>

# Exploratory Data Analysis (EDA)
Visualizations show more males than females, yet females had higher survival rates.
Passengers in 1st class had the highest chance of survival.
People with no family onboard had a higher survival rate.
Key insights:<br>
% of women who survived: 0.742<br>
% of men who survived: 0.188<br>

# Model Building
Model Used: RandomForestClassifier from sklearn<br>
Train-Test Split: 80% training, 20% testing<br>
Evaluation Metrics:<br>

Accuracy: 79%<br>

Confusion Matrix:<br>
TN = 90, FP = 12<br>
FN = 22, TP = 52<br>
Precision = TP / (TP + FP)<br>
Recall = TP / (TP + FN)<br>
Accuracy = (TP + TN) / Total<br>

# Author
Tushar<br>
Undergraduate in Economics | Aspiring Data Scientist

