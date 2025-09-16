# 🌾 Pandas Agriculture Project – Maji Ndogo Farm Survey

This project is part of the **ALX Data Science course assignments**.  
The task focuses on exploring, cleaning, and analyzing agricultural survey data from **Maji Ndogo farms** using **Pandas**.  

---

## 📌 Project Overview
The dataset represents farm survey data across different regions, with details about:
- Geographic features (location, elevation, slope, etc.)  
- Weather features (rainfall, temperature, etc.)  
- Soil and crop features (soil type, fertility, crop type, yield, etc.)  
- Farm management features  

The goal of this project is to:
1. **Load and merge multiple tables** from an SQLite database into one Pandas DataFrame.  
2. **Clean the dataset**:
   - Fix swapped or mislabeled columns.  
   - Correct spelling errors and inconsistencies in crop types.  
   - Remove extra spaces in categorical values.  
   - Convert negative `Elevation` values to positive.  
3. **Explore and analyze** crop distribution and performance using Pandas functions.  

---

## 🛠️ Key Steps
- Connected to SQLite database using **SQLAlchemy**.  
- Combined the tables into one DataFrame (`MD_agric_df`) using `Field_ID` as the join key.  
- Cleaned the dataset:
  - Fixed inconsistent crop names (e.g., `wheat ` → `wheat`, `cassaval` → `cassava`).  
  - Reordered and swapped incorrect columns (`Crop_type` and `Annual_yield`).  
  - Converted negative elevation values to positive.  
- Created functions to:
  - Explore crop-specific rainfall and elevation averages.  
  - Identify the top-performing crop by standard yield.  
  - Filter conditions to find what makes a crop successful.  

---

## 📊 Insights
- Identified the **most successful crop** in Maji Ndogo by filtering fields with above-average `Standard_yield`.  
- Analyzed conditions under which this crop performs best (temperature range, pollution level, etc.).  
- Practiced grouping, filtering, and sorting operations in Pandas.  

---

## 🚀 Skills Practiced
- Pandas: data cleaning, filtering, grouping, aggregation  
- SQL with Python (SQLAlchemy)  
- Exploratory Data Analysis (EDA)  
- Writing reusable functions for analysis  
 

---

## ✅ Status
This is **Assignment 01** in the ALX Data Science course series.  
Future assignments will build on different aspects of Python for data science.  


