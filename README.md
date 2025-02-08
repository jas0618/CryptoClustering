# CryptoClustering

# Objective 
- The goal was to identify patterns and similarities among different cryptocurrencies using machine learning techniques.

# Steps in the Jupiter Notebook

1. Data Preparation

Loaded the dataset from Resources/crypto_market_data.csv into a Pandas DataFrame.

Inspected the first few rows to understand the structure of the dataset.

Checked for missing values and handled them appropriately.

Generated summary statistics to gain insights into the dataset distribution.

2. Data Processing

Converted categorical data into numerical format if applicable.

Normalized numerical features using StandardScaler to ensure all variables contributed equally to clustering.

Dropped any irrelevant or highly correlated features to reduce noise.

3. K-Means Clustering

Determined the optimal number of clusters using the Elbow Method by plotting the inertia values for different k values.

Fitted a K-Means model to the data and assigned each cryptocurrency to a cluster.

Analyzed the characteristics of the formed clusters.

4. Dimensionality Reduction with PCA

Applied Principal Component Analysis (PCA) to reduce the dataset dimensions to two components.

Transformed the data into a lower-dimensional space while retaining as much variance as possible.

Compared the clustering results in PCA-reduced space to the original feature space.

5. Data Visualization

Used hvplot to create interactive scatter plots of clustered cryptocurrencies.

Visualized clusters in both the original multi-dimensional feature space and in the PCA-reduced 2D space.

Labeled clusters appropriately to distinguish patterns among cryptocurrencies.

6. Interpretation and Analysis

Analyzed the characteristics of different clusters to understand what grouped certain cryptocurrencies together.

Identified any trends, anomalies, or insights that emerged from the clustering process.

Discussed potential real-world applications of these insights in cryptocurrency trading, portfolio management, or market segmentation.

# Output

Identification of clusters among cryptocurrencies.

Visual representation of clusters in both original feature space and reduced PCA space.
