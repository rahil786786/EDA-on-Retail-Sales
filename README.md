🛍️ Retail Sales Dataset - Exploratory Data Analysis (EDA)

📌 Project Overview  
This project performs an in-depth Exploratory Data Analysis (EDA) on a retail sales transaction dataset. The goal is to understand sales performance, customer behavior, product trends, and profitability to derive actionable business insights.

📊 Dataset Information  
- **Entries**: 73,547  
- **Variables**: 18  
- **Data Types**:  
  - Numerical Variables: 8  
  - Categorical Variables: 10  
  - DateTime Variable: 1 (order_date)  

📂 Columns Include:  
- `order_id`, `customer_id`, `branch`, `product_category`, `product_model`  
- `unit_cost`, `unit_price`, `quantity`, `shipping_cost`, `discount`  
- `payment_method`, `sales_channel`, `return_status`, `loyalty`  
- **Derived Columns**: `Total_Sales`, `Total Cost`, `Profit`  

✅ Data Quality:  
- No missing values  
- No duplicates  
- Proper data types  
- Unique `order_id` values  

🔍 EDA Steps Included:  
- Data loading and inspection  
- Descriptive statistics (mean, min, max, quartiles)  
- Derived metric calculations:  
  - Total Sales = unit_price × quantity  
  - Total Cost = unit_cost × quantity  
  - Profit = Total Sales – Total Cost  
- Univariate analysis (e.g., unit_cost distribution)  
- Unique value analysis per column  

📈 Key Insights (Preliminary):  
- The dataset is clean and structured appropriately for analysis.  
- Profit metrics have been successfully derived.  
- Initial univariate analysis shows right-skewed distributions (e.g., unit_cost).  
- Further analysis will explore trends over time, product performance, and customer segments.  

🛠️ Tools & Libraries Used:  
- Python  
- Pandas – Data manipulation  
- NumPy – Numerical operations  
- Matplotlib & Seaborn – Visualization (plots not shown in provided snippet)  

📅 Next Steps:  
- Time series analysis of sales  
- Multivariate analysis (e.g., by product category, branch)  
- Correlation analysis  
- Visualization of sales channels, payment methods, and loyalty effects  

This EDA lays the foundation for deeper business intelligence and data-driven decision-making in retail operations.
