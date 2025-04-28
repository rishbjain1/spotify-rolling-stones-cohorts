# Rolling Stones Song Clustering and Cohort Analysis

This project explores the clustering of Rolling Stones' songs on Spotify based on musical and popularity attributes. The goal is to create meaningful cohorts (groups) of similar songs to enhance song recommendations and deepen understanding of musical features influencing user preferences.

## 📌 Problem Statement
Spotify aims to boost user engagement by offering song recommendations tailored to listener tastes. Using Spotify API data for all Rolling Stones albums, this project performs:
- Data cleaning and preparation
- Exploratory Data Analysis (EDA)
- Feature engineering
- Dimensionality reduction discussion
- Clustering analysis to form song cohorts

---

## 🛠️ Data Description

Each song in the dataset contains features such as:
- **Name, Album, Release Date, Track Number, ID, URI**
- **Musical Attributes:** Acousticness, Danceability, Energy, Instrumentalness, Liveness, Loudness, Speechiness, Tempo, Valence
- **Popularity and Duration**

---

## 📊 Steps Followed

### 1. Initial Data Inspection and Cleaning
- Removed duplicates
- Handled missing values
- Identified and treated outliers
- Ensured dataset consistency

### 2. Data Refinement
- Selected relevant numerical features
- Dropped irrelevant columns (e.g., `id`, `uri`)

### 3. Exploratory Data Analysis (EDA) and Feature Engineering
- Identified top albums based on number of popular songs
- Explored relationships between song features and popularity
- Visualized distributions and correlations
- Discussed the importance of dimensionality reduction (e.g., PCA)

### 4. Cluster Analysis
- Determined optimal number of clusters (using Elbow Method and Silhouette Score)
- Applied KMeans clustering
- Characterized each song cohort based on musical features
- Visualized clustering results using dimensionality reduction techniques (e.g., PCA plots)

---

## 📈 Key Insights
- Popularity correlates strongly with energy, danceability, and valence.
- Dimensionality reduction (like PCA) is crucial for visualizing and speeding up clustering while minimizing noise.
- Clustering successfully groups songs into meaningful musical cohorts (e.g., high-energy vs acoustic ballads).

---

## 📚 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn (EDA, Clustering, PCA)

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rolling-stones-song-clustering.git
   cd rolling-stones-song-clustering
