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

As IMDB Rating increases, so does the revenue. Metacritic score has very small impact
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

## Correlation Heatmap

![obraz](https://github.com/user-attachments/assets/7a0028ba-256d-4a2b-8d44-774b92981896)

## IMBD Rating Analysis

Runtime and gross revenue have very minimal impact on the rating. 

![obraz](https://github.com/user-attachments/assets/2e768fd6-5840-4903-aab6-3fe34deace0c)

## Temporal analysis

The average runtime has been steadily increasing. 

![obraz](https://github.com/user-attachments/assets/e9388579-be65-4456-90f8-2fd82df78b50)

## Actor analysis

Once again, there's not a lot of overlap between top actors by number of movies and revenue. Only Tom Hanks and Matt Damon are in both tops.

![obraz](https://github.com/user-attachments/assets/9e118f5c-9cdb-4b7d-a592-13e2de142a6a)

## Certificate analysis
Most movies received U certificate, followed by A and UA. Highest grossing certificate is UA. All of them mean that the movie is rated for everyone.

![obraz](https://github.com/user-attachments/assets/44089e51-0d95-4102-9b78-fcf047518b74)


