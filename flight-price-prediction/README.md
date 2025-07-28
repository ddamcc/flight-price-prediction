# ✈️ Flight Price Prediction using Machine Learning

## 📌 Problem Statement  
The goal of this project is to **predict flight prices** based on several features such as airline, source, destination, duration, and more. This is a **regression problem**, where the model learns to estimate the flight fare based on historical data.

---

## 📊 About the Dataset  
The dataset consists of flight details and their corresponding fares. It is split into two files:

- **Training Data**:  
  - Rows: 10,682  
  - Columns: 11  
- **Testing Data**:  
  - Rows: 2,671  
  - Columns: 10 (excluding the target column)

These files contain features such as airline name, source, destination, date of journey, duration, total stops, etc., which influence the flight fare.

---

## 🤖 Model Used  
We use the **Random Forest Regressor**, a powerful ensemble learning method based on decision trees, well-suited for handling non-linear relationships and mixed data types.

- **Algorithm**: Random Forest  
- **Model Type**: Regression  
- **Library**: scikit-learn

---

## 🚀 Workflow  
1. Load and preprocess the data (handle missing values, encode categorical features, feature engineering).
2. Train the **Random Forest Regressor** on the training dataset.
3. Predict the flight price on unseen/test data.
4. Build a simple UI to allow users to enter flight details and view the predicted price.

---

## ✅ Output Examples  

### 🏠 Home Page  
![Home Page](https://user-images.githubusercontent.com/76621987/175784174-20c71ea5-e77a-4977-903a-83dba3783483.png)

---

### 💰 Predicted Flight Price  
![Predicted Price](https://user-images.githubusercontent.com/76621987/175784173-941cce21-df9c-4cae-b2da-d3511f7439dd.PNG)

---

## 🧰 Tech Stack  
- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Streamlit (for web UI)  
- Matplotlib / Seaborn (for EDA)
