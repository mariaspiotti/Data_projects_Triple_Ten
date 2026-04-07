# Customer Churn Prediction

## 📌 Project Description
The goal of this project is to predict customer churn for a telecommunications company. Customer churn occurs when a customer stops using a service, and identifying at-risk customers is critical for improving retention and reducing revenue loss.

This project focuses on building and evaluating machine learning models to accurately predict which customers are likely to churn.

---

## 📊 Data Description
The dataset includes information about customers such as:

- Personal information (gender, age, etc.)
- Contract details (type of contract, duration)
- Services used (internet, phone, additional features)
- Payment methods and billing information

The target variable is whether the customer churned or not.

---

## ⚙️ Methods and Approach

### Data Preprocessing
- Merged multiple datasets into a single dataframe
- Converted data types and handled missing values
- Created the target variable (churn)
- Encoded categorical variables

### Exploratory Data Analysis (EDA)
- Analyzed class balance
- Investigated relationships between features and churn
- Identified key patterns in customer behavior

### Model Development
- Trained Logistic Regression model
- Trained Random Forest model
- Tuned hyperparameters for improved performance

### Model Evaluation
- Used ROC-AUC as the primary metric
- Compared models using a validation set
- Evaluated final model on the test set

---

## 📈 Results

- The Random Forest model achieved the best performance
- ROC-AUC was used as the main evaluation metric
- The model demonstrated strong ability to distinguish between churned and active customers

---

## 💡 Conclusion

The project shows that machine learning can effectively predict customer churn and help businesses identify at-risk customers.

These insights can be used to:
- Improve customer retention strategies
- Target specific customer segments
- Reduce overall churn rate

---

## 🛠️ Tools and Technologies
- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib / Seaborn

---

## 📁 Files
- `Customer Churn Prediction.ipynb`
