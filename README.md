# Project Motivation
A look at Airbnb listings in Edinburgh. I want to know whether review scores can be used to predict predict the price of a listing. I would also like to know which areas are more or less expensive so that I can make more informed decisions next time I visit. Finally, I am interested in exploring the change in supply and whether it affects the average price in a neighbourhood. 

This has been part of my Udacity Data Scientist Nanodegree.

# Summary
I ask three questions in this notebook:

1) Can I predict the price of a listing from its review scores? I find that, using a simple linear regression model I cannot.

2) How does the average price of a listing vary by neighbourhood? In 2018, Southside is the most expensive neighbourhood (~£105 per night) while Leith is the cheapest (~£65 per night).

3) Is there a relationship between how much supply a neighbourhood adds relative to its neighbours and the change in its relative price. I use data from 2014 and 2017 and find that, although supply has gone up accross the city and prices have generally come down, there was no significant correlation amongst neighbourhoods.

# Installations
Python 3
Jupyter
Numpy
Pandas
Scikit-Learn
SciPy
Matplotlib
Tqdm

# Data sources
Both the datasets I used came from Inside Airbnb. You can find them at the following links:
http://insideairbnb.com/get-the-data.html and http://insideairbnb.com/edinburgh/
