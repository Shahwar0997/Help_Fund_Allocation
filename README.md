# Help Fund Allocation Using Unsupervised Learning

## 📌 Problem Statement
HELP International wants to allocate $10M in aid based on socio-economic and health indicators. We apply clustering (unsupervised learning) to group countries and prioritize funding.

## 📊 Dataset
- Source: https://www.kaggle.com/datasets/gauravduttakiit/help-international
- Features: [GDP, Health Index, Infant Mortality, Imports, Exports, Life Expectancy, Income]

## 🔍 Methodology
1. **Data Cleaning and EDA**
   - Handled missing values
   - Visualized distributions
   - Scaled features using StandardScaler

2. **Clustering Algorithms**
   - K-Means
   - Hierarchical Clustering (optional: DBSCAN)
   - Elbow and Silhouette methods for optimal `k`

3. **Dimensionality Reduction**
   - PCA used for 2D and 3D visualization of clusters

## 📈 Results
- Identified 3 clusters of countries
- Interpretation of each cluster is provided
- Recommended funding allocation strategy

