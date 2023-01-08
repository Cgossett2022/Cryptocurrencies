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

<img width="797" alt="clustered_df" src="https://user-images.githubusercontent.com/111243284/211222454-f65287a9-8ab8-414f-ae52-d21c9f1558de.png">


### Visualized Cryptocurrencies Results

1. I built a 3D-Scatter plot to illustrate the PCA data and the clusters.

<img width="778" alt="3d_scatter_plot" src="https://user-images.githubusercontent.com/111243284/211222509-b9685bf5-c33d-460b-ae3c-698f4179775f.png">

2. I made a table which contains only the tradable cryptocurrencies.

<img width="756" alt="tradable_crypto_table" src="https://user-images.githubusercontent.com/111243284/211222536-0017bfb2-c89d-4394-ad1d-eca02451be0a.png">


3. I created a final dataframe which would includes the scaled data with the clustered dataframe.

<img width="440" alt="plot_df" src="https://user-images.githubusercontent.com/111243284/211222606-d6b67365-b6f0-494a-93bd-ce82b08de534.png">

4. I created a scatter plot which displays Total Coins Supply, Total Coins Mined, Classes, and Coin Names.

<img width="748" alt="hv_scatter_plot" src="https://user-images.githubusercontent.com/111243284/211222646-e08f202c-e76f-43f2-b596-3a35d93a64d2.png">


## Summary

Based on my analysis, the cryptocurrency investment can be divided into three classes.
