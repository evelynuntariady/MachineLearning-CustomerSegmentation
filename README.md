# MachineLearning-CustomerSegmentation
Customer Segmentation with Clustering
This project applies unsupervised machine learning to segment customers based on their behavior patterns. The goal is to help organizations better understand different customer groups and enable more personalized strategies.

Features :
1. Data Preprocessing
   
   Handled categorical and numerical features with encoding and scaling
   
   Prepared dataset for clustering analysis

   
2. Clustering Analysis
   
   Applied clustering algorithms (K-Means)
   
3. Determined the optimal number of clusters using evaluation metrics (silhouette score, elbow method)
   
4. Grouped customers into distinct behavioral clusters


Insights :

1. Analyzed cluster characteristics to identify meaningful patterns in customer behavior
   
2. Provided interpretation of clusters for actionable business use


The analysis identified 3 key customer segments:

Cluster 1: At-Risk / Low Satisfaction Customers

a. Few or no dependents, lowest referrals, lowest satisfaction scores

b. Low total refunds → may indicate silent dissatisfaction

c. Customers in this cluster are most likely to churn


Cluster 2: High-Spending but Demanding Customers

a. Highest monthly charges, high dependents and referrals

b. Second-highest satisfaction score but also highest refunds → loyal but complain often

c. Requires strong customer support and service improvements


Cluster 3: Loyal & Highly Satisfied Customers

a. Highest satisfaction score, lowest refund rates

b. Active customers with many dependents and referrals

c. Most valuable segment, likely to promote and stay loyal
