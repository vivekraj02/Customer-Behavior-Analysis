📊 Customer Shopping Behavior Analysis (Product + Data Project)

🔍 Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segmentation, and product preferences.

Unlike a typical analytics project, this was also managed using Agile product management practices in Jira, simulating a real-world product lifecycle from data exploration to business decision-making.

The analysis is based on ~3,900 transactions across multiple product categories.

🎯 Objective
•	Segment customers into meaningful groups 
•	Analyze revenue and purchasing trends 
•	Build an interactive dashboard 
•	Generate actionable business recommendations 
•	Manage the project using Agile workflow (Jira) 

📁 Dataset

•	Rows: ~3,900

•	Columns: 18 

Key Features:

    •	Customer demographics (Age, Gender, Location) 
    •	Purchase details (Item, Category, Amount, Season) 
    •	Behavioral data (Discounts, Frequency, Ratings, Shipping Type) 
Data Issues Handled:

    •	Missing values in review ratings 
    •	Redundant columns removed 
    •	Feature engineering (age groups, purchase frequency)

🛠️ Tools & Technologies

•	Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning & EDA 

•	SQL (PostgreSQL / MySQL / SQL Server) – Business analysis 

•	Power BI – Dashboard visualization 

•	Jira – Agile project management & workflow tracking 

•	Gamma – Presentation (PPT generation) 

•	Jupyter Notebook – Development environment

⚙️ Project Workflow / Steps

1. Data Loading & Exploration
   
       Loaded dataset using Pandas 
       Checked structure using .info() and .describe() 
       Identified missing values and inconsistencies 

2. Data Cleaning & Preparation

       •	Handled missing values using median imputation 
       •	Standardized column names 
       •	Created new features: 
           o	age_group 
           o	purchase_frequency_days 
       •	Removed redundant columns

3. Exploratory Data Analysis (EDA)

       •	Analyzed customer demographics 
       •	Identified purchase patterns and seasonal trends 
       •	Derived behavioral insights

<img width="1881" height="876" alt="Screenshot 2026-04-23 081004" src="https://github.com/user-attachments/assets/6742a79c-8af9-4341-9d15-d17a5a3b363b" />

<img width="1886" height="949" alt="Screenshot 2026-04-23 081118" src="https://github.com/user-attachments/assets/517e9f73-27bb-4e10-9e9b-57b2e77fbdfa" />

4. SQL Analysis
   
Performed business-focused queries such as:

    •	Revenue by gender 
    •	Top-rated products 
    •	High-spending discount users 
    •	Subscriber vs non-subscriber behavior 
    •	Customer segmentation (New, Returning, Loyal) 
    •	Revenue by age group

<img width="1483" height="582" alt="Screenshot 2026-04-23 081353" src="https://github.com/user-attachments/assets/7d3c9dc0-ab61-40ea-8d96-9d81d3cccf7b" />

<img width="1594" height="759" alt="Screenshot 2026-04-23 081624" src="https://github.com/user-attachments/assets/f5c5fec6-82b5-43b1-917b-e53817529b60" />


🧩 Product Management (Jira Workflow)

The project was structured using Agile methodology in Jira to simulate a real-world product lifecycle.

🔹 Epics (High-Level Features)

    •	User Segmentation 
    •	Data Analysis 
    •	Dashboard Development 
    •	Business Insights 

🔹 User Stories

    •	Segment users into categories 
    •	Analyze revenue trends 
    •	Build Power BI dashboard 
    •	Generate business recommendations 

🔹 Workflow

Tasks were tracked across stages:

Idea → To Do → In Progress → Testing → Done

🔹 Key Practices

    •	Defined acceptance criteria for each task 
    •	Broke work into subtasks (SQL, dashboard, validation) 
    •	Simulated sprint-based execution 
    •	Ensured validation before final insights 

<img width="1609" height="718" alt="Screenshot 2026-04-23 083511" src="https://github.com/user-attachments/assets/912ad8f6-72fa-46c9-83ee-2a6e5b968271" />

<img width="1601" height="759" alt="Screenshot 2026-04-23 094855" src="https://github.com/user-attachments/assets/995a3e7d-0e4c-41bc-a769-d0d812a2e54d" />

<img width="1599" height="751" alt="Screenshot 2026-04-23 094912" src="https://github.com/user-attachments/assets/daae35f1-2190-428d-8088-949d908c3cde" />

<img width="1603" height="756" alt="Screenshot 2026-04-23 094927" src="https://github.com/user-attachments/assets/27278002-aecd-428f-9cb2-cb20bacfc8c3" />

<img width="1604" height="768" alt="Screenshot 2026-04-23 094937" src="https://github.com/user-attachments/assets/4a51a511-4f41-436e-8253-65c505bc4f7f" />

<img width="1603" height="766" alt="Screenshot 2026-04-23 094952" src="https://github.com/user-attachments/assets/736c229c-e130-4f2c-b481-3adeceab15d6" />

<img width="1602" height="756" alt="Screenshot 2026-04-23 094959" src="https://github.com/user-attachments/assets/964b7eb4-adad-40d5-b641-3105a33d2752" />

<img width="1594" height="758" alt="Screenshot 2026-04-23 095024" src="https://github.com/user-attachments/assets/2c9bf1d4-67ee-4b3a-a165-594ec46cc7e8" />

📌 This approach helped transform the project from pure analysis into a product-driven solution.

📊 Dashboard

An interactive Power BI dashboard was created to visualize insights.

Key Highlights:

    •	Total customers, average purchase amount, ratings 
    •	Revenue by category and age group 
    •	Subscription distribution 
    •	Sales trends and comparisons

📈 Results & Insights

    •	Female customers generated higher revenue than males 
    •	Loyal customers contributed the majority of revenue 
    •	Discounts significantly influenced purchasing behavior 
    •	Young adults contributed the highest revenue share 
    •	Express shipping users showed slightly higher spending

💡 Business Recommendations

    •	Promote subscription benefits to increase retention 
    •	Introduce loyalty programs for repeat customers 
    •	Optimize discount strategies to balance profit 
    •	Focus marketing on high-value customer segments

<img width="1327" height="720" alt="Screenshot 2026-04-23 080508" src="https://github.com/user-attachments/assets/4bc99e2a-da99-439b-91d9-d52f9b9e892d" />


▶️ How to Run

1. Clone the Repository

       git clone https://github.com/your-username/customer-shopping-analysis.git
       cd customer-shopping-analysis

2. Run Python Analysis

       pip install -r requirements.txt
       jupyter notebook

3. Setup Database

       •	Import cleaned dataset into PostgreSQL/MySQL/SQL Server 
       •	Run SQL scripts from /sql folder

4. View Dashboard

       •	Open .pbix file in Power BI Desktop

5. View Reports

       •	Check PDF report in /reports 
       •	Open presentation (Gamma PPT) 

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

    •	Data preprocessing and analysis 
    •	SQL-based business insights 
    •	Dashboard visualization 
    •	Agile project management using Jira 
    •	Data-driven decision making 
👉 It showcases the ability to bridge the gap between data and product thinking, making it highly relevant for Product, Data Analyst, and Business Analyst roles.

