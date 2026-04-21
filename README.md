📊 Customer Shopping Behavior Analysis
🔍 Overview

This project focuses on analyzing customer shopping behavior using transactional data to uncover meaningful insights about spending patterns, customer segments, and product preferences.

The workflow covers data cleaning, exploratory data analysis (EDA), SQL-based querying, dashboard visualization, and reporting to support data-driven decision-making.

The analysis is based on ~3,900 transactions across multiple product categories

📁 Dataset
Rows: ~3,900
Columns: 18
Key Features:
Customer demographics (Age, Gender, Location)
Purchase details (Item, Category, Amount, Season)
Behavioral data (Discounts, Frequency, Ratings, Shipping Type)
Data Issues Handled:
Missing values in review ratings
Redundant columns removed
Feature engineering (age groups, purchase frequency)
🛠️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib/Seaborn) – Data cleaning & EDA
SQL (PostgreSQL / MySQL / SQL Server) – Data analysis
Power BI – Dashboard creation
Gamma – Presentation (PPT generation)
Jupyter Notebook – Development environment
⚙️ Project Workflow / Steps
1. Data Loading & Exploration
Loaded dataset using Pandas
Checked structure using .info() and .describe()
Identified missing values and inconsistencies
2. Data Cleaning & Preparation
Handled missing values using median imputation
Standardized column names
Created new features:
age_group
purchase_frequency_days
Removed redundant columns
3. Exploratory Data Analysis (EDA)
Analyzed:
Customer demographics
Purchase patterns
Seasonal trends
Identified correlations and behavioral insights
4. SQL Analysis

Performed business-focused queries such as:

Revenue by gender
Top-rated products
High-spending discount users
Subscriber vs non-subscriber behavior
Customer segmentation (New, Returning, Loyal)
Revenue by age group
📊 Dashboard

An interactive Power BI dashboard was created to visualize insights.

Key Highlights:

Total customers, average purchase amount, ratings
Revenue by category and age group
Subscription distribution
Sales trends and comparisons
📈 Results & Insights
Female customers generated higher revenue compared to males
Loyal customers formed the majority segment
Discounts significantly influenced purchasing behavior
Young adults contributed the highest revenue share
Express shipping users had slightly higher spending
💡 Business Recommendations
Promote subscription benefits to increase retention
Introduce loyalty programs for repeat customers
Optimize discount strategies to balance profit
Focus marketing on high-value customer segments
▶️ How to Run
1. Clone the Repository
git clone https://github.com/your-username/customer-shopping-analysis.git
cd customer-shopping-analysis
2. Run Python Analysis
pip install -r requirements.txt
jupyter notebook
3. Setup Database
Import cleaned dataset into PostgreSQL/MySQL/SQL Server
Run SQL scripts from /sql folder
4. View Dashboard
Open .pbix file in Power BI Desktop
5. View Report & Presentation
Check PDF report in /reports
Open Gamma-generated PPT
📌 Project Structure
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── reports/
└── README.md
🚀 Conclusion

This project demonstrates end-to-end data analytics skills, including:

Data preprocessing
SQL-based business analysis
Data visualization
Insight generation

It highlights the ability to turn raw data into actionable business insights, making it highly relevant for data analyst roles.
