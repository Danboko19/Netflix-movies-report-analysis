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
## Result of the analysis
#### Q1)	What is the total number of records in the dataset?
The total records in the dataset are "8769".
![Q1](https://github.com/Danboko19/international-Brewery-report/assets/148493509/d38aee25-aa0e-4085-a1ca-80ca713cea6b)

#### Q3)  How many unique countries are represented in the dataset?
we have "86" distinct country in the dataset.
![q3](https://github.com/Danboko19/international-Brewery-report/assets/148493509/5fda3cf9-218c-4094-9a55-6f28a6cbe633)
#### Q4)  What is the earlist release year?
'1925'
![q4](https://github.com/Danboko19/international-Brewery-report/assets/148493509/ebb00b08-c422-4ff2-a2dc-3a2e145efde7)
#### Q5)  What is the most recent release year?
'2021'
![Q6](https://github.com/Danboko19/international-Brewery-report/assets/148493509/070c2e1b-55a5-497d-8e44-be46db3b08bb)
#### Q2)  what is the average duration of tv shows
The average durations of tv shows is "1.75 seasons"
![q2](https://github.com/Danboko19/international-Brewery-report/assets/148493509/9440e1bb-8301-409d-82fa-08ddaf41d923)
#### Q6)  How many tv shows were released in the united states?
A total of "844" tv_shows were released
![Q6i](https://github.com/Danboko19/international-Brewery-report/assets/148493509/733bf6bd-4e50-4fbc-9881-31b1ac75ba12)
#### Q7) What is the total duration of all the movies in the dataset?
The sum of the duration of movies is "608358"
![Q7](https://github.com/Danboko19/international-Brewery-report/assets/148493509/cf8f15cf-b9fd-4ab8-b0bf-472dabd82b3e)
#### Q8)  How many movies were released in 2015?
The total of movies released in 2015 was "396"
![q8](https://github.com/Danboko19/international-Brewery-report/assets/148493509/2c513535-89d5-433a-9f01-6e2249a01d70)
#### Q9)  Top 5 countries with the most movies in the dataset?
![q9](https://github.com/Danboko19/international-Brewery-report/assets/148493509/e0f00a3d-44e0-4798-b005-9d27445df785)
#### Q10)  What is the avearge duration of movies in the dataset?
The average duration of tv shows in the dataset is "99.63min"
![q10](https://github.com/Danboko19/international-Brewery-report/assets/148493509/846c9062-b9dd-4828-8fe5-59b8f04088ce)
#### Q11)  How many movies were directed by martin scorsese?
