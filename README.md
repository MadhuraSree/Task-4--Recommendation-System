COMPANY : CODTECH IT SOLUTIONS

NAME : Dharmapuri Madhura Sree

INTERN ID : CT06DF2223

DOMAIN : MACHINE LEARNING

DURATION : 6 WEEKS

MENTOR : NEELA SANTHOSH KUMAR

## Task-4--Recommendation-System

This project focuses on building a personalized movie recommendation system using Collaborative Filtering powered by Singular Value Decomposition (SVD). The objective is to predict which movies a user would likely enjoy based on their previous ratings and preferences of similar users.

By using matrix factorization (SVD), we break down the user-item ratings matrix into lower-dimensional latent factors that represent user and movie characteristics. This approach helps in capturing complex patterns in user behavior and movie similarities.

This system recommends top N movies to a user that they haven’t rated yet, based on predicted scores. The task demonstrates the real-world application of recommender systems and is developed as part of the CodTech IT Solutions Machine Learning Internship.

## Dataset Used:
Source: MovieLens "ml-latest-small"

Files:

ratings.csv: Contains 100,000 ratings from 600 users on 9,000+ movies

→ Columns: userId, movieId, rating, timestamp

movies.csv: Contains movieId, title, and genres

## Objectives

Load and preprocess a movie ratings dataset

Create a user–movie ratings matrix

Apply Truncated SVD to reduce dimensionality and discover latent features

Reconstruct predicted ratings matrix for all users and movies

Recommend Top-N unseen movies for any given user based on predicted scores

Evaluate the system using RMSE (Root Mean Squared Error)

## Key Features
✅ Builds a user–item matrix from real rating data

✅ Applies TruncatedSVD from sklearn.decomposition

✅ Predicts ratings for unseen movies

✅ Recommends top 5 personalized movies per user

✅ Calculates RMSE to measure recommendation accuracy

## Technologies & Libraries:

Python

pandas, numpy

scikit-learn (for TruncatedSVD & evaluation)

Matrix Factorization (Collaborative Filtering)

## output

![Image](https://github.com/user-attachments/assets/a519990a-a2ed-410d-8543-247e898d719e)
