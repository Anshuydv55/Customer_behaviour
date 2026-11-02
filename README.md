# 🛍️ Customer Shopping Behaviour Analysis

## 📌 Project Overview

This project focuses on analyzing customer shopping behaviour using Python, Pandas, and MySQL. The objective is to explore customer purchasing patterns, understand shopping preferences, and generate meaningful business insights from retail transaction data.

The project involves loading the dataset using Python, storing it in a MySQL database, and performing SQL-based data analysis.

## 🎯 Objectives

- Analyze customer purchasing behaviour.
- Identify popular product categories and shopping preferences.
- Understand customer spending patterns.
- Explore relationships between customer demographics and purchasing decisions.
- Generate actionable insights to support business decisions.

## 🛠️ Technologies Used

- **Python:** Data handling and processing.
- **Pandas:** Data loading and manipulation.
- **MySQL:** Database management and SQL analysis.
- **SQLAlchemy:** Connecting Python with MySQL.
- **Jupyter Notebook:** Development and analysis environment.

## 📂 Project Structure

```text
Customer-Shopping-Behaviour/
│
├── customer_shopping_behaviour.csv
├── Customer_Shopping_Behaviour.ipynb
└── README.md
```

## ⚙️ Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Explored the dataset using `head()`, `info()`, and `describe()`.

### 2. Data Preparation
- Inspected missing values.
- Checked duplicate records.
- Reviewed column names and data types.

### 3. Database Connection
- Connected Python to MySQL using SQLAlchemy.
- Created a database named `cust`.
- Loaded the dataset into the `customer` table using Pandas `to_sql()`.

### 4. SQL Analysis
Performed SQL queries to explore customer shopping behaviour, purchasing trends, and product preferences.

## 💡 Key Business Questions

1. Which product categories generate the most purchases?
2. What is the average purchase amount?
3. Which age groups spend the most?
4. Which product categories are most popular among different customer segments?
5. Does subscription status influence customer purchasing behaviour?
6. Which customers have the highest purchase frequency?
7. What are the most preferred payment methods?
8. How do discounts influence purchasing decisions?

## 📊 Expected Outcomes

- Better understanding of customer purchasing patterns.
- Identification of popular product categories.
- Insights into customer spending habits.
- Customer segmentation based on shopping behaviour.
- Data-driven recommendations for improving business performance.

## 🚀 How to Run the Project

**Step 1:** Clone the repository.


[git clone YOUR_REPOSITORY_URL](https://github.com/Anshuydv55/Customer_behaviour/edit/main)


**Step 2:** Install the required libraries.


pip install pandas sqlalchemy pymysql jupyter

**Step 3:** Configure your MySQL database connection.

**Step 4:** Open the Jupyter Notebook.

jupyter notebook

**Step 5:** Run the notebook cells to load and analyze the dataset.

## 👨‍💻 Author

**Anshu Yadav**

Aspiring Data Analyst | MIS Executive

Skills: Python | SQL | MySQL | Power BI | Excel | Data Analysis

---

⭐ If you find this project useful, feel free to star the repository!
