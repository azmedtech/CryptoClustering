# Unsupervised Learning Challenge 

## Project Title - CryptoClustering

Using your knowledge and experience in Python, you will create an unsupervised learngin model that will predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Project Requirements
* Requirement 1: Review the summary statistics and plot of the data to understand the data before processing.
* Requirement 2: Prepare and normalize the data using StandardScalar from scikit-learn, then create a dataframe of the scaled data with the "coin-id" set as the index.
* Requirement 3: Determine the best k value for the scaled data, using the elbow method. 
* Requirement 4: Use K-means to cluster the cryptocurrencies, using the original scaled data. Display the data using hvPlot, with color graph points, and the "coin_id" parameter visible in hover over each data point. Set the x-axis as "price_change_percentage_24h" and the y-axis as "price_change_percentage_7d".
* Requirement 5: Optimize the cryptocurrency clusters with Principal Component Analysis, reducing the features to three principal components. Display the PCA data in a new dataframe and determine the explained variance for the three principal components.
* Requirement 6: Determine the best k value for the PCA data, using the elbow method.
* Requirement 7: Use K-means on the PCA data to cluster the cryptocurrencies. Display the data using hvPlot, with color graph points, and the "coin_id" parameter visible in hover over each data point. Set the x-axis as "PCA1" and the y-axis as "PCA2".
* Requirement 8: Use the information from your analysis to answer the question "What is the impact of using fewer features to cluster the data using K-Means?

## Credits 
1. ASU DA Course starter code file and crypto_market_data.csv dataset
2. ASU Learning Assistants - debugging of code
