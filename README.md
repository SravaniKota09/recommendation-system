link for dataset '
# Book Recommendation System

This project implements a content-based book recommendation system using collaborative filtering techniques. The system suggests books to users based on their reading preferences and similarities with other users.

## Key Features:
- Uses a dataset of books, users, and ratings to generate recommendations
- Implements cosine similarity to find books with similar rating patterns
- Recommends 5 books that are most similar to a user's preferred book
- Includes book titles, authors, and cover images in the recommendations

## Technical Details:
- Built with Python using Pandas, NumPy, and scikit-learn
- Uses StandardScaler for data normalization
- Employs cosine similarity to measure book similarity
- Filters data to focus on active users (100+ ratings) and popular books (50+ ratings)

## How It Works:
1. Processes book metadata and user ratings
2. Creates a user-book rating matrix
3. Normalizes the rating data
4. Computes similarity scores between books
5. Recommends books based on similarity to a given book

The system helps readers discover new books they might enjoy based on their reading history and preferences.
