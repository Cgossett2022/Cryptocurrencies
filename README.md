# Cryptocurrencies

## Overview
For this project, I used unsupervised machine learning to analyze various cryptocurrencies and determine how they could be grouped to create a classification system for an investment portfolio. In order to complete this project, I took the following steps: 

1. Preprocessed the Data for Principal Component Analysis (PCA)
2. Reduced Data Dimensions Using Principal Component Analysis (PCA)
3. Clustered Cryptocurrencies Using K-Means 
4. Visualized Cryptocurrencies Results


## Results

### Preprocessed the Data for PCA

I used pandas to read in the data and build a crypto dataframe.

<img width="436" alt="crypto_df" src="https://user-images.githubusercontent.com/111243284/211222102-62b97a5a-4698-4214-91f4-d32ef508b32c.png">


### Reduced Data Dimensions Using PCA

I built a new pcs dataframe which contains PC columns.

<img width="269" alt="pcs_df" src="https://user-images.githubusercontent.com/111243284/211222228-fee82280-8941-4972-9308-f940e311849b.png">


### Clustered Cryptocurrencies Using K-Means

1. I created an Elbow Curve based on the pcs dataframe

<img width="785" alt="elbow_curve" src="https://user-images.githubusercontent.com/111243284/211222444-ba8cd3dd-f53f-413d-80e0-f11783b817bf.png">


2. I created a clustered dataframe which combined the crypto_df and pcs_df.

<img width="796" alt="clustered_df" src="https://user-images.githubusercontent.com/111243284/211223619-3255de8d-f02a-4fb4-a5bd-ed737666fe82.png">


### Visualized Cryptocurrencies Results

1. I built a 3D-Scatter plot to illustrate the PCA data and the clusters.

<img width="777" alt="3d_scatter_plot" src="https://user-images.githubusercontent.com/111243284/211223626-2338d25a-a360-4395-a365-f18dd78aeae7.png">


2. I made a table which contains only the tradable cryptocurrencies and found that there are 532.

<img width="759" alt="tradable_crypto_table" src="https://user-images.githubusercontent.com/111243284/211223641-9de30520-7492-45d5-b81c-25dddb9030a2.png">


3. I created a plot dataframe which would includes the scaled data with the clustered dataframe.

<img width="456" alt="plot_df" src="https://user-images.githubusercontent.com/111243284/211223656-6cbde5f9-d3a3-4b40-9b92-5a1726e36785.png">


4. I created a scatter plot which displays Total Coins Supply, Total Coins Mined, Classes, and Coin Names.

<img width="759" alt="hv_scatter_plot" src="https://user-images.githubusercontent.com/111243284/211223665-df5eea0f-f8b4-4e61-886e-ffe65e80d847.png">


## Summary

Based on my analysis, the cryptocurrency investment can be divided into four classes. Each class would need to be thorougly analyzed to determine risk, performance, and other factors that would be of interest ot potential clients.
