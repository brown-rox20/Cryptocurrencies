# Cryptocurrencies

## Tools Used
Jupyter Notebook

## Background

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. Using knowlegde of processing data, clustering, reducing dimensions, and reducing principal components create an analysis for your clients who are preparing to get into the cryptocurrency market. Create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. 




## Deliverable 1: Preprocessing the Data for PCA
The data will need to be processed to fit the machine learning models. Use unsupervised learning to group the cryptocurrencies on a clustering algorithm. Use data visualizations to share findings with the board.

## Deliverable 2: Reducing Data Dimensions Using PCA

Using your knowledge of how to apply the Principal Component Analysis (PCA) algorithm, you’ll reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

## Deliverable 3: Clustering Cryptocurrencies Using K-means

Using your knowledge of the K-means algorithm, you’ll create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.
## Deliverable 4: Visualizing Cryptocurrencies Results

Using your knowledge of creating scatter plots with Plotly Express and hvplot, you’ll visualize the distinct groups that correspond to the three principal components you created in Deliverable 2, then you’ll create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.