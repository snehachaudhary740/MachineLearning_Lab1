# MachineLearning_Lab1

# 🚖 Taxi Fare Prediction - City of Chicago

This project aims to predict the **total taxi fare** in Chicago using features like trip duration, distance, tip amount, payment type, and taxi company. The dataset is taken from the **City of Chicago Taxi Trips** dataset.

---

## 📂 Dataset

The dataset contains records of individual taxi rides in Chicago.  
Used columns:
- `Trip Miles`
- `Trip Seconds`
- `Tips`
- `Payment Type`
- `Company`
- `Trip Total` (Target)

---

## 🧠 Objective

Build a **Linear Regression model** to predict the **Trip Total (fare)** for a given trip using selected features.

---

## 🛠 Tech Stack

- Python 🐍
- pandas, NumPy
- scikit-learn
- matplotlib

---

## 🔍 Steps Followed

### ✅ Step 1: Load the dataset
Used `pandas` to load and inspect the dataset.

### ✅ Step 2: Select Features
Selected only the most relevant columns and removed rows with missing values.

### ✅ Step 3: Preprocessing
- Used `OneHotEncoder` to encode categorical columns (`Payment Type`, `Company`)
- Built a `Pipeline` to apply preprocessing + Linear Regression

### ✅ Step 4: Model Training & Evaluation
- Split the data into training and test sets (80/20)
- Trained a Linear Regression model
- Evaluated using:
  - **Mean Absolute Error (MAE)**
  - **R² Score**

### ✅ Step 5: Visualization
Plotted **Actual vs Predicted Fare** to visualize performance.

---

## 📊 Sample Results

