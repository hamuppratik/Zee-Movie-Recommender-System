Zee Movie Recommender System

In this project, I developed a personalized movie recommendation system using the Zee movies dataset to enhance user experience by suggesting films tailored to individual preferences.

Key Actions:

Data Preparation:

Performed data cleaning, formatting, and feature engineering on the MovieLens dataset, which included ratings, user, and movie data.
Exploratory Data Analysis (EDA):

Conducted extensive EDA to understand user preferences and movie characteristics.

Recommendation Techniques Implemented:

Collaborative Filtering:

User-Based Filtering: Identified users with similar rating patterns and recommended movies enjoyed by these similar users.
Item-Based Filtering: Recommended movies similar to those a user had previously rated highly.

Similarity Measures:

Pearson Correlation Coefficient: Measured the strength of linear relationships between user ratings.
Cosine Similarity: Evaluated similarity between users based on the cosine of the angle between their rating vectors.
Matrix Factorization: Decomposed the user-movie rating matrix to uncover latent factors representing user preferences and movie characteristics.
Created a function for user feed generation using user-user and item-item based collaborative filtering.

Machine Learning Model:

Developed a regression model using LightGBM to predict whether a user would like a movie or not.
Evaluation and Results:

Achieved a Precision@K of 85% and a 37% overlap in recommendations, reflecting high accuracy and alignment with user preferences.
Evaluated recommendation accuracy using metrics like Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE) and assessed user engagement through metrics such as click-through rates and conversion rates.

Outcome:

The developed system provides personalized movie suggestions, leading to increased user satisfaction and improved user experience on the movie platform.
