
# Microsoft Movie Analysis

**Author**: [Muthomi Millicent Kanana](millicent.muthomi@moringaschool.com)

## Overview

Microsoft have decided to create a new movie studio and require more insight into which types of films are doing best at the box office. This project uses descriptive statistical analysis on data gathered from IMDb website to gain insight into which genres are most popular. Three seperate datasets were used for this analysis to gain insight into the top 5 most and least rated movies while taking note of their genres, genres of movies that topped the domestic gross sales, foreign gross sales and which genres had the top average ratings. The results of the top genres in Domestic Sales, Foreign Sales and number of productions was clearly the Adventure, Drama, Comedy and Action with adventure being present in the majority of the top categories. My recommendation for which type of Movie to produce would be Adventure, Drama, Comedy or Action as this is the most predominant genre in the analysis. I would advise Microsoft to produce a movie that belong to the Adventure, Drama or a combination of both incorporating Comedy and Action into it. The movie should also idearly last for less than 120 minutes.

## Business Problem

Microsoft want to produce movies that are going to be successful in order to make profits, they want to know which types of movies are the most successful. To answer that question both Domestic and Foreign Sales data was analysed to see the most financially successful genres, along with the average rating given and number of votes for each type or genre of movie to see how popularity compared with financial success.

## Data
The data analysed came from IMDb website. IMDb (an acronym for Internet Movie Database) is a popular worldwide online database of infomation relating to all movies, television programs, video games and streaming content online. I used 3 files from IMDb to answer the question of which genres were most successful, mainly focusing on the Domestic and Foreign Gross sales along with average ratings given and number of votes received.

After checking the information on each table to see column names and null values, I joined the two datasets, df_titles_basic_info and df_ratings together using the 'tconst' column as it was a unique identifier creating a new dataframe called merged_df2_df3. I then renamed the title column from df1 to primary title so that it may relate to the other data set that has already been merged. I then joined the dataset merged_df2_df3 with the df1 using the primary title as the unique identifier, creating a combined new dataset called data set.

Checking the information on the new dataframe, I then cleaned up the null values by filling them with the mean, for the non numeric values, filled it with the most common values, tidied up the "Domestic Gross' and 'Foreign Gross' columns and added the commas for easier readability and analysis. The column "original title" was deleted it was required to carry out this analysis

## Methods

The data analysed came from IMDb website. IMDb (an acronym for Internet Movie Database) is a popular worldwide online database of infomation relating to all movies, television programs, video games and streaming content online. I used 3 files from IMDb to answer the question of which genres were most successful, mainly focusing on the Domestic and Foreign Gross sales along with average rating. I mainly used bar graphs to model my data.

## Results
 - Top 5 genres with highest foreign gross is Drama, Adventure, Action, Comedy, Thriller
 - Top 5 genres with the highest domestic gross is Adventure, Action, Comedy, Drama, Sci-Fi
 - Top 5 genres that are mostly produced over the years Drama, Comedy, Action, Romance, Thriller.
 - Top 5 genres that are moslty rated Documentary, News, Biography, History, Sports.
 - The Top rated movies had the following genres Adventure, Documentary, Drama and Comedy.
 - Most rated movies do not last more than 120 minutes
 
Special emphasis on Adevnture and Drama genres that top the highest foreign gross and most produced films.


## Conclusions

From the data collected and analyzed, we can conclude that.
 - The population loves the following genres; Adventure, Drama, Comedy and Action films that appear most in the top lists.
 - The ratings of a movie may not necessarily accurately depict a movies popularity ( Documentaries, News.)
 - Our movie should not last more than 120minutes.


### Next Steps

 - We could consider the age range from which this statistics were collected.
 - We can look at which months was a specific movie genre produced, e.g February, Romace movie because of Valentines.



## Repository Structure

```
├── Presentation pdf.pdf
├── README.md
├── Microsoft_movie_analysis.ipnb

```
