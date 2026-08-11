# Amazon Prime Movies & TV Shows Data Analysis

## 📌 Project Overview

This project analyzes the Amazon Prime Movies and TV Shows dataset using Python. The objective is to clean, explore, visualize, and identify useful patterns in Amazon Prime's content library.

The dataset contains **9,800+ movies and TV shows**, along with information about ratings, popularity, release years, runtime, actors, and directors.

## 🛠 Tools & Technologies

* Python
* Pandas
* Plotly
* Matplotlib
* Google Colab

## 📂 Dataset

The project uses two datasets:

* `titles.csv` – Contains information about movies and TV shows, including title, type, release year, runtime, IMDb score, TMDB score, and popularity.
* `credits.csv` – Contains information about actors, directors, characters, and their roles.

## 🔍 Project Steps

### 1. Data Loading

Loaded the Amazon Prime `titles` and `credits` datasets into Google Colab using Pandas.

### 2. Data Understanding

Explored the dataset using:

* `head()`
* `shape`
* `columns`
* `info()`
* `describe()`

### 3. Data Cleaning

* Checked missing values
* Removed duplicate records
* Handled missing descriptions
* Handled missing age certifications
* Handled missing character information

### 4. Exploratory Data Analysis

Analyzed:

* Total movies and TV shows
* Average IMDb and TMDB ratings
* Content release trends
* Top-rated titles
* Most popular titles
* Movie runtime
* TV show seasons
* Age certifications
* Top actors
* Top directors

### 5. Data Visualization

Created interactive and static visualizations using **Plotly and Matplotlib**, including bar charts, pie charts, line charts, and histograms.

## 📊 Key Insights

* Movies represent a major portion of the Amazon Prime content library.
* The platform contains content from a wide range of release years.
* IMDb and TMDB ratings help identify highly rated content.
* Popularity analysis highlights titles receiving strong audience attention.
* Actor and director analysis identifies frequently appearing talent in the catalog.

## 🎯 Conclusion

This project demonstrates an end-to-end beginner-level data analysis workflow using Python, including **data loading, data cleaning, exploratory data analysis, visualization, and insight generation**.

## 💻 Skills Demonstrated

`Python` `Pandas` `Data Cleaning` `EDA` `Plotly` `Matplotlib` `Data Visualization` `Google Colab`
