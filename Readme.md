# Hidden Markov Models (HMM) and Linear Dynamical Systems (LDS) - Estimate Sequential Data with Hidden States in Python

In this repository, I'll introduce you famous machine learning methods to analyze sequential data, Hidden Markov Models (HMM) and Linear Dynamical Systems (LDS). These both models are mixture models, in which the choice of mixture component for each observation will depend on the choice of component for the previous observation.<br>
Historically hidden Markov models (HMM) and linear dynamical systems (LDS) were developed independently, however, these models have the deep relationship as you will find in these examples.

When there exist some sequential pattern in data, in which the sets of data is not independent or identically distributed (shortly, i.i.d.), these examples (tutorials) will help you find patterns in Markov chain.

To make you have a clear picture for how it will be resolved in mathematics, I'll also give you mathematical descriptions, with clear examples in Python script. (I'll construct programming code from scratch without packages in Python, as possible.)

- [Hidden Markov Models (HMM)](01-hmm-em-algorithm.ipynb)
- [Linear Dynamical Systems (LDS)](02-lds-em-algorithm.ipynb)

> Note : For time series in sequential data, see "[Introduce Time Series Analysis with ARIMA](https://tsmatz.wordpress.com/2017/07/26/time-series-arima-r-tutorial-01-ar-ma/)".

Reference : "[Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf?ranMID=24542&ranEAID=TnL5HPStwNw&ranSiteID=TnL5HPStwNw-g4zE85KQgCXaCQfYBhtuFQ&epi=TnL5HPStwNw-g4zE85KQgCXaCQfYBhtuFQ&irgwc=1&OCID=AID2200057_aff_7593_1243925&tduid=%28ir__vhvv9m6caokf6nb62oprh029if2xo0rux3ga300300%29%287593%29%281243925%29%28TnL5HPStwNw-g4zE85KQgCXaCQfYBhtuFQ%29%28%29&irclickid=_vhvv9m6caokf6nb62oprh029if2xo0rux3ga300300)" (Christopher M. Bishop, Microsoft) Chapter 13
