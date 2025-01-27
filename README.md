# Online Retailer Transactional Data Analysis

This project analyzes transactional data from a UK-based online retailer between 2010 and 2011. The goal is to identify customer purchasing patterns, trends, and insights to support business decision-making.

## Data Description:
The dataset contains the following columns:
- **InvoiceNo**: Unique transaction identifier
- **StockCode**: Product code
- **Description**: Product name
- **Quantity**: Quantity of products purchased
- **InvoiceDate**: Date of transaction
- **UnitPrice**: Price per unit of the product
- **CustomerID**: Unique identifier for each customer
- **Country**: Country of the customer

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Goals
1. Analyze customer purchasing patterns.
2. Identify trends and correlations in the data.
3. Generate actionable insights for business decision-making.

   
**Exploratory Data Analysis (EDA)**
During the EDA phase, the following steps were performed:

**Data Cleaning**: Handling missing values and removing duplicate entries.

**Data Visualization**: Visualizing the distribution of key features such as product categories, sales by country, and purchase quantities.

**Time Series Analysis**: Analyzing the time series data to identify trends and seasonal patterns.

**Data Preprocessing**
To prepare the data for modeling, the following steps were taken:

**Encoding Categorical Variables**: Product categories and countries were encoded.

**Normalization**: Numerical features were normalized to ensure consistent scaling.

**Train-Test Split**: The data was split into training and testing sets for model validation.

**Predictive Modeling**
Several machine learning algorithms were employed to build predictive models:

**Linear Regression**: To predict sales based on historical data.

**Random Forest**: To identify important features and improve prediction accuracy.

**K-Means Clustering**: To segment customers into distinct groups based on their purchasing behavior.

**Model Evaluation**
The performance of the models was evaluated using the following metrics:

**Mean Absolute Error (MAE)**: To measure the average magnitude of errors in predictions.

**Root Mean Squared Error (RMSE)**: To penalize larger errors and provide a more comprehensive evaluation.

**R-squared (R²)**: To assess the proportion of variance explained by the model.

**Results**
Sales Trends: Analysis revealed the highest sales during November and December, likely due to holiday shopping.

- Top-Selling Products: The most frequently purchased products were decorative items and gifts.

- Customer Demographics: Majority of customers were from the UK, with a significant number of international customers from Europe.

- Purchase Behavior: Repeat customers showed a higher average transaction value compared to one-time customers.

**Findings**
- Seasonal Impact: Sales peak during the holiday season, suggesting the need for strategic inventory management.

- Product Popularity: Certain products have consistent high demand, which can inform stocking and marketing strategies.

- Customer Segmentation: Understanding customer demographics and purchase behavior can help tailor marketing efforts.

- Loyalty Insights: Fostering customer loyalty leads to higher transaction values and repeat purchases.

**Recommendations**
- Inventory Management: Stock up on popular products before peak seasons to meet customer demand.

- Marketing Campaigns: Focus marketing efforts on high-demand products and peak shopping periods.

- Customer Loyalty Programs: Implement loyalty programs to encourage repeat purchases and increase average transaction values.

- International Expansion: Explore opportunities to expand the customer base in international markets.
