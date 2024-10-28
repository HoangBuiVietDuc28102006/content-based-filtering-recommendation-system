# Content-based Filtering Recommendation System

## Content-based Filtering
![Recommendation Diagram](Content-based%20Filtering%20Diagram.png)
1. User watches a movie.
2. Analyse the movie content (60%), average rating (20%), and popularity (20%).
3. Find similar movies based on the features (content, average rating, and popularity.
4. Make recommendations.

## Project Overview
- A movie recommendation system.
- Dataset: MovieLens dataset.
- Libraries:
  - Pandas, Matplotlib, Seaborn, NLTK, and Scikit-learn.
  - Scikit-learn: TfidfVectorizer, MinMaxScaler, NearestNeighbors.

## Code Explanation
- In the `main.ipynb`.

## System Evaluation
- Good:
  - Transparency: Easy to understand and interpret why certain movies are recommended to the user.
  - Effective with limited data: Works well as it relies on item features
- Bad:
  - Narrow recommendations: Mainly based on the content (genres, tags) of the movie.
  - Cold start for new users: Without any user preferences, it will be difficult to make effective recommendations.
  - Scalability: The system can become significantly slower as the dataset size grows.
