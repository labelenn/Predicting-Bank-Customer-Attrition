```markdown
# 🏦 Predicting Bank Customer Attrition

## 📌 Project Overview

This project focuses on exploring a dataset related to bank customer attrition, specifically customers leaving their credit card services. The primary goal is to analyze key factors contributing to churn and develop a predictive model that can identify customers at risk of leaving. By doing so, bank staff can take proactive measures to retain valuable customers and reduce attrition.

## 📊 Dataset Information

The dataset consists of **10,000** bank customers and includes **18 features** related to their demographics, credit card usage, and account activity.

- 🔗 **Dataset Source:** [Kaggle](https://www.kaggle.com/datasets/whenamancodes/credit-card-customers-prediction)
- 📈 **Churn Rate:** Only **16.07%** of customers have churned, making this an imbalanced classification problem.
- 📡 **Additional Resource:** [Analyttica Leaps](https://leaps.analyttica.com/home) - A platform explaining business problem-solving with datasets.

## 🗂 Data Dictionary

| Feature                        | Description                                                     |
| ------------------------------ | --------------------------------------------------------------- |
| **CLIENTNUM**                  | Unique identifier for the customer holding the account          |
| **Attrition\_Flag**            | 1 = Account closed, 0 = Active account                          |
| **Customer\_Age**              | Age of the customer in years                                    |
| **Gender**                     | M = Male, F = Female                                            |
| **Dependent\_count**           | Number of dependents                                            |
| **Education\_Level**           | Educational qualification (e.g., High School, College Graduate) |
| **Marital\_Status**            | Married, Single, Divorced, Unknown                              |
| **Income\_Category**           | Annual income category (< \$40K, \$40K-\$60K, etc.)             |
| **Card\_Category**             | Credit card type (Blue, Silver, Gold, Platinum)                 |
| **Months\_on\_book**           | Relationship duration with the bank (in months)                 |
| **Total\_Relationship\_count** | Total number of products held by the customer                   |
| **Months\_Inactive\_12\_mon**  | Months inactive in the last 12 months                           |
| **Contacts\_Count\_12\_mon**   | Number of contacts in the last 12 months                        |
| **Credit\_Limit**              | Credit limit on the card                                        |
| **Total\_Revolving\_Bal**      | Total revolving balance on the card                             |
| **Avg\_Open\_To\_Buy**         | Available credit line (average of last 12 months)               |
| **Total\_Amt\_Chng\_Q4\_Q1**   | Change in transaction amount (Q4 over Q1)                       |
| **Total\_Trans\_Amt**          | Total transaction amount in the last 12 months                  |
| **Total\_Trans\_Ct**           | Total transaction count in the last 12 months                   |
| **Total\_Ct\_Chng\_Q4\_Q1**    | Change in transaction count (Q4 over Q1)                        |
| **Avg\_Utilization\_Ratio**    | Average card utilization ratio                                  |

## 🏗 Project Goals

✔️ Perform exploratory data analysis (EDA) to understand patterns in customer churn. ✔️ Handle data imbalance using techniques such as oversampling/undersampling or weighted loss functions. ✔️ Train and evaluate different machine learning models to predict customer attrition. ✔️ Deploy the best-performing model for real-world use.

## 🛠 Tech Stack

- **Programming Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Machine Learning Models:**

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/labelenn/Predicting-Bank-Customer-Attrition.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the data preprocessing and model training script:
   ```bash
   python train_model.py
   ```
4. Evaluate model performance and analyze predictions.

## 📌 Future Improvements

🔹 Feature engineering to improve model accuracy.\
🔹 Hyperparameter tuning for better generalization.\
🔹 Deployment as a web application or API.

---

🔍 **Author:** Lance Belen\
📬 **Contact:** lancebelen.a@gmail.com(mailto\:lancebelen.a@gmail.com)\
```
