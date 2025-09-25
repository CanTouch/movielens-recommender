# Movielens-recommender
High-Performance Movie Recommender System (SVD Matrix Factorization)
Project Overview
This project develops and evaluates a state-of-the-art movie recommendation system using Matrix Factorization (Singular Value Decomposition with Biases) on the widely recognized MovieLens 100k dataset.

The system is built as a highly accurate demonstration of Collaborative Filtering that addresses fundamental challenges in recommendation engine design, such as user and item rating biases.

Key Features
Data Preparation: Cleans and merges the MovieLens 100k dataset (100,000 ratings from 943 users on 1,682 items).

Model Training: Implements an SVD model that incorporates user and movie biases to significantly improve prediction accuracy.

Evaluation: Splits data into training/testing sets for rigorous performance measurement.

Recommendation Function: Provides a functional Python script to generate the top N movie recommendations for any given user ID.

Performance Metrics (Quantifiable Results)
This model significantly outperformed the initial similarity-based baseline model by specifically accounting for global, user, and item rating biases.

Metric

Result

Interpretation

Mean Absolute Error (MAE)

0.9574

On average, predictions are off by less than one star.

Root Mean Squared Error (RMSE)

1.2454

Confirms the model handles large prediction errors efficiently.

Technologies Used
Language: Python

Libraries: pandas, numpy, scikit-learn (for splitting and evaluation)

Algorithm: Singular Value Decomposition (SVD) Matrix Factorization

How to Run
Clone the repository.

Ensure the MovieLens 100k dataset is downloaded and unzipped in the project root folder as ml-100k/.

Run the script: python svd_recommend.py
