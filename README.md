# Movies-Recommendation-system-
This project implements a movie recommender system using collaborative filtering with the K-nearest neighbors (KNN) algorithm. Collaborative filtering is a popular technique for generating recommendations by analyzing similarities in user-item interaction data.
Movie Recommender System with Collaborative Filtering using K-Nearest Neighbors (KNN)
This project implements a movie recommender system using collaborative filtering with the K-nearest neighbors (KNN) algorithm. Collaborative filtering is a popular technique for generating recommendations by analyzing similarities in user-item interaction data.


**Introduction****

This Python script demonstrates how to build a movie recommender system using collaborative filtering. It loads movie ratings and metadata, creates a user-item matrix, finds similar movies using the KNN algorithm, and recommends movies to users based on their highest-rated movie.


**Download datasets**
ratings.csv: Dataset containing user ratings for movies.
movies.csv: Dataset containing movie details (title, genres).
Data Description
ratings.csv: Contains user ratings for movies with columns userId, movieId, rating, and timestamp.
movies.csv: Provides movie details including movieId, title, and genres.
Usage
Basic Functionality
Basic Statistics:

Calculates and displays basic statistics about the dataset, such as the number of ratings, unique movies, unique users, and average ratings per user and movie.
User-Item Matrix Creation:

Converts the raw ratings data into a sparse user-item matrix using csr_matrix from scipy.sparse.
Finding Similar Movies:

Implements a function to find similar movies based on user ratings using the KNN algorithm with cosine similarity.
Movie Recommendations:

Provides functionality to recommend movies to a user based on their highest-rated movie using the KNN approach.
Algorithm Details
The movie recommender system utilizes collaborative filtering with the K-nearest neighbors (KNN) algorithm:

User-Item Matrix:

Creates a sparse matrix where rows represent movies, columns represent users, and cells contain ratings.
Finding Similar Movies:

Computes similarities between movies based on user ratings using cosine similarity.
Recommends movies to users by identifying movies with similar user ratings patterns.
Example Usage
Recommend Movies for a User:

Adjust the user_id in the script to recommend movies to different users based on their highest-rated movie.
Checking User Details:

Verify details of a specific user by setting user_id and checking their ratings in the dataset.
Contributing
Contributions to improve and extend the functionality of this movie recommender system are welcome! If you have suggestions, feature requests, or bug fixes, please fork the repository and create a pull request with your proposed changes.
