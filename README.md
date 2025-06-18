# MusicRecommendation_UsingKNN
 🔍 Overview
This project implements a content-based music recommendation system using K-Nearest Neighbors (KNN) and cosine similarity to suggest songs with similar audio characteristics.

The system uses Spotify audio features to find and recommend tracks that are musically similar to a given input song. This approach does not rely on user history or collaborative filtering, making it useful for cold-start scenarios.

📁 Dataset
Source: Spotify dataset
File: SpotifyFeatures.csv

The dataset includes audio features such as:

->Popularity
->Danceability
->Energy
->Valence
->Tempo
->Acousticness
->Instrumentalness
->Speechiness
->Loudness
->Liveness

🛠️ Technologies Used
->Python 3
->Pandas & NumPy – Data manipulation and analysis
->Scikit-learn – KNN modeling, feature scaling
->Matplotlib – Visualization
->Cosine Similarity – For distance metric in KNN
