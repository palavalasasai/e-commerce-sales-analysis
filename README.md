🛒 E-Commerce Sales Analysis – End-to-End Analytics Project

This project focuses on analyzing E-Commerce transactional data to understand customer buying behavior, sales trends, product performance, and operational efficiency. Using Python-based exploratory data analysis (EDA) combined with an interactive Power BI dashboard, the project uncovers insights related to sales, profit, product demand, regional performance, delivery speed, and payment preferences.
It helps businesses identify high-value customers, top-performing products, regional trends, and operational bottlenecks to enable smarter decision-making.

📊 Project Overview

This project analyzes large-scale E-Commerce sales data to uncover patterns across customers, products, regions, payments, and couriers.
The main goal is to help businesses understand key revenue drivers, optimize supply chain processes, and improve customer satisfaction through data-driven insights.

🎯 Objectives

Analyze relationships between sales, profit, discount, and product categories.

Understand customer purchasing behavior across cities, states, payment methods, and delivery partners.

Perform detailed univariate, bivariate, and multivariate analysis for insight generation.

Build an interactive Power BI dashboard to summarize KPIs and trends.

Provide actionable insights to support marketing, operations, and product strategy.

🧩 Dataset Description

File: ecommerce_sales_dataset.csv
Rows: ~200 (sample; scalable to thousands+)
Columns: 15+ (after cleaning and feature creation)

Column Name	What It Means	Type
Order_ID	Unique order identifier	Categorical
Order_Date	Date of purchase	Date
Ship_Date	Date of shipment	Date
City	Customer’s city	Categorical
State	Customer’s state	Categorical
Product	Purchased product name	Categorical
Category	Product category (Electronics, Fashion, etc.)	Categorical
Unit_Price	Selling price per unit	Numerical
Quantity	Number of units purchased	Numerical
Sales	Total revenue from the order	Numerical
Discount(%)	Discount applied	Numerical
Profit	Profit earned from the order	Numerical
Payment_Method	UPI, Credit Card, COD, etc.	Categorical
Courier	Delivery partner used	Categorical
Order_Status	Delivered / Returned / Cancelled / Shipped	Categorical
Delivery_Days	Days taken to deliver (derived feature)	Numerical
🔍 Key Analysis Performed
✔ Data Cleaning & Feature Engineering

Handled missing values

Converted date columns

Created Delivery_Days feature

Removed duplicates

Standardized categories

✔ Univariate Analysis

Histogram of sales, profit, quantity, discount

Pie charts for categories, payment methods, couriers

Frequency distribution of cities & states

✔ Bivariate Analysis

Category vs Sales

City vs Profit

Courier vs Delivery Days

Payment Method vs Sales/Profit

Stacked bar & box plots

✔ Multivariate Analysis

Category × Payment Method × Sales

Courier × Order Status × Delivery Days

State → City → Sales Tree Map

3D Scatter: Unit Price × Quantity × Profit

Clustered comparisons (Category × Order_Status)

✔ Correlation & Risk Analysis

Numeric heatmap (Sales, Profit, Unit Price, Quantity)

Business impact evaluation of discount on sales

📈 Sample Visuals
Visualization	Insight
Tree Map	State-wise revenue concentration
Box Plot	Category-wise sales + payment type patterns
Heatmap	Correlation between numeric features
3D Plot	Unit Price vs Quantity vs Profit
Pie Chart	City or Payment Method distribution
🛠️ Tools & Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Jupyter Notebook

Power BI

Power Query

DAX Measures

Interactive Visualizations

KPI Cards and Filters

📂 Repository Structure
ecommerce-sales-analysis/
├── data/
│   └── ecommerce_sales_dataset.csv
├── notebooks/
│   └── EDA_Ecommerce.ipynb
├── powerbi/
│   └── Ecommerce_Dashboard.pbix
├── visuals/
├── README.md
├── requirements.txt
└── LICENSE

⚙️ How to Run the Project
Clone the repository
git clone https://github.com/<your-username>/ecommerce-sales-analysis.git

Navigate to the folder
cd ecommerce-sales-analysis

Install dependencies
pip install -r requirements.txt

Open the notebook
jupyter notebook notebooks/EDA_Ecommerce.ipynb

Open the Power BI Dashboard

Open:

powerbi/Ecommerce_Dashboard.pbix

💡 Insights Summary

Electronics category contributes the highest revenue and profit.

UPI and Credit Card dominate payment preferences.

Metro cities (Bengaluru, Hyderabad, Pune) drive the most orders.

Higher-priced items produce significantly higher profit margins.

Faster deliveries (1–3 days) show higher customer success rates.

Discounts do not significantly impact sales volume.

🧾 Future Scope

Build predictive models to forecast sales and profit.

Add customer segmentation & RFM analysis.

Deploy the dashboard as a web analytics app.

Integrate with live e-commerce data streams.

👨‍💻 Author

Palavalasa Sai
📧 palavalasasai42@gmail.com

💼 Data Analytics Enthusiast | Python | SQL | Power BI | Visualization

📜 License

This project is open-source and available under the MIT License.
