# Cryptocurrencies
Use unsupervised machine learning techniques to analyze cryptocurrency data.

# Project Overview
This project uses machine learning to identify which cryptocurrencies are on the trading market and to better understand how cryptocurrencies should be grouped to create classifications for developing an investment product. Unsupervised machine learning was chosen used since there is no known output for what I'm looking for. To group the cryptocurrencies, a clustering algorithm was also chosen to help determine whether or not I should be investing in this product.

Steps included in this project:
1. **Data preprocessing**. This step included in-depth data cleaning, such as removing null values and removing cryptocurrencies without coins mined. In addition, the encoding method "get_dummies()" was used for the text features and StandardScaler() was used to standardize and transform the data.
2. **Reducing data dimensions using PCA**. In this step, a dataframe's dimensions was reduced to three principal components and a new dataframe was created.
3. **Clustering cryptocurrencies using K-means**. During step, an elbow curve was created to find the best value for the clustering groups and a K-means algorithm was used to predict the K clusters for the cryptocurrencies’ data.
4. **Visualizing results**. In this final step, three types of figures were used: a 3D scatter plot to visualize the three PCAs, a hvplot.table to visualize all the current tradable cryptocurrencies, and a 2D scatter plot to visualize "Total Coins Mined" vs. "Total Coin Supply" by coin name and clusters.
