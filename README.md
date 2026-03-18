# Amazon E-Commerce Sales Analysis (EDA Project)

## Objective

The objective of this project is to perform an end-to-end Exploratory Data Analysis (EDA) on an Amazon-style e-commerce dataset to understand customer purchasing behavior, analyze sales performance, and extract meaningful insights that support data-driven decision-making.

---

## Dataset Description

The dataset contains approximately 98,640 transaction records with 20 features, including:

- Order details (OrderID, OrderDate, OrderStatus)
- Customer information (CustomerID, CustomerName)
- Product details (ProductID, ProductName, Category, Brand)
- Sales metrics (Quantity, UnitPrice, Discount, Tax, ShippingCost, TotalAmount)
- Payment methods (Credit Card, Debit Card, UPI, Cash on Delivery, etc.)
- Geographic data (City, State, Country)
- Seller information (SellerID)

This dataset represents realistic Amazon-style e-commerce transactions and enables comprehensive business analysis.

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Jupyter Notebook    

---

## Project Workflow

### Day 1 — Data Understanding & Profiling

The project began with exploring the dataset structure using `.head()`, `.info()`, and `.describe()`. Columns were categorized into numerical, categorical, and date types, and missing value analysis was performed. The dataset was found to be clean and well-structured, providing a strong foundation for analysis.

---

### Day 2 — Data Cleaning & Preprocessing

Data preprocessing included correcting data types, standardizing categorical variables, and handling outliers using the IQR method. Duplicate records were checked, and the dataset was prepared for analysis. The cleaned dataset was saved for further use.

---

### Day 3 — Exploratory Data Analysis (EDA)

Univariate and bivariate analyses were performed to understand patterns and relationships.

- Sales distribution was right-skewed, indicating most transactions are low-value  
- Outliers revealed high-value or bulk purchases  
- Orders were evenly distributed across categories and cities  
- Customers showed a strong preference for digital payment methods  
- A strong positive relationship was observed between quantity and total sales  
- Revenue was mainly influenced by unit price and quantity  

---

### Day 4 — Time Analysis & Statistical Testing

Time series analysis was conducted by extracting features such as year, month, and day from the order date.

- Monthly sales showed fluctuations, indicating seasonality  
- Yearly sales remained stable, showing consistent performance  

Business analysis revealed:

- Sales are evenly distributed across cities and categories  
- Digital payments dominate transactions  
- High delivery success rate with low cancellations  
- Sellers contribute equally with no dependency risk  

Statistical tests were applied:

- **T-Test:** No difference in spending between payment methods  
- **ANOVA:** No difference across categories  
- **Chi-Square:** No relationship between payment method and order status  

---

## Key Findings

- Sales follow a **right-skewed distribution**  
- Most revenue comes from **low-value transactions**  
- A small number of high-value orders contribute significantly  
- Sales are **balanced across categories, cities, and sellers**  
- Digital payments dominate customer preferences  
- Revenue is mainly driven by **quantity and unit price**  
- Business shows **seasonal patterns** but stable yearly performance  
- No statistically significant differences across key variables  

---

## Insights

The business operates on a **high-volume, low-value model**, where frequent small purchases drive revenue. A small segment of high-value customers contributes disproportionately to total sales.

Customer behavior is consistent across categories and locations, indicating a well-diversified and stable business. The strong adoption of digital payments reflects modern consumer preferences.

Seasonal trends influence sales, but the overall business remains stable. Statistical testing confirms that no single factor significantly affects sales outcomes, highlighting a balanced and unbiased system.

---

## Recommendations

- Increase **Average Order Value (AOV)** through bundling and upselling  
- Identify and retain **high-value customers** using loyalty programs  
- Promote **digital payments** with incentives and offers  
- Leverage **seasonal trends** for marketing and inventory planning  
- Optimize pricing strategies instead of relying heavily on discounts  
- Encourage **bulk purchasing behavior**  

---

## Final Conclusion

This project demonstrates a complete data analysis workflow, from data cleaning to advanced statistical validation. The analysis reveals that the Amazon e-commerce system is stable, balanced, and operationally efficient.

Sales are driven primarily by transaction volume rather than individual high-value purchases, and customer behavior remains consistent across categories, regions, and payment methods. The insights derived from this analysis can help improve pricing strategies, customer engagement, and overall business performance.

---
