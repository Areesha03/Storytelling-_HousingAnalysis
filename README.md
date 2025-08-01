# Storytelling-_HousingAnalysis
# 🏠 Housing Prices Data Analysis Project

This project explores and analyzes a housing price dataset from Kaggle to uncover trends in pricing, area, bedrooms, and other key housing features. It includes full data cleaning, statistical analysis, visualizations, and summary insights using Python and Pandas.

---

## 📁 Dataset

- **Name**: Housing Price Prediction Dataset  
- **Source**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- **File Used**: `housing.csv`
- **Main Features**:
  - `price`: Price of the house
  - `area`: Area of the house in square feet
  - `bedrooms`: Number of bedrooms
  - `furnishingstatus`, `bathrooms`, `mainroad`, etc.

---

## 📊 Key Objectives

1. Load and clean the dataset using Pandas.
2. Compute descriptive and inferential statistics.
3. Visualize important trends using Matplotlib and Seaborn.
4. Group data by price categories and bedroom count.
5. Generate insights to help understand the housing market.

---

## 🚀 Technologies Used

- **Python 3.x**
- **Pandas** (data analysis)
- **Matplotlib & Seaborn** (visualization)
- **Jupyter Notebook / Python Script**

---

## 🧮 Steps Performed

### 📌 1. Setup & Load Data
- Loaded the dataset using `pd.read_csv()`
- Inspected structure with `df.info()` and `df.describe()`
- Removed rows with missing data

### 📌 2. Statistical Analysis
- Computed `mean`, `median`, `mode`, `std`, `var`, `min`, `max`, `skew`, `kurtosis` for:
  - `price`, `area`, and `bedrooms`
- Created a statistics summary table

### 📌 3. Grouping & Binning
- Grouped data to calculate average price per bedroom count
- Binned prices into categories like `<2M`, `2M–4M`, `>8M`, etc.

### 📌 4. Visualizations
- **Histogram** for house prices
- **Scatter plot** of Price vs Area (by bedrooms)
- **Bar chart** of Average Price by Bedroom
- **Bar + Pie charts** of House Count by Price Category

### 📌 5. Summary Story
Summarized key findings in a 5–8 sentence narrative

---

## 📈 Sample Insights

- The average home price is high, but there's wide variability in the market.
- Price distribution is right-skewed, due to a few expensive houses.
- Bedroom count alone does not determine price — location, size, and furnishing matter.
- Some larger homes are cheaper than expected, likely due to location.
- Market includes both affordable and high-end segments.

---

## 📂 Project Files

