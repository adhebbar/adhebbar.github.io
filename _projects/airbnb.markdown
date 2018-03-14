---
layout: post
title:  "Airbnb San Francisco data analyzer (November 2017)"
tags: python machine-learning scikit-learn javascript HTML CSS google-maps-API data-analysis 
sidebar: true
text: true
description: Designed a webapp that uses Machine learning to analyze, map and graph Airbnb Data.
image: /assets/images/projects/webapp.jpg
---
Designed a webapp that uses Machine learning to analyze, map and graph Airbnb Data. This was a solution adressing a [mindsumo challenge](https://www.mindsumo.com/contests/airbnb-sf) 

I split this problem into three main parts: 

1) Processing the data, and storing it in formats that could most easily be used by the browser.  
  I created a script in Python (airbnb.py) to do this for me. It processed the CSV files, extracted useful data for each graph and prediction, and stored them in json format in the javascript files buisnessesData.js (for buisnesses vs independant pie chart), neighbourhoodsData.js (for listings per neighbourhood bar chart), map.js ( for google maps api) and optimizerData.js (to store data for price optimization). The script also performed some basic linear regression machine learning, to build up a model for revenue estimation.  

2) Creating the graphs, as well as revenue prediction/ price optimization.  
  generated the graphs and map in the javascript file graphs.js, and I did the revenue prediction/ price optimization in optimize.js. I made use of the google api to generate the map, as well as mdbootstrap to generate graphs easily.  

3) Making the UI   
I used a bootstrap template from w3 schools. Unfortunately, I was not very careful, and the website can only be viewed from medium sized laptop for best results.  

The webapp is currently hosted with CMU web service [here](http://www.andrew.cmu.edu/user/ahebbar/webapp/) 

 

I was one of 40 students from 500+ applicants to be selected to attend a one week long 
Software Engineering Summit in Capital One’s corporate headquarters on the basis of this project.



