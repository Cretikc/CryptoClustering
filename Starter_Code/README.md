# -CryptoClustering
Using the provided cryptocurrency dataset with seven features, I explored clustering techniques. The analysis, visualizations, and code can be found in Crypto_Clustering.ipynb.

First, I normalized the data using StandardScaler() from scikit-learn. I then applied the elbow method to determine the optimal number of clusters, identifying k = 4 as the best choice. Next, I fit the data using a k-means model and visualized the clusters in a scatter plot.

To further refine the analysis, I used Principal Component Analysis (PCA) to reduce the dataset to three features, which together explained 89% of the variance. Reapplying the elbow method and k-means clustering confirmed that k = 4 remained the optimal choice, validating PCA’s effectiveness in preserving the data’s structure.

Finally, I compared the elbow curves and scatter plots before and after PCA. While PCA helped highlight outliers, it did not significantly improve the distinction between clusters 0 and 3, at least in the two-dimensional visualization.