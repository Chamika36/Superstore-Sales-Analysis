# **Superstore Sales: Profitability & Discount Optimization**

## **Project Overview**

This project explores the **Superstore Sales dataset** to identify "Profit Leaks" and optimize retail performance. It was developed as part of the **IS4116 Business Intelligence Systems** course. The analysis follows a complete data science lifecycle—from data cleaning to predictive modeling—aimed at improving organizational decision-making.

---

## **Business Problem**

The primary objective is to answer the following core question:

> **"How does the current discount strategy impact regional profitability, and which product categories require immediate intervention?"**

---

## **The Analytics Process**

Following the requirements of the assignment, the project is divided into four main phases:

### **1. Data Preprocessing**

* **Handling Missing Values**: Filled missing entries in **Postal Code** attributes to maintain dataset integrity.
* **Temporal Formatting**: Converted **Order Date** and **Ship Date** into `datetime` objects for time-series trend analysis.
* **Feature Encoding**: Applied **Label Encoding** to categorical features such as **Region**, **Segment**, **Category**, and **Ship Mode** to prepare the data for statistical modeling.

### **2. Exploratory Data Analysis (EDA)**

* **Summary Statistics**: Generated metrics including **Mean**, **Median**, **Mode**, **Variance**, and **Range** to understand data distribution.
* **Profitability Mapping**: Visualized total profit/loss by **Sub-Category** to isolate specific underperforming products.

### **3. Statistical Analysis**

* **Correlation Analysis**: Quantified the significant **inverse relationship** between **Discount** and **Profit Margin**.
* **Multiple Linear Regression**: Built a predictive model to estimate **Profit** based on **Sales volume** and **Discount rates**.
* **K-Means Clustering**: Segmented orders into high, medium, and low-performance clusters to help target specific regional sales strategies.

### **4. Visualizations**

* **Static Insights**: Utilized **Seaborn** to create correlation heatmaps.
* **Interactive Analytics**: Employed **Plotly** to generate geographical profit maps for identifying regional trends.

---

## **Key Findings**

* **Profit Leaks**: The **Tables** and **Supplies** categories are consistently generating net losses, largely due to excessive discounting.
* **Regional Performance**: Analysis identified significant margin erosion specifically within the **Central Region**.
* **Statistical Proof**: The negative correlation between discount and profit margin proves that the current promotional strategy is unsustainable for specific high-loss segments.

---

## **Technologies Used**

* **Language**: Python
* **Libraries**:
* **Data Handling**: Pandas, NumPy
* **Machine Learning**: Scikit-learn
* **Visualization**: Matplotlib, Seaborn (Static), Plotly (Interactive)


* **Platform**: Google Colab / Jupyter Notebooks

---
