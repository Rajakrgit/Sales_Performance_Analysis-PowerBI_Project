# Sales_Performance_Analysis-PowerBI_Project
# 1. Project Overview
The Sales Performance Analysis project uses Microsoft Power BI to examine sales performance, profitability, product contribution, customer behaviour, regional performance and product returns. The report is organised into three interactive pages:

• Sales Overview – headline business KPIs, monthly sales trend, annual sales, category contribution, regional performance and top products.

• Customer & Regional Analysis – sales by country, gender, occupation and education level, customer income analysis and returns.

• Product & Category Analysis – product colour distribution, category-wise sales and profit, product-level sales versus profit, and a detailed product performance table.

# 2. Business requirements
• Track sales, profit, customers, orders, quantity and profit margin.

• Compare monthly and yearly sales performance.

• Identify high-performing regions, countries, categories and products.

• Analyse customer sales by gender, occupation, education and income.

• Monitor product returns and return rate.

• Provide interactive filters and detailed product-level analysis.

# 3. Tools & Technologies
• Power BI Desktop: data modelling, visuals, slicers and report pages.

• DAX: reusable calculations such as Total Sales, Total Profit, Total Orders, Profit Margin and Return Rate.

• Power Query: data preparation and data-type management, where applied.

# 4. Challenges Faced
• Connecting multiple fact and dimension tables without duplicating sales.

• Defining distinct order/customer counts and profit margin consistently.

• Calculating return rate with a clearly defined numerator and denominator.

• Ensuring calendar relationships and month sorting work correctly.

• Checking geographic labels because the Top 5 visual appears to mix country and subregion names.

• Investigating the large NA product-colour group.

• Keeping a dense dashboard readable and easy to navigate.

# 5. Key Business Insights
• Category concentration: Bikes contribute about 23.64M (94.89%) of displayed category sales. Accessories contribute about 0.91M (3.64%); Clothing contributes the small remainder.

• Monthly trend: Sales rise toward May–June, drop sharply in July and recover in December. Exact monthly values are not printed in the screenshot.

• Yearly trend: The chart shows 2016 and 2017 sales above 2015; confirm exact amounts in the report.

• Country performance: United States and Australia are the leading countries in the Sales by Country chart.

• Gender split: Female sales are 12.52M (50.23%); male sales are 12.24M (49.14%); NA is 0.16M (0.63%).

• Customer profile: Professional is the largest occupation group, and Bachelor's is the leading education category in the displayed visuals.

• Product colour: NA is the largest displayed group at about 51K (60.68%). Its meaning should be checked.

• Returns: The dashboard displays approximately 2K returns and a 2.17% return rate.

# 6. Recommendations
• Reduce dependence on Bikes by exploring relevant Accessories and Clothing bundles and cross-selling.

• Investigate the July decline using order volume, stock availability, discounts and marketing activity.

• Review products with strong sales but weak margins; examine price, cost and discounting.

• Monitor product-level return rates, not only total return count.

• Standardise country, territory and region fields.

• Investigate missing or not-applicable product attributes represented by NA.

• Add sales targets, year-over-year growth and monthly variance reporting.
