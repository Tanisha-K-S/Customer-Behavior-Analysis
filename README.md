# 🛍️ Customer Shopping Behavior Analysis  

## 📘 Overview  
This project analyzes **customer shopping behavior** using transactional data to uncover insights into **spending patterns, product preferences, subscription trends, and customer segments**.  
It integrates **Python (EDA)**, **PostgreSQL (SQL analysis)**, and **Power BI (dashboard visualization)** to deliver actionable insights that support data-driven business decisions.  

---

## 📊 Dataset  
**Source:** Simulated transactional dataset of 3,900 customer purchases  

**Size:**  
- Rows: 3,900  
- Columns: 18  

**Key Features:**  
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Amount, Season, Size, Color  
- **Behavioral Data:** Discount Applied, Promo Code Used, Review Rating, Shipping Type, Frequency of Purchases  

**Missing Values:**  
- 37 missing values in the *Review Rating* column were imputed using the median category rating.  

---

## 🧰 Tools & Technologies  
| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy, Matplotlib)** | Data loading, cleaning, and exploratory analysis |
| **PostgreSQL** | Business-level SQL queries |
| **Power BI** | Dashboard creation and visualization |
| **MS PowerPoint / Report** | Final presentation and documentation |

---

## ⚙️ Steps Followed  

### 1. **Data Loading & Cleaning (Python)**  
- Imported dataset using `pandas`  
- Handled missing values and standardized column names  
- Created new features such as `age_group` and `purchase_frequency_days`  
- Removed redundant columns (e.g., `promo_code_used`)  
- Exported cleaned data to **PostgreSQL** for structured analysis  

### 2. **Exploratory Data Analysis (EDA)**  
- Used `describe()` and `info()` for initial exploration  
- Visualized purchase trends by gender, category, and season  
- Analyzed distributions of ratings, discounts, and shipping types  

### 3. **SQL Analysis (PostgreSQL)**  
Performed queries to answer key business questions, such as:  
- 💰 *Revenue by Gender* – male vs. female contribution  
- 🛒 *Top 5 Products by Rating*  
- 🚚 *Standard vs. Express Shipping Comparison*  
- 🎯 *Subscribers vs. Non-Subscribers* – revenue & frequency comparison  
- 💡 *Customer Segmentation* – New, Returning, Loyal  
- 🧾 *Revenue by Age Group*  

### 4. **Dashboard Development (Power BI)**  
Created an interactive dashboard with:  
- Revenue breakdown by gender, category, and location  
- Subscription vs. non-subscription comparison  
- Discount and shipping insights  
- Top products and category performance  

### 5. **Reporting & Presentation**  
- Documented all insights in a **comprehensive report (PDF)**  
- Summarized key findings and business recommendations in a **PowerPoint presentation**  

---

## 📈 Key Results & Insights  
- **Subscribers** spent more and purchased more frequently than non-subscribers.  
- **Express shipping** correlated with higher spending.  
- **Top-rated products** were also the most frequently purchased.  
- **Discounts** boosted sales but reduced margins; a balanced strategy is needed.  
- **Loyalty programs** can effectively retain and convert returning customers.  

---

## 🖥️ How to Run  

### 1. **Clone the Repository**
git clone https://github.com/yourusername/customer-shopping-behavior.git
cd customer-shopping-behavior

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run the Python Script
python eda_analysis.py

### 4. Load Data into PostgreSQL
Edit your credentials in the script:
engine = create_engine("postgresql+psycopg2://username:password@localhost:5432/database_name")

### 5. Execute SQL Queries
Use pgAdmin / DBeaver to run sql_queries.sql for analysis.

### 6. View Power BI Dashboard
Open Customer_Shopping_Behavior.pbix in Power BI Desktop.

## 🏁 Conclusion

This project demonstrates an end-to-end data analytics workflow, from raw data handling to actionable insights through Python, SQL, and Power BI.
It highlights strong analytical thinking, visualization expertise, and business understanding—ideal for Data Analyst, BI Analyst, or Data Science roles.
git clone https://github.com/yourusername/customer-shopping-behavior.git
cd customer-shopping-behavior
