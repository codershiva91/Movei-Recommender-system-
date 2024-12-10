🎥 Movie Recommender System

A machine learning project aimed at building a personalized movie recommendation system using collaborative and content-based filtering techniques.

📑 Overview

This project demonstrates the development of a movie recommender system utilizing data from the TMDB dataset. It preprocesses movie data, extracts features, and employs recommendation algorithms to suggest movies tailored to user preferences.

🛠️ Technologies Used

Programming Language: Python
Libraries:
Data Manipulation: Pandas, NumPy
Machine Learning: Scikit-learn
Visualization: Matplotlib, Seaborn
📂 Dataset

The project uses two primary datasets:


tmdb_5000_movies.csv – Contains metadata about movies, including genres, keywords, and popularity.
tmdb_5000_credits.csv – Provides additional information about movie cast and crew.
🚀 Key Features
Data Preprocessing:


Cleaned and merged datasets to handle missing values and inconsistencies.
Extracted key features such as genres, cast, crew, and keywords.
Feature Engineering:

Used TF-IDF vectorization to process textual data.
Applied cosine similarity to calculate movie recommendations.
Recommendation System:

Content-Based Filtering: Recommended movies based on user preferences and metadata similarity.
Collaborative Filtering: Incorporated user ratings to enhance recommendations.
Visualization:

Presented data insights through plots and charts for better understanding.

📊 Results

The system effectively generates movie recommendations based on user input, demonstrating accuracy and relevance through rigorous testing.

