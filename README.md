# synent-task6-customersegmentation-krishsankhavara
# Customer Segmentation using K-Means Clustering

## Project Overview
This project focuses on performing customer segmentation using the K-Means clustering algorithm on the `Mall_Customers.csv` dataset. The primary goal is to identify distinct customer groups based on their `Annual Income` and `Spending Score` to enable targeted marketing strategies and improve business outcomes for a retail mall.

## Dataset
The dataset used for this analysis is `Mall_Customers.csv`, containing information about customers including their CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).

## Key Features Analyzed
- `Annual Income (k$)`: Income of the customer.
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature.

## Methodology
1.  **Data Loading and Preprocessing**: Loaded the dataset, performed initial checks for missing values and data types. No missing values were found, ensuring data quality.
2.  **Exploratory Data Analysis (EDA)**: Visualized distributions of Gender, Age, Annual Income, and Spending Score. A correlation heatmap was generated to understand relationships between numerical features.
3.  **K-Means Clustering**: 
    - Selected `Annual Income (k$)` and `Spending Score (1-100)` as features for clustering.
    - Applied the Elbow Method to determine the optimal number of clusters, which was found to be **5**.
    - Trained a K-Means model with 5 clusters.
    - Assigned each customer to a segment.
4.  **Cluster Visualization**: Created a scatter plot to visualize the 5 customer segments, clearly marking cluster centroids.
5.  **Insights and Recommendations**: Analyzed each customer segment based on their characteristics and provided actionable business recommendations.

## Customer Segments Identified
Five distinct customer segments were identified:

-   **Segment 0: High Income, Low Spending (Careful Spenders)**: High earners who spend conservatively.
-   **Segment 1: Medium Income, Medium Spending (Average Shoppers)**: Balanced customers with moderate income and spending.
-   **Segment 2: High Income, High Spending (Target Customers / VIPs)**: The most valuable segment, both high income and high spending.
-   **Segment 3: Low Income, High Spending (Impulsive / Budget Shoppers)**: Customers with lower income but high spending tendencies, possibly driven by deals or impulse.
-   **Segment 4: Low Income, Low Spending (Frugal Shoppers)**: Budget-conscious customers with minimal spending.

## Business Recommendations
-   Develop **tailored marketing campaigns** for each segment.
-   **Diversify product offerings** to cater to various income and spending levels.
-   Implement **customer engagement and loyalty programs** specific to segment needs.
-   **Enhance the overall shopping experience** to convert potential from high-income, low-spending segments.
-   Utilize **data-driven decision making** for continuous optimization.

## Conclusion
This analysis provides a robust framework for the mall to understand its customer base better, enabling the creation of personalized strategies that can lead to increased customer satisfaction, loyalty, and revenue growth.
