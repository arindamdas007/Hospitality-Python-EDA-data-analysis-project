# Hospitality-Python-EDA-data-analysis-project
# 🏨 Hospitality Data Analysis Project

## 📌 Project Overview
This project focuses on analyzing hotel booking data for a multi-city hotel chain, **AtliQ Grands**, which is facing declining revenue and market share. The objective is to perform data analysis and generate actionable insights to support data-driven business decisions.

---

## 🎯 Problem Statement
AtliQ Grands operates in multiple cities across India and has been experiencing a decline in revenue due to increased competition. The goal of this project is to analyze booking data and identify key factors impacting revenue and occupancy.

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Matplotlib

---

## 📂 Dataset Description
The project uses multiple datasets:

- **fact_bookings.csv** → Booking transaction data  
- **dim_hotels.csv** → Hotel information (city, category)  
- **dim_rooms.csv** → Room classification  
- **dim_date.csv** → Date-related details  
- **fact_aggregated_bookings.csv** → Aggregated booking data  

---

## 🔄 Project Workflow

### 1. Data Understanding
- Explored dataset structure using `.info()`, `.describe()`, `.value_counts()`

### 2. Data Cleaning
- Removed invalid entries (e.g., negative guest counts)
- Handled missing values in ratings
- Detected and removed outliers using statistical methods (3 standard deviation rule)

### 3. Data Transformation
- Merged multiple datasets using joins
- Created new features such as **revenue in INR**
- Normalized currency values

### 4. Exploratory Data Analysis (EDA)
- Analyzed booking platform performance
- Studied city-wise revenue trends
- Evaluated room category contribution

---

## 📊 Key Insights

- 📍 **Mumbai generates the highest revenue**
- 🌐 **Online platforms contribute the majority of bookings**
- 🛏️ **Premium and luxury rooms drive maximum revenue**
- ❌ **Cancellations significantly impact realized revenue**
- 📈 **Business hotels show more stable occupancy trends**

---

## 💡 Business Recommendations

- Focus marketing efforts on high-performing cities like Mumbai  
- Strengthen partnerships with top booking platforms  
- Promote premium room upgrades to increase revenue  
- Reduce cancellations through better booking policies  

---

## 📈 Future Improvements
- Build interactive dashboards using Power BI or Tableau  
- Perform advanced analysis using SQL  
- Apply predictive modeling for demand forecasting  

---

## 🙋‍♂️ About Me
I am an aspiring Data Analyst with hands-on experience in Python, SQL, and Power BI. This project demonstrates my ability to work with real-world datasets and generate meaningful insights.

---

## ⭐ If you found this project useful, please consider giving it a star!
