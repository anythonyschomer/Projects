# Projects
**# This file details all current Projects in this folder**
# MovieLens Recommender System 🎬

A collaborative filtering recommender system built on the **MovieLens 100k dataset** using the **Surprise library (SVD algorithm)**.  
It demonstrates how to preprocess rating data, train/evaluate models, and generate personalized movie recommendations.

## 📊 Dataset
- **u.data** → user, movie, rating, timestamp  
- **u.item** → titles, release year, genres  
- Users: 943 | Movies: 1682 | Ratings: 100,000  

Source: [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/)

## ⚙️ Tools & Libraries
- Python 3.11  
- pandas, numpy, scipy  
- scikit-surprise  

## 🚀 How It Works
1. Load and preprocess MovieLens ratings and movies  
2. Build dataset with Surprise `Reader` and `Dataset.load_from_df`  
3. Train/test split (80%/20%)  
4. Train **SVD** recommender  
5. Evaluate with **RMSE**  
6. Generate top-5 movie recommendations for a user  

## 📈 Results
- Test RMSE: **0.936**  
- Example top-5 recommendations for User 1:
  - Rear Window (1954) → 4.88  
  - L.A. Confidential (1997) → 4.80  
  - A Close Shave (1995) → 4.75  
  - Secrets & Lies (1996) → 4.73  
  - Dr. Strangelove (1963) → 4.71 
