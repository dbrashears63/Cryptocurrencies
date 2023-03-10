# Crypto Currencies

## Purpose:
The objective of this undertaking is to generate a report intended for an investment bank keen on proposing a novel portfolio for investing in cryptocurrencies. The report comprises of an inventory of the cryptocurrencies currently available for trading and an analysis of how they could be categorized to formulate a classification system for this innovative investment. The completion of this project requires executing unsupervised machine learning tasks.

## Coding and Data Resources
### Coding Resources
Python, Jupyter Notebook
### Data Resources
crypto_data.csv

## Results
To achieve the requested report intended for the client several tasks must be completed. One of the first tasks of any data analysis is to review and clean the data. The data has been cleaned and will need to be processed. The Python PCA method was used to preprocess and reduce the data dimensions. Next the K-mean was used to cluster the data. Finally, a three-dimensional graph was created to help the client visualize what would be their best plan of action. Below are a select series of images that will display snippets of the process.

Fig #1 Original Crypto Currency DataFrame.

![1 orginal_crypto_df](https://user-images.githubusercontent.com/113568268/221070489-c18cb0ac-d414-45fa-b16b-c941a276ab16.png)

Fig #2 Results of the Clean Data Output.

![2 cleaned_crypto_df](https://user-images.githubusercontent.com/113568268/221070520-e74bfd5f-70e8-44c9-8722-722aa14af403.png)

Fig #3 Results of using the PCA Method to reduce the dimensions to three principal components.

![4 pca_df](https://user-images.githubusercontent.com/113568268/221070568-619ed79d-cf26-4276-9c5f-80e252b213b4.png)

Fig #4 Results of using the K-means to cluster the data and create an Elbow Curve. 

![3 elbow_curve](https://user-images.githubusercontent.com/113568268/221070585-0d078393-4a51-44c4-89e0-d87ab1dc0c01.png)

Fig #5 Results of creating the 3D graph.  

![5 3D_module](https://user-images.githubusercontent.com/113568268/221070666-a38ce6e6-ff41-46cb-a38e-f0dcd9e0f51e.png)

Fig #6 Results of creating a scatter plot. 

![8 scatter_plot](https://user-images.githubusercontent.com/113568268/221070712-89b3ca4e-6c80-4e69-95a3-e325b72ca36c.png)


## Summary
From the analysis of the three-dimensional graph, it was observed that there are four distinct groups. The first two groups are closely clustered together, with most of the currencies falling under these two groups. The third group comprises a few currencies that are relatively distant from the other groups, while the fourth group only has a single currency. This indicates that while there are many currencies that perform similarly, there are a few that stand out as outliers. However, to determine whether these outliers are over-performers or under-performers, further analysis would be required.
To gain a better understanding of the performance of each of these currencies, a detailed analysis would need to be conducted. This would enable investors to gauge the stability and risk associated with their investments based on the various cryptocurrencies they choose to invest in.




