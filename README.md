# RETAIL-SALES-AND-CUSTOMER-ANALYSIS
# Executive Summary
This analysis reviewed sales data from 1,000 recorded transactions. The results show that Electronics, Clothing, and Beauty are the top-performing categories, contributing most to total revenue. Monthly sales trends reveal fluctuations across different periods, suggesting uneven demand throughout the year. Demographic patterns show that purchases are concentrated within specific age groups, indicating that certain customer segments drive most of the sales.
The dataset records one unique customer per transaction, meaning there is no evidence of repeat buyers. This limits the ability to assess customer loyalty or long-term purchasing behaviour.
# Key recommendations include:
1.	Focus marketing and promotional efforts on high-revenue categories (Electronics, Clothing, and Beauty).
2.	Introduce a customer identification system to track repeat buyers and build loyalty programs.
3.	Run targeted marketing campaigns based on age and gender to reach high-value segments.
4.	Develop a simple operational dashboard to monitor monthly sales, product performance, and key performance indicators (KPIs).
These steps will help the business make better data-driven decisions, improve sales consistency, and strengthen customer relationships.
# Data Understanding
The analysis used a dataset named retail_sales_dataset.csv, which contains detailed information on customer purchases across different product categories. The dataset serves as the primary source for understanding sales patterns, customer demographics, and product performance. The dataset was compiled from point-of-sale transaction records of the business. It captures sales activity across several months.
The key metrics are:
•	Number of records: 1000
•	Number of customers: 1,000
•	Number of Columns: 10
•	Key fields: Customer ID, Age, Product Category, Total Amount
# Methodology 
# Data Cleaning
The data was cleaned and prepared by checking for duplicates, missing values and date standardisation to ensure accuracy, consistency, and readiness for analysis. Each step focused on improving data quality for better insights into sales trends and customer behaviour. After these cleaning steps, the dataset became structured, consistent, and ready for deeper analysis through PivotTables, charts, and forecasting models.
<img width="2704" height="562" alt="data Claeann" src="https://github.com/user-attachments/assets/26ef1cb1-c0bf-404b-974e-89dcf528c24f" />
# Feature engineering 
A new column (Age group) was introduced to include the age range of customers
# Data Exploration
PivotTables were used to explore key relationships in the dataset to summarise sales by product, gender, month, age category and their related quantities
Data analysis Techniques: Formula segmentation
# Visualisation: 
A dashboard with pivot charts was created to explain and show the KPIs.
•	KPI Cards for total revenue, customers, units sold, and average age.
•	Bar Charts comparing quantity and revenue by product category and gender.
•	Line Chart showing monthly revenue fluctuations.
•	Category and Age Segment Charts showing demographic contributions.
<img width="3479" height="3108" alt="DASHBOARD PIC" src="https://github.com/user-attachments/assets/8c24953c-e3b2-4b22-be17-13991264eb3b" />
# Data Analysis 
# Revenue Performance
Total revenue reached GHS 456,000 across 2,514 units sold to 1,000 customers. The Young Adult category generated the highest revenue at GHS 242,655 (53.2%), followed by Youth at GHS 123,155 (27.0%) and Adult at GHS 90,190 (19.8%).
Female customers contributed GHS 232,840 (51.1% of total revenue), while male customers accounted for GHS 223,160 (48.9%). This distribution indicates near-equal purchasing power between genders.
Product Category Analysis
Beauty products dominated revenue generation at GHS 143,515, representing 31.5% of total sales. Electronics contributed GHS 156,905 (34.4%), while Clothing generated GHS 155,580 (34.1%). The three categories show balanced revenue distribution with no single dominant product line.
In terms of units sold, Clothing led with 894 units (35.6% of total stock), followed by Electronics at 849 units (33.8%) and Beauty at 771 units (30.7%). Average revenue per unit varies significantly: Electronics at GHS 184.81, Clothing at GHS 174.04, and Beauty at GHS 186.14.
# Gender and Product Preferences
Female customers purchased 1,298 units (51.6% of total volume), with strong concentration in Beauty (418 units, 32.2%) and Clothing (441 units, 34.0%). Male customers bought 1,216 units (48.4% of total), showing a preference for Electronics (410 units, 33.7%) and Clothing (453 units, 37.3%).
Gender differences appear in product category revenue. Females generated GHS 81,275 in Clothing, GHS 74,830 in Beauty, and GHS 76,735 in Electronics. Males contributed GHS 74,305 in Clothing, GHS 68,685 in Beauty, and GHS 80,170 in Electronics. Males spent more on Electronics while females led in Clothing and Beauty purchases.
# Age Segment Performance
The Young Adult segment generated GHS 242,655 from 1,374 units sold (average GHS 176.61 per unit). This segment contributed 54.7% of total units and 53.2% of total revenue, making it the primary customer group.
The youth segment produced GHS 123,155 from 625 units (average GHS 197.05 per unit). Adult segment yielded GHS 90,190 from 515 units (average GHS 175.13 per unit). Youth customers show the highest average transaction value despite lower volume.
Product preferences vary by age. Young Adults purchased 491 Clothing units, 413 Beauty units, and 470 Electronics units. Youth bought 214 Clothing units, 215 Beauty units, and 196 Electronics units. Adults acquired 189 Clothing units, 143 Beauty units, and 183 Electronics units.
# Temporal Patterns
Monthly revenue ranged from GHS 23,620 (September) to GHS 53,150 (May), representing a 125% difference between the lowest and highest months. The top five revenue months were May (GHS 53,150), October (GHS 46,580), December (GHS 44,690), February (GHS 44,060), and January (GHS 36,980).
Unit sales per month varied from 170 units (September) to 259 units (May). High-volume months included May (259 units), October (252 units), August (227 units), February (214 units), and April (214 units).
September represents a critical low point, recording both the lowest revenue and the lowest unit sales. This month generated only 52.6% of May's revenue and 65.6% of May's unit volume.
# Age Segment Temporal Performance
Young Adult segment showed consistent monthly contributions, with peaks in June (GHS 26,790), May (GHS 26,790), and October (GHS 23,915). The youth segment peaked in January (GHS 41,400), March (GHS 18,730), and February (GHS 18,730). The adult segment reached its highest revenue in February (GHS 20,670), October (GHS 13,320), and May (GHS 14,330).
January demonstrates strong Youth segment performance at GHS 20,670 Adult, GHS 81,445 Young Adult, and GHS 41,400 Youth revenue. February shows Adult segment strength with GHS 4,630 Adult revenue compared to other months.
# Decision-Making and Recommendations 
Based on the analysis of revenue performance, customer demographics, product preferences, and seasonal trends, several key business decisions can be made to strengthen sales, improve marketing focus, and enhance operational planning. The findings reveal clear behavioural patterns among customers and provide a practical foundation for informed decision-making.
# Focus on the Young Adult Segment
The analysis shows that Young Adults (25–40 years) are the most consistent contributors to both revenue and units sold, accounting for 53.2% of revenue and 54.7% of total sales volume. This group demonstrates strong engagement across multiple categories, particularly in Clothing and Electronics. The business should therefore prioritise marketing and promotional efforts toward Young Adults. Personalised promotions, loyalty programs, and lifestyle-focused messaging will be effective. Product bundles that mix Clothing, Electronics, and Beauty items can further increase average transaction values within this segment.
# Tailor Marketing by Gender
Gender-based analysis revealed that spending is nearly balanced between males and females, but purchasing patterns differ. Female customers show stronger preferences for Beauty and Clothing, while male customers purchase more Electronics. Marketing efforts should reflect these preferences. Gender-specific campaigns can be used—for instance, beauty tutorials and fashion content for females, and technology-focused ads or product demonstrations for males. Advertising budgets should be allocated proportionally based on each gender’s category performance to maximise returns on marketing investment.
# Optimise Product Strategy
All three product categories—Electronics, Clothing, and Beauty—perform well, but the Beauty category records the highest average revenue per unit. This suggests a higher profit margin potential. The business should therefore expand its Beauty product line and promote high-margin items. Introducing premium or limited-edition products in all three categories could help raise average transaction values. Additionally, stock levels should be closely monitored to maintain a balanced product mix and prevent shortages during high-demand periods.
# Address Seasonal Fluctuations
Monthly sales trends revealed strong peaks in May, October, and December, with a significant dip in September. To address these fluctuations, the business should maintain high inventory levels and stronger promotions during peak months, while using September for clearance or back-to-school campaigns. Strategies like “End of Season Sales” can boost revenue during slower months. Insights from peak months should also guide planning for future promotional calendars and stock management.
# Leverage the High-Spending Youth Segment
Although the Youth segment (18–24 years) buys fewer items, it records the highest average spending per unit, especially in Electronics. This group is price-tolerant and trend-driven. The company should introduce premium and trendy product options, particularly in Electronics, and market them through digital channels popular among young audiences, such as TikTok and Instagram. Positioning high-end Electronics and fashion products as “must-have” lifestyle items could drive stronger engagement from this segment.
# Align Inventory and Promotions with Temporal Patterns
Sales and revenue vary significantly month to month. The business should use historical sales data to forecast demand and adjust inventory accordingly. Peak months (May, October, and December) are ideal for launching new products or running major campaigns. During low-demand months, dynamic pricing or targeted discounts could sustain sales momentum. This data-driven inventory planning will minimise overstocking and stockouts while improving cash flow efficiency.
# Enhance Customer Retention Strategies
The average customer age of 41 suggests a mature and potentially loyal customer base. To strengthen retention, the business should implement loyalty programs, exclusive previews, or personalised discounts for repeat buyers. Regular engagement through email newsletters or mobile notifications can help maintain long-term relationships and increase repeat purchases.
# Conclusion
The findings show that business growth depends on understanding customer behaviour and aligning operations with real demand patterns. Young Adults and female customers are the most profitable segments, while Electronics, Beauty, and Clothing remain key product drivers. Sales fluctuate seasonally, peaking in May, October, and December, which calls for proactive inventory and marketing planning.
By adopting data-driven decisions targeting high-value customers, tailoring marketing by gender, expanding profitable products, and improving inventory forecasting, the business can improve both efficiency and profitability. Strengthening customer retention and enhancing data tracking systems will also create a foundation for sustainable, long-term growth.
