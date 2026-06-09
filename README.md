# SpotifyMusicDataAnalysis
A Decision Support System Project using EDA and Machine Learning

# Project Title
In the modern music industry, streaming platforms like Spotify generate vast amounts of data related to songs, artists, and listener behavior. However, this data is often underutilized when it comes to making strategic decisions.
The key problem is:
How can data analytics and machine learning be used to extract meaningful insights from Spotify data to support decision-making in music production, recommendation systems, and audience targeting?
This project aims to solve this problem by analyzing music data and building models that help stakeholders make informed, data-driven decisions.

# Brief Introduction
This project focuses on applying data science and machine learning techniques to Spotify music data to support decision-making processes.

# Project Objectives
Perform Exploratory Data Analysis (EDA) on track and artist data
Uncover trends in audio features, popularity, and listener behavior
Build machine learning models (KMeans, KNN) for:
Music style clustering
Personalized music recommendation
Provide data-driven insights and recommendations for producers, curators, and marketers

# Dataset
The dataset was sourced from Kaggle and includes:

tracks.csv: Audio features and metadata of Spotify tracks artists.csv: Artist-level metadata including popularity and followers
Both the dataset are too large so not able to provide the file here, so you can find it on kaggle

artist: https://www.kaggle.com/datasets/nimishasen27/spotify-dataset?select=artists.csv
track : https://www.kaggle.com/datasets/nimishasen27/spotify-dataset?select=tracks.csv

➡️ These files were merged using the artist ID to create a unified dataset for analysis.

# Technologies Used 
Python (Jupyter Notebook)

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

# Key Analyses & Insights
Popularity Trends: Most tracks have low popularity; a few dominate streams (long-tail effect).
Feature Correlation: Energy and danceability moderately correlate with track popularity.
Explicit Content: Slightly higher popularity, especially in hip-hop/pop genres.
Temporal Evolution:
Popularity, danceability, and energy have increased since 2000
Track releases have grown exponentially in the digital era
Artist Influence: Follower count is a strong proxy for consistent popularity

# Machine Learning Models
KMeans Clustering Groups songs into stylistic clusters based on audio features (energy, danceability, etc.)
KNN Recommendation System Suggests tracks based on input preferences for:
Danceability
Energy
Release year
Artist followers
📌 Use Case Applications Playlist curation and personalization
Strategic song production based on popular features
Artist development and marketing
Data-driven decision support for streaming platforms


The approach includes:
Performing Exploratory Data Analysis (EDA) to identify patterns and trends
Analyzing key features such as popularity, energy, and danceability
Building machine learning models:
KMeans Clustering for grouping songs by style
KNN Recommendation System for personalized music suggestions

The final goal is to develop a Decision Support System (DSS) that can assist music producers, marketers, and streaming platforms in making strategic decisions.


# Repository Links

## Main Document
- [Main Document](Documentation/main_document.md)

## Documentation Files
- [Project Overview](Documentation/project_overview.md)
- [Problem Analysis](Documentation/problem_analysis.md)
- [System Design](Documentation/system_design.md)
- [Gantt Chart](Documentation/gantt_chart.md)
- [Dataset](Documentation/dataset.md)
- [Tools and Technologies](Documentation/tools_and_technologies.md)

## Logs
- [Day 1 Log](Logs/log_day1.md)

## Project Folders
- [Data Folder](Data/)
- [Source Folder](Source/)
- [Reports Folder](Reports/)

- ## 👥 Team Members

- Necla Ilayda Guler – [GitHub](https://github.com/tnaduivnmani)
- Sourav Jaiswal – [GitHub](https://github.com/souravjaiswal440)
- Omer Furkan Bilici – [GitHub](https://github.com/username4)
- Harshal Tittamelanahalli – [GitHub](https://github.com/username5)
- Tabassum Nadavinmani – [GitHub](https://github.com/tnaduivnmani)

