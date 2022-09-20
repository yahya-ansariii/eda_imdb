# Exploratory Data Analysis on IMDB data set
Exploratory data analysis on imdb dataset using pandas library

## Problem Definition
You have been hired by a rookie movie producer to help him decide what type of movies to produce and which actors to cast. You have to back your recommendations based on thorough analysis of the data he shared with you which has the list of 3000 movies and the corresponding details.

As a data scientist, you have to first explore the data and check its sanity.

Further, you have to answer the following questions:
- Which movie made the highest profit? Who were its producer and director? Identify the actors in that film.
- This data has information about movies made in different languages. Which language has the highest average ROI (return on investment)?
- Find out the unique genres of movies in this dataset.
- Make a table of all the producers and directors of each movie. Find the top 3 producers who have produced movies with the highest average RoI?
- Which actor has acted in the most number of movies? Deep dive into the movies, genres and profits corresponding to this actor.
- Top 3 directors prefer which actors the most?


## Motivation
To learn Python programming and use python package pandas for exploratory data analysis.

## Dependencies
- [Python](https://python.org) 3.9.5

- [Pandas](https://pandas.pydata.org) 1.2.4

## Conclusion
With the help of pandas library, the exploratory data analysis of the imdb_data.csv is done. The required data is imported from google drive to dataframe. The data is explored to evaluate the sanity and all only the required columns are used to create a working dataframe.

All the columns that had string data type for the list of dictionary were converted to the list datatype with the help of custom function and eval function. All the rows with null values in the working dataframe were dropped.

Solution to the questions are obtained by using various functions and methods.


## Author

[Yahya Ansari](https://github.com/novus-afk)
