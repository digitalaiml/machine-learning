# Movie Keyword Model:

This repository is for Jupyter Notebook(s) that are used to develop and refine our machine learning algorithms.

We use scikit-learn TF-IDF to extract important keywords from a movie plot to characteriorze in the collected texts. These keywords cab be used as a very simple summaries or topics for the text selected from the movie episode, which can also be one of the sources in the following content-based movie recommendation engine.


## Movie Recommendation Model:

Our movie recommendation system is a machine learning content-based engine since we make predictions based on the specific contents in the movie plot and not based on the user. We used contens of genres, title, overview and taglines in the movie plot to recommend 10 similia movies. In order to enhance and provide more accurate similia movies, we added some statistic analysis on 'vote_average' and 'vote_cont' in moview data set. We calculate average of vote, filter out all qualified movies, and compute the weighted rating of each movie.
