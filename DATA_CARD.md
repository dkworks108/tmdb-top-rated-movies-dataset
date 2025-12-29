# 📊 Data Card — TMDB Top-Rated Movies Dataset

## Dataset Summary
This dataset contains metadata for 10,000+ top-rated movies collected from The Movie Database (TMDB) API. It is intended for exploratory data analysis, visualization, and machine learning projects.

---

## Dataset Details
- **Source:** TMDB API
- **Records:** 10,000+ movies
- **Format:** CSV
- **Update Frequency:** Manual
- **Language Coverage:** Multiple (global)
- **Temporal Coverage:** ~1990 to 2024

---

## Features
| Feature | Description |
|------|------------|
| id | Unique TMDB movie identifier |
| original_title | Original movie title |
| original_language | Original language of the movie |
| popularity | Popularity score from TMDB |
| release_date | Official release date |
| vote_count | Number of votes received |

---

## Data Collection
- Collected programmatically using Python
- Retrieved via TMDB Top Rated Movies endpoint
- JSON responses validated and normalized
- Exported to CSV format

---

## Data Quality
- Minor missing values may exist (e.g., release dates)
- No synthetic data added
- Reflects real-world API behavior

---

## Intended Use
- Exploratory Data Analysis (EDA)
- Machine Learning practice
- Movie analytics
- Educational projects
- Kaggle notebooks

---

## Limitations
- Does not include genres or revenue
- Popularity score is TMDB-defined
- Not suitable for financial forecasting

---

## License
CC0 1.0 Universal (Public Domain)

---

## Acknowledgements
Data provided by The Movie Database (TMDB).  
This product uses the TMDB API but is not endorsed or certified by TMDB.
