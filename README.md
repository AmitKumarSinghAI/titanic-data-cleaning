# 🚢 Titanic Dataset — Data Cleaning & Preprocessing

## 🎯 Project Objective
To clean and preprocess the **Titanic dataset** for building accurate and efficient Machine Learning models.

---

## 📂 Dataset Information
- **Source:** [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
- **File Used:** `titanic.csv`

---

## 🧰 Technologies & Libraries
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 🧭 Workflow Overview

### 1️⃣ Data Loading & Initial Exploration
- Imported the dataset using Pandas.  
- Examined dataset structure using:
  - `df.info()`
  - `df.describe()`
  - `df.head()`
- Understood data types, missing values, and basic statistics.

---

### 2️⃣ Handling Missing Values
- Imputed missing values using appropriate methods:
  - `Age` → Filled with **mean**  
  - `Embarked` → Filled with **mode**  
- Dropped `Cabin` column due to excessive missing data.

---

### 3️⃣ Encoding Categorical Variables
- Converted categorical features into numerical format using:
  - **Label Encoding** for `Sex`
  - **One-Hot Encoding** for `Embarked` and `Pclass`

---

### 4️⃣ Feature Scaling
- Normalized continuous variables (`Age`, `Fare`) using **MinMaxScaler** to bring all features into a similar range.

---

### 5️⃣ Outlier Detection & Treatment
- Detected outliers using **boxplots** and **IQR (Interquartile Range)** method.  
- Removed extreme outliers to improve model performance.

---

## 📊 Visual Explorations
- 🔥 **Correlation Heatmap** — to study relationships between features  
- 📦 **Boxplots** — for outlier detection  
- 📈 **Countplots** — to visualize survival distribution across different variables

---

## ✅ Final Outcome
- Cleaned, encoded, and scaled dataset ready for model training.  
- Applied key preprocessing techniques:
  - Handling missing data  
  - Encoding categorical variables  
  - Normalization  
  - Outlier removal  
- Built a strong foundation for future Machine Learning modeling.

---


## ▶️ How to Run the Project

1. **Open the notebook:**
   - **File:** `Data Cleaning & Preprocessing.ipynb`  
   - **Environment:** Jupyter Notebook / VS Code  

2. **Run all cells sequentially** to execute each preprocessing step.

---

## 🌐 View on NBViewer

> 💡 **Note:** Some plots or HTML tables may not display correctly on GitHub.  
> For a better viewing experience, open the notebook via NBViewer:

🔗 [**Open Notebook on NBViewer**](https://nbviewer.org/github/Amit905460/titanic-data-cleaning/blob/main/Data%20Cleaning%20%26%20Preprocessing.ipynb)

---

## 🧩 Trusting the Notebook (If Prompted)

If Jupyter shows a message like:  
> “In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook...”

Follow these steps:

1. Go to **File → Trust Notebook**  
2. Or click the blue **“Not Trusted”** bar  
3. Then restart and run all cells: **Kernel → Restart & Run All**

---

## 🏁 Summary

This project demonstrates:

- ✅ Practical **data preprocessing workflow**  
- 🧹 Handling **real-world data issues**  
- 🤖 Preparing a dataset for **machine learning** efficiently  

---

👨‍💻 **Developed by:** [Amit Kumar Singh Kurmi](https://github.com/Amit905460)  
📅 **Project Type:** Data Preprocessing / Machine Learning  
