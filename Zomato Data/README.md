## Table of Contents
- [Introduction](#introduction)
- [Process and Libraries](#Process-and-libraries)
  - [Process](#Process)
  - [Libraries](#Libraries)
- [Details](#details)


## Introduction
One of my favorite project, made with Zomato dataset includes restraurants,ratings, locations, comments. I used nltk for NLP and Geopy along with the other libraries. The project includes 2 notebooks: 1-Zomato data and 2-Zomato_different_approach.The second one is slightly more advanced than the first one. I separated them to have a cleaner view.   

## Process and Libraries
### Process
Data was in SQL format, used it with server connection. I analyzed the data with Python in Jupyter Notebook.
 <li> 1.Data collected from Kaggle
 <li>2.Data Exploring/ Cleaning 🔍
 <li>3.Data Transformation 📦
 <li>4.Analyzing the data ⚡️
 <li>5.Visualisation 📊
 <li>6. Interpretation of the results 🧠

### Libraries
During the analysis, i used following libraries:

<li>Numpy              <li>keras
<li>Pandas             <li>sklearn
<li>Matplotlib         <li>gensim
<li>Seaborn            <li>tf-idf
<li>NLTK               <li>word2vec
<li>Geopy
<li>Plotly
<li>Folium


## Details

Zomato dataset gives chance for different approaches as it includes variety of data. In the first notebook, I analyzed the following topics:
<li> How online order and rating is related? I also normalized the data to have a better picture.
<li> What are the most used words in reviews? Using NLP, running unigram,bigram and trigram analysis. An example: bigram analysis of 'Quick Bites' restaurant type's comments:

<img width="571" alt="Screenshot 2023-08-10 at 12 50 23" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/551ac685-6e2b-4657-868a-e26e60217099">


<li>Showing restaurants in an interactive map-here I used Folium map.
<li> An example map for finding certain type of cuisines-in my example it is North Indian cuisine and then automated the map for all cuisines in the dataset.

In the second notebook which is little more advanced, I used deep learning libraries along with the others. In detail: 
<li>Restaurants with most outlets.
<li>Restaurants accepts online orders/table booking availability.
<li> Rating distribution.
<li> Cost of food for two and rating relationship

<img width="837" alt="Screenshot 2023-08-10 at 13 22 44" src="https://github.com/lilalayla/Data_Analysis_Projects/assets/126274626/f9ae8f04-d73e-41ba-94f2-f6bcef8f9324">


<li>Most common restaurant types
<li>Best budget resturants in the given location, showing on interactive map, automated
<li>Foodie areas and most common cuisines in the given location, again on folium map and automated

The second notebook is still on going, current one is not pushed as there is a server problem(500) in geopy nominatim at the moment.

