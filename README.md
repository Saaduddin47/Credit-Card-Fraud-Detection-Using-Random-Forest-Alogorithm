# 💳 Credit Card Fraud Detection

This project is a machine learning-based system to detect fraudulent credit card transactions using the **Random Forest** classification algorithm. It is designed to analyze transaction data and accurately classify transactions as either legitimate or fraudulent.

## 🔍 Project Objective

To develop a reliable and accurate fraud detection system that:
- Detects fraudulent transactions in real-time or batch mode.
- Minimizes false positives while catching fraudulent behavior.
- Is interpretable and efficient for practical implementation.

## 📊 Dataset

The dataset used is the **Credit Card Fraud Detection dataset** available on [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains transactions made by European cardholders in September 2013 and includes:

- **Total records:** 284,807
- **Fraudulent transactions:** 492 (0.172%)
- **Features:** 30 (V1-V28 are PCA-transformed features, plus Time and Amount)

> **Note:** The dataset is highly imbalanced, which makes this a good use case for robust classifiers like Random Forest.

## 🧠 Machine Learning Model

### Algorithm: Random Forest Classifier

Random Forest is an ensemble method based on decision trees, providing high accuracy, robustness to overfitting, and feature importance.

### Steps Involved:
1. **Data Preprocessing**
   - Handling class imbalance using undersampling or SMOTE
   - Normalizing `Amount` and `Time` features
2. **Model Training**
   - Splitting dataset into train and test sets (e.g., 80:20)
   - Training the Random Forest classifier
3. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix

## 📈 Evaluation Metrics

The model's performance is evaluated using:

- **Accuracy**
- **Precision**
- **Recall**

These metrics help ensure the model not only identifies fraud correctly but also reduces false alarms.

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Project Structure

