![image](https://github.com/user-attachments/assets/4efb2467-4835-4459-9040-d1b0be70aa51)

## Overview
A content-based movie recommendation system built using Python, NLP, and machine learning, which suggests movies similar to the user’s input based on genres, cast, crew, and movie descriptions.

## Features
🔹Content-Based Filtering – Uses movie metadata (overview, genres, cast, crew) for recommendations.
🔹TF-IDF Vectorization & Cosine Similarity – Computes similarity between movies.
🔹Efficient Preprocessing – Data cleaning, handling missing values, and text vectorization.

Tech Stack
🔹 Python (Pandas, NumPy, Scikit-learn)
🔹 Natural Language Processing (TF-IDF, Cosine Similarity)
🔹 Streamlit (for Web UI)
🔹 TMDb Movie Dataset

## How It Works
🔹 The system processes the dataset of movies to extract relevant features such as genres, descriptions, or keywords.
🔹 A similarity matrix is generated using cosine similarity.
🔹 Based on the movie selected by the user, the system retrieves and ranks the most similar movies.
🔹 The top 5 movies are displayed as recommendations.
