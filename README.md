# Movie Recommendation System using PySpark

This project implements a movie recommendation system using PySpark, featuring both collaborative and content-based filtering techniques. The dataset used for this project is sourced from Kaggle and can be found here: https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset

## Introduction
This recommendation system is designed to provide personalized movie recommendations based on user preferences and movie content. It utilizes the PySpark library, which is a fast and distributed framework for large-scale data processing.

## Features
Collaborative Filtering: Implemented using the ALS (Alternating Least Squares) algorithm in PySpark. This technique makes recommendations based on user-item interactions and patterns.

Content-Based Filtering: Utilizes movie genres as features to recommend movies similar to the user's preferences. TF-IDF and cosine similarity are employed for this purpose.

## Prerequisites
* Python
* Jupyter Notebook
* PySpark

## Usage
1. Thhe directory "data" contains the datasets used
2. The file named "collaborative_filter" contains the code for collaborative fliterning
3. The file named "content_based_filtering" contains the code for content-based fliterning
