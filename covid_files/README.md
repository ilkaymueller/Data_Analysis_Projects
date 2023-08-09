## Table of Contents
- [Introduction](#introduction)
- [Process and Libraries](#Process-and-libraries)
  - [Process](#Process)
  - [Libraries](#Libraries)
- [Details](#details)
- [Geospatial Analysis](#geospatial-analysis)
- [License](#license)

## Introduction
An EDA project to anaylze the Covid19 data per country.

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
<li> Automating the pairwise analysis for the next pairs.

<img width="809" alt="Screenshot 2023-08-09 at 14 16 11" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/cee22f2c-0b2c-4262-aa3d-74d618a42526">


  
## Geospatial Analysis

<li>Created an interactive map to show rush locations on map using Folium.
<li> In the Choropleth notebook, created a Choropleth hexagon map using geojson and h3-py.

## License
This project is licensed under the [MIT License](LICENSE).

