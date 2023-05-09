# Movie Recommendation System using Cosine Similarity

This repository contains a movie recommendation system that utilizes cosine similarity to provide personalized movie recommendations to users. The system analyzes the similarity between movies based on their features and suggests movies with similar characteristics.

## Features
- Utilizes cosine similarity to measure the similarity between movies.
- Extracts relevant features from movies, such as genre, actors, and ratings, to calculate similarity scores.
- Provides movie recommendations based on movie similarity.
- Supports efficient searching and retrieval of movie recommendations.

## Installation
1. Clone the repository: `git clone https://github.com/Kaustav-Sarkar/Movie-Recommendation.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## Usage
1. Data available at https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
2. Run `streamlit run app.py`
3. Select a movie for which recommendations are desired.
4. The system will generate and display a list of recommended movies based on cosine similarity.
