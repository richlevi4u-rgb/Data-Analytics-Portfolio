# 📊 Stock Market Analysis

## Project Overview

This project analyzes historical stock market data to identify trends, relationships, patterns, and meaningful insights across multiple publicly traded companies.

The analysis covers data cleaning, exploratory data analysis, statistical analysis, regression modelling, and unsupervised machine learning.

---

## 🎯 Objectives

* Clean and prepare historical stock market data
* Explore stock price and trading-volume patterns
* Analyze relationships between opening and closing prices
* Examine individual stock performance
* Apply regression analysis
* Group stocks using K-Means clustering
* Generate meaningful business and financial insights

---

## 🗂️ Dataset

The dataset contains historical stock market records with the following variables:

| Column   | Description         |
| -------- | ------------------- |
| `symbol` | Stock ticker symbol |
| `date`   | Trading date        |
| `open`   | Opening price       |
| `high`   | Highest price       |
| `low`    | Lowest price        |
| `close`  | Closing price       |
| `volume` | Trading volume      |

The dataset contains approximately **497,000 records across 505 stock symbols**.

---

## 🛠️ Tools & Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 🔍 Analysis Performed

### 1. Data Cleaning

The dataset was inspected and prepared for analysis by:

* Checking missing values
* Handling empty cells
* Checking duplicate records
* Correcting data types
* Converting the date column into a proper datetime format

### 2. Exploratory Data Analysis

Statistical summaries and visualizations were created to understand:

* Stock price distributions
* Trading volume
* Price movements
* Market trends
* Individual stock behaviour

### 3. Regression Analysis

A linear regression model was developed to examine the relationship between opening and closing stock prices.

The model produced an **R² score of approximately 0.9997**, indicating an extremely strong linear relationship within this dataset.

### 4. K-Means Clustering

K-Means clustering was applied to group stocks according to their characteristics.

The analysis identified **5 clusters** using the elbow method.

---

## 📈 Key Insights

* Opening and closing prices showed an extremely strong relationship.
* Stock behaviour varied significantly across companies.
* Trading volume differed substantially between stocks.
* K-Means clustering revealed distinct groups of stocks with similar characteristics.

---

## 📁 Project Files

* `stock_analysis.ipynb` — Complete analysis and visualizations
* `README.md` — Project documentation
* `data/` — Dataset or sample dataset, where applicable

---

## 💡 Conclusion

The project demonstrates how Python-based data analytics can be used to transform large financial datasets into actionable insights.

It combines data preparation, exploratory analysis, statistical modelling, visualization, and machine learning into an end-to-end analytics workflow.

---

**Author:** Rich Ejim
**GitHub:** https://github.com/richlevi4u-rgb
