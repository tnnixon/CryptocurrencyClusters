# CryptocurrencyClusters
<b>Background</b><br>
<br>
A prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. They’ve asked me to create a report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new investment.
<br>
First I processed the raw data to make it fit the machine learning models. Since there is no known classification system, I used unsupervised learning. I used several clustering algorithms to explore whether the cryptocurrencies can be grouped together with other similar cryptocurrencies. I used data visualization to share my findings with the investment bank.
<br>
<b>Data Preparation</b><br>
[x] Read crypto_data.csv into Pandas. The dataset was obtained from CryptoCompare.<br>
[x] Discard all cryptocurrencies that are not being traded. (Filter for currencies that are currently being traded.)<br>
[x] Remove all rows that have at least one null value.<br>
[x] Filter for cryptocurrencies that have been mined. That is, the total coins mined should be greater than zero.<br>
[x] Delete the CoinName from the original dataframe because the value is not numeric and does not contribute to analysis.<br>
[x] Convert the remaining features with text values, Algorithm and ProofType, into numerical data.<br>
[x] Standardize your dataset so that columns that contain larger values do not unduly influence the outcome.<br>
<br>

<b>Dimensionality Reduction</b><br>
Creating dummy variables above dramatically increased the number of features in your dataset.
<br>
[x] Perform dimensionality reduction with PCA.<br>
[x] State the desired explained variance.<br>
[x] Using PCA(n_components=0.99) create a model that will preserve approximately 99% of the explained variance.<br>
[x] For this project, 90% of the explained variance in dimensionality reduction was preserved.<br>
[x] Reduce the dataset dimensions with t-SNE and visually inspect the results. (Run t-SNE on the principal components: the output of the PCA transformation.<br>
[x] Create a scatter plot of the t-SNE output.<br>
<br>

<b>Cluster Analysis with k-Means</b><br>
[x] Create an elbow plot to identify the best number of clusters.<br>
[x] Use a for-loop to determine the inertia for each k between 1 through 10.<br>
[x] Determine, if possible, where the elbow of the plot is, and at which value of k it appears.<br>
<br>

<b>Recommendation</b><br>
According to the plots that were generated from the data set, there are no instances of meaningful clusters to be shown.<br>

<h1>References</h1>
<b>Crypto Coin Comparison Ltd. (2020) </b>Coin market capitalization lists of crypto currencies and prices. Retrieved from https://www.cryptocompare.com/coins/list/all/USD/1
