📊 Customer Shopping Behavior Analysis (Product + Data Project)

🔍 Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segmentation, and product preferences.

Unlike a typical analytics project, this was also managed using Agile product management practices in Jira, simulating a real-world product lifecycle from data exploration to business decision-making.

The analysis is based on ~3,900 transactions across multiple product categories.

🎯 Objective
Segment customers into meaningful groups
Analyze revenue and purchasing trends
Build an interactive dashboard
Generate actionable business recommendations
Manage the project using Agile workflow (Jira)
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
Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning & EDA
SQL (PostgreSQL / MySQL / SQL Server) – Business analysis
Power BI – Dashboard visualization
Jira – Agile project management & workflow tracking
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
Analyzed customer demographics
Identified purchase patterns and seasonal trends
Derived behavioral insights
4. SQL Analysis

Performed business-focused queries such as:

Revenue by gender
Top-rated products
High-spending discount users
Subscriber vs non-subscriber behavior
Customer segmentation (New, Returning, Loyal)
Revenue by age group
🧩 Product Management (Jira Workflow)

The project was structured using Agile methodology in Jira to simulate a real-world product lifecycle.

🔹 Epics (High-Level Features)
User Segmentation
Data Analysis
Dashboard Development
Business Insights

🔹 User Stories
Segment users into categories
Analyze revenue trends
Build Power BI dashboard
Generate business recommendations

🔹 Workflow

Tasks were tracked across stages:
Idea → To Do → In Progress → Testing → Done

🔹 Key Practices
Defined acceptance criteria for each task
Broke work into subtasks (SQL, dashboard, validation)
Simulated sprint-based execution
Ensured validation before final insights

📌 This approach helped transform the project from pure analysis into a product-driven solution.

📊 Dashboard

An interactive Power BI dashboard was created to visualize insights.

Key Highlights:
Total customers, average purchase amount, ratings
Revenue by category and age group
Subscription distribution
Sales trends and comparisons
📈 Results & Insights
Female customers generated higher revenue than males
Loyal customers contributed the majority of revenue
Discounts significantly influenced purchasing behavior
Young adults contributed the highest revenue share
Express shipping users showed slightly higher spending
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
5. View Reports
Check PDF report in /reports
Open presentation (Gamma PPT)
📌 Project Structure
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── jira/
├── reports/
└── README.md
🚀 Conclusion

This project demonstrates end-to-end data analytics combined with product management practices, including:

Data preprocessing and analysis
SQL-based business insights
Dashboard visualization
Agile project management using Jira
Data-driven decision making

👉 It showcases the ability to bridge the gap between data and product thinking, making it highly relevant for Product, Data Analyst, and Business Analyst roles.
