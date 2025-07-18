# 🎬 Movie Recommendation System

This is a content-based movie recommendation system built using Python and pandas. It suggests movies to users based on their preferred genres and movie ratings. The system uses datasets from [MovieLens](https://grouplens.org/datasets/movielens/) and [TMDb (The Movie Database)](https://www.themoviedb.org/).

---

## 📂 Datasets Used

The project uses the following CSV files:

- `ratings_small.csv`: Contains user ratings for movies.
- `movies_metadata.csv`: Contains metadata for movies such as title and genres.
- `links_small.csv`: Maps MovieLens `movieId` to TMDb `tmdbId`.

---

## 🛠️ Features

- Extracts and cleans movie metadata and ratings.
- Allows user input for genre preferences.
- Filters movies based on user-selected genres.
- Sorts movies by average rating.
- Displays top 5 movie recommendations.

---

## 📌 Requirements

- Python 3.x
- pandas
- re (built-in)
- Google Colab (for file upload and execution)

---

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload the required CSV files when prompted:
   - `ratings_small.csv`
   - `movies_metadata.csv`
   - `links_small.csv`
3. Follow the on-screen prompt to enter your preferred movie genres (e.g., `Action, Comedy, Drama`).
4. The system will return the top 5 recommended movies.

---

## 📈 Sample Output

Enter which Categories Movies Would you like to watch Today from above list of genre (comma-separated): Comedy, Action

Top Movie Recommendations Based on Your Preferred Genres:
The Dark Knight (Genre: Action, Rating: 4.9)
Back to the Future (Genre: Comedy, Rating: 4.8)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

- **Himanshu Choudhary** – [HimanshuC-7](https://github.com/HimanshuC-7)

---

## 🙌 Acknowledgments

- [MovieLens](https://grouplens.org/datasets/movielens/)
- [The Movie Database (TMDb)](https://www.themoviedb.org/)
