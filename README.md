# Description

This repository contains datasets that can be used for online portfolio selection algorithms.
I collected the historical prices of 505 stocks that were the components of the S&P 500 on October 31, 2018. 
The data was obtained from Yahoo Finance. Out of the 505 stocks, I excluded the 111 stocks 
that were not listed on January 1, 2000 and 5 stocks whose data could not be retrieved correctly. 
I then sort the remaining 389 stocks in alphabetical order by the ticker symbols of
the companies and make 10 portfolios each of which contains 38 or 39 stocks in the order of the sort. 

# Folders

./csv: datasets in .csv format. The files whose name contain 'detail' include dates and ticker symbols.\
./mat: datasets in .mat format. Compatible with OLPS (https://github.com/OLPS/OLPS).
