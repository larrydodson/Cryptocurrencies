# Cryptocurrencies
UTMCC DataViz Module 18 Cryptocurrencies, unsupervised algorithms

---

## Contents 
  * Overview
    - Purpose
    - Resources
  * Results
  * Summary
 

---  

## Overview 
  
  An investment bank is interested in offering a new cryptocurrency investment portfolio for customers. However, the industry of cryptocurrencies has hundreds of choices. A report was requested that is to include the various cryptocurrencies that are currently trading in the market and how they could be grouped to create a classification system.

   ### Purpose
   Data is to be processed to fit machine learning models for unsupervised learning, since there is no known standard output. To group the cryptocurrencies, a clustering algorithm is used. Visualizations are generated to share findings with company stake holders.
  
   The deliverables are: 
   - Deliverable 1: Preprocessing the Data for PC
   - Deliverable 2: Reducing Data Dimensions Using PCA
   - Deliverable 3: Clustering Cryptocurrencies Using K-means
   - Deliverable 4: Visualizing Cryptocurrencies Results
   
  
   ### Resources
  * Data/content data source: crypto_data.csv, retrieved from CryptoCompare https://min-api.cryptocompare.com/ 
  * Software: Windows10, Python 3.8.3, Jupyter Notebook, Libraries: Pandas, Scikit-learn, KMeans, PCA, StandardScaler, MinMaxScaler, Plotly, plotly.express, hvPlot   
  
<br>

--- 

## Results


   ### Deliverable 1: Preprocessing the Data for PC
   
   | **crypto_df DataFrame**<br>after preprocessing | **get_dummies method**<br>creating variables for text Features |
   | :---: | :---: | 
   | ![D1_crypto_df.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D1_crypto_df.png) | ![D1_dummies.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D1_dummies.png) | 
   
. 
   
   ### Deliverable 2: Reducing Data Dimensions Using PCA
   
   | **crypto_pca_df DataFrame**<br>Principal Component Analysis |
   | :---: |
   | ![D2_crypto_pca_df.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D2_crypto_pca_df.png) |
 
 
 .
   
   ### Deliverable 3: Clustering Cryptocurrencies Using K-means
   
   | **Elbow Curve**<br>using hvPlot, finding the best value for K | **clustered_df DataFrame** |
   | :---: | :---: | 
   | ![D3_elbow_curve.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D3_elbow_curve.png) | ![D3_clustered_df.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D3_clustered_df.png) | 
   
      
.
   
   ### Deliverable 4: Visualizing Cryptocurrencies Results

   
   | **3D Scatter Plot**<br>using Plotly Express, plotting the clusters from clustered_df, with hover_data parameters | **Tradable Cryptocurrencies Table**<br>using hvplot.table() function |
   | :---: | :---: | 
   | ![D4_3Dscatter.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D4_3Dscatter.png) | ![D4_tradable_cryptocurrencies.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D4_tradable_cryptocurrencies.png) | 
   
      
   | **clustered_scaled**<br>using the MinMaxScaler().fit_transform method | **2D Scatter Plot**<br>using hvplot, with hover_cols |
   | :---: | :---: | 
   | ![D4_clustered_scaled.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D4_clustered_scaled.png) | ![D4_2Dscatter.png](https://github.com/larrydodson/Cryptocurrencies/blob/main/images/D4_2Dscatter.png) | 
   

<br>

---

.end
