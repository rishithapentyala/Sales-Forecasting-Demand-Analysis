Sales Forecasting and Cluster Analysis:
Project Overview:
This project focuses on Sales Forecasting and Cluster Analysis to generate actionable business insights. It combines Python-based data processing, forecasting techniques, clustering analysis, and Power BI visualization to support strategic decision-making.

Objectives:
Predict future sales using historical data and forecasting models.
Segment products into clusters based on pricing and sales behavior.
Analyze the impact of promotions and price elasticity on sales.
Provide a clear, interactive dashboard for business insights.
Document findings, observations, and recommendations in a comprehensive report.

Data Processing:
Cleaned raw sales data to remove inconsistencies and missing values.
Created custom variables to capture business-relevant features (e.g., promotion flags, cluster identifiers).
Aggregated data for accurate analysis by product, cluster, and time periods.

Analysis & Modeling:
Forecasting: Applied time series forecasting techniques to estimate future sales, considering seasonal peaks and promotional effects.

Clustering: Performed clustering to categorize products into four clusters:
Medium Price Steady Sale
Fast-Moving Low Price
Moderately Priced Low Volume
Luxury
Calculated price elasticity for each cluster to understand responsiveness to pricing.

Power BI Dashboard:
Modeled cleaned and processed data in Power BI.

Created an interactive dashboard to visualize:
Total sales and quantity sold
Seasonal trends and peak months
Cluster-wise performance and top-selling products
Promotion impact on sales
Forecasting results and errors

Key Observations:

Peak sales occur in November and December.
Fast-Moving Low Price products dominate top sellers.
Low-Mid Steady products are highly price-sensitive and respond most to promotions.
Luxury products show steady growth with negligible price elasticity.
Top SKU: 22850
Highest forecast error: Product 6200650

Business Insights:

Seasonal peaks require optimized inventory planning.
Promotions effectively drive sales for specific clusters but need careful planning.
Cluster-specific strategies improve forecasting accuracy and operational efficiency.
Price-sensitive products need targeted pricing strategies to maximize revenue.

Forecasting Performance:
Average forecast accuracy: -1.76% (slight underestimation).
Total forecasting error: -1.39M units, mainly due to high-variance SKUs.
Incorporating promotions and cluster behavior improves predictive performance.

Tools & Technologies:
Python: Data cleaning, custom variable creation, forecasting, clustering
Power BI: Dashboard creation and visualization
Libraries Used: pandas, numpy, scikit-learn, statsmodels, matplotlib/seaborn (for exploratory analysis)

Conclusion
This project demonstrates the integration of data analytics, forecasting, and visualization to provide actionable insights for sales and inventory planning. The combination of Python and Power BI enables a data-driven approach to optimize promotions, pricing strategies, and inventory management across product clusters.
