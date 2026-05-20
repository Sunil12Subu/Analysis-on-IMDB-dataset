# IMDB Top-100 EDA — Film Ratings Analysis

> Exploratory data analysis on the top 100 rated films of the past decade, examining what drives audience ratings, actor influence, and voter behaviour patterns.

---

## Overview

This project analyses the IMDB Top-100 dataset to uncover patterns in film ratings across genres, directors, cast, and audience voting behaviour. The goal was to build intuition for data that has mixed data types, missing values, and non-obvious relationships — mirroring real-world BI requirements gathering.

## Key questions explored

- Which genres consistently produce top-rated films?
- Does a higher vote count correlate with a higher rating?
- What is the distribution of ratings across decades?
- Which directors and actors appear most frequently in the top 100?

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

## Project structure

```
imdb-eda-python/
├── data/
│   └── imdb_top100.csv        # Raw dataset
├── notebooks/
│   └── imdb_analysis.ipynb    # Full EDA notebook
└── README.md
```

## Selected findings

- **Drama and Crime** dominate the top 100, accounting for 60%+ of entries
- Vote count and rating show a **weak positive correlation** — popularity alone doesn't drive quality perception
- Films from the **1990s and 2000s** are over-represented relative to more recent releases, suggesting recency bias works against newer films

## How to run

```bash
git clone https://github.com/Sunil12Subu/imdb-eda-python
cd imdb-eda-python
pip install pandas matplotlib seaborn jupyter
jupyter notebook notebooks/imdb_analysis.ipynb
```

---

*Part of a data analysis portfolio by [Sunil Subramaniam Sreedhar](https://linkedin.com/in/sunil-subramaniam-sreedhar) — Senior Data Analyst based in Dortmund, Germany.*
