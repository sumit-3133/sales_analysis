# SALES ANALYSIS

### OBJECTIVE -

To optimize sales and profitability by leveraging insights from historical performance, with a particular focus on maximizing high-performing areas and addressing underperforming segments.

### ABOUT DATASET - 

Sourced directly from Kaggle, this dataset provides a rich collection of sales records. It features detailed columns covering order and shipping specifics, customer demographics, product classifications (Category, Sub-Category, Product Name), geographical locations (Country, City, State, Region), and critical financial data (Sales, Quantity, Discount, Profit).

![Screenshot 2025-06-29 165236](https://github.com/user-attachments/assets/d4961cd6-c611-4a80-9bd2-22ef5c532eb1)

### GOAL - 
This project aims to drive sustainable business growth by leveraging data-driven insights to optimize our sales and product profitability, while simultaneously enhancing customer satisfaction. We're focusing on identifying and maximizing our highest-selling and most profitable products and categories, with a keen eye on capitalizing during peak periods like November and December. Concurrently, we're developing strategies to mitigate dips in February sales and January profitability. A core component of our approach involves understanding and acting on customer sentiment through continuous analysis of feedback, allowing us to refine our offerings and improve the overall customer experience. Ultimately, this project is about using smart data analysis to make better, faster business decisions that boost both our bottom line and customer loyalty.

KEY QUESTION EXPORED -
1. Which month has the highest and lowest sales?
2. What is the sales performance ranking from highest to lowest category bias?
3. Which product has the highest sales as per the sub-category?
4. Which month is profitable for the owner?
5. Which category make the highest profit?
6. Which customer segment has the highest sale?

### TECHNOLOGY USED - 
1. Python (Pandas)
2. Plotly (Visulization)

![Screenshot 2025-06-29 171643](https://github.com/user-attachments/assets/eabba270-a4c7-490a-b03a-ec2c3e9a04ae)


### INSIGHT / RESULT
1. The line plot illustrates the sales trends over the 12 months (presumably of a year):
Highest Sales Month: Sales peak notably around November (Month 11), reaching over $350,000.
Lowest Sales Month: February (Month 2) records the lowest sales, falling below $100,000.
Fluctuations: Sales show significant fluctuations, with another local peak around September (Month 9) and a dip around April (Month 4). This suggests seasonality in sales performance.

 ![Screenshot 2025-06-29 165556](https://github.com/user-attachments/assets/ccb378cc-58e6-4155-b800-d09c781af605)

 2. This table provides a precise breakdown of total sales per major product category:
Technology: Leads significantly with sales totaling $836,514.033.
Furniture: Ranks second with total sales of $741,999.793.
Office Supplies: Has the lowest sales among the three categories at $718,947.082.
This directly quantifies the sales dominance of Technology.

![Screenshot 2025-06-29 165631](https://github.com/user-attachments/assets/b578a7d4-4026-4ad0-b25c-d350afb2abea)
![Screenshot 2025-06-29 165652](https://github.com/user-attachments/assets/93ec0ddc-f417-4b57-a47c-480a03ec822c)

3. This bar chart offers a granular view of sales performance across various sub-categories:
Top-Performing Sub-Categories: Phones and Chairs are clearly the highest-selling sub-categories, both exceeding $300,000 in sales.
Strong Performers: Other strong contributors include Binders, Storage, Tables, and Accessories, each with sales generally above $150,000.
Low-Performing Sub-Categories: Sub-categories like Fasteners, Envelopes, Labels, and Copiers show very low sales volumes, some barely crossing $10,000.
This analysis highlights specific products or product types that drive the most revenue and those that might require attention due to low sales.

![Screenshot 2025-06-29 165710](https://github.com/user-attachments/assets/60feb6b6-5a1f-4842-bf87-695547829298)

4. The line plot illustrates the profit trends over the 12 months:
Highest Profit Month: Similar to sales, profit peaks significantly in November (Month 11) and continues to rise into December (Month 12), reaching over $40,000.
Lowest Profit Month: February (Month 2) records the lowest profit, similar to sales, indicating a clear correlation.
Profit Volatility: Profit margins show considerable fluctuation throughout the year, with a notable dip around April (Month 4) and another rise in late months, mirroring the sales trends but with different magnitudes. This suggests that profitability is also subject to seasonal variations.

![Screenshot 2025-06-29 165805](https://github.com/user-attachments/assets/741a473b-b636-4120-a35f-e86dadebaa9f)

5. This donut chart provides insights into the profitability of each category:
Technology: Dominates profit generation, accounting for 50.8% of the total profit, indicating its high profitability despite not being overwhelmingly superior in sales volume.
Office Supplies: Contributes a significant 42.8% to total profit, showcasing its strong profit margins relative to its sales volume.
Furniture: Shows a remarkably low profit contribution of only 6.44%, despite being the second-highest in sales. This suggests that Furniture products have significantly lower profit margins or higher associated costs compared to Technology and Office Supplies.

![Screenshot 2025-06-29 165747](https://github.com/user-attachments/assets/a0f93512-ca33-422e-8654-f40262821a41)

6.  The Consumer segment is the most significant in terms of raw sales volume and total profit. However, observing the ratio of profit to sales across segments, while the Consumer segment brings in the most revenue, the Corporate segment appears to maintain a relatively good profit margin, making it a valuable contributor. The Home Office segment, while smaller, also contributes positively to both sales and profit. This analysis is crucial for segment-specific marketing strategies and resource allocation.

![Screenshot 2025-06-29 165823](https://github.com/user-attachments/assets/e7172ec9-bb46-4c50-8ca9-a0cd778e83f1)

### CONCLUSION - 
Our analysis reveals Technology as the leading category in both sales and, significantly, in profit. While Furniture generates high sales, its low profit contribution (6.44%) signals a key area for re-evaluation. Conversely, Office Supplies shows strong profitability despite lower sales.
Sales and profit exhibit clear seasonality, peaking in November and bottoming out in February. Phones and Chairs are key sales drivers at the sub-category level. The Consumer segment drives the highest overall sales and profit, followed by Corporate and Home Office.
In essence, the business shows strong performance, particularly in Technology, but optimizing Furniture's profitability is crucial for overall growth.


