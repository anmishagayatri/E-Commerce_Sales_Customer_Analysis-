# Customer Shopping Behavior Analysis

## 📌 Overview

An end-to-end **Data Analytics project** analyzing customer shopping behavior using transactional data from **3,900 purchases across multiple product categories**.

The project focuses on understanding **spending patterns, customer segments, product preferences, discounts, subscriptions, and revenue trends** to generate actionable business insights.

---

## 📊 Dataset

The dataset contains **3,900 rows and 18 columns** covering:

* Customer demographics — Age, Gender, Location, Subscription Status
* Purchase details — Item, Category, Purchase Amount, Season, Size, Color
* Shopping behavior — Discounts, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

The dataset initially contained **37 missing values in Review Rating**.

---

## 🛠️ Tools & Technologies

* **Python** — Data loading, EDA & data cleaning
* **Pandas** — Data manipulation
* **PostgreSQL** — SQL analysis
* **Power BI** — Interactive dashboard
* **Gamma** — Business presentation
* **Git & GitHub** — Version control and project documentation

---

## 🔄 Project Workflow

### 1. Data Loading & EDA

Loaded the dataset into Python using Pandas and performed initial exploration using:

* `df.info()`
* `df.describe()`
* Null-value analysis
* Data structure and consistency checks

### 2. Data Cleaning

The following preprocessing steps were performed:

* Handled missing review ratings using the **median rating of each product category**
* Standardized column names using `snake_case`
* Created an `age_group` feature
* Created `purchase_frequency_days`
* Checked redundancy between discount and promo-code fields
* Removed the redundant `promo_code_used` column

### 3. SQL Analysis

The cleaned data was loaded into **MySQL** for business analysis.

Key questions answered included:

* Revenue by gender
* High-spending customers using discounts
* Top-rated products
* Standard vs. Express shipping performance
* Subscribers vs. non-subscribers
* Products most dependent on discounts
* Customer segmentation
* Top 3 products within each category
* Repeat buyers and subscription behavior
* Revenue by age group

### 4. Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize the major findings and make the analysis easier for business stakeholders to explore.

### 5. Business Report & Presentation

The analysis was documented in a business report and converted into a presentation using **Gamma** to communicate the key findings and recommendations.

---

## 📈 Dashboard

The Power BI dashboard provides an interactive view of:

* Customer spending
* Revenue trends
* Product performance
* Customer segments
* Subscription behavior
* Discount usage
* Age-group performance
* Shipping insights


---

## 💡 Key Insights & Recommendations

The analysis resulted in several business recommendations:

* **Boost subscriptions** by providing exclusive subscriber benefits.
* **Strengthen loyalty programs** to convert repeat buyers into loyal customers.
* **Review discount strategies** to balance sales growth with margin control.
* **Promote top-rated and best-selling products** in marketing campaigns.
* **Use targeted marketing** toward high-revenue age groups and relevant shipping segments.

---

## 📂 Project Files

- `Python Notebook` — Data loading, EDA and data cleaning
- `SQL Queries` — Business analysis using PostgreSQL
- `Power BI Dashboard` — Interactive visualization
- `Project Report` — Detailed analysis and recommendations
- `Presentation` — Business presentation created using Gamma

---

## 🎯 Skills Demonstrated

**Python • Pandas • EDA • Data Cleaning • MySQL • Power BI • Data Visualization • Business Analysis • Customer Segmentation • KPI Analysis • Data Storytelling**

---

