# FlatIron Capstone: Letterboxd Recommendation System

## Business Case:
Through this project, we aim to create various recommendation systems that will recommend 5 movies to any given Letterboxd user using various methods including non-personal recommendations, Surprise and PySpark. 


## Methodology:
There are two main notebooks used for this project. The first was used to gather data from Letterboxd and TMdB. The other notebook is where the meat of the recommendation system code is located. 


### Data Notebook Methodology
1. Import necessary libraries including Beautiful Soup, Pandas, and Requests.
2. Create a function the scrapes the the usernames that follows the given username and returns the usernames in a list.
3. Run user_list function with 'fuchsiadyke' to scrape the usernames since they are followed by over 16,000 users ensuring we can easily gather over 2,000 usernames from them.
4. Create and run a function that uses the list of usernames to scrape user ratings from Letterboxd and store it in a dataframe.
5. Save the dataframe as a .csv file.
6. Create and run a function that scrapes information for the first 3000 pages of the most popular films on letterboxd. 
7. Create and run a function that scrapes director name, tmdb id, and whether it is a movie or tv show.
8. Remove the year from the movie name and create a new column with it.
9. Save the dataframe as a .csv file


### Recommendation System
Write about recommendation System

## The Data
Overview of data

## Results
overview of results

## Future Work
- tmdb
- front end/website
- recs based on other criteria
- expanded user base
- expanded film base

