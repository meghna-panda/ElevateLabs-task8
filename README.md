# ElevateLabs-task8
## Customer Segmentation using KMeans Clustering
This project performs customer segmentation using KMeans Clustering on a mall customer dataset. It applies unsupervised machine learning techniques to group similar customers based on features such as age, annual income, and spending score.

# Objectives
1. Cluster customers into distinct groups based on behavior.
2. Identify optimal number of clusters using Silhouette Score.
3. Visualize customer segments using PCA.
4. Provide a simple and interpretable segmentation model for marketing strategies.

# Technologies Used
1. Python (Google Colab)
2. Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

# Methods
1. Data Preprocessing
  -Removed unnecessary columns (e.g., CustomerID)
  -Converted categorical data (e.g., Gender) to numeric
  -Scaled features using StandardScaler
2. Clustering
  -Applied KMeans Clustering with multiple values of k (2 to 10)
  -Selected the best number of clusters using Silhouette Score
  -Achieved a maximum score of ~0.4208 with 10 clusters
3. Visualization
  -Applied PCA to reduce dimensionality for plotting
  -Visualized clusters in 2D with color-coded scatter plots
4. Bonus
  -Included a synthetic dataset example with perfect separation, achieving Silhouette Score ≈ 1.0 (for educational reference)

# Results
  -Optimal number of clusters: 10
  -Final Silhouette Score: 0.4208
  -Clusters are well-separated in PCA visualization
  -Ready for use in targeted marketing and customer profiling
