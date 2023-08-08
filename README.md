# Discharge Data Analysis and Modeling
This repository contains a Python script to analyze and model annual maximum discharge data.

<img src="[https://github.com/snohatech/StochasticRiverMigration/blob/main/JupyterNotebook/Img/1.png"](https://github.com/snohatech/DischargeReturn/blob/main/dischargereturn/observedyear.png) width="800" height="640">


## Read a dataset with daily discharge measurements.
Extract the maximum discharge value for each year.
Model the annual maximums using various statistical methods, notably the LogPearson method.
Visualize the data and the modeling results.

Libraries: pandas, numpy, matplotlib, scipy, re, and os.
To install the necessary libraries, use the following:

## Structure
The dataset (caonillas.txt) is expected to have:

Date: A date in a recognizable format.
Value: Daily discharge measurements.
