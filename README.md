📊 Retail Sales Analytics — Python Project
End-to-End Retail Insights Using Pandas, Matplotlib & Exploratory Data Analysis (EDA)

This project demonstrates a complete real-world retail analytics workflow using Python.
You take raw sales data → clean it → engineer features → perform EDA → extract business insights → visualise → summarise.

This is a portfolio-ready project showcasing skills required for Data Analyst roles.

🚀 Project Objectives

* Analyse retail sales across products, customers, weekdays, months, and countries
* Identify top-performing categories, products, and customers
* Understand customer purchasing frequency
* Build actionable business insights
* Communicate results using charts and summary files

<br>🗂️ Project Structure
Retail_Sales_Analytics_Python/
<br>│
<br>├── 01_Data/
<br>│   ├── 01_Raw/                 # Original input dataset (Excel/CSV)
<br>│   └── 02_Processed/           # Cleaned dataset exported from Python
<br>│
<br>├── 02_Notebooks/
<br>│   └── retail_sales_analysis.ipynb   # Full Jupyter Notebook with analysis
<br>│
<br>├── 03_Src/
<br>│   └── README.md
<br>│
<br>├── 04_Outputs/
<br>│   ├── 01_Charts/              # All visualisations (PNG)
<br>│   └── 02_Summary/             # Summary CSVs for further review
<br>│
<br>├── exec_summary.md             # Written executive summary
<br>└── README.md                   


<br>🧹 Data Cleaning & Preparation

Processed using Pandas:

✔️ Converted dates → datetime
<br>✔️ Extracted year, month, day, weekday
<br>✔️ Added revenue = quantity * unit_price
<br>✔️ Removed errors, fixed dtypes
<br>✔️ Created processed dataset for downstream analysis

<br>📈 Key Analysis Performed
<br><br>1️⃣ Revenue by Product Category

* Identified high-level performance across major product categories.
* Furniture and Electronics were strongest performers.

2️⃣ Revenue by Month

* Shows seasonal / monthly performance.
(Current dataset contains only January)

3️⃣ Revenue by Weekday

* Analysed daily performance patterns.
* Wednesday showed the highest revenue.

4️⃣ Revenue by Country

* Compared international sales performance.
* United Kingdom showed strongest sales activity.

5️⃣ Top 5 Products by Revenue

* Ranked individual product performance:
* Standing Desk, Office Chair, and Wireless Mouse were top sellers.

6️⃣ Top 6 Customers by Purchase Frequency

* Analysed customer lifetime engagement using value_counts().

<br>📊 Visualisations

All charts exported as PNG into:

![Charts Folder](Retail_Sales_Analytics_Python/04_Outputs/01_Charts)
<br>
![Chart Preview](Retail_Sales_Analytics_Python/04_Outputs/01_Charts/revenue_by_top5_customers.png)

<br>Includes:

* revenue_by_category

* revenue_by_country

* revenue_by_month

* revenue_by_product

* revenue_by_top5_product

* revenue_by_weekday

* customer_top6_purchase_freq

* Each chart includes:

✔️ labelled x/y axes
✔️ data labels
✔️ rotated text for readability
✔️ clean formatting for professional presentation

<br>📄 Summary Files

All summary tables exported as .csv into:

![Summary Folder Folder](Retail_Sales_Analytics_Python/04_Outputs/02_Summary)


<br>Includes:

* revenue_by_category.csv

* revenue_by_country.csv

* revenue_by_month.csv

* revenue_by_weekday.csv

* revenue_by_product.csv

* revenue_by_top5_product.csv

* customer_top6_purchase_freq.csv

* retail_sales_processed.csv (full cleaned dataset)

<br>🧠 Executive Summary

A separate exec_summary.md file outlines:

* topline findings

* sales trends

* customer behaviour patterns

* recommended actions for the business

* This simulates real-world stakeholder reporting.

🛠️ Technologies Used
Tool / Library	Purpose
Python	Core data manipulation
Pandas	Cleaning, grouping, aggregations
Matplotlib	Visualisation
Jupyter Notebook	Analysis environment
Excel/CSV	Dataset & exports

<br>📦 How to Run This Project

Clone the repo:

git clone https://github.com/yourusername/Retail_Sales_Analytics_Python.git


Install libraries:

pip install pandas matplotlib notebook


Open Jupyter Notebook:

jupyter notebook


Run:

![Notebooks Folder](Retail_Sales_Analytics_Python/02_Notebooks/)

<br>🧩 Future Improvements

* Add time series forecasting (Prophet, ARIMA)

* Integrate Power BI for dashboards

* Add customer segmentation (K-means clustering)

* Build dynamic Python scripts in /03_Src/

<br>⭐ Key Takeaways

This project demonstrates:

✔️ End-to-end data analysis workflow
✔️ Clean modular folder structure
✔️ Visual storytelling
✔️ Business-ready insights
✔️ Strong analytical thinking

<br><br>👤 About the Developer

Schikan (Portfolio Project)
<br>Aspiring Data Analyst | BI Analyst
<br>Focused on Power BI, SQL, Azure, and real-world practical analytics.

## 📬 Contact
📧 Email: **schikan@yahoo.co.uk**  
🔗 GitHub: **https://github.com/shikzta**

![SQL](https://img.shields.io/badge/SQL-Expert-blue?style=flat&logo=database)
![Excel](https://img.shields.io/badge/Excel-Advanced-green?style=flat&logo=microsoft-excel)
![Power BI](https://img.shields.io/badge/Power_BI-Learning-yellow?style=flat&logo=power-bi)
![Azure](https://img.shields.io/badge/Azure-Studying-blue?style=flat&logo=microsoft-azure)
![Python](https://img.shields.io/badge/Python-Learning-blue?style=flat&logo=python)

<br>📄 License

This project is open for educational and portfolio use.

