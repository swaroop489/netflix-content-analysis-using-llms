# Netflix Content Analysis

📊 Exploratory Data Analysis (EDA) | Data Cleaning | Trend Analysis | Business Insights

---

## 📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on Netflix’s content dataset to understand content distribution, genre trends, country contributions, ratings, release patterns, and strategic growth insights.

The objective was to clean the dataset, analyze trends over time, and derive actionable insights about Netflix’s content strategy.

---

## 📊 Dataset Description

The dataset contains Netflix titles information including:

- Category (Movie / TV Show)
- Director
- Cast
- Country
- Release Date
- Rating
- Genre (Type)
- Duration
- Number of reviews
- Service fee

---

## 🧹 Data Cleaning & Preprocessing

Performed the following preprocessing steps:

- Removed duplicate records
- Handled missing values:
  - Filled missing Director and Cast as "Not Available"
  - Filled missing Country as "Unknown"
  - Filled missing Rating as "Not Rated"
- Converted Release_Date to datetime format
- Extracted Year, Month, and Day from Release_Date
- Cleaned genre strings and split multi-genre entries

---

## 🔍 Exploratory Data Analysis

### 🎬 Movies vs TV Shows
- Analyzed distribution of Movies and TV Shows
- Observed growth trends across years
- Identified significant rise in TV Shows after 2016

### 🌍 Country-wise Content Distribution
- Top contributing countries
- Country-wise content growth over time
- Comparative analysis of Movies vs TV Shows per country

### 🎭 Genre Analysis
- Top 10 genres on Netflix
- Genre trends over years
- Stacked genre distribution visualization
- Growth of International content

### ⭐ Ratings Analysis
- Distribution of content ratings
- Ratings comparison: Movies vs TV Shows

### 🎥 Cast & Directors Analysis
- Top 10 actors by number of titles
- Top 10 directors by number of titles

### 📅 Release Trends
- Monthly release trends
- Content growth by year

### ⏱ Duration Analysis
- Distribution of movie durations
- Runtime patterns across titles

---

## 📈 Key Insights

- TV Shows increased sharply after 2016.
- International content expanded significantly between 2018–2020.
- USA remains the top content-producing country.
- Drama and Comedy dominate Netflix’s catalog.
- Growth in global content reflects Netflix’s international expansion strategy.
- Strategic opportunity exists in emerging markets and trending genres.

---

## 📊 Visualizations Used

- Bar plots
- Count plots
- Line plots
- Area charts
- Histograms
- Violin plots
- Correlation heatmaps
- Scatter plots

All visualizations created using:

- Matplotlib
- Seaborn

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---


## 🚀 Business Implications

1. Netflix’s strategic shift towards TV Shows aligns with binge-watching trends.
2. Growth in International titles indicates expansion into global markets.
3. Investment in top-performing genres like Drama and Comedies should continue.
4. Emerging markets offer strong growth potential.

---

## 👤 Author

Swaroop Sandanshive
