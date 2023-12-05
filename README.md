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
### General Analysis
####  What is the total number of records in the dataset?
The total records in the dataset are "8769".

![Q1](https://github.com/Danboko19/international-Brewery-report/assets/148493509/d38aee25-aa0e-4085-a1ca-80ca713cea6b)

####  How many unique countries are represented in the dataset?
we have "86" distinct country in the dataset.

### Date Analysis
![q3](https://github.com/Danboko19/international-Brewery-report/assets/148493509/5fda3cf9-218c-4094-9a55-6f28a6cbe633)
####  What is the earlist release year?
'1925'

![q4](https://github.com/Danboko19/international-Brewery-report/assets/148493509/ebb00b08-c422-4ff2-a2dc-3a2e145efde7)
####  what is earliest date added in the dataset?
01/01/2016 was the first date a show was added!

![Q18](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/f4c90dee-b658-41cb-ae3c-5cf5e588057e)
####  What is the most recent release year?
'2021'

![Q6](https://github.com/Danboko19/international-Brewery-report/assets/148493509/070c2e1b-55a5-497d-8e44-be46db3b08bb)
### Tv shows analysis
#### what is the average duration of tv shows
The average durations of tv shows is "1.75 seasons"

![q2](https://github.com/Danboko19/international-Brewery-report/assets/148493509/9440e1bb-8301-409d-82fa-08ddaf41d923)
#### How many tv shows were released in the united states?
A total of "844" tv_shows were released

![Q6i](https://github.com/Danboko19/international-Brewery-report/assets/148493509/733bf6bd-4e50-4fbc-9881-31b1ac75ba12)
#### What is the total durations of all the tv shows?
The total durations of all the tv shows is "4666 seasons"

![Q14](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/a40fd45c-e362-42fe-b5c8-df84c28faa8c)
#### How many tv shows were released in India?
"81" Tv shows were released in India

![Q17](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/55283bc8-e12e-4044-9900-54e060ce7666)
#### what is the maximum durtion of tv shows 
The maximum season on a single tv shows was "seasons"

![q12](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/6448777a-c1ee-43c8-a956-ee1e7ba65a56)

### Movies Analysis
#### What is the total duration of all the movies in the dataset?
The sum of the duration of movies is "608358"

![Q7](https://github.com/Danboko19/international-Brewery-report/assets/148493509/cf8f15cf-b9fd-4ab8-b0bf-472dabd82b3e)
#### What is total duration of all movies released in 2010
The total durations of all movies released in 2010 is "15853 minute"

![Q20](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/4d1c1f34-337e-42a5-adac-aad278b69849)
#### How many movies were released in 2015?
The total of movies released in 2015 was "396"

![q8](https://github.com/Danboko19/international-Brewery-report/assets/148493509/2c513535-89d5-433a-9f01-6e2249a01d70)
#### Top 5 countries with the most movies in the dataset?

![q9](https://github.com/Danboko19/international-Brewery-report/assets/148493509/e0f00a3d-44e0-4798-b005-9d27445df785)
#### What is the avearge duration of movies in the dataset?
The average duration of tv shows in the dataset is "99.63min"

![q10](https://github.com/Danboko19/international-Brewery-report/assets/148493509/846c9062-b9dd-4828-8fe5-59b8f04088ce)
#### How many movies were released in the United kingdom?
A total of "387" movies were released in the united kingdom

![Q13](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/65fbc4e7-5ded-4b1c-aa0e-ca55dbf846a2)
####  How many movies were relesed in canada?
"187" movies were released in canada

![Q15](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/a3815abb-5d31-4750-a559-4d78db4e1b14)

### Directors Analysis
####  How many movies were directed by martin scorsese?
Martin scorsese directed a totl number of 12 "movies"

![Q11](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/2143e4a8-640b-49a7-b2a5-aaf46d1c1dc6)

####  what is the total durations of movies directed by christopher Nolan?
Christopher Nolan directed just a movies with a duration of "148 minute"

![q16](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/652e9cf7-2811-4f05-bb21-5687faacebd4)

#### Q19)  How many movies were directed by Steven Spielberg?
Steve speilberg directed a total of "11" movies

![Q19](https://github.com/Danboko19/Netflix-movies-report-analysis/assets/148493509/a09ac98a-9bcd-4f9f-a394-b6cb4486c6e4)


