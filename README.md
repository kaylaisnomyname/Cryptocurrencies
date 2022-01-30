# Cryptocurrencies

## Overview
Purpose of this challenge is to apply unsupervised machine learning models to create classification system for cryptocurrency investment.

Data source: [crypto_data.csv](https://min-api.cryptocompare.com/data/all/coinlist)  


## Results  
- D1: details shown in [code](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/crypto_clustering.ipynb)  
- D2: details shown in [code](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/crypto_clustering.ipynb)  
##### df with 3 PC:  
![df_3PC](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/df%20with%203%20PC.png?raw=true)  
- D3: predictions shown in [code](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/crypto_clustering.ipynb)   
##### Elbow Curve: 
![elbow_curve](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/elbow%20curve.png?raw=true)  
##### df with 3 PCs, CoinName, and class:
![D3_new_df](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/clustered_df%20shape.png?raw=true)  

- D4: Visualizations
##### 3D scatter plot:
![3D_scatter_plot](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/3D%20scatter%20plot.png?raw=true)  
##### Table of tradable cryptocurrencies:
![tradable_table](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/Tradable%20table.png?raw=true)  
##### Total number of tradable cryptocurrencies:  
![total_tradable_number](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/total%20tradable%20number.png?raw=true)  
##### df with scaled data:  
![scaled_df](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/new%20df%20with%20scaled%20data.png?raw=true)  
##### scaled data scatter plot:
![scaled_df_scatter_plot](https://github.com/kaylaisnomyname/Cryptocurrencies/blob/main/images/tradable%20scaled%20scatter%20plot.png?raw=true)  

### ps:
Challenge encountered: jupyter notebook kernel kept crushing when running KMean and plotly imports.  
Fixed: plotly installed with conda/pip was out of date and thus not function properly in jupyter notebook; Update plotly libraries in anaconda prompt have the issue fixed. 
