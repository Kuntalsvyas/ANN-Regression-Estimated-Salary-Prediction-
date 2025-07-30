# 💼 Estimated Salary Prediction using ANN (Regression)

This project demonstrates how to predict a person's **estimated salary** using an **Artificial Neural Network (ANN)** regression model. The model learns from user data like age, experience, and education to make continuous value predictions.

---

## 📊 Features

- 🔢 Performs regression using a deep neural network (ANN)
- 📚 Trains on structured user data (e.g., age, education level, years of experience)
- 🔍 Includes preprocessing: feature scaling and encoding
- 📈 Visualizes training loss and evaluation metrics
- 💾 Saves trained model as `salary_ann_model.h5`

---

## 🧰 Tech Stack

- **Python 3.10+**
- **TensorFlow / Keras**
- **Pandas / NumPy**
- **Matplotlib / Seaborn**
- **Scikit-learn**

---

## 🎯 Problem Statement

> Predict the **estimated salary** of a user using historical data and regression modeling techniques. The model is trained to fit a continuous output using an ANN.

---

## 🚀 Installation

**1. Clone the repository**
- git clone https://github.com/Kuntalsvyas/ANN-Regression-Estimated-Salary-Prediction-.git
- cd ANN-Regression-Estimated-Salary-Prediction-

**2. Create a virtual environment**
- python -m venv venv
- source venv/bin/activate  # For Windows: venv\Scripts\activate

**3. Install dependencies**
- pip install -r requirements.txt

**4. Run the script**
- python ann_salary_prediction.py

---

# 📈 Model Summary
- Input Layer (e.g., Age, Experience, Education)
- Multiple Dense Layers (ReLU)
- Output Layer with linear activation for regression

---

# 📌 Future Enhancements
 - Hyperparameter tuning for better accuracy
 - Add deployment via Flask/Streamlit
 - Use larger datasets with more demographic features
 - Compare with linear regression and XGBoost

---

# 🙌 Author
Developed by Kuntal Vyas
If you found this helpful, ⭐ the repo to support
