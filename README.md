# Clustering - Segmenting Mall Customer
To cluster mall customers, I conducted two unsupervised machine learning algorithms (K-Means and DBScan) in R using Kaggle dataset [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
## Introduction
Clustering is one of the most popular unsupervised machine learning techniques. The data can be divided on the basis of centroids (K-Means), densities (DBScan), etc. Thus, in this project, I applied K-Means and DBScan these two clustering methods to find customer segments in the mall.
## Exploratory Data Analysis
1. Univariate Analysis
2. Bi-variate Analysis
3. Missing Value & Outlier Treatment
## Data Preprocessing
1. Choose Variables
2. Data Standardization
## Data Modeling
1.  K-Means
    - Determine Optimal Clusters (K)
      - Elbow Method
      - Average Silhouette Method
      - Gap Statistic Method
    - Plot Clusters and Interpret Clustering Results
    - Plot 3D Scatter Plot
2. DBScan
   - Find Optimal Knee (eps/radius) using k-distance curve
   - Plot Clusters and Interpret Clustering Results
## Conclusion
To sum up, being able to determine different segments of customers can help the marketing team approach those customer segments in unique ways. For example, based on customer clustering analysis of K-Means, I could give three data-driven recommendations.
1. Blue (Target customers, High annual income and High spending score): the mall can give them some special services, showing their importances to retain them as they give the most profit margin.
2. Beige (Low annual income and Low spending score): the mall can send them extra offers or discounts to attract them towards spending.
3. Barbie Pink (Upper Middle to High annual income but Low spending score): the mall can investigate those customers in-detail to find whether they are unsatisfied or unhappy with the mall’s services. Then, if the mall can solve the problems, those customers can then become higher spenders, as they have the potential to spend more money.
