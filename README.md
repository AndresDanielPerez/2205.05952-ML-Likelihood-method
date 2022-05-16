# A method for approximating optimal statistical significances with machine-learned likelihoods
https://arxiv.org/abs/2205.05952

Machine-learning techniques have become fundamental in high-energy physics and, for new physics searches, it is crucial to know their performance in terms of experimental sensitivity, understood as the statistical significance of the signal-plus-background hypothesis over the background-only one. We present here a new method that combines the power of current machine-learning techniques to face high-dimensional data with the likelihood-based inference tests used in traditional analyses, which allows us to estimate the sensitivity for both discovery and exclusion limits through a single parameter of interest, the signal strength. Based on supervised learning techniques, it can perform well also with high-dimensional data, when traditional techniques cannot. We apply the method to a toy model first, so we can explore its potential, and then to a LHC study of new physics particles in dijet final states. Considering as the optimal statistical significance the one we would obtain if the true generative functions were known, we show that our method provides a better approximation than the usual naive counting experimental results. 



Note: to run the W' example, you need the following file from https://zenodo.org/record/6466204#.YoIevTnMJH4:
events_anomalydetection_v2.features.h5
