
## Cryptocurrencies

### Overview
The purpose of this analysis is to offer a new cryptocurrency investment portfolio for its customer. So, we are to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. We decided to use unsupervised learning for this analysis, using clustering algorithm to group the data, and data visualizations to share our findings with the board.

following methods for the analysis:
- preprocessing the database,
- reducing the data dimension using Principal Component Analysis,
- clustering cryptocurrencies using K-Means,
- visualizing classification results with 2D and 3D scatter plots.

#### Resources

Jupyter Notebook
CryptoCompare comparison data (crypto_data.csv)
Pandas Library
Scikit-learn Library
Plotly and Plotly-Express Libraries
hvPlot Library

### Results

The imported DataFrame before cleaning, 1252 rows of data

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/dataframe_before_cleaning.PNG?raw=true)

The list of tradable cryptocurrencies after cleaning, 532 rows of data

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/dataframe_after_cleaning.PNG.jpg?raw=true)

K-means Clustering Algorithm, Elbow Curve

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/elbow_curve.PNG.jpg?raw=true)

Applying the Principal Component Analysis

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/dataframe_after_PCA.PNG.jpg?raw=true)

3D Scatterplot with Clusters, Visualizing Tradable Cryptocurrencies

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/3D_model.png.jpg?raw=true)

Number of Tradable Cryptocurrencies

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/number_of_tradable_cryptos.PNG.jpg?raw=true)

DataFrame to plot results

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/dataframe_for_Cryptos.PNG.jpg?raw=true)

Tradable Cryptocurrencies

![](https://github.com/AshleshaV/Cryptocurrencies/blob/main/images/tradable_crypto_results.png.jpg?raw=true)


#### Summary
We have identified total of 532 tradable cryptocurrencies in this analysis based on features.
Recommend further analysis of each group to determine their performance and potential interest for the investment bank's clients.
