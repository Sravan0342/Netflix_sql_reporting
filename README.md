# Netflix_sql_reporting

![Netflix logo](https://github.com/Sravan0342/Netflix_sql_reporting/blob/main/logo.png)

## Objective

This a comprehensive analysis of Netflix's movies and TV shows information utilizing SQL. The objective is to extract significant bits of knowledge and answer different business questions in view of the dataset. 

## Objectives
Analyze the distribution of content types (movies vs TV shows).
Identify the most common ratings for movies and TV shows.
List and analyze content based on release years, countries, and durations.
Explore and categorize content based on specific criteria and keywords.


## Dataset 
The data for this project is sourced from the Kaggle dataset:

- **Dataset Link:** [Movie Dataset](https://github.com/Sravan0342/Netflix_sql_reporting/blob/main/netflix_titles.csv)

## Schema

***sql
--Netflix project

DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
***

