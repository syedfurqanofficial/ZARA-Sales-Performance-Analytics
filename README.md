Project Explanation: ZARA Sales Performance Analysis

This set of files presents a detailed analytical project focused on the sales performance of ZARA, a retail fashion brand. The project’s goal is to extract actionable business intelligence from sales data to understand product performance, seasonal trends, the effectiveness of promotions, and the impact of store layout and product attributes on sales.

The work is structured into two key documents: a comprehensive analytical report and the underlying SQL code used to generate the insights.

1. Untitled document.pdf (Analytical Report)
This is the formal business report that presents the findings in a structured, narrative format. It begins with an introduction and clearly states the objectives: to analyze sales trends, identify high-revenue products, and provide actionable recommendations for marketing and inventory strategies.

The report then systematically presents the analysis, starting with a high-level summary of annual performance: ZARA sold over 22 million units, generating approximately PKR 884.60 million in revenue.

It proceeds with specific insights:

- It lists the top 10 and bottom 10 best-selling products, identifying clear winners and underperformers in the portfolio.
- It reveals that **Autumn is the highest-selling season**, followed by Winter, providing crucial data for seasonal inventory planning.
- It assesses promotion effectiveness, noting a positive but not dramatic sales lift during promotional periods, suggesting promotions work but may need optimization.
- A significant portion of the analysis is dedicated to **product placement**. It ranks top-selling items in key store positions like Aisle, End-cap, and Front of Store, demonstrating how shelf placement directly influences sales volume. For instance, products placed at End-caps and the Front of Store achieve high visibility and sales.
- It analyzes customer preference by **material** (Wool and Cotton are top choices) and product **origin**, giving insights into sourcing and design preferences.
- Finally, it isolates **high-value products priced above 130** to understand their contribution to total revenue, highlighting which expensive items are the most profitable.

The report concludes with strategic recommendations: focus marketing on high-revenue products, ensure stock availability for top sellers, use placement strategies to boost visibility, and leverage insights on materials and seasons for product development and promotions.

2. zara_business_sales_.sql (SQL Analysis Script)
   
This is the technical engine behind the report. The script starts by creating a database and a detailed table schema that captures all necessary dimensions: product ID, name, price, sales volume, promotion status, product position in store, season, material, and origin.

It then executes a series of SQL queries, each designed to answer a specific business question from the report:

- Queries 1 & 2 calculate total performance and identify top/bottom selling products by units sold.
- Query 3 analyzes seasonal sales trends.
- Query 4 evaluates promotion effectiveness by comparing sales volume with and without promotions.
- Queries 5 & 6 use advanced ranking logic (with variables like `@rank`) to list the top 10 products within specific store positions (`Aisle`, `Front of Store`). This technical approach allows for precise in-category ranking.
- Queries 7 & 8 summarize sales by material and origin.
- Queries 9 & 10 calculate revenue per product and specifically analyze high-value products (price > 130), showing their individual revenue and percentage contribution to the total.

**In essence, this project demonstrates a complete data-to-insight workflow for retail analytics. The SQL script performs the heavy lifting of data aggregation and calculation, while the report translates those numbers into a clear business narrative. Together, they provide ZARA with a data-backed foundation to optimize product assortment, inventory planning, in-store merchandising, and promotional strategies to drive sales and profitability.**
