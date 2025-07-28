# 🚗 Car Modeling Prediction

An AI-powered model that predicts the selling price of a car based on features like brand, mileage, fuel type, engine capacity, and more.  
Built using machine learning with love, logic, and vision. 💡❤️

---

## 📦 Project Highlights

- 📊 Exploratory Data Analysis (EDA) for feature insights
- 🧠 Linear Regression & other models to predict car prices
- 🧼 Data preprocessing and label encoding
- 📈 Performance evaluation with R² score and visual plots

---

## 📁 Folder Structure

├── car_modeling_prediction.ipynb # Jupyter Notebook with full ML pipeline
├── dataset.csv # Dataset used for training & evaluation
├── model.pkl # Trained regression model
└── README.md # Project description and usage guide
---

## 🧠 Model Overview

The model uses:
- Label encoding for categorical features
- Feature selection based on correlation
- Linear Regression for prediction
- R² score for accuracy check
- Visualization for insights

You can retrain the model or use the `model.pkl` to predict new data.

---

## 🛠️ How to Use

1. Clone this repo:
https://github.com/KarthikSai2246/car-modeling-prediction.git
2. Open `car_modeling_prediction.ipynb` in Jupyter Notebook.
3. Follow the notebook steps to preprocess, train, and evaluate.
4. Use the `model.pkl` for predictions with new data.

---

## 🧪 Sample Prediction

You can load and test the model using:

```python
import pickle

model = pickle.load(open("model.pkl", "rb"))
prediction = model.predict([[car_features]])
print("Predicted Price:", prediction)

