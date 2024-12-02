# Movie Recommendation System

## Introduction
This project implements a **Content-Based Movie Recommendation System** using Python and machine learning techniques. The recommendation engine suggests movies to users based on the metadata of the input movie, such as cast, crew, genres, and keywords.

### Features
- **Content-Based Filtering**: Recommends movies similar to the input movie based on metadata features.
- **Exploratory Data Analysis (EDA)**: Understand the structure and patterns in the movie dataset.
- **Cosine Similarity**: Calculates the similarity between movies based on metadata.
- **Cleaned and Preprocessed Data**: Data is processed to extract useful features like cast, crew, keywords, and genres.

## Dataset
This project uses the **TMDB Movie Dataset**. It contains two CSV files:
- `tmdb_credits.csv`: Contains metadata information about the movie (e.g., cast, crew).
- `tmdb_movies.csv`: Contains movie-related details (e.g., title, budget, genres).

**Columns Used:**
- `id`: Unique identifier for the movie.
- `title`: Title of the movie.
- `cast`: Cast members of the movie.
- `crew`: Crew members, including the director.
- `keywords`: Keywords related to the movie.
- `genres`: Genres of the movie.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/username/Movie-Recommendation-System.git
   ```
2. Install the required libraries:

  ```bash
  pip install -r requirements.txt
  ```
3. Download the dataset and place the [tmdb_credits.csv](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download&select=tmdb_5000_credits.csv) and [tmdb_movies.csv](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download&select=tmdb_5000_movies.csv) files in the datasets/ directory.

## License
This project is licensed under the MIT License - see the [LICENSE]() file for details.
