# Project 3 - Weekend Movie Trip

### Scope

The datasets used in this project (linked below) contain movie review data from MovieLens, a movie recommendation service. The purpose of this project is to use a clustering model to find pockets of similar datapoints that can then be used to recommend movies to similar users.

### Results

I used the DBSCAN and Spectral Clustering models to cluster the movie data. Overall, both models produced similar results. The Spectral Clustering model produced cleaner results with more delineated clusters, but it was slower to execute as a result of higher complexity. The DBSCAN algorithm still produced reasonable results in most situations and was able to execute faster.

Please see the Jupyter Notebook for more details and further discussion.

### Data
Datasets obtained from:
1. https://grouplens.org/datasets/movielens/

### Relevant Variable descriptions
- userId: the ID for a given user
- movieId: the ID for a given movie
- Rating: A user's rating of a given movie. Ratings are made on a 5-star scale, with half-star increments (0.5 stars - 5.0 stars)
- Tag: A user's tag/comment about a given movie
- TitleOnly: The title of the rated and tagged movie
- Year: The year the movie was released
- Genres: the genre of the rated and tagged movie
- GenreCat: A categorization of the genre combinations
- tagSentiment: a score between -1 and 1. Scores less than 0 indicate negative sentiment, a 0 score indicates neutral sentiment, and scores greater than 0 indicate positive sentiment.


### References
1. To normalize the data: https://www.geeksforgeeks.org/implementing-dbscan-algorithm-using-sklearn/
2. To implement DBSCAN: https://medium.com/@mohantysandip/a-step-by-step-approach-to-solve-dbscan-algorithms-by-tuning-its-hyper-parameters-93e693a91289
3. To implement Spectral Clustering: https://www.geeksforgeeks.org/ml-spectral-clustering/
4. To create the tag sentiment variable: https://medium.com/swlh/simple-sentiment-analysis-for-nlp-beginners-and-everyone-else-using-vader-and-textblob-728da3dbe33d
