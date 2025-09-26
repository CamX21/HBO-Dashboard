# HBO-Dashboard
HBO dashboard created from an HBO dataset using Power BI.
Overview:
For this project, I worked with a large dataset from HBO Max containing data about movies and shows. The goal was to analyze viewing trends and turn raw data into actionable insights. The motivation behind this project came from my interest in exploring entertainment data and applying my skills in building clear, engaging reports. This project allowed me to transform raw streaming data into meaningful visuals that highlight important patterns. The final report includes multiple visuals that explain trends in runtime, genre, popularity, ratings, and more.

Data Structure:
The dataset I worked with is large, having several columns that describe different details about movies and shows. Each row represents either a movie or a TV show entry.

Here’s a breakdown of some of the key columns in the dataset:

Name: The title of the movie or show

Runtime: Length of the movie or TV episode in minutes

Seasons: The number of seasons for a TV show

Genre: The category or type of content (e.g., Comedy, Drama, Action)

Release Year: The year the movie or show was released

IMDB Score: The rating given to the title by IMDB users

IMDB Votes: The number of votes received on IMDB

TMDB Popularity: A score showing how popular the title is on TMDB

Role: Information about people involved in the title (such as actors, directors, etc.)

This data structure made it possible to analyze movies and shows from different perspectives — like by genre, year, rating, popularity, or people involved.

Data Model:
For this project, I used a star schema model with additional bridge tables to handle complex relationships.

The main fact table is called Titles, which contains core information about each movie or show such as runtime, release year, scores, popularity, and seasons.

Dimension Tables:

People Table: Stores information about actors, directors, and others involved in productions.

Type Table: Breaks down entries into movies or TV shows.

Production Country Table: Lists the countries where titles were produced.

Genre Table: Contains a list of genres for classification.

Bridge Tables: Used to manage many-to-many relationships between titles, genres, and people.

This setup makes it possible to filter and slice the data easily in Power BI, creating dashboards that give clear insights into different aspects of the entertainment data.

Data Preparation:
Before analysis, I prepared the data to ensure accuracy and consistency:

Removed unwanted columns that weren’t relevant to the analysis.

Eliminated duplicate entries to prevent skewed results.

Changed data formats (e.g., converting runtimes into hours/minutes, formatting release years).

Created calculated columns for deeper insights.

Fixed misspellings and standardized text values for consistency.

Findings:
After analyzing the HBO Max dataset, I discovered several key insights:

The average runtime for highly rated movies is 1 hour and 51 minutes.

The most popular genre in 2022 was Comedy.

Drama has the most high-rated films overall.

TV shows with 9–12 seasons have the highest average popularity compared to shorter or longer series.

These insights provide a deeper understanding of viewing preferences, content performance, and trends in popularity, which could be useful for strategic decision-making in streaming services.
