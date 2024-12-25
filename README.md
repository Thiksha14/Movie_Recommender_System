# Movie Recommender System

## Overview

The Movie Recommender System is a simple yet efficient tool that uses content-based filtering to recommend the top 5 movies related to the one selected by the user. By analyzing the attributes of the chosen movie, such as genres, keywords, and other metadata, the system identifies and suggests similar movies that align with the user's interests.

## Features
- Content-Based Filtering: Recommends movies based on their similarity to the selected movie.
- Top 5 Recommendations: Displays the most relevant movies tailored to the user's choice.
- Interactive User Input: Allows users to pick a movie and get instant recommendations.

## How It Works
- The system processes the dataset of movies to extract relevant features such as genres, descriptions, or keywords.
- A similarity matrix is generated using cosine similarity.
- Based on the movie selected by the user, the system retrieves and ranks the most similar movies.
- The top 5 movies are displayed as recommendations.
