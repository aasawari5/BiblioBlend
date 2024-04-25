# BiblioBlend - Book Recommendattion Engine

This project implements a book recommendation engine using the K-Nearest Neighbors (KNN) algorithm. 

## Table of Contents
1. Introduction
2. Dataset
3. Approach
4. Results

## Introduction
Recommendation systems play a crucial role in providing personalized experiences to users. This project focuses on recommending books to users based on the similarity of their preferences to other users' preferences.

## Dataset
The dataset used in this project contains information about books, including their titles, authors, genres, ratings, and languages. The dataset is provided in the books.csv file.

## Approach
We utilize the K-Nearest Neighbors (KNN) algorithm to recommend books. The steps involved in the recommendation process are as follows:

1. Data Preprocessing: Clean the dataset and prepare it for training.
2. Feature Engineering: Extract relevant features such as average rating and language similarity.
3. KNN Model Training: Train the KNN model using the prepared dataset.
4. Recommendation Generation: Given a book's name as input, find the K nearest neighbors based on rating and language similarity and recommend 8 books.

## Results
The recommendation engine successfully provides 8 book recommendations based on the input book's name, considering factors such as average rating and language similarity.
