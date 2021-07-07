#Movie Review Analysis using python

Scraped data from the 3 websites i.e [IMDB](https://www.imdb.com/chart/top "IMDB"),[Metacritics](https://www.metacritic.com/browse/movies/score/metascore/all/filtered?sort=desc "Metacritics") and [RottenTomatoes](https://www.rottentomatoes.com/top/bestofrt/ "RottenTomatoes") and created a single ipynb file (Samantha.ipynb).3 separate csv files (Top50_Imdb_movie.csv, Rotten_Tomatoes_top_50.csv, and Metactric_top_50.csv) are generated for each scraped website data which contains top 50 movies and genres. The data of the top_50_movies along with name, number and genre is also stored in the SQLite database (Top50.db). The database contains 3 tables, each for 1 website scrapped data. Cosine similarity score between the genres of movies ranked as top 50 across the 3 websites is generated which is 0.79.

###Steps to follow:
* Install SQLite database to store the Top50movies and Jupyter to run the code.