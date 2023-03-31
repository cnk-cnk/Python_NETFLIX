# Python_NETFLIX
This data set include information on movies and tv-shows added on netflix from 2008 to 2021, downloaded from Kaggle.
# Analysis objective on a NETFLIX Dataset from Kaggle
- Netflix got more movies or TV shows  
- Number of films and television programs added to the platform yearly
- What is the annual average number of movies and tv shows added to the platform  
- How long it takes for a movie or tv-show to be added to NETFLIX after its relaese date 
- Time interval difference distribution between date added on NETFLIX and release date of Movies and TV shows  
- Movies and TV Shows duration distribution 
- Movies and TV Shows Ratings
- Locations where movies and tv shows were produced
# Data Analysis process
- I started by importing the data to my jupyter notebook
- Exploration of the different columns, records of dataframe
- Data cleaning and reshaping my data based on the analsyis objective
- Answering the business task listed above
# Findings
- We observe that we have more Movies than TV shows added on NETFLIX

- We have a lot of variations throughout the years. We first have very few and constant
addings from **[2008 - 2014]** for Movies, a sudden rise from **[2014 - 2018]** then a fall from
**[2018 - 2021]**
For TV shows, we have addings in 2008, then no addings up to 2013. From 2013 we
experience a rise and a fall from 2019
More to that we have 10 records of TV-shows, where we don't have a date added value

- On average (yearly) we have **267 TV shows** and **438 Movies** added on NETFLIX from our
sample data (dataset)
From the adding trend, there is alot of variation throughout the years, the yearly
average varies a lot, we can't give a firm conclusion, that each year we will fairly expect
the above calculated average values.

- We have a negative linear relationship, as the years increase the time NETFLIX takes to
add a movie or TV-show to its platform reduces, this is pretty good
By the year 2013 we have approxiamtely 1 year for an adding, for the years >2016 the
addings are done in less than a year.

- The bottom 50 % of movies has a duration < 95 min and the upper 50 % of movies
has a duration > 95 min
The bottom 25 % of movies has a duration < 85 min and the upper 25 % of movies
have a duration >115 min
There is a lot of variation in the data, the median does not cut exactly at half of the
boxplot, the data is skewed to the right... thereby dragging the mean value to a higher
duration
We also have outliers represented by extreme congested circles, these are Movies that
have duration < 45 min and > 150 min

- The bottom 50 % of TV shows has 1 season, there is no variation that is why we have
no box or tail below the median of the boxplot
The upper 50 % of TV shows has more than 1 seasons
The upper 25 % of our data has more than 2 seasons and a maximum of 3 seasons,
with outliers that ranges from 4 seasons to 17 seasons
There is a lot of variation in the duration of TV shows as compared to Movies, it is
highly skewed to right

- Generally, we have more videos(movies & tv-shows) in the ratings TV-MA, TV-14, TVPG, R which are for mature, adult audiences and may be unsuitable for children under 17
For a young audience we have: PG-13 more in movies than tv-shows(very few), 
TV-Y and TV-G are more in tv-shows than movies
We have few movies and tv-shows for the ratings V-Y7-FV, NR,NC-17 and PG-13

- We have more movies produced in the United states, followed by India, Canada, etc.
More tv-shows in the United States, followed by United Kingdom, Canada, Japan,
India, etc.



