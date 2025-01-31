# 🚢 **Titanic Survival Prediction** 🌊
### Predicting survival on the Titanic using machine learning 🚀

**Objective**: The goal of this project is to predict whether a passenger survived the Titanic disaster based on various features such as age, gender, socio-economic class, and more.

### 🧳 **Introduction**
This project is part of the Kaggle competition titled **"Titanic: Machine Learning from Disaster"**. The task is to predict whether a passenger survived or not based on multiple features. This is a classic example of binary classification, where we aim to classify each passenger as either a survivor (1) or a non-survivor (0).

### 📊 **Dataset**
The dataset consists of two main CSV files:

1. **train.csv**: Contains information about 891 passengers, including their survival status (our target variable). This will be used for training the model.
2. **test.csv**: Similar to **train.csv**, but without the survival status. The task is to predict the survival status for these 418 passengers.

Both datasets contain features like:
- **Name** 👤  
- **Age** 🧑‍🦱  
- **Gender** 🚻  
- **Socio-economic class** 💼  
- **Number of siblings/spouses aboard** 👨‍👩‍👧‍👦  
- **Number of parents/children aboard** 👶  
- **Ticket number** 🎫  
- **Fare** 💰  
- **Cabin number** 🛏️  
- **Port of embarkation** 🌍  

### 🧠 **Approach**
To tackle this challenge, I implemented a **Random Forest classifier** using the **scikit-learn** library in Python. Here’s how I approached the problem:

1. **Data Preprocessing**:  
   - **Handling missing values** 💧: I imputed missing data (e.g., for Age, Cabin, etc.) using suitable strategies.  
   - **Encoding categorical features** 📝: Features like **Gender** and **Embarked** were encoded into numerical values so the model could understand them.

2. **Model Training**:  
   I trained the model using the **train.csv** dataset, which contains labeled passenger data. Random Forests were chosen due to their robustness and ability to handle both numerical and categorical data effectively.

3. **Prediction**:  
   Once the model was trained, I used it to predict the survival status of passengers in **test.csv**.

4. **Submission**:  
   The predicted survival outcomes were submitted to **Kaggle**, where the model's performance is evaluated.

### 🎯 **Results & Conclusion**
After training and testing, the model achieved a solid performance (based on the Kaggle leaderboard). I will continue to refine the model by experimenting with other classifiers and tuning hyperparameters for even better predictions.
