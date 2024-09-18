# Predictive Analysis of Product Demand for Modern Supply Chain Management

**Project Overview**
This project focuses on predicting product demand to optimize supply chain management for companies operating in fast-paced industries such as retail, manufacturing, and logistics. By developing accurate demand forecasting models using historical data, businesses can improve inventory management, resource allocation, and overall operational efficiency.

**Key Objectives:**
Data Exploration and Visualization: Analyze historical demand data to identify trends, seasonality, and hidden patterns.
Model Development: Implement and evaluate various forecasting models, such as linear, exponential, polynomial, and seasonal models.
Performance Evaluation: Assess the accuracy of models using appropriate metrics.
Forecasting: Generate future demand predictions based on the best-performing model to support decision-making.
Business Problem
Accurately predicting future demand is challenging due to changing market conditions and consumer behavior. Misjudging demand can lead to overstocking, stockouts, or missed revenue opportunities. The goal of this project is to develop robust forecasting models that provide actionable insights to help businesses anticipate demand and improve decision-making.

**Dataset**
The dataset contains information on product demand across different categories and warehouses over a span of several years. Key features include:

Product Code: Unique identifier for each product.
Warehouse: Location of the product.
Product Category: Category to which the product belongs.
Date: Date of the recorded demand.
Order Demand: Quantity of product demand on the specified date.
Data Cleaning and Preprocessing
Duplicate Removal: Ensured the integrity of the data by removing duplicate records.
Handling Missing Values: Addressed missing data by either imputation or removal, as less than 1% of the data was affected.
Outlier Treatment: Applied statistical techniques like z-score analysis to detect and mitigate the impact of outliers.
Demand Adjustments: Converted negative demand values to their absolute equivalents to maintain consistency.

**Data Exploration and Visualization**
Key visualizations include:

Average Demand per Product Category: Identifies demand trends for different product categories.
Total Demand by Warehouse: Highlights distribution patterns of product demand across different warehouses.
Top 5 Product Categories: Provides insights into the most popular products based on order counts.
Monthly and Yearly Demand Trends: Tracks demand variations over time to reveal seasonal patterns and long-term trends.

**Forecasting Models**
Several forecasting models were developed and evaluated:

Linear Trend Model: Captures the linear progression of demand over time.
Exponential Trend Model: Accounts for exponential growth in demand.
Polynomial Trend Model: Models more complex relationships between time and demand.
Seasonal Decomposition: Breaks down demand into seasonal, trend, and residual components.
Exponential Smoothing: Applied to reduce the effect of noise in the data.
Model Evaluation
R-Squared: Measures how well the model fits the data. The linear trend model showed an R² of 0.30.
Mean Absolute Error (MAE): Evaluated the prediction errors; lower values indicate better performance. The MAE for exponential smoothing was 2.8081.

**Conclusion**
This project successfully identified demand trends and developed models that improve forecast accuracy. The results highlight the importance of integrating both classical and modern machine learning techniques to improve decision-making in supply chain management. Accurate demand forecasting helps businesses optimize their inventory and resource allocation, ensuring better customer satisfaction.
