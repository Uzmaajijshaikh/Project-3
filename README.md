Data Analytics Internship – Project 3 (E-Commerce Customer Segmentation – RFM Analysis)

This repository contains my submission for the E-Commerce Customer Segmentation (RFM Analysis) Project of the Data Analytics Internship.

Dataset - Online Retail Dataset

Objective - The objective was to analyze customer purchasing behavior using Recency, Frequency, and Monetary (RFM) analysis, assign RFM scores, identify customer segments, apply K-Means clustering, and develop marketing recommendations supported by an interactive Power BI dashboard.

Tools Used
1. Google Colab
2. Python (Pandas, Scikit-learn, and Matplotlib)
3. Excel
4. Power BI Desktop

E-Commerce Customer Segmentation (RFM Analysis)
1. Used the Online Retail dataset containing 541,909 records and 8 columns.
2. Inspected the dataset for missing values, duplicate records, cancelled invoices, invalid quantities, and invalid unit prices.
3. Removed records with missing required values, cancelled invoices, non-positive quantities, and non-positive unit prices.
4. Removed duplicate records and created a TotalAmount column using quantity multiplied by unit price.
5. Prepared the cleaned dataset containing 392,692 records and 9 columns.
6. Identified 4,338 unique customers for the RFM analysis.
7. Calculated Recency using the number of days since each customer's most recent purchase, Frequency using the number of unique invoices, and Monetary using total customer spending.
8. Created RFM scores from 1 to 5 for Recency, Frequency, and Monetary values and combined them into an RFM score.
9. Assigned customers to six rule-based segments: Champions, Loyal Customers, Potential Loyalists, Recent Customers, At Risk, and Lost Customers.
10. Created visualizations to analyze customer distribution by segment and the relationships between Recency, Frequency, and Monetary values.
11. Applied K-Means clustering using log-transformed RFM values, StandardScaler, and four clusters.
12. Analyzed cluster sizes, average Recency, average Frequency, average Monetary value, and total revenue.
13. Assigned business-friendly names to the four K-Means clusters based on their purchasing behavior.
14. Exported the RFM customer data, RFM segment summary, and K-Means cluster summary into an Excel workbook.
15. Developed an interactive Power BI dashboard containing four KPI cards, two customer distribution charts, and slicers for RFM segments and K-Means segments.
16. Prepared marketing recommendations for customer retention, loyalty programs, repeat purchases, cross-selling, and reactivation campaigns.

Key Results
1. Original Dataset - 541,909 records and 8 columns.
2. Cleaned Dataset - 392,692 records and 9 columns.
3. Unique Customers Analyzed - 4,338.
4. RFM Segments Identified - 6 customer segments.
5. Champions - 942 customers (21.7%).
6. At Risk Customers - 661 customers (15.2%).
7. Lost Customers - 366 customers (8.4%).
8. Potential Loyalists - 1,551 customers (35.8%).
9. K-Means Clusters Identified - 4 customer groups.
10. High-Value Loyal Customers Cluster - 713 customers, with an average monetary value of 8,088.02 per customer.
11. Inactive / At-Risk Customers Cluster - 1,622 customers, with an average recency of approximately 182 days.
12. Power BI Dashboard - Created four KPI cards for Total Customers, Total Revenue, Champions, and At Risk customers, along with two charts and two interactive slicers.

Key Insights
1. Potential Loyalists represented the largest RFM segment, with 1,551 customers, highlighting an opportunity to encourage repeat purchases and develop long-term customer loyalty.
2. Champions accounted for 942 customers and represented an important group for customer retention, VIP rewards, and referral programs.
3. The At Risk segment contained 661 customers who may benefit from targeted re-engagement and win-back campaigns.
4. The High-Value Loyal Customers cluster had the highest average monetary value and frequency, making it an important group for retention and personalized marketing.
5. The Inactive / At-Risk Customers cluster had an average recency of approximately 182 days, indicating that these customers had not purchased for a longer period relative to the other clusters.
6. Combining rule-based RFM segmentation with K-Means clustering provided two complementary ways to understand customer purchasing behavior and identify marketing opportunities.

Recommendations
1. Offer VIP rewards, exclusive discounts, early access, and referral incentives to Champions and High-Value Loyal Customers.
2. Use loyalty points, personalized product recommendations, and complementary-product offers to encourage repeat purchases among Loyal Customers.
3. Target Potential Loyalists and Recent Customers with second-purchase incentives and relevant product recommendations.
4. Develop targeted win-back campaigns for At Risk customers using personalized emails and carefully tested limited-time offers.
5. Test low-cost reactivation campaigns for Lost Customers and monitor their response before increasing marketing expenditure.
6. Track repeat purchase rate, customer retention, campaign conversion rate, revenue per customer, and reactivation rate to evaluate marketing performance.

Files
1. Project_3.ipynb - Google Colab notebook containing data cleaning, RFM analysis, customer segmentation, visualizations, and K-Means clustering.
2. Project 3.xlsx - Excel workbook containing RFM customer data, RFM segment summary, and K-Means cluster summary.
3. Project 3.pbix - Power BI dashboard containing KPI cards, customer distribution charts, and interactive slicers.
4. Marketing Recommendations.md - Marketing recommendations for the identified customer segments and clusters.
5. README.md - Summary of the E-Commerce Customer Segmentation Project.

Conclusion
The E-Commerce Customer Segmentation Project was completed using Python, RFM analysis, K-Means clustering, Excel, and Power BI. The analysis identified valuable customers, potential loyalists, and inactive customer groups, providing insights that can support targeted marketing and customer retention strategies. The combination of RFM scoring, clustering, and interactive visualization demonstrates how customer purchase data can be transformed into actionable business recommendations.
