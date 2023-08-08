# Discharge Data Analysis and Modeling
This repository contains a Python script to analyze and model annual maximum discharge data. Example uses [Rio Caonillas at Paso Palma, PR - 50026025](https://waterdata.usgs.gov/monitoring-location/50026025/#parameterCode=00065&period=P7D).

### 1995~2023 return discharge calculation

<img src="https://github.com/snohatech/DischargeReturn/blob/main/dischargereturn/observedyear.png" width="800" height="600">

### 1000 year return discharge calculation

<img src="https://github.com/snohatech/DischargeReturn/blob/main/dischargereturn/1000year.png" width="800" height="600">

## Read a dataset with daily discharge measurements.
Extract the maximum discharge value for each year.
Model the annual maximums using various statistical methods, notably the LogPearson method.
Visualize the data and the modeling results.

Libraries: pandas, numpy, matplotlib, scipy, re, and os.

## Structure
The dataset [caonillas.txt]('https://github.com/snohatech/DischargeReturn/blob/main/dischargereturn/caonillas.txt') is expected to have:

Date: A date in a recognizable format | Value: Daily discharge measurements
