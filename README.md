# 🎬 Movie Recommendation System

## 📌 Introduction
This project implements a **Content-Based Movie Recommendation System** using Python and machine learning techniques. The recommendation engine suggests movies to users based on the metadata of the movie, such as cast, crew, genres, and keywords.

## 🚀 Features
- **Content-Based Filtering**: Recommends movies similar to the input movie based on metadata features.
- **Exploratory Data Analysis (EDA)**: Understand the structure and patterns in the movie dataset.
- **Cosine Similarity**: Calculates the similarity between movies based on metadata.
- **Cleaned and Preprocessed Data**: Data is processed to extract useful features like cast, crew, keywords, and genres.

## 🧠 How It Works
1. Load movie and credits datasets  
2. Merge datasets based on movie title  
3. Extract important features (genres, cast, crew, keywords)  
4. Combine features into a single text column  
5. Convert text into vectors using CountVectorizer  
6. Compute cosine similarity between movies  
7. Recommend top similar movies 

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn

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
4. Run the Jupyter Notebook:
```bash
jupyter notebook
```
## 💬 Example
Input: 
```
Avatar
```
Output:
```
Titanic
Guardians of the Galaxy
John Carter
...
```
## 📌 Future Improvements
- Add user-based recommendations
- Include ratings and personalization
- Deploy as a web application
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
