# IMDB Top 1000 Movies Analysis

This project involves analyzing a dataset of the top 1000 movies on IMDB. Using Python and libraries such as Pandas, Matplotlib, and Seaborn, we perform exploratory data analysis (EDA) to identify patterns and trends in the dataset, analyze the distribution of genres, ratings, runtime, and other attributes, identify top directors and genres based on metrics such as number of movies, ratings, and revenue, and visualize findings using plots and charts.

## Dataset Description
The dataset contains information about the top 1000 movies on IMDB. 
| Column Name        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| **Poster_Link**    | URL link to the movie's poster as displayed on IMDB.                       |
| **Series_Title**   | The title of the movie.                                                    |
| **Released_Year**  | The year the movie was released.                                           |
| **Certificate**    | The age certificate assigned to the movie (e.g., PG, R, U, etc.).          |
| **Runtime**        | The total runtime of the movie in minutes.                                 |
| **Genre**          | The genre(s) of the movie (e.g., Drama, Action, Comedy).                   |
| **IMDB_Rating**    | The movie's rating on IMDB (out of 10).                                    |
| **Overview**       | A brief summary or description of the movie's plot.                        |
| **Meta_score**     | The movie's Metacritic score (out of 100).                                 |
| **Director**       | The name of the director(s) of the movie.                                  |
| **Star1**          | Name of the lead actor or actress.                                         |
| **Star2**          | Name of the second lead actor or actress.                                  |
| **Star3**          | Name of the third lead actor or actress.                                   |
| **Star4**          | Name of the fourth lead actor or actress.                                  |
| **No_of_votes**    | Total number of votes the movie received on IMDB.                          |
| **Gross**          | Total gross revenue earned by the movie (in USD, typically in millions).   |

---


# Exploratory data analysis

## Number of movies released per year

As expected most movies were released after year 2000.

![obraz](https://github.com/user-attachments/assets/d02b73b2-10a1-4adc-b600-51ecd37e1e1f)


## Distribution of IMDB Ratings and Metacritic score

Most movies were rated at around 8/10

![obraz](https://github.com/user-attachments/assets/a99b7757-eb21-4a5c-95fa-8200c9ba005b)

## Runtime distribution

Most movies are barely two hours long.
![obraz](https://github.com/user-attachments/assets/0288e1fb-066a-441f-97ec-0749ec2730e7)

## Regression analysis IMDB Ratings/Metacritic score vs Gross Revenue

As IMDB Rating increases, so does the revenue, but as metacritic score increases the revenue decreases slightly
![obraz](https://github.com/user-attachments/assets/cbab1940-48c3-4f81-a9e3-fc86eaaa142f)


## Directors analysis
There's not a lot of overlap between top directors by number of movies released, average IMDB rating and gross revenue.

None of the directors with highest IMDB rating are present in other charts.

![obraz](https://github.com/user-attachments/assets/fb5abced-81cf-4f04-8404-e2104887ea7e)

## Genre analysis
By far the most popular genre is Drama, dwarfing all the others. Surprisingly the gap in gross revenue between drama, adventure and action is not as big as the number of the movies.

![obraz](https://github.com/user-attachments/assets/d7ef6d83-94c4-4342-8c90-ba9e9c399689)

## Top movies analysis

The only movie that's in both top 10 is "The Dark Knight", suggesting that highly rated movies may not be highly popular.

![obraz](https://github.com/user-attachments/assets/bfb58f01-44ec-4935-a84b-299580a347b6)

