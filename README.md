# Movie-Recommender
Movie Recommender System using Python (Machine learning)
Objective:
1. Create a popularity-based recommender system at a genre level. The user will input a 
genre (g), minimum rating threshold (t) for a movie, and no. of
recommendations(N) for which it should be recommended top N movies which are 
most popular within that genre (g) ordered by ratings in descending order where each 
movie has at least (t) reviews.

2. Create a content-based recommender system that recommends top N movies based on 
similar movie(m) genres.
  
3. Create a collaborative based recommender system which recommends top N movies 
based on “K” similar users for a target user “u”

Data Description
The data consists of 105339 ratings applied over 10329 movies. The average rating and 
minimum and maximum rating are 0.5 and 5 respectively. There are 668 users who have given 
their ratings for 149532 movies.
There are two data files which are provided:
Movies.csv
● movieId: ID assigned to a movie
● title: Title of a movie
● genres: pipe-separated list of movie genres.
Ratings.csv
● userId: ID assigned to a user
● movieId: ID assigned to a movie
● rating: rating by a user to a movie
● Timestamp: time at which the rating was provided.

Task To Be Done ::  Design the 3 different types of recommendation modules as mentioned in the objectives.
