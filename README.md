Market Segmentation with KMeans Clustering

Overview:

This project applies KMeans clustering to segment customers based on their purchasing behavior. By analyzing various financial metrics such as balance, purchases, credit limit, and payments, customers are grouped into distinct segments to help businesses understand different spending behaviors. The insights gained can assist in targeted marketing, credit risk assessment, and personalized financial services.

Methodology USed

Data Preprocessing:
Checked for missing values and filled them with the mean.
Removed duplicate records and dropped irrelevant columns (e.g., Customer ID).
Standardized numerical values for clustering.

Exploratory Data Analysis (EDA):
Visualized distributions of key financial metrics.
Identified correlations between features to understand purchasing behavior.

Optimal Cluster Selection:
Used the Elbow Method to determine the ideal number of clusters.

KMeans Clustering:
Applied KMeans with the optimal cluster count to segment customers.
Analyzed cluster characteristics to derive business insights.

Principal Component Analysis (PCA):
Reduced dimensions to visualize clusters in a 2D space.

Insights

Transactors: Customers who pay off their balances in full and have low credit utilization.
Revolvers: Customers who carry high balances and use credit for cash advances.
High-Spending Customers: Customers with high purchase frequency and high credit limits.
Low-Tenure Customers: Recently acquired customers with limited spending history.

Conclusion
KMeans clustering provided valuable customer segmentation insights that can be used for targeted marketing and financial decision-making. Future work could involve testing additional clustering techniques or incorporating time-series analysis for customer behavior prediction.

