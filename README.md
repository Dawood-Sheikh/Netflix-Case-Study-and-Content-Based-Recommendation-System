# Introduction

In this project, we have worked on analyzing and visualizing of the data for Netflix by doing EDA using variables provided for addition of content. We have several 
features to do analysis and find out interesting observations. The target of this work is to utilize and execute the ML model utilizing SciKit-learn, find designs
that determine clients' interest in regards to the nature of the services given by the company and analyzing the facts to find out the trend of the content in 
different parts of the world.

The popularity of Netflix is known throughout the world as a media and video streaming platform. As of mid2021, the platform have over 8000 movies or TV shows available
for 200M+ subscribers globally. This dataset consists of all the movies and TV shows available on Netflix, along with their details such as - release year, duration cast, directors, ratings, etc.

In this project, we focused on the EDA/visualization and creating a recommendation system of the dataset. This analysis gives us better understanding towards the nature
of the content in different countries and the target audiences of the platform.

# User Requirements

* Hardware requirements:
  1. Operating system- Windows 7,8,10
  2. Processor- Dual core 2.4 GHz (i5 or i7 series Intel processor or equivalent AMD)
  3. RAM - 4GB
* Software Requirements:
  1. Python 3.8
  2. PyCharm
  3. PIP
  4. Jupyter Notebook
  5. Anaconda
  6. Chrome
  7. Cloud Environment to Deploy Model

# Attributes & Data Fields:

We have used a data set uploaded by Shivam Bansal on Kaggle for cognition purpose. You can download the data set from this link https://www.kaggle.com/datasets/shivamb/netflix-shows .
It consists of one files, name as '**netflix_titles.csv**' which contains 8807 records (rows) and 12 features (columns). They are:

Features | Description
---------|-------------
show_id | Unique ID for every content
type | Identifier for Movie or TV Show content
title | Title of the content
director | Director of the Movie
cast | Actors involved in the content
country | Country/countries where the movie / TV show was produced
date_added | Date it was added on platform
release_year | Actual Release year of the move / TV show
rating | Rating of the movie / TV show by rating board
duration | Total Duration of the content - in minutes or number of seasons
listed_in | Genres of the content
description | The summary description

---
# Code is uploaded and accessible for knowledge purpose!

# Conclusions:

## Case Study:

* The total amount of content available on the platform is more of a movie type. It varies from country to country, but the 
  majority do prefer movies to TV shows.

* More than 90% of the content available in India on Netflix is of movie type. Netflix India does have done their research 
  while adding content, but the trend of watching TV series is increasing.

* Most content is targeted towards Mature/Adults and Teenagers based on the ratings (TV-MA and TV-14).

* The average duration of the movies added of the 2000s and after is 125 mins(2.08hrs).

* More than half of the TV series on the platform has only 1 season.

* Movies comprise 20 types of genre categories whereas, TV Shows comprise 22 types of genre categories.

* International Movies/TV Shows are the most common genre in all the content, followed by Dramas/TV Dramas and Comedies/TV Comedies.

* Around 46% of the content is targeted toward Adults. This percentage does change from country to country based on the target 
  audience to that Netflix is providing its service.

* There is no particular celeb or director whose content is more than others on the platform. Some have more content than other, 
  but not enough to dominate the market of their respective regions.

## Recommendation System:

* A plot-based recommendation system may work fine if it were the only important feature present in our dataset, although cast, 
  director, and genre also play an important role in creating a good recommendation system.

* While country, rating, release year, and other features present in the dataset are significant, they are not essential in 
  creating a content-based recommendation system. If they are included, the system will generate incorrect suggestions and will 
  be meaningless.
  
# Bibliography:

* **Dataset Link** - https://www.kaggle.com/datasets/shivamb/netflix-shows
* **Kaggle** - https://www.kaggle.com/
* **Google** - https://www.google.com
* **Matplotlib** - https://matplotlib.org/
* **Seaborn** - https://seaborn.pydata.org/
* **Scikit-learn** - https://scikit-learn.org/stable/
