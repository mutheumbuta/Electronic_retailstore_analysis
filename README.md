# Electronic_retailstore_analysis
## Project Overview
This capstone project analyzes sales, customer demographics, product categories, and store performance for an 

electronics retail chain. Using Excel for data cleaning and Tableau for visualization, the project delivers 

actionable insights into revenue growth, profitability, and customer segmentation.

The analysis highlights key trends, evaluates market performance, and provides strategic recommendations for 

post‑pandemic recovery and future growth.

## Problem Statement


## Methodology

### 1.Data Collection

Raw sales, customer, product, and store data consolidated into Excel (5 worksheets).

### 2. Data Cleaning (Excel)

Removed duplicates, standardized date formats, filled missing values, grouped ages into categories.

### 3. Data Loading (Tableau)

Cleaned tables imported into Tableau Desktop for relationship mapping.

### 4. Table Merging (Tableau)

Linked via relationships:

Sales ↔ Customers (Customer Key)

Sales ↔ Products (Product Key)

Sales ↔ Stores (Store Key)

### 5. Calculated Fields

Revenue, Profit, RFM Scores, Average Orders per Customer, Average Purchase per Customer.

### 6. Dashboard Development


#### Revenue & Profitability Dashboard

![Revenue dashboard](/Revenue_dashboard.png)


#### Customer segmentation dashboard

![Customer Dashboard](/customers_dashboard.png)


##  Dataset Structure

| Table     | Records | Key Fields                          | Purpose                  |
|-----------|---------|-------------------------------------|--------------------------|
| Products  | 2,517   | Product Key, Brand, Category, Price | Product catalog           |
| Customers | 11,887  | Customer Key, Age Group, Country    | Customer demographics     |
| Sales     | 62,884  | Order No, Customer Key, Product Key | Transaction-level data    |
| Stores    | 67      | Store Key, Country                  | Physical store locations  |


## Key Findings
### Revenue insights
* **Revenue Trends**: Strong growth from 2016–2019, sharp decline in 2020–2021 due to pandemic disruptions.

* **Top Category**: Computers lead in both revenue and profit.

* **Market Leader**: United States contributes nearly half of total revenue.

* **Channel Performance**: In‑store sales ($44.34M) outperform online sales ($11.4M).

### Customer Insights:

* Seniors & Middle‑aged customers generate 76.8% of revenue.

* Gender split is nearly even, showing broad appeal.

* U.S. market dominates with 6,885 customers.

## Recommendations

### 1.Grow Online Channel 

Invest in e‑commerce UX, digital marketing, and same‑day delivery.

### 2. Expand Geographic Footprint 

Target Australia and Southern Europe (Italy) for growth.

### 3.Senior Segment Strategy 

 Loyalty programs, simplified product lines, and in‑store assistance.

### 4.Focus on High‑Margin Categories –

 Cameras (60.1% margin) and TV & Video (59.7% margin).

### 5.Post‑Pandemic Recovery 

Reactivation campaigns, aggressive pricing for laptops & home electronics.

### Author
Nancy Mutheu
Github:mutheumbuta


