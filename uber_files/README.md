## Table of Contents
- [Introduction](#introduction)
- [Process and Libraries](#Process-and-libraries)
  - [Process](#Process)
  - [Libraries](#Libraries)
- [Details](#details)
- [Geospatial Analysis](#geospatial-analysis)
- [License](#license)

## Introduction
An EDA project to anaylze the data of Uber pickups in NYC dataset which includes information of pick ups from 2014 to 2015.

## Process and Libraries
### Process
All files for the data were in csv format. I analyzed the data with Python in Jupyter Notebook.
 <li> 1.Data collected from Kaggle
 <li>2.Data Exploring/ Cleaning 🔍
 <li>3.Data Transformation 📦
 <li>4.Analyzing the data ⚡️
 <li>5.Visualisation 📊
 <li>6. Interpretation of the results 🧠

### Libraries
During the analysis, i used following libraries:

<li>Numpy
<li>Pandas
<li>Matplotlib
<li>Seaborn
<li>Geopy
<li>Scipy
<li>Plotly
<li>Folium
<li>h3-py

## Details

After cleaning and transforming the data, analyzed the dataset for the following questions:
<li> Which month has the most pickups? To find out the best season for Uber.
<li> On which day/hour is the busiest? Here I tried to find the rush hour of the New York City. For that, also binned the hours for every 15 minutes to have a better understanding.
<li>Detecting the trends as daywise and weekwise.
<li> Pairwise analysis for day and hour togetger.


  <img width="883" alt="uber_nyc_daytime" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/05a3d2e2-40d8-4bfc-97ef-3669cd62e351">

<li> Automating the pairwise analysis for the next pairs.


## Geospatial Analysis

<li>Created an interactive map to show rush locations on map using Folium.
<li> In the Choropleth notebook which is advanced, created a Choropleth hexagon map using geojson and h3-py, you can see below:

  <img width="1001" alt="choropleth" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/6ebf00be-0a55-437a-9069-7f21e1f61c64">


## License
This project is licensed under the [MIT License](LICENSE).

