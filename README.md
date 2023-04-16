# Predictive-Analytics-Project

Streaming Content Recommendation System

By

NIDHI MISHRA - 20MIA1007

CHETAN SRIVASTAVA - 20MIA1122

UTKARSH ARYAN - 20MIA1155


This project aims to create a content recommendation system for streaming platforms like Netflix, Amazon Prime, Disney Plus, Hulu etc. The recommendation system is based on clustering movies and TV shows by their description using FastText embeddings and KMeans clustering. The system takes in the title of a movie/TV show and an exploration flag as input and returns a list of recommended content based on similarity.

# Files

1) Dataset: Their are four CSV files that contains the dataset used in the project, including the title, description, and genre of the movies and TV shows.

2) Predicitve_Analytics_Project_Code.ipynb: This Jupyter Notebook contains the code used for preprocessing, vectorizing, clustering, and recommending content.


# Usage

To use the recommendation system, follow these steps:

1) Clone the repository to your local machine.
2) Open the Jupyter Notebook Predicitve_Analytics_Project_Code.ipynb.
3) Run the code cells in the notebook to preprocess the data, generate FastText embeddings, cluster the data, and create the recommendation system.
4) Call the recommendation_system function with the title of a movie/TV show and an exploration flag (0 or 1) as input to get a list of recommended content.
