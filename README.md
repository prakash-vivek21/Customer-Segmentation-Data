# Customer Segmentation Data Analysis (Clustering)

Welcome to the Customer Segmentation Data Analysis project. This project focuses on utilizing clustering techniques to segment customers based on various demographic and behavioral features. The insights derived from this analysis can help businesses tailor their marketing strategies and product offerings to better meet the needs of different customer segments.

### Table of Contents
* Introduction
* Dataset
* Features
* Preprocessing
* Clustering Techniques
* Principal Component Analysis (PCA)
* Visualization
* Insights
* Conclusion

### Introduction
Customer segmentation is the practice of dividing a customer base into distinct groups that share similar characteristics. This project applies clustering techniques to identify these segments based on demographic and behavioral features, enabling targeted marketing and personalized customer experiences.

### Dataset
The dataset used in this project includes the following features:

* age: Customer's age
* income: Customer's income
* spending_score: A score assigned based on customer spending behavior
* membership_years: Number of years the customer has been a member
* purchase_frequency: Frequency of purchases made by the customer
* last_purchase_amount: Amount spent during the customer's last purchase
* preferred_category: The product category preferred by the customer (e.g., Electronics, Sports, Home & Garden)
* gender: Gender of the customer

### Features
The project focuses on the following features for clustering:

* Age
* Income
* Spending Score
* Membership Years
* Purchase Frequency
* Last Purchase Amount

### Preprocessing
Preprocessing steps include:

* Handling missing values
* Normalizing the data to ensure features contribute equally to the clustering process
* Encoding categorical variables (e.g., gender, preferred category)

### Clustering Techniques
We apply the following clustering techniques:

* K-Means Clustering: Identifies clusters by minimizing the variance within each cluster.
* Agglomerative Clustering: A hierarchical clustering method that builds nested clusters by merging or splitting them successively.

### Principal Component Analysis (PCA)
PCA is performed to reduce the dimensionality of the dataset while retaining 95% of the variance. The top three components are used to visualize the clusters in a 3D space.

### Visualization
Various plots are generated to visualize the clusters:
* Box Plot: helps in outlier analysis.
* 3D Scatter Plot: Shows the distribution of clusters based on the top three PCA components.
* Bar Plots: Illustrate the distribution of genders and preferred categories within each cluster.
* Histograms: Display the distribution of key features within each cluster.

### Conclusion
The clustering analysis has provided valuable insights into customer segmentation, highlighting distinct groups within the customer base. Each cluster exhibits unique demographic and behavioral characteristics, which can inform targeted marketing strategies and personalized customer engagement efforts. For example, younger, high-income customers in Cluster 0 show a strong preference for Electronics, while Cluster 1, consisting predominantly of higher-income males and other genders, is more interested in Sports products. By understanding these segments, businesses can optimize their marketing campaigns, improve product offerings, and enhance overall customer satisfaction, ultimately driving better business outcomes.

### Insights
Key insights derived from the analysis:

*Cluster 0: Largest customer segment with younger, higher-income customers who prefer Electronics.
*Cluster 1: Predominantly higher-income males and others who prefer Sports.
*Cluster 5: Diverse group of older, higher-income females and others with interests in Electronics and Sports.
*Cluster 2: Mix of genders with lower incomes, preferring Home & Garden, Sports, and Electronics.
