# 🎬 TMDB Top-Rated Movies Dataset (EDA & Machine Learning)

A clean and structured dataset of **10,000+ top-rated movies** collected from **The Movie Database (TMDB) API**.  
This dataset is designed for **Exploratory Data Analysis (EDA)**, **data visualization**, and **machine learning projects**.

---

## 📌 About the Dataset

This dataset contains metadata for top-rated movies retrieved programmatically using Python from the TMDB API.  
Each row represents a single movie with key attributes such as title, language, popularity score, vote count, and release date.

The dataset reflects real-world movie data and is suitable for both beginners and advanced data science workflows.

---

## 🔗 Kaggle Dataset & Notebook

- 📦 Kaggle Dataset:  
  [link](https://www.kaggle.com/datasets/doreshkumawat/tmdb-top-rated-movies-dataset-for-eda-and-ml-10k)

- 📓 Kaggle Notebook (EDA & ML):  
  [link](https://www.kaggle.com/code/doreshkumawat/tmdb-top-rated-movies-eda-ml-ipynb)


## 📊 Dataset Details

- **Source:** TMDB API  
- **Total Records:** 10,000+ movies  
- **Format:** CSV  
- **File Name:** `tmdb_top_rated_movies.csv`  

### Columns
| Column Name | Description |
|------------|------------|
| id | Unique movie identifier (TMDB) |
| original_title | Original movie title |
| original_language | Original language of the movie |
| popularity | Popularity score from TMDB |
| release_date | Official release date |
| vote_count | Number of votes received |

---

## 🧪 Use Cases

- Exploratory Data Analysis (EDA)
- Movie popularity trend analysis
- Recommendation system development
- Machine learning model training
- Data visualization projects
- Kaggle notebooks and competitions

---

## 🧹 Data Notes

- Minor missing values may exist (e.g., a few missing release dates)
- No artificial cleaning applied to preserve real-world data behavior
- Dataset is ready for immediate analysis

---

## 🛠️ How the Data Was Collected

- Data retrieved using Python with `requests` and `pandas`
- Multiple pages fetched from TMDB Top Rated Movies endpoint
- JSON responses validated and transformed into tabular format
- Exported as a single CSV file

---

## 📁 Repository Structure

```text
.
tmdb-top-rated-movies-dataset/
├── tmdb_top_rated_movies.csv
├── README.md
├── DATA_CARD.md
├── RELEASE_NOTES.md
├── .gitignore
└── notebooks/
    └── tmdb-top-rated-movies-eda-ml.ipynb
