# Data Cleaning Process
Before performing the analysis, the dataset was cleaned and standardized to ensure accuracy and consistency.
## Steps performed:
### 1. Removed duplicates
- Identified and removed duplicate records to avoid double counting and ensure data integrity.
### 2.	Standardized text values
Used Find & Replace (Ctrl + H) to correct inconsistent naming:
- "IT" → "Insta Tag"
- "Neon" → "Neon Sign"
### 3.	Formatted text consistency
- Applied the =PROPER() function to ensure all text values follow proper capitalization (first letter uppercase).
### 4.	Corrected spelling errors
- Used filters to identify and fix incorrect values such as "Bussines" → "Business".
### 5.	Removed extra spaces
- Applied the =TRIM() function to eliminate leading, trailing, and extra spaces between words.
### 6.	Adjusted data types
- Converted numeric columns from Currency format to Number format for accurate calculations and analysis.
### Result:
The dataset became clean, consistent, and ready for further analysis and visualization.

# Data Analysis
After cleaning the dataset, additional calculated fields were created to enhance analysis and extract meaningful insights.
Steps performed:
### 1. Revenue calculation
- Created a new column to calculate total revenue for each transaction. (=L2*K2)
### 2. Profit calculation
- Calculated profit using the formula:
- Profit = Revenue - Unit Cost (=N2-(M2*K2))
### 3. Customer segmentation by age
#### Used the =IF function to group customers into three categories:
=IF(I2<=35,"Young",IF(I2<=49,"Middle Age",IF(I2>=50,"Old")))
- Young
- Middle Age
- Old
This segmentation helps analyze customer behavior across different age groups.
4. Time-based analysis (Month column)
Extracted the month from the order date to simplify time-based analysis and identify trends over time.
Result
These transformations enabled deeper analysis of sales performance, customer segmentation, and monthly trends.






📊 Key Insights & Findings
In this project, I conducted a comprehensive sales analysis of a sign business using Excel, focusing on product performance, regional distribution, customer behavior, and revenue trends.
1. Product Performance
Neon signs were the primary revenue driver, generating a total of $4,123,675 over the year.
Insta tag contributed significantly less, with total revenue of $453,418.
Conclusion:
The business is highly dependent on neon signs as its core product, indicating a strong product-market fit in this category.
2. Regional Analysis
The highest number of orders came from Western Ukraine, followed by Southern, Eastern, Central, and Northern regions.
In terms of profitability:
•	Western region was the most profitable 
•	Northern region showed the weakest performance 
Conclusion:
The Western region is the key market for the business, while the Northern region may require additional marketing efforts or strategic improvements.
3. Sales Channels & Customer Behavior
Revenue by channel:
•	Website – highest revenue 
•	TikTok 
•	Referral 
•	Instagram – lowest revenue among channels 
Additionally, the dataset shows no repeat purchases, meaning each customer made only one order.
Conclusion:
•	The website is the most effective sales channel and should remain the primary focus. 
•	The absence of repeat customers highlights a major growth opportunity.
Implementing retention strategies (e.g., discounts, loyalty programs, or follow-up campaigns) could significantly increase revenue. 
4. Customer Demographics
Across all age groups (young, middle-aged, and older), female customers consistently made more purchases than male customers.
Conclusion:
The target audience is predominantly female, suggesting that marketing strategies should be tailored accordingly.
5. Time-Based Trends (Seasonality)
•	Neon signs performed best in March 
•	Insta tag peaked in August 
Conclusion:
Sales exhibit seasonality, and marketing campaigns should be aligned with peak months for each product category.
6. Business Type Analysis
•	Tattoo salons generated the highest revenue 
•	Retail stores contributed the least 
Conclusion:
Tattoo salons represent the most valuable customer segment, and the business could benefit from focusing more on this niche while reassessing its strategy for retail clients.
Overall Conclusion
This analysis reveals key revenue drivers, high-performing regions, and customer behavior patterns.
The business shows strong performance in specific segments (neon signs, Western region, tattoo salons) but also has clear opportunities for growth, particularly in customer retention and underperforming regions/channels.
 


<img width="468" height="661" alt="image" src="https://github.com/user-attachments/assets/28e75a84-9e76-4ad5-8ceb-bec2fd250aee" />
