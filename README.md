# 📱 Google Playstore Data Analysis

This project performs an in-depth analysis of the **Google Playstore dataset**, focusing on understanding app behavior across categories, ratings, installs, pricing models, and user engagement. The notebook includes complete data cleaning, transformation, and KPI-driven analysis to extract meaningful insights from real-world data.

---

## 🚀 Project Objectives
- Clean and preprocess raw Playstore data  
- Explore app categories, sizes, installs, reviews, and pricing  
- Analyze relationships between **ratings**, **popularity**, and **app type**  
- Generate actionable **KPIs** using analytical queries  
- Simulate real business problem-solving scenarios

---

## 📂 Workflow Overview

### **1️⃣ Data Import & Initial Exploration**
- Cloned datasets from GitHub  
- Loaded into Pandas and inspected using `head()`, `info()`, and `describe()`  
- Checked for missing values, incorrect formatting, and duplicates  

### **2️⃣ Data Cleaning**
Performed extensive cleaning on:
- **App names** (removing duplicates, correcting inconsistencies)  
- **Installs column** (converted from strings like `"1,000+"` to numeric)  
- **Size column** (handled `"Varies with device"` and unit conversions)  
- **Price column** (removed `$` and converted to numbers)  
- **Rating & Reviews** (handled missing and invalid entries)  
- **Content Rating** (standardized categories)

---

## 🔍 Column-Wise Analysis
Each column was examined to:
- Detect anomalies  
- Standardize formats  
- Extract deeper insights  
Examples include analyzing app sizes, install count distribution, and content rating patterns.

---

## 🎯 KPI Analysis (Business Insights)

The notebook answers key analytical questions such as:

1. **How many free apps exist in the ART_AND_DESIGN category?**  
2. **How many ART_AND_DESIGN apps have rating > 4.5?**  
3. **How many FAMILY apps are free and have rating > 4.5?**  
4. **List all free FAMILY apps with rating > 4.5**  
5. **Top ENTERTAINMENT apps with rating > 4.5 (sorted by rating)**  
6. **Category with highest average rating**  
7. **Count of paid apps per category (descending)**  
8. **Count of free apps per category (descending)**  
9. **Apps in ART_AND_DESIGN sorted by number of reviews**

These KPIs reflect real business scenarios such as evaluating market trends, analyzing user preferences, and understanding app store dynamics.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**
- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**

---

## ✅ Project Outcome
This analysis demonstrates the ability to:
- Work with messy real-world datasets  
- Apply strong data cleaning and transformation techniques  
- Build KPI-based insights for business decision-making  
- Perform EDA using Python tools  
- Present insights clearly and professionally  

---

## 📁 Repository Contents
- `GooglePlaystore.ipynb` → Main analysis notebook  
- `README.md` → Project description  

---





