# code-for-NNQR-in-currency
This is the code for CoVaR estimation, adjacency matrix calculation and various network topology metrics in the article " Risk Spillover between Cryptocurrencies and Traditional Currencies: An Analysis Based on Neural Network Quantile Regression". Here is what each file is used for
## "estimate_code.ipynb"
This code is used as, descriptive statistics, to estimate the VaR, to estimate the CoVaR using the NNQR, to compare the DM detection results (95% quantile) of the NNQR and the linear quantile model, to compute the adjacency matrix and to export the data, which allows for the generation of Panel A of Tables 1 and 2.
## "estimate_code-99QuantileDMtest.ipynb" 
This code is used as a way to calculate the DM test results for the NNQR and linear quantile models at the 99% quantile, which generates Panel B of Table 2.
## "network_topology"
This code is used as a network topology related metrics calculation that generates all the graphs in the article as well as Table 3. Note that the VaR,CoVaR, and adjacency matrix must be calculated and derived using “estimate_code.ipynb” before running this code.
## "estimate_data.xlsx"
This is the daily logarithmic yield file for the currencies used in the article.
## "VIX.xls"
This isthea file of the daily series of the VIX.
## “caviar”
This is a library for estimating VaR using the CAViaR model.
## References
Engle, R. F., & Manganelli, S. (2004). CAViaR: Conditional autoregressive value at risk by regression quantiles. Journal of business & economic statistics, 22(4), 367-381.

G. Keilbar, W. Wang, Modelling systemic risk using neural network quantile regression, Empirical Economics 62 (2022) 93–118.
