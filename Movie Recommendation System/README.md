# 🎬 Movie Recommendation System using CountVectorizer

A content-based movie recommendation system that processes movie descriptions using **CountVectorizer** to measure similarity between movies and generate personalised recommendations.

---

## 🔍 Overview

This project builds an end-to-end movie recommendation system from scratch. It combines a movie database with a text-based similarity engine powered by CountVectorizer. 

---

## ✨ Features

- 🗄️ Movie database with titles, genres, descriptions, and ratings
- 📝 Text preprocessing using **CountVectorizer** to convert movie descriptions into feature vectors
- 🎯 Content-based filtering — recommends movies based on description similarity
- 🤝 Collaborative filtering — recommends movies based on what similar users have rated highly
- 📐 Cosine similarity to rank and retrieve the most relevant suggestions

---

## ⚙️ How It Works

### 1. Movie Database
A structured dataset is used containing movie titles, genres, textual descriptions, and user ratings. This serves as the foundation for all recommendations.

### 2. User System
Users enter a movie name and then get recommendations based on that movie

### 3. Text Processing with CountVectorizer
Movie descriptions are tokenized and converted into a numerical feature matrix using `CountVectorizer` from scikit-learn. This transforms raw text into a format suitable for similarity calculations.


### 4. Similarity Measurement
Cosine similarity is computed between the feature vectors to identify how closely related two movies are based on their descriptions.


### 5. Recommendation Generation

| Method | How it works |
|--------|-------------|
| **Content-Based Filtering** | Recommends movies with descriptions similar to ones the user has rated highly |
| **Collaborative Filtering** | Recommends movies liked by users with similar rating patterns |

---

## 🛠️ Tech Stack

- Python 3.x
- pandas, NumPy
- scikit-learn (CountVectorizer, cosine_similarity)
- Flask
- Turtle
