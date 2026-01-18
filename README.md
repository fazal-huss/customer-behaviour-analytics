# customer-behaviour-analytics
Data Analytics Portfolio Project with end-to-end industry standard Data Analysis of Customer Shopping Trends from Retail Data using SQL, Python and Power BI.

## 📌 Business Objective
The objective of this project is to analyze retail customer shopping behavior and identify how demographics, subscription status, product categories, shipping methods, and purchase frequency influence revenue, customer value, and customer satisfaction.

The analysis is designed to support data-driven decisions related to marketing strategy, customer retention, and operational optimization.

## ❓ Key Business Questions Answered
- Which customer segments generate the highest revenue per customer?
- Do subscribed customers spend more than non-subscribers?
- How does shipping type impact customer spending behavior?
- Which product categories drive revenue versus transaction volume?
- How does customer satisfaction (review rating) relate to spending patterns?

## ⚙️ Challenges & Solutions

### 1️⃣ Handling Incomplete & Inconsistent Data
**Challenge:**  
The dataset contained missing values in the review_rating column, which could distort customer satisfaction analysis.

**Solution:**  
Performed category-wise median imputation using Python (Pandas) to preserve realistic rating distributions within each product segment.

**Impact:**  
Improved reliability of customer sentiment KPIs and downstream Power BI visuals.

---

### 2️⃣ Feature Engineering for Business Analysis
**Challenge:**  
Raw attributes such as age and purchase frequency were not directly suitable for segmentation or behavioral analysis.

**Solution:**  
Engineered new features:
- Age Group (Young Adult, Adult, Middle-aged, Senior)
- Purchase Frequency (converted to numeric days)
- Customer lifecycle indicators

**Impact:**  
Enabled deeper demographic, behavioral, and retention analysis.

---

### 3️⃣ Scalable Analysis Using SQL
**Challenge:**  
Flat-file analysis limited query flexibility and real-world scalability.

**Solution:**  
Loaded cleaned data into a SQL database and executed structured business queries to analyze customer value, loyalty, and purchase drivers.

**Impact:**  
Replicated an industry-grade analytics workflow.

![Uploading image.png…]()
## 🛠️ Tools & Technologies Used
- **Python:** Pandas, NumPy (Data Cleaning & Feature Engineering)
- **SQL:** PostgreSQL / MS SQL Server (Business Analysis)
- **Power BI:** Interactive Dashboards & KPI Reporting

## 🔄 Project Workflow

1. Performed data cleaning, exploration, and feature engineering using Python.
2. Loaded the cleaned dataset into a SQL database.
3. Executed SQL queries to answer key business questions.
4. Built an interactive Power BI dashboard with executive-level KPIs.
5. Created a business report and presentation summarizing insights and recommendations.
## 📈 Key Insights
- Subscribed customers demonstrate higher average spend compared to non-subscribers.
- Faster and free shipping options are associated with higher customer value.
- Clothing and Accessories drive the highest revenue and transaction volume.
- Younger customer segments contribute significantly to overall revenue.


