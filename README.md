# Movie Recommender System

## Overview
This project implements a movie recommender system utilizing collaborative filtering, multi-arm bandits, and content-based filtering techniques. The system recommends the top 3 movies to users based on their preferences. The MovieLens dataset with 10,000 movies is used as the basis for recommendation.

## Algorithms Used
1. **Collaborative Filtering**: Collaborative filtering is employed to recommend movies by leveraging user-item ratings similarity.
2. **Multi-Arm Bandits**: Multi-arm bandits algorithm is utilized to dynamically recommend movies based on user interactions and feedback.
3. **Content-Based Filtering**: Content-based filtering technique is used to recommend movies based on user-item profiles and genre similarities.

## Implementation Details
- The `bandit_collaborative_filtering` function implements the multi-arm bandits algorithm to recommend movies based on user preferences and exploration parameters.
- The `recommendation` function combines collaborative filtering and content-based filtering to recommend the top 3 movies to the user.
- User input is taken to specify the active user ID for whom movie recommendations are generated.

## Dataset
The MovieLens dataset with 10,000 movies is used for training and evaluation. This dataset provides user ratings and movie details necessary for building the recommender system.

## Acknowledgements
- MovieLens dataset
- Collaborative filtering, multi-arm bandits, and content-based filtering algorithms
- NumPy and Pandas libraries for data manipulation and analysis
