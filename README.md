# CryptoClustering

## Cryptocurrency Market Analysis with K-Means Clustering

### Introduction
This project aims to analyze cryptocurrency market data using K-Means clustering technique. The analysis includes preprocessing the data, determining the optimal number of clusters using the elbow method, performing clustering using K-Means, and visualizing the results. Additionally, Principal Component Analysis (PCA) is applied to reduce the dimensionality of the data and improve clustering accuracy.

### Data
The dataset used in this analysis contains various features related to cryptocurrency price changes over different time periods. 
### Preprocessing
Before clustering, the data is preprocessed by normalizing using StandardScaler to scale the features. The scaled data is then used for further analysis.

### Determining the Optimal Number of Clusters
The elbow method is utilized to determine the optimal number of clusters for both the original and PCA-transformed data. The inertia values for different numbers of clusters are plotted, and the elbow point is identified as the optimal number of clusters.

### Clustering with K-Means
K-Means clustering is performed on both the original and PCA-transformed data using the optimal number of clusters identified earlier. The clusters are predicted, and the results are visualized using scatter plots.

### Results and Discussion
After visually analyzing the cluster analysis results, it is observed that reducing the number of features using PCA had a significant impact on clustering accuracy. The optimal number of clusters obtained after PCA transformation led to more meaningful and interpretable clusters compared to the original data.

### Conclusion
In conclusion, this project demonstrates the application of K-Means clustering and PCA in analyzing cryptocurrency market data. By reducing dimensionality and identifying optimal cluster numbers, it provides insights into grouping cryptocurrencies based on price change characteristics.

### Dependencies
- pandas
- scikit-learn
- hvplot

### Usage
1. Clone the repository.
2. Install the required dependencies.
3. Run the main script to perform cryptocurrency market analysis with K-Means clustering.


