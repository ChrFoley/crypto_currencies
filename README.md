# crypto_currencies

## Develping an unsupervised machine learning model, to develop a portfolio of investable cryptocurrencies.

### Development steps

#### 1) Data processing and cleaning.
 Data from CryptoCompare loadd into a Pandas DataFrame, this data was subsequntly cleaned and processed. This consisted of removing currencies that are not being traded, and those that do not have a defined crypto algorithm. Columns that were deemed not useful were removed, as were all currencies that had a null value. Any currency that did not currently have any currency mined was also removed. StandardScaler from Scikit.learn was utilized to standardize all of the data into a DataFrame as a preprocess for using PCA and K-means algorithms.
 
 #### 2) Develop a PCS DataFrameusing the crypto_df, and use K-means to develop a cluster and elbow diagram and a new dataframe that contains the processed clustered cryptocurrencies.
 
 #### 3) develop three different visualizations
  ##### a. Three demensional scatter plot
  ##### b. hvplot table
  ##### c. hvscatter plot
