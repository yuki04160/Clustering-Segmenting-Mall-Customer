# Clustering - Segmenting Mall Customer
To segment mall customers and give data-driven business strategies to the marketing team, I conducted two unsupervised machine learning algorithms, K-Means and DBScan, in R using Kaggle dataset - [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python).
## Introduction
Clustering is one of the most popular unsupervised machine learning techniques. The data can be divided on the basis of centroids (K-Means), densities (DBScan), etc. Thus, the project aims to use two different clustering methods to find customer segments in the mall.
## Exploratory Data Analysis
   - Univariate analysis
   - Bi-variate analysis
   - Missing value & Outlier treatment
## Data Preprocessing
   - Choose variables
     - I decided to use numerical variables: age, annual income, and spending score
   - Data standardization
     - Since K-Means is a distance-based algorithm and "age", "annual income", and "spending score" have different units of measurements, I standardized the data to have a mean of 0 and a standard deviation of 1.
## Data Modeling
1.  K-means
    - To determine optimal clusters (K), I used three methods:
      - Elbow method
      - Average silhouette method
      - Gap statistic method
    - I plotted clusters and interpreted clustering results
    - I plotted 3D scatter plot
2. DBScan
   - To find optimal knee (eps/radius), I plotted a k-distance curve
   - I plotted clusters and interpreted clustering results
## Conclusion
To sum up, being able to determine different segments of customers can help the marketing team approach those customer segments in unique ways. For example, based on customer clustering analysis results of K-Means, I could give three data-driven recommendations:
1. Blue (Target customers, High annual income and High spending score): the mall can give them some special services, showing their importances to retain them as they give the most profit margin.
2. Beige (Low annual income and Low spending score): the mall can send them extra offers or discounts to attract them towards spending.
3. Barbie Pink (Upper Middle to High annual income but Low spending score): the mall can investigate those customers in-detail to find whether they are unsatisfied or unhappy with the mall’s services. Then, if the mall can solve the problems, those customers can then become higher spenders, as they have the potential to spend more money.
