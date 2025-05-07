# 🎬 Movie Recommendation System (Tkinter GUI)

This project is a content-based **Movie Recommendation System** built using a graphical interface with **Tkinter**. It provides personalized movie suggestions based on plot and genre similarities, delivering an interactive and visually appealing user experience.

## 🔧 Tech Stack
- **Python**, **Tkinter** – GUI development
- **Pandas**, **Scikit-learn** – Data handling and ML
- **TMDB API** – Real-time movie poster fetching
- **TF-IDF** + **Cosine Similarity** – Plot-based recommendations
- **Jaccard Similarity** – Genre-based matching

## 📌 Features

- 📽️ **Recommendations Tab**  
  Select any movie from the dropdown and get top 10 similar movie suggestions with posters.

- 🎭 **Browse by Genre Tab**  
  Choose a genre (Action, Comedy, Drama, Romance, Sci-Fi, etc.) and browse trending movies visually.

- 🧠 **Hybrid Recommendation System**  
  Combines:
  - 70% plot similarity (TF-IDF)
  - 30% genre similarity (Jaccard index)

- 🖼️ **Poster Integration**  
  Uses the TMDB API to display high-quality posters alongside movie titles.

## 📁 Dataset
- [TMDB 5000 Movies and Credits Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## 🚀 How to Run
1. Clone the repo.
2. Make sure `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv` are in the same directory.
3. Install required libraries:
   ```bash
   pip install pandas scikit-learn requests pillow
