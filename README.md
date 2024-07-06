Movie Recommender System

This project focuses on building a movie recommender system using data from the TMDB (The Movie Database) API.

Project Overview

Imported data of 10,000 movies from the TMDB database.
Developed a cosine similarity function using vectorization to find the 5 most similar movies to a given movie.
Implemented the frontend using Streamlit to create an interactive user interface.
Utilized TMDB's API to display movie posters of the recommended movies.
Technologies Used

Python: Used for data manipulation, algorithm implementation, and backend logic.
Streamlit: Framework used for building and deploying the web application.
TMDB API: Accessed to fetch movie data including posters and details.
Cosine Similarity: Calculated using vectorization techniques for efficient similarity measurement.
How to Use

Installation:

Clone the repository.
Install dependencies using pip install -r requirements.txt.
Run the Application:

Navigate to the project directory.
Run streamlit run app.py to start the Streamlit application.
Usage:

Enter a movie title to get recommendations based on cosine similarity.
Explore recommended movies and their details.
Future Enhancements

Incorporate user ratings and reviews for personalized recommendations.
Implement additional similarity measures and algorithms for comparison.
Enhance UI/UX for better user interaction and visual appeal.
