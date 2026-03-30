# 🧠 Alpha Day 2: Data Surgeon

## 📌 Project Overview
This project focuses on **data cleaning and preprocessing**, a critical step in data science.  
The dataset was intentionally "broken" with missing values and outliers, and then cleaned using professional techniques.

---

## 🎯 Objectives
- Detect missing values in the dataset  
- Perform data imputation without damaging data integrity  
- Identify and handle outliers  
- Prepare clean data for analysis and machine learning  

---

## 📂 Dataset Issues
The dataset contained the following problems:
- ❌ Missing values in **Sales** and **Quantity**
- ❌ Incorrect/Extreme values (Outliers)
- ❌ Inconsistent data affecting analysis

---

## 🛠️ Data Cleaning Steps

### 1. Handling Missing Values
- Filled missing **Sales** using **median of Electronics category**
- Replaced missing **Quantity** for specific product (Chair) with correct value

### 2. Outlier Detection & Treatment
- Identified unrealistic values (e.g., Quantity > 100)
- Replaced outliers using **mean of Office category**

### 3. Data Validation
- Ensured no missing values remain using `.info()`  
- Verified cleaned dataset integrity  

---

## 📊 Visualization
An interactive bar chart was created using **Plotly** to analyze total sales by category after cleaning.

---

## 🧰 Technologies Used
- Python 🐍
- Pandas 📊
- Plotly 📈

---

## 📁 Files Included
- `broken_sales_data.csv` → Raw dataset  
- `AlphaDay2_DataSurgeon.py` → Data cleaning script  

---

## 💡 Key Learnings
- Data cleaning is **80% of real-world data science**
- Importance of handling missing values properly
- Outliers can distort analysis and must be treated carefully
- Clean data leads to reliable business insights  

---

## 🚀 Future Improvements
- Add automated data cleaning pipeline  
- Build dashboard for business insights  
- Apply machine learning models on cleaned data  

---

## 👩‍💻 Author
**Laiba Amjad**  
Aspiring Data Scientist 🚀
