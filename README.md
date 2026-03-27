# Diabetes Prediction System

## Overview

This project is a **Machine Learning Classification System** that predicts whether a person is diabetic or not based on medical features such as glucose level, BMI, age, and more.

The project includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Training multiple ML models
* Model evaluation and comparison
* Final prediction system

---

## Dataset

The dataset used is the **Pima Indians Diabetes Dataset**, which contains medical diagnostic measurements.

### Features:

* Pregnancies
* Glucose
* BMI
* Age
* (Other features were tested and optimized)

### Target:

* `0` → Not Diabetic
* `1` → Diabetic

---

## Project Pipeline

### 1. Data Preprocessing

* Removed unnecessary features based on correlation
* Handled missing/invalid values (e.g., replaced zeros with mean)
* Removed outliers using IQR method
* Standardized features using `StandardScaler`

---

### 2. Visualization

* Histograms for feature distributions
* Correlation heatmap
* Boxplots for outlier detection

---

### 3. Models Used

The following machine learning models were implemented and compared:

* Support Vector Machine (SVM)
* Logistic Regression  (Best Model)
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Gradient Boosting

---

### 4. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Train vs Test comparison (to detect overfitting)

---

## Best Model

**Logistic Regression** achieved the best performance:

* Test Accuracy: **~80%**
* Stable performance (no overfitting)

---

## How to Run

```bash
# Clone the repository
git clone https://github.com/engasmaaibrahim/Diabetes-Prediction


# Install dependencies
pip install -r requirements.txt

```

---


## Author

**Asmaa Ibrahim**
AI & Machine Learning Engineer

