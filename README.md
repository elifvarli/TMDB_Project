# TMDB_Project
- The analysis begins with loading the dataset TMDB_movies.csv and performing routine checks on the data, such as checking for missing values and data types of columns.
- A function concatenate_json is created to extract information from JSON-like strings in the dataset's columns. This function is applied to columns containing JSON-like strings, such as genres and keywords, to extract relevant -information and create new columns.
- Some columns that are not going to be included in the analysis are dropped to simplify the dataset.
- The top 10 most popular movies are identified based on the popularity column. A bar plot is created to visualize the number of votes for these movies.
- The top 10 highest-rated movies are identified based on the vote_average column. Another bar plot is created to visualize the average vote for these movies.
- Correlations between popularity and other numerical features are explored, indicating that vote counts and revenue are strongly correlated with popularity.
- Scatter plots and bar plots are used to investigate relationships between budget, popularity, and vote counts. It's observed that higher budget or revenue does not necessarily lead to higher popularity.
- The relationship between genres and vote counts is explored. Adventure and Science Fiction genres tend to receive higher vote counts on average.
- The relationship between keywords and vote counts is explored, indicating that specific keywords do not have a significant impact on vote counts.
- Further analysis is conducted on specific movies, such as "Minions" and "The Shawshank Redemption," to understand why they are popular or highly rated.
- The analysis concludes that popularity does not necessarily correlate with higher ratings, and further investigation is needed to understand the factors driving popularity and ratings for specific movies.
Overall, the analysis covers basic data loading, data cleaning, visualization, and deeper insights into specific movies based on popularity and ratings.
