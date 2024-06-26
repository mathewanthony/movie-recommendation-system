
Movie Recommendation System
-

Introduction

This repository contains code for building a movie recommendation system using Python. The recommendation system utilizes various techniques such as content-based filtering and collaborative filtering to provide personalized movie recommendations to users.

Types of Recommender System
-


Demographic Filtering - Demographic filtering provides each user with generic recommendations based on the popularity and/or genre of films. Users that share similar demographic characteristics are recommended the same films by the system. Since every user is unique, this method is seen as excessively simplistic.

Content-Based Filtering - Content-based filtering suggests similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

Collaborative Filtering - Collaborative filtering matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.


Installation
-

To run the code in this repository, you'll need to have Python installed on your system along with the following libraries:

* pandas

* numpy

* matplotlib

* scikit-learn

* surprise


You can install these libraries using pip:
```bash
pip install pandas numpy matplotlib scikit-learn scikit-surprise
```

Usage
-

1. Clone this repository to your local machine or download the files directly.
2. Ensure you have the required dataset files (tmdb_5000_credits.csv and tmdb_5000_movies.csv) stored in the appropriate location or adjust the file paths in the code accordingly.
3. Open a terminal or command prompt and navigate to the directory containing the code files.
4. Run the Python scripts using the Python interpreter:
```bash
python movie_recommendation_system.py
```

* Follow the instructions provided in the code comments and output to explore the movie recommendation system functionalities.

Code Overview
-

* The movie_recommendation_system.py script contains the implementation of the movie recommendation system.
* It includes functions for data preprocessing, feature extraction, similarity computation, and recommendation generation.
* The code utilizes libraries such as pandas, scikit-learn, and surprise for data manipulation, feature extraction, and collaborative filtering.
* Various techniques such as TF-IDF vectorization, cosine similarity, and collaborative filtering (SVD) are employed to generate movie recommendations.
* The code provides options for exploring top-rated movies, popular movies, and generating personalized recommendations based on user preferences.

Conclusion
-

The movie recommendation system implemented in this code repository offers a basic framework for building personalized movie recommendation systems. By combining content-based and collaborative filtering techniques, the system can provide relevant movie suggestions to users based on their preferences and viewing history.
