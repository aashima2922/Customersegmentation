# Customersegmentation
Customer Segmentation on the basis of number of products and cancelled orders

1. **Data Loading and Cleaning:**
   Data is loaded from a CSV file, and duplicate rows are removed. Separate categorical and numeric columns are identified.

2. **Missing Values Handling:**
   Missing values are checked, and rows with missing 'CustomerID' are dropped.

3. **Customer-Level Aggregation:**
   Customer-level aggregation is performed, counting the number of products and identifying canceled orders.

4. **Correlation Heatmap**
5. **KMeans Clustering:**
   The optimal number of clusters (k) is determined using the elbow method.
   KMeans clustering is applied to group customers based on their numeric features.
   After that 2 types of plots are displayed that are pair plot and violin plots for each cluster.

6. **Gaussian Mixture Model (GMM) Clustering:**
   Gaussian Mixture Model (GMM) clustering is performed, and BIC and AIC scores are calculated for different numbers of
   components. Results are visualized using a violin plot.


**The code provides insights into customer segmentation using KMeans and GMM clustering techniques, allowing for a better understanding of customer behavior and preferences based on their order-related features.**
