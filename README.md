# anomaly
Tesseract - Anomaly Detection

Placeholder for development of anomaly detection algorithms for Project <<Tesseract>>
  
  Datasets that can be used for testing anomaly algorithms are taken from kaggle (source: https://www.kaggle.com/mczielinski/bitcoin-historical-data). 
  
  Author: Zielak (Mark Zielinski https://www.linkedin.com/in/mark-zielinski-95124943/)
  Bitcoin Historical Data

Bitcoin data at 1-min intervals from select exchanges, Jan 2012 to Jan 2018
Content
coincheckJPY_1-min_data_2014-10-31_to_2018-01-08.csv
bitflyerJPY_1-min_data_2017-07-04_to_2018-01-08.csv
coinbaseUSD_1-min_data_2014-12-01_to_2018-01-08.csv
bitstampUSD_1-min_data_2012-01-01_to_2018-01-08.csv

CSV files for select bitcoin exchanges for the time period of Jan 2012 to Jan 2018, with minute to minute updates of OHLC (Open, High, Low, Close), Volume in BTC and indicated currency, and weighted bitcoin price. Timestamps are in Unix time. Timestamps without any trades or activity have their data fields populated with NaNs. If a timestamp is missing, or if there are jumps, this may be because the exchange (or its API) was down, the exchange (or its API) did not exist, or some other unforseen technical error in data reporting or gathering. All effort has been made to deduplicate entries and verify the contents are correct and complete to the best of my ability, but obviously trust at your own risk.
