# 📊 Sales Data Cleaning & Exploratory Data Analysis (EDA)

This project was completed as **Week 1 Task** of the **Vortex Tech Data Science & Analytics Internship 2026**.

The objective was to clean a real-world sales dataset, perform Exploratory Data Analysis (EDA), and create visualizations to identify business trends and insights.

---

## 📌 Project Overview

The dataset contains **1,000 sales records** with a combination of **numeric** and **categorical** features.

The project focuses on:

- Data Cleaning
- Handling Missing Values
- Removing Duplicate Records
- Correcting Data Types
- Exploratory Data Analysis (EDA)
- Business Insights
- Data Visualization

---

## 📂 Dataset Information

- **Rows:** 1,000
- **Columns:** 8

### Features

- Order_Date
- Region
- Category
- Sales
- Customer_Age
- Gender
- Payment_Method
- Customer_Segment

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Converted `Order_Date` to DateTime format
- Filled missing values in **Region** with `"Unknown"`
- Converted **Sales** to numeric values
- Replaced invalid values using **NumPy (`np.nan`)**
- Filled missing Sales values using the **mean**
- Filled missing Customer Age using the **median**
- Converted Customer Age back to integer
- Filled missing Payment Method values with `"Unknown"`

---

## 📈 Visualizations

The project includes **5 business-focused visualizations**:

1. Sales by Category
2. Sales by Region
3. Orders by Payment Method
4. Monthly Sales Trend
5. Sales Distribution

---

## 💡 Key Insights

- 👕 **Clothing generated the highest total sales** among all product categories.
- 🌍 Sales were distributed across all four regions, with noticeable regional differences in revenue.
- 💳 **Wallet** was the most preferred payment method, followed closely by Card payments.
- 📅 Monthly sales fluctuated throughout the year, with higher sales observed during the later months.
- 📊 Sales values were spread across the dataset, indicating a healthy mix of low-, medium-, and high-value orders.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

---

## 📁 Project Structure

```
├── sales_dataset.csv
├── Week1.ipynb
├── sales_by_category.pdf
├── region_sale.pdf
├── orders_by_payment_method.pdf
├── monthly_sales_trend.pdf
├── sales_distribution.pdf
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/vortextech-datasci-week1.git
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib
```

3. Open the notebook

```bash
jupyter notebook Week1.ipynb
```

4. Run all cells to reproduce the analysis and visualizations.

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Missing Value Handling
- Data Type Conversion
- Exploratory Data Analysis (EDA)
- Business Data Visualization
- Extracting Actionable Insights using Python

---

## 👨‍💻 Author

**Hammas Akhtar**

Data Science & Analytics Intern — Vortex Tech 2026

GitHub: https://github.com/Hammas-Akhtar

LinkedIn: https://www.linkedin.com/in/hammas-akhtar/
