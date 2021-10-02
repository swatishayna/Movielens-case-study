## DESCRIPTION

## Background of Problem Statement :

The GroupLens Research Project is a research group in the Department of Computer Science and Engineering at the University of Minnesota. Members of the GroupLens Research Project are involved in many research projects related to the fields of information filtering, collaborative filtering, and recommender systems. The project is led by professors John Riedl and Joseph Konstan. The project began to explore automated collaborative filtering in 1992 but is most well known for its worldwide trial of an automated collaborative filtering system for Usenet news in 1996. Since then the project has expanded its scope to research overall information by filtering solutions, integrating into content-based methods, as well as, improving current collaborative filtering technology.

## Problem Objective :

Here, we ask you to perform the analysis using the Exploratory Data Analysis technique. You need to find features affecting the ratings of any particular movie and build a model to predict the movie ratings.

## Domain: Entertainment


## Dataset Description :

These files contain 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.

### Ratings.dat
    Format - UserID::MovieID::Rating::Timestamp

- Field	Description
- UserID	Unique identification for each user
- MovieID	Unique identification for each movie
- Rating	User rating for each movie
- Timestamp	Timestamp generated while adding user review
UserIDs range between 1 and 6040 
The MovieIDs range between 1 and 3952
Ratings are made on a 5-star scale (whole-star ratings only)
A timestamp is represented in seconds since the epoch is returned by time(2)
Each user has at least 20 ratings
 

### Users.dat
Format -  UserID::Gender::Age::Occupation::Zip-code

- Field	Description
- UserID	Unique identification for each user
 - Genere	Category of each movie
 - Age	User’s age
- Occupation	User’s Occupation
- Zip-code	Zip Code for the user’s location
All demographic information is provided voluntarily by the users and is not checked for accuracy. Only users who have provided demographic information are included in this data set.

Gender is denoted by an "M" for male and "F" for female
Age is chosen from the following ranges:


![age](https://user-images.githubusercontent.com/30625979/135703590-9fee0f1c-9bba-432c-8a6d-3e36f2efaf7e.png)
 

Occupation is chosen from the following choices:


![occupation1](https://user-images.githubusercontent.com/30625979/135703569-935ab364-e96a-478c-9d7b-7276b99a4b27.png)
![occupation2](https://user-images.githubusercontent.com/30625979/135703580-544dc5de-894e-4a2c-ba04-b2c09b92e08c.png)


## Movies.dat
- Format - MovieID::Title::Genres

- Field	Description
- MovieID	Unique identification for each movie
- Title	A title for each movie
- Genres	Category of each movie
 

 Titles are identical to titles provided by the IMDB (including year of release)
 

Genres are pipe-separated and are selected from the following genres:
Action
Adventure
Animation
Children's
Comedy
Crime
Documentary
Drama
Fantasy
Film-Noir
Horror
Musical
Mystery
Romance
Sci-Fi
Thriller
War
Western
Some MovieIDs do not correspond to a movie due to accidental duplicate entries and/or test entries
Movies are mostly entered by hand, so errors and inconsistencies may exist