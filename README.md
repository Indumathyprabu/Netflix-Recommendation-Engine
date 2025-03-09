# Netflix-Recommendation-Engine
Netflix Recommendation Engine
Overview
This project is a Netflix Recommendation Engine built using collaborative filtering techniques. The goal is to recommend movies to users based on their past ratings and preferences. The project uses the Singular Value Decomposition (SVD) algorithm from the Surprise library to predict user ratings and generate recommendations.

# **Dataset**
The dataset used in this project consists of movie ratings provided by Netflix users. The dataset includes:

Movie Titles: Contains movie IDs, titles, and release years.

Ratings: Contains user IDs, movie IDs, and ratings.

Requirements
To run this project, you need the following Python libraries:

pandas

numpy

matplotlib

scikit-learn

surprise


Project Structure
Data Preprocessing: The dataset is cleaned and preprocessed to remove movies and users with fewer ratings.

Model Training: The SVD algorithm is used to train the recommendation model.

Recommendation Generation: The trained model predicts ratings for movies and generates recommendations for a specific user.

Code Explanation
Data Loading and Preprocessing:

The dataset is loaded and cleaned to remove movies and users with fewer ratings.

The dataset is then split into training and testing sets.

Model Training:

The SVD algorithm is used to train the recommendation model.

The model is evaluated using cross-validation to compute RMSE and MAE.

Recommendation Generation:

The trained model predicts ratings for movies for a specific user.

The top recommendations are displayed based on the predicted ratings.

Results
The recommendation engine successfully predicts user ratings and generates personalized movie recommendations. The model achieves an RMSE of ~0.9967 and an MAE of ~0.8017, indicating good predictive accuracy.
