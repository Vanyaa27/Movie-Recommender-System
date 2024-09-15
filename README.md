# Movie-Recommender-System
A Movie Recommender System using Content-Based Filtering built with Streamlit, Pandas, and scikit-learn. It fetches movie metadata from TMDb API and recommends similar movies based on genres, keywords, and descriptions using TF-IDF and cosine similarity. The system provides an interactive interface for real-time recommendations.

This repository contains a Movie Recommender System built using Content-Based Filtering. The system recommends movies based on their similarity to a selected movie, using data such as genres, keywords, and other metadata. The project leverages the following technologies:

     Streamlit: For creating an interactive web interface for the recommender system.
    Pandas: For efficient data manipulation and analysis.
    scikit-learn: To implement the machine learning algorithms, including TF-IDF and cosine similarity, for finding similar movies.
    JSON API: Movie metadata and recommendations are fetched via The Movie Database (TMDb) API.
# Features:
    Content-Based Filtering: Recommends movies similar to the user's selected movie based on genres, keywords, and         descriptions.
    Interactive Web Interface: Streamlit allows for an intuitive user interface where users can search for movies and get recommendations instantly.
    Real-time Movie Data: Movie details, posters, and metadata are retrieved dynamically from TMDb using their API.
# How It Works:
    1. Data Preparation: Movie metadata is fetched from the TMDb API and stored locally in a Pandas DataFrame.
    2. Text Vectorization: The system uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert movie descriptions into feature vectors.
    3. Similarity Calculation: Cosine similarity is applied to find and rank movies most similar to the selected one.
    4. Recommendation Display: The recommendations are presented in a user-friendly format with movie posters and details, thanks to Streamlit's UI capabilities.
