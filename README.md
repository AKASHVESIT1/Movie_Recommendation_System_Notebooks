# 🎬 Movie Recommendation System

This project demonstrates two basic approaches to building a movie recommendation system using the **TMDB dataset**:

---

## ✅ Algorithms Used

1. **Content-Based Filtering**  
   - Utilizes movie metadata such as genres, cast, crew, keywords, etc.  
   - Recommends movies similar in content to the one the user likes.

2. **Collaborative Filtering (Using Cosine Similarity)**  
   - Based on user ratings and behavior.  
   - Recommends movies based on what similar users liked.

---

## ⚠️ Note on Data Size

The original dataset included large files (`ratings.csv`, `credits.csv`, `archive.zip`, etc.) which **exceeded GitHub’s 100MB upload limit**.  
To keep the repository lightweight and pushable, only the `.ipynb` notebooks are included.

> 📌 Due to memory limitations, only a **subset of the dataset was used** while testing and running the notebooks.  
This means:
- The models currently **recommend movies accurately only for a limited number of titles**.
- Full dataset-based recommendations may require more memory and are not included in this notebook version.

---

## 📥 Dataset Download Links

You can manually download the required datasets from the following sources:

- 📁 [`tmdb_5000_movies.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- 📁 [`tmdb_5000_credits.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- 📁 [`ratings.csv`](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
- 📁 [`movies_metadata.csv`](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
- 📁 [`keywords.csv`](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

> You’ll need a free [Kaggle](https://www.kaggle.com) account to download the datasets.

---

## 🗂️ Contents

- `Movie_Recommendation_Content_Based_Filtering.ipynb`  
- `Movie_Recommendation_Using_Collaborative_Filtering.ipynb`

Feel free to clone and run these notebooks locally with the complete dataset if you want more accurate and broader recommendations!

---

## 📌 Disclaimer

This repository is for learning and demonstration purposes. For better results, use the full dataset on a local machine with sufficient memory.
