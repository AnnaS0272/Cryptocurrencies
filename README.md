# Cryptocurrencies Analysis

In order to create a cryptocurrencies investment portfolio offering for customer we need to analyse the trading/mining data, specifically determine how cryptocurrencies could be grouped toward **creating a classification** for developing this new investment product.

Since the data we obtained was not ideal, we had to perform a degree of cleaning up using pandas dataframe. The important thing in cleaning up was to remove all N/A, null and values above zero to arrive at meaninful informartion. It is important to notw after the clean up was performed data et reduced by almost 50% from 1200+ to 500+ items. Since there is no known output we are looking for, we then used **unsupervised machine learning learning**.

In order to group the cryptocurrencies, we used clustering algorithm to help determine about investing in this product and data visualizations to share findings. the following steps were performed to accomplish the task:

-Prepared the data for dimensions reduction with PCA and clustering using K-means

-Reduced data dimensions using PCA algorithms from sklearn

-Predicted clusters using cryptocurrencies data using the K-means algorithm form sklearn

-Created some plots and data tables to present your results

