# Customer_Shopping_Behavior_Analysis
data analytics project showcasing customer behavior analysis using python, sql and power BI.

# 📊 Data Analytics Project

## 📌 Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from dataset loading and data cleaning to SQL analysis, interactive dashboard creation, reporting, and presentation.

The project uses **Python for data analysis and EDA, PostgreSQL for SQL-based analysis, Power BI for visualization, and Gamma for presentation creation**.

The main objective is to transform raw data into meaningful insights that can support better business understanding and decision-making.

## 📂 Dataset

The project uses a structured dataset containing relevant business/data records.

The dataset is:

* Loaded and explored using Python
* Cleaned and prepared for analysis
* Stored/processed for SQL analysis using PostgreSQL
* Used to create visualizations and dashboards in Power BI

**Dataset file:** `data/customer_shopping_behavior.csv`

## 🛠️ Tools & Technologies

| Tool / Technology        | Purpose                             |
| ------------------------ | ----------------------------------- |
| **Python**               | Data loading, cleaning and analysis |
| **Pandas**               | Data manipulation                   |
| **NumPy**                | Numerical operations                |
| **Matplotlib / Seaborn** | Data visualization                  |
| **Jupyter Notebook**     | EDA and analysis                    |
| **PostgreSQL**           | SQL queries and database analysis   |
| **Power BI**             | Interactive dashboard               |
| **Git & GitHub**         | Version control and project sharing |


## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading using Python
     ↓
Data Cleaning & Preprocessing
     ↓
Exploratory Data Analysis (EDA)
     ↓
Load Data into PostgreSQL
     ↓
SQL Queries & Analysis
     ↓
Power BI Dashboard
     ↓
Insights & Report
```

## 🚀 Project Steps

### 1. Data Loading

The dataset is loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("data/customer_shopping_behavior.csv")

print(df.head())
print(df.shape)
print(df.info())
```

The initial analysis includes:

* Number of rows and columns
* Data types
* Missing values
* Duplicate records
* Basic statistical information

### 2. Data Cleaning

The raw dataset is cleaned and prepared for further analysis.

Major cleaning steps include:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Handling inconsistent values
* Renaming columns where required
* Treating outliers where appropriate
* Preparing clean data for SQL and visualization

### 3. Exploratory Data Analysis (EDA)

EDA is performed using Python to understand patterns, relationships, and trends in the dataset.

The analysis includes:

* Descriptive statistics
* Univariate analysis
* Bivariate analysis
* Correlation analysis
* Distribution analysis
* Trend analysis
* Data visualization

Example:

```python
df.describe()
```

Visualizations are created using **Matplotlib and Seaborn** to identify important patterns and relationships.


### 4. PostgreSQL & SQL Analysis

The cleaned dataset is loaded into a **PostgreSQL database**.

SQL queries are used to perform structured analysis and answer important business questions.

Example:

```sql
SELECT category,
       COUNT(*) AS total_records
FROM dataset
GROUP BY category
ORDER BY total_records DESC;
```

SQL analysis includes:

* Filtering
* Aggregation
* GROUP BY
* ORDER BY
* JOIN operations
* Subqueries
* CASE statements
* Aggregate functions
* Business-oriented queries


## 📊 Power BI Dashboard

An interactive dashboard is created using **Microsoft Power BI**.

The dashboard presents important KPIs, trends, comparisons, and patterns identified during the analysis.

### Dashboard Features

* KPI cards
* Charts and graphs
* Category-wise analysis
* Trend analysis
* Filters and slicers
* Interactive visualizations
* Summary of key insights

### Dashboard Preview
<img width="621" height="338" alt="image" src="https://github.com/user-attachments/assets/597ea6a9-c4b3-455e-b72a-c17f6b4104c1" />


## 📈 Key Results & Insights

The analysis of 3,900 customer records provided the following key insights:

- **Total Customers:** 3,900
- **Average Purchase Amount:** approximately **$59.76**
- **Average Review Rating:** approximately **3.75**
- **Clothing** is the highest-performing category in terms of both sales volume and revenue.
- **Accessories** is the second-highest-performing category based on the dashboard analysis.
- **Young Adult** customers contribute the highest revenue among the analyzed age groups.
- Customer purchasing behavior was analyzed across **gender, category, age group, subscription status, shipping type, and discount usage**.
- SQL analysis was used to identify customers who used discounts while spending at or above the average purchase amount. :contentReference[oaicite:0]{index=0}
- Product performance was analyzed using **average review ratings** and purchase counts. :contentReference[oaicite:1]{index=1}
- Customers were segmented into **New, Returning, and Loyal** groups based on their previous purchases. :contentReference[oaicite:2]{index=2}
- The analysis also examined **subscription behavior among repeat buyers** and revenue contribution across different age groups. :contentReference[oaicite:3]{index=3}

### Business Analysis Areas

The project provides a structured view of:

- Category-wise sales and revenue
- Customer age-group contribution
- Subscription behavior
- Discount usage
- Product ratings
- Shipping preferences
- Repeat customer behavior
- Customer segmentation


## 📝 Report

A detailed report was prepared to document the complete analytics process.

The report covers:

1. Project Objective
2. Dataset Description
3. Data Cleaning
4. Exploratory Data Analysis
5. SQL Analysis
6. Power BI Dashboard
7. Key Insights
8. Conclusion


## 📁 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   └── your_dataset.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── sql/
│   └── analysis.sql
│
├── dashboard/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

## ▶️ How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/data-analytics-project.git
```

### Step 2: Navigate to the Project

```bash
cd data-analytics-project
```

### Step 3: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/EDA.ipynb
```

and run the cells sequentially.

### Step 5: PostgreSQL Analysis

1. Install PostgreSQL.
2. Create a database.
3. Import the cleaned dataset.
4. Execute the SQL queries from:

```text
sql/analysis.sql
```

### Step 6: Power BI

Open:

```text
dashboard/dashboard.pbix
```

in Power BI Desktop.

If required, update the database/data source connection.


## 🎯 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analytics
* Python
* Pandas
* Exploratory Data Analysis
* Data Cleaning
* SQL
* PostgreSQL
* Data Visualization
* Power BI
* Dashboard Development
* Business Intelligence
* Report Writing
* Data Storytelling


## 💡 Conclusion

This project demonstrates an end-to-end approach to solving a data analytics problem by combining **Python, SQL, PostgreSQL, Power BI, and presentation tools**.

The workflow transforms raw data into cleaned information, analytical insights, interactive visualizations, and a final business-oriented presentation.

---

## 👩‍💻 Author

**Pranjali Pawar**

B.Tech – Information Technology
