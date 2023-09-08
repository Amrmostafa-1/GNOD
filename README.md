# GNOD

## Song Recommender System

A machine learning powered song recommendation system that provides song suggestions based on a user's input.

## Introduction

The Song Recommender System is designed to help users discover new music that aligns with their taste. Given a song name, the system searches for its audio features and leverages clustering to recommend a similar song.

## Features

- Spotify API Integration: Fetches song information and audio features.
- Data Preprocessing: Uses a Standard Scaler to normalize audio features.
- Machine Learning Model: Employs KMeans clustering to group songs based on their audio features.
- User-friendly Interface: Simply input a song name to receive a recommendation.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Spotipy (for Spotify API)

## Acknowledgements

- Spotify API for providing access to extensive song metadata and audio features.
- The open-source community for the valuable libraries and tools.
- Song dataset from kaggle:
	https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset
