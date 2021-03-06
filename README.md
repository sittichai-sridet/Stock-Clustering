# Stock-Clustering


## Introduction:
The stock selection to build a profitable portfolio remains to be a challenging task for investors. Stock price or future value of a stock is hard to estimate because of 
the daily changing and the sensitivity of stock market price, but not that each of the stock is changing or responding in the same way even in the same industrial sector
also has a different changes, stock price movement analysis is fluctuating and is efficient only in short period of time. In this research is going to introduce a time series
data transformation method using wavelet transform in each period then analyze slide windows (short-term) and long-term groups by different techniques to specify stock groups
that is likely to be similar representing the evolution of transition and direction at various times of the top 100 ranking in The Stock Exchange of Thailand (SET100 index). 
From Experimental, we found, the highest efficiency techniques for the slide window (short-term) is Kmeans algorithm and the long-term is Agglomerative hierarchical algorithm.
The correlation between stocks and its movement does not depend on industrial sector. Moreover, those patterns is able to specify investment behavior to be capable of increasing
an efficiency of managing investment and portfolio for investor

## Library
pip install PyWavelets
pip install sklearn

## Reference:
1. https://pywavelets.readthedocs.io/en/latest/
2. https://scikit-learn.org/stable/modules/clustering.html
3. https://ataspinar.com/2018/12/21/a-guide-for-using-the-wavelet-transform-in-machine-learning/
