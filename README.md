# Machine Learning Internship – Data Preprocessing (Iris Dataset)

## 📌 Project Description
This project focuses on preprocessing a raw dataset to make it suitable for
machine learning. The Iris dataset was used to demonstrate common preprocessing
techniques required before training ML models.

---

## 🗂 Dataset
- **Name:** Iris Dataset
- **Type:** Multiclass classification dataset
- **Features:** Sepal length, sepal width, petal length, petal width
- **Target:** Species of iris flower

---

## ⚙️ Preprocessing Steps

### 1. Data Loading
The dataset was loaded using the pandas library.

### 2. Data Exploration
Initial exploration was performed using:
- `.head()`
- `.info()`
- `.describe()`

This helped understand the structure, data types, and statistical properties
of the dataset.

### 3. Handling Missing Values
The dataset was checked for missing values using:
```python
data.isnull().sum()
