**Name**: Heer Chauhan <br>
**Company**: CODTECH IT SOLULTIONS <br>
**ID**: CS24NY354846 <br>
**DOMAIN**: DATA SCIENCE <br>
**DURATION**: DECEMBER TO JANUARY 2025 <br>

**Objective**
Build a machine learning model to predict whether a passenger on the Titanic survived, based on features like age, gender, ticket class, fare, and embarkation port.<br> This is a supervised classification problem, with survival (0 = Did not survive, 1 = Survived) as the target variable.

**Dataset Overview**
The Titanic dataset contains the following columns (features): <br>
Survived: Target variable (0 = No, 1 = Yes).<br>
Pclass: Passenger class (1st, 2nd, or 3rd class).<br>
Sex: Gender (Male/Female).<br>
Age: Age of the passenger.<br>
SibSp: Number of siblings/spouses aboard.<br>
Parch: Number of parents/children aboard.<br>
Fare: Ticket fare.<br>
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

**Technologies Used in Titanic Survival Prediction Project**

1. **Programming Language: Python**
   - Popular and beginner-friendly.
   - Key Libraries: **Pandas**, **NumPy**, **Matplotlib/Seaborn**, **Scikit-learn**.

2. **Data Preprocessing**
   - **Handling Missing Values**: Impute missing data (mean for numerical, mode for categorical).
   - **Feature Encoding**: Convert `Sex` and `Embarked` to numerical using Label Encoding or One-Hot Encoding.
   - **Data Scaling**: Normalize numeric features if needed using **StandardScaler** or **MinMaxScaler**.

3. **Machine Learning Algorithms**
   - **Primary Model**: Random Forest Classifier.
   - **Other Models**: Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Gradient Boosting.

4. **Data Source**
   - **Kaggle**: Titanic - Machine Learning from Disaster.
   - **Seaborn Library**: Contains a built-in Titanic dataset for quick use. 


**Results** <br>
Accuracy: A well-trained model should yield around 75-85% accuracy, depending on preprocessing and hyperparameter tuning. <br>
Insights: Use feature importance to understand which variables (e.g., gender, class) most influence survival.
