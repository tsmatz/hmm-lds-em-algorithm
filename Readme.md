# Estimate Hidden Markov Models (HMM) and Linear Dynamical Systems (LDS)

**\- Estimate Sequential Data with Hidden States in Python \-**

In this repository, I'll introduce you machine learning methods, **EM algorithm**, to analyze sequential data, Hidden Markov Models (HMM) and Linear Dynamical Systems (LDS).<br>
These both models are mixture models, in which the choice of mixture component for each observation will depend on the choice of component for the previous observation.

To make you have a clear picture, I'll give you mathematical descriptions, with clear examples in Python script.

- [Hidden Markov Models (HMM)](01-hmm-em-algorithm.ipynb)
- [Linear Dynamical Systems (LDS)](02-lds-em-algorithm.ipynb)

When there exist some sequential pattern in data, in which the sets of data is not independent or identically distributed (shortly, i.i.d.), these tutorials will help you find patterns in Markov chain.

> Note : For time series analysis in sequential data based on AR (auto-regressive) and MA (moving average), see "[Introduce Time Series Analysis with ARIMA](https://tsmatz.wordpress.com/2017/07/26/time-series-arima-r-tutorial-01-ar-ma/)".

## Reference

This program code is inspired by Chapter 13 in "[Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf?ranMID=24542&ranEAID=TnL5HPStwNw&ranSiteID=TnL5HPStwNw-g4zE85KQgCXaCQfYBhtuFQ&epi=TnL5HPStwNw-g4zE85KQgCXaCQfYBhtuFQ&irgwc=1&OCID=AID2200057_aff_7593_1243925&tduid=%28ir__vhvv9m6caokf6nb62oprh029if2xo0rux3ga300300%29%287593%29%281243925%29%28TnL5HPStwNw-g4zE85KQgCXaCQfYBhtuFQ%29%28%29&irclickid=_vhvv9m6caokf6nb62oprh029if2xo0rux3ga300300)" (Christopher M. Bishop, Microsoft).<br>
For the further reading, see "Pattern Recognition and Machine Learning".
