# Netflix-movies-report-analysis
## Aims and Objectives
1. To know the country with the most movies on Netflix

2. To determine the most watched movies on the app

3. To know the oldest movies on Netflix

4. To know the trend in movies addition per year on the app

## Data Source
The data was an open source gotten from twitter, mainly for practices of my SQL skills 

## Data Cleaning and Preparation
The data was a csv file before being imported to my sql, did neccessary cleaning using excel cleaning tools, like splitting the date added to days, month, and year also with the date released too to ease my analysis. After which data has 13 Attributes and 8769 records, the attributes are as follows; show_id, Type, Title, Directors, country, date_added, Release_year, ratings, duration, listed_in, month_added, day_addede, year_added.

## Explaining all columns
Show_id: This is a unique serial number that is assign to every show to identify each of the show;

Type: This only have two things, movies and tv shows, the tells the tye of show;

Title: The main identifier of every shows, its the name given to the show, and it is use to look up the shows on the platform

Directors: The director is like a scientist that produced a drug, he directed every steps of the shows

Country: That is the country of production of the show

Date_year: This is the exact added the movies are added to each platform. And it's denoted in mm/dd/yyyy format

Released_year: This shows the year each shows were released, and it's denoted in yyyy format

Ratings: This the average viewer remarks on the shows

Durations: this is the time needed to complete each shows, and are categorised into two, mminute, and seasons, each representing Movies and Tv shows 

Listed_in:  This shows the categories of movies they are as either to who cn watch it

Month_added: shows the month they are added to platform

Day_added: The day of the month they are added

Year_added: Shows the year they are added to platform
