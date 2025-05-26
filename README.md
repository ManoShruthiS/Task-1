# Task-1
Data Cleaning & Preprocessing

This project is part of the **AI & ML Internship Task 1**, focused on cleaning and preparing raw data for machine learning using Python libraries.

## Objective

Clean and preprocess the Titanic dataset to make it suitable for machine learning models.


## ✅ Steps Performed

### 1. Data Exploration
- Loaded the dataset using `pandas`
- Displayed shape, data types, and summary statistics

### 2. Missing Value Handling
- Filled missing values in `Age` using the **mean**
- Filled missing values in `Embarked` using the **mode**
- Dropped `Cabin` column due to high null percentage

### 3. Categorical Encoding
- Converted `Sex` to numeric using **Label Encoding**
- Encoded `Embarked` using **One-Hot Encoding**

### 4. Feature Scaling
- Applied **StandardScaler** to `Age` and `Fare` columns

### 5. Outlier Detection & Removal
- Visualized outliers using **boxplots**
- Removed outliers using **IQR method**


## 🧰 Tools Used

- Python 
- Pandas 
- NumPy 
- Seaborn 
- Matplotlib 
- Scikit-learn 

## 📁 Files Included

- `titanic.csv` — raw dataset
- `AIML T-1.ipynb` — Jupyter Notebook with full code
- `titanic_cleaned.csv` — cleaned version of the dataset

## 💡 How to Run

1. Clone this repo or download the files.
2. Open `Titanic_Data_Cleaning.ipynb` in Jupyter Notebook or VSCode.
3. Run the notebook step-by-step to see preprocessing in action.

## 🔗 Dataset Source

[Titanic Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
