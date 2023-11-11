# Movie-Recommender
Movie Recommender System using Python (Machine learning)
Objective:
1. Create a popularity-based recommender system at a genre level. The user will input a 
genre (g), minimum rating threshold (t) for a movie, and no. of
recommendations(N) for which it should be recommended top N movies which are 
most popular within that genre (g) ordered by ratings in descending order where each 
movie has at least (t) reviews.
Example:
Input: 
• Genre (g) : Comedy
• Minimum reviews threshold (t): 100
• Num recommendations (N) : 5
Output:
S.No Movie Title Average Movie Rating Num Reviews
1 A 4.5 422
2 B 4.4 495
3 C 4.3 342
4 D 4.22 531
5 E 4.21 454
2. Create a content-based recommender system that recommends top N movies based on 
similar movie(m) genres.
Example:
Input:
• Movie Title (t): Toy Story
• Num recommendations (N): 5
Output:
Sl.No Movie Title
1 A
2 B
3 C
4 D
5 E
Certification Project
© B r a i n 4 c e E d u c a t i o n S o l u t i o n s P v t . L t d Page 3
3. Create a collaborative based recommender system which recommends top N movies 
based on “K” similar users for a target user “u”
Example:
Input:
• UserID: 1
• Num recommendations(N): 5
• Threshold for similar users (k: 100
Output:
S.No Movie Title
1 A
2 B
3 C
4 D
5 E
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
Certification Project
© B r a i n 4 c e E d u c a t i o n S o l u t i o n s P v t . L t d Page 4
Steps and Tasks
● Import libraries and load dataset
● Exploratory Data Analysis including:
o Understanding of distribution of the features available
o Finding unique users and movies
o Average rating and Total movies at genre level.
o Unique genres considered..
● Design the 3 different types of recommendation modules as mentioned in the objectives.
