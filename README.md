# 📊 Experiment 15: Data Normalization and Encoding using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-orange?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Ops-blue?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Encoding-yellow?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-green?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🔰 Introduction

Data preprocessing is a crucial step in data analysis and machine learning. This experiment focuses on two major preprocessing techniques:

- **Data Normalization** (scaling numerical data)  
- **Encoding** (converting categorical data into numerical form)  

These techniques ensure that datasets are **consistent, comparable, and suitable for analysis and modeling**. :contentReference[oaicite:0]{index=0}

---

## 🎯 Objectives

- Apply different normalization techniques  
- Convert categorical data into numerical format  
- Prepare datasets for machine learning algorithms  
- Improve data consistency and interpretability  

---

## 📚 Theory

### 🔹 Data Normalization
- Process of scaling numerical values to a standard range  
- Helps improve model performance and accuracy  

---

### 🔹 Types of Normalization

#### ✅ Min-Max Normalization
- Scales values between 0 and 1  
- **Formula:**
  ```
  (X - Xmin) / (Xmax - Xmin)
  ```
- **Functions Used:**
  - `df.min()`
  - `df.max()`
  - Column operations: `df['col'] = (...)`

---

#### ✅ Z-Score Normalization
- Centers data around mean (0)  
- **Formula:**
  ```
  (X - μ) / σ
  ```
- **Functions Used:**
  - `df.mean()`
  - `df.std()`

---

#### ✅ Decimal Scaling
- Scales values by dividing by powers of 10  
- **Functions Used:**
  - Direct arithmetic operations (`/ 1000`, `/ 100000`)

---

### 🔹 Encoding Techniques

#### ✅ Label Encoding
- Converts categories into numeric labels  
- **Functions Used:**
  - `LabelEncoder()`
  - `fit_transform()`

---

#### ✅ One-Hot Encoding
- Converts categories into multiple binary columns  
- **Functions Used:**
  - `pd.get_dummies()`

---

#### ✅ Dummy Encoding
- Similar to one-hot but avoids redundancy  
- **Functions Used:**
  - `pd.get_dummies(drop_first=True)`

---

### 🔹 Additional Important Functions

- `pd.DataFrame()` → Create dataset  
- `pd.read_csv()` → Load dataset  
- `print()` → Display output  
- `df[['col1','col2']]` → Column selection  
- `df.columns` → View column names  

---

## 📊 Dataset Description

### 1️⃣ Product Dataset
- Product Name  
- Price  
- Units Sold  
- Discount  

### 2️⃣ E-Commerce Dataset
- Order ID  
- Gender  
- Payment Method  
- Product Category  
- City  
- Order Value  

### 3️⃣ Amazon Dataset
- Product Name  
- Price  
- Rating  
- Reviews  
- Units Sold  

### 4️⃣ Student Dataset
- Gender  
- Department  
- CGPA  
- Attendance  
- Placement Status  
- Salary  

---

## 🔧 Key Operations Performed

### 🟢 Normalization Techniques
- ✔️ Min-Max normalization  
- ✔️ Z-score normalization  
- ✔️ Decimal scaling  

---

### 🔵 Encoding Techniques
- ✔️ Label encoding  
- ✔️ One-hot encoding  
- ✔️ Dummy encoding  

---

### 🟣 Data Processing
- ✔️ Handling multiple datasets  
- ✔️ Transforming structured data  
- ✔️ Preparing machine-learning-ready data  

---

## 🚀 Workflow

1. Data Creation / Loading  
2. Data Inspection  
3. Applying Normalization  
4. Encoding Categorical Data  
5. Data Transformation  
6. Final Dataset Preparation  

---

## 📈 Key Highlights

- Multiple normalization techniques applied  
- Conversion of categorical data into numerical format  
- Real-world datasets used for implementation  
- Strong foundation for machine learning preprocessing  

---

## ⚠️ Observations

- Different normalization techniques yield different scales  
- Encoding is essential for machine learning models  
- Proper method selection depends on data type and use-case  

---

## ✅ Conclusion

This experiment demonstrates how **data normalization and encoding transform raw data into machine-ready format**.

Key outcomes:
- 📊 Improved comparability of numerical data  
- 🔢 Effective transformation of categorical variables  
- 📌 Better understanding of preprocessing techniques  
- 🚀 Readiness for machine learning applications  

---

## 👨‍💻 Author

**Lakshya Sonawane**
