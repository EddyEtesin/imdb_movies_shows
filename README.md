# imdb_movies_shows

IMDB Movies and TV Shows Analysis
Overview
This project analyzes a dataset of movies and TV shows scraped from IMDB. The dataset contains information about titles, types (movie or show), release years, age certifications, runtimes, genres, production countries, seasons (for shows), IMDB IDs, IMDB scores, and IMDB votes. The analysis explores various aspects of the dataset to uncover trends and insights.

## Dataset Information
The dataset contains 5,806 entries with the following columns:

title: Name of the movie or TV show

type: Type of content (MOVIE or SHOW)

release_year: Year of release

age_certification: Age rating (e.g., R, PG, TV-MA)

runtime: Duration in minutes

genres: List of genres

production_countries: List of production countries

seasons: Number of seasons (for TV shows)

imdb_id: IMDB unique identifier

imdb_score: IMDB rating (out of 10)

imdb_votes: Number of votes on IMDB

## Key Questions Explored
Top 10 Movies/Shows by IMDB Score: Identified the highest-rated titles.

Most Common Genres: Determined the most frequent genres in the dataset.

Average Runtime Comparison: Compared the average runtime of movies vs. TV shows.

Top Production Countries: Listed the countries that produce the most content.

Age Certification Distribution: Analyzed the distribution of age ratings.

Release Trends Over Time: Examined how the number of releases has changed annually.

Most Voted Titles: Identified movies/shows with the highest number of IMDB votes.

Correlation Between Runtime and IMDB Score: Checked for any relationship.

Missing Data: Counted titles with missing IMDB scores or votes.

TV Show Seasons: Analyzed the distribution and average number of seasons.

Longest and Shortest Runtimes: Found titles with extreme runtimes.

Mature Audience Content: Counted titles rated for mature audiences (R, TV-MA).

Average IMDB Scores: Compared average scores for movies vs. TV shows.

Production Countries with Highest Scores: Identified countries with the highest average IMDB scores.

Most Common Genre Combinations: Listed the most frequent genre pairs.

Content Type Distribution Over Years: Tracked the number of movies vs. TV shows released annually.

Multi-Country Productions: Counted titles produced by multiple countries.

## Key Findings
Top-Rated Title: "Khawatir" and "#ABtalks" share the highest IMDB score of 9.6.

Most Common Genres: Drama (2,901), comedy (2,269), and thriller (1,178) are the top genres.

Runtime: Movies average ~99 minutes, while TV shows average ~39 minutes.

Top Production Country: The US produces the most content (2,327 titles).

Age Certifications: TV-MA (841) and R (575) are the most common mature ratings.

Release Trends: The number of releases peaks around 2019 (848 titles).

Most Voted Title: "Inception" has the highest number of IMDB votes (2,268,288).

TV Show Seasons: Most shows have 1 season, with an average of 2 seasons.

Mature Audience: 1,416 titles are rated for mature audiences (R or TV-MA).

IMDB Scores: TV shows (7.02) slightly outperform movies (6.27) on average.


## Dependencies
Python 3
pandas
matplotlib
numpy
seaborn


## Author
Etesin Ediomo Usoro
ediomoetesin40@gmail.com

