+++
title = "SRTT Distribution"
date = "2026-08-07"
aliases = ["srtt","distribution","projects"]
[ author ]
  name = "Alberto"
+++
The goal of the [**SRTT Distribution APP**](https://github.com/albertooof/SRTT_Distribution_APP) package is to provide a set of R functions for exploring how different statistical distributions fit *reaction time data* collected during a Serial Reaction Time Task (SRTT).

I created and currently use the package to investigate how **mean, variance, lag, and other distributional properties** change across different sample sizes and windows of reaction time data. The package allows me to compare different fitting approaches, including the **normal, gamma, and shifted log-normal distributions**, and to identify which distribution provides the best fit to the observed reaction time data.

A particular focus of the package is to examine how the choice of the fitting distribution changes depending on the **amount of data available**. The analyses show that when working with very small samples or very small windows of the data (e.g., around **1% of the total trials**), the normal distribution can provide the best fit. However, as the window increases (e.g., **>10% of the total data**), other distributions, such as the gamma or shifted log-normal, can provide better fits to the reaction time data. The package therefore provides a way to visualise and explore how the estimated distribution and its parameters change as progressively larger portions of the data are considered.

![SRTT_Distribution](/img/SRTT_Distribution.gif)


