# 🚗 Used Car Price Analysis – Cars4U Dataset

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a used car dataset to identify the key factors that influence the **resale price of cars**. The analysis helps understand how features such as **car age, fuel type, transmission, engine power, ownership history, and brand** impact pricing in the used car market.

This project is designed for **portfolio showcase, data analysis practice, and business insight generation**.

---

## 📂 Dataset Information

- Dataset contains **7,253 records** of used cars
- 14 original columns including:
  - `Name`
  - `Year`
  - `Kilometers_Driven`
  - `Fuel_Type`
  - `Transmission`
  - `Owner_Type`
  - `Mileage`
  - `Engine`
  - `Power`
  - `Seats`
  - `Price`
- Additional features created:
  - `Car_Age`
  - `Brand`
  - `Model`
  - `Mileage_Value`

---

## 🎯 Objective

The main goals of this analysis were:

✅ Clean and preprocess the data  
✅ Handle missing values  
✅ Perform feature extraction (Brand, Model, Age)  
✅ Analyze relationships between features and car price  
✅ Provide business recommendations  

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Missingno

---

## 📊 Key Analysis Performed

### 1. Univariate Analysis
- Distribution of numerical features (Price, Engine, Mileage, etc.)
- Top 10 brands, models, fuel types, etc.

### 2. Multivariate Analysis
- Correlation heatmap
- Pairplot for numerical features

### 3. Bivariate Analysis
- `Year vs Price` by Transmission
- `Year vs Price` by Fuel Type
- `Year vs Price` by Owner Type
- `Seats vs Price` comparison

---

## 🔍 Key Insights

✔ Car price increases as the manufacturing year increases  
✔ Automatic cars are more expensive than Manual  
✔ Diesel cars generally retain higher resale value  
✔ First-owner cars are priced significantly higher  
✔ Higher engine power & bigger engine capacity → higher price  
✔ Luxury brands (Audi, BMW, Mercedes) dominate the premium segment  

---

## 💡 Business Recommendations

📌 Promote vehicles that are:
- Diesel
- Automatic
- First-owner
- Less than 7 years old

📌 Segment the cars into:
- **Budget Category** – Maruti, Hyundai, Tata
- **Luxury Category** – Audi, BMW, Mercedes, Jaguar

📌 Provide website filters by:
- Transmission type
- Owner type
- Fuel type
- Car age

These features can significantly improve customer targeting and business profitability.

---

## 📁 Files in this Repository

| File Name | Description |
|------|------|
| `cars4u.ipynb.ipynb` | Full EDA notebook with visualization |
| `used_cars_data.csv` | Raw dataset |
| `README.md` | Project documentation |

---

## ✅ Conclusion

This EDA provides valuable insights into the **used car market** and highlights the most important features influencing the final selling price. The project demonstrates strong data cleaning, visualization, and analytical skills suitable for a Data Analyst role.

