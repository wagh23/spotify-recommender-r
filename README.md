# 🎵 Spotify Recommender System (R)

This project explores a dataset of 2000 songs from 1998 to 2020 and builds a **basic music recommendation system** using R.

It includes:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA) with ggplot2
* Visualization of trends and feature correlations
* A simple recommender with four approaches:

  * Popularity-based
  * Feature similarity-based
  * Genre-based
  * Rule-based

## 📁 Dataset

The dataset includes columns like:

* `artist`, `song`, `genre`, `year`
* Audio features: `danceability`, `energy`, `tempo`, `valence`, etc.
* Metadata: `duration_ms`, `explicit`, `popularity`

## 🛠️ Technologies

* Language: **R**
* Libraries: `dplyr`, `ggplot2`, `tidytext`, `tidyr`, `reshape2`, `tm`

## ⚠️ Limitations

* Only works with the provided CSV format.
* Requires manual installation of R packages.
* The recommender is simple and not ML-based.
