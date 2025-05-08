
## 💳 Credit Card Fraud Detection Using Random Forest

This project implements a desktop application using **Tkinter** and **Random Forest Classifier** to detect fraudulent credit card transactions. It provides an intuitive GUI to upload datasets, train a model, predict fraud, and visualize results.

---

### 📌 Features

* Upload a CSV dataset of credit card transactions.
* Automatically preprocesses and splits the dataset into training and testing sets.
* Trains a Random Forest Classifier to detect fraud.
* Predicts fraudulent or clean transactions from a separate test file.
* Visualizes results with a bar graph showing fraud vs. normal transactions.

---

### 🖼 GUI Preview

The application is built using Python’s Tkinter library for a desktop-based interface. Key buttons include:

* **Upload Credit Card Dataset**
* **Generate Train & Test Model**
* **Run Random Forest Algorithm**
* **Detect Fraud From Test Data**
* **Clean & Fraud Transaction Detection Graph**
* **Exit**

---

### 🛠 Tech Stack

* **Language:** Python
* **Libraries:**

  * `sklearn`
  * `numpy`
  * `pandas`
  * `matplotlib`
  * `tkinter`

---

### 📂 Dataset

The model uses the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), where:

* Features `V1` to `V28` are PCA components.
* `Amount` and `Time` are original features.
* `Class` = 1 indicates a fraud transaction.

---

### ⚙️ How to Run

1. Clone this repository:


2. Install required libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```

3. Run the application:

   ```bash
   python fraud_detection_gui.py
   ```

4. Use the buttons to:

   * Upload dataset (CSV)
   * Train the model
   * Predict using test file
   * View classification graph

---

### 📊 Output

* Accuracy of the model on test data
* Printed predictions of 50 transactions
* Graph showing:

  * Total transactions tested
  * Number of fraud transactions
  * Number of clean transactions

---

### 📄 License

This project is licensed under the MIT License.

---

### 🙋‍♂️ Author

**Syed Saaduddin Azhaan**
[LinkedIn](https://www.linkedin.com/in/syed-saaduddin-b7682726b/) | [GitHub](https://github.com/Saaduddin47)

