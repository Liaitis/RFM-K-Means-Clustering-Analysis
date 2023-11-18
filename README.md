# RFM-K-Means-Clustering-Analysis
## Overview
This project employs RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to perform customer segmentation. The dataset used, "sample-orders.csv," contains information about orders, including order date, order ID, customer, and grand total. The goal is to categorize customers into distinct clusters based on their transaction behavior.

## Project Structure
**1. Imports and Setup:**
Essential libraries/modules are imported.
The dataset is loaded, and initial configurations are set.

**2. Data Exploration and Preprocessing:**
A function provides an overview of the dataset.
'order_date' is converted to a datetime format for better analysis.

**3. RFM Calculation:**
Recency, Frequency, and Monetary metrics are calculated for each customer.

**4. Standardization:**
RFM metrics are standardized using StandardScaler for comparable scales.

**5. Elbow Method and K-Means Clustering:**
The Elbow Method is employed to find the optimal number of clusters.
K-Means clustering is performed with k=4.

**6. Cluster Analysis and Visualization:**
Characteristics of each cluster are visualized through scatter plots and boxplots.

**7. RFM Score and Customer Segmentation:**
RFM scores are created, and customer segments are defined based on quantiles.
Segments are mapped to specific clusters.

**8. Cluster Analysis and Segmentation Visualization:**
The distribution of customer segments within each cluster is visualized using count plots.

**9.Conclusion Based on Cluster Analysis:**
Each cluster's dominant segments and observations are highlighted.
General observations, opportunities, and recommendations are provided in the jupyter notebook.

## Conclusion
**Based on the cluster analysis:**
- Cluster 1 contains potential loyalists and loyal customers.
- Cluster 2 includes promising, at-risk, and about-to-sleep customers.
- Cluster 3 is characterized by potential loyalists and champions.
- Cluster 4 consists of new customers and potential loyalists.
- Recommendations include tailored strategies, retention efforts, a focus on new customers, and strengthening loyalty programs. The project successfully identifies customer segments, aiding in targeted marketing strategies for improved engagement and value.

Feel free to explore the detailed analysis in the Jupyter Notebook and reach out for any questions or further discussions!
