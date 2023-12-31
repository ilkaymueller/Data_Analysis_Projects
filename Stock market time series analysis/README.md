## Table of Contents
- [Introduction](#introduction)
- [Process and Libraries](#Process-and-libraries)
  - [Process](#Process)
  - [Libraries](#Libraries)
- [Details](#details)

## Introduction
Stock market time series analysis with more than 500 datasets. 

## Process and Libraries
### Process
Data analyzed with Python in Jupyter Notebook. Used 'glob' to read all the files.
 <li> 1.Data collected online.
 <li>2.Data Exploring/Cleaning 🔍
 <li>3.Data Transformation 📦
 <li>4.Analyzing the data ⚡️
 <li>5.Visualisation 📊
 <li>6. Interpretation of the results 🧠

### Libraries
During the analysis, I used following libraries:

<li>Numpy
<li>Pandas
<li>Matplotlib
<li>Seaborn
<li>Plotly
  
## Details

Time Series Analysis for stock market prices. Sampled the 4 big companies' prices(Microsoft, Apple, Google, Amazon) to work with smaller data (due to cpu restrictions:)) 
<li> Calculated the mean prices of certain time windows(10,20,50 following days) using 'rolling' function.
<li> Comparison of closure prices for the specified time windows per company. Looks like this via Matplotlib: 

<img width="826" alt="Screenshot 2023-08-10 at 10 43 25" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/4f1602dc-7f5c-49f7-850a-b446e545bdeb">

  
<li> Daily returns of Apple stocks and resampling the Apple data montly and yearly basis to have more insights to detect the trends.

<img width="817" alt="Screenshot 2023-08-10 at 10 55 56" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/a7e0bf8e-19fe-47fe-b819-8f8f783ef07b">


<li> Checking the correlation between the closing prices of these 4 companies and used the heatmap below to build further graphs.

<img width="597" alt="Screenshot 2023-08-10 at 10 53 33" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/182901ec-8e4b-4bee-b3d5-3a3129a536af">

<li> Price change compare to previous day and final closing price for the day is correlated or not using pairgrid from seaborn.
