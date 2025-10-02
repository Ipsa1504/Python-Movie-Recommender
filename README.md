# MovieLens Recommender System Tutorial

![Python](https://img.shields.io/badge/Python-3.10-blue) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.12-orange) ![License](https://img.shields.io/badge/License-MIT-green)

---

## Overview

This project is a **step-by-step tutorial** on building a practical **Recommendation System** using Python and TensorFlow Recommenders (TFRS).  
The system demonstrates both **retrieval-based** and **ranking-based** recommendation techniques using the popular **MovieLens dataset**.

This tutorial is designed for students, aspiring data scientists, and professionals to learn how to implement an **end-to-end recommender system pipeline** from scratch.

---

## Features

- Complete **recommendation pipeline**:
  - Data preprocessing & exploration
  - Model training and evaluation
  - Personalized movie recommendations
- Implements **Collaborative Filtering** using TensorFlow Recommenders
- Covers both **retrieval** (candidate generation) and **ranking** (scoring & ordering) approaches
- Simple, modular, and easy-to-understand code
- Includes **evaluation metrics** like Recall@K
- Ready-to-run **Jupyter Notebook** with minimal setup

---

## Technologies & Libraries

- **Language**: Python 3.x  
- **ML Frameworks**: TensorFlow, TensorFlow Recommenders (TFRS)  
- **Data Handling**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  

---

## Dataset

- Dataset used: [MovieLens 100k](https://grouplens.org/datasets/movielens/100k/)  
- Contains user ratings for movies:
  - User ID
  - Movie ID
  - Rating
  - Timestamp  
- Used for training, validation, and testing recommender models

---

## Project Structure
  Recommendation-Systems-Tutorial/
│
├── data/ # Dataset folder
├── notebooks/ # Jupyter notebooks with tutorial
│ └── movie_recommender.ipynb
├── scripts/ # Python scripts for training and evaluation
├── requirements.txt # Required Python packages
└── README.md


---

## Installation

1. **Clone the repository**
   ```bash
    git clone https://github.com/your-username/MovieLens-Recommender-System.git
    cd MovieLens-Recommender-System
2. **Install dependencies**

       pip install -r requirements.txt


3. **Run Jupyter Notebook**
   ```bash
    jupyter notebook


4. **Open notebooks/movie_recommender.ipynb to start.**

# How to Use

1. Load the MovieLens dataset.

2. Preprocess data to create user-item interactions.

3. Train a retrieval model to generate candidate items.

4. Train a ranking model to score and rank recommendations.

5. Evaluate model performance using Recall@K and other metrics.

6. Generate personalized movie recommendations for a user.

# Sample Output

Top-5 movie recommendations for User ID 123:

1. The Shawshank Redemption

2. Forrest Gump

3. The Godfather

4. Fight Club

5. The Dark Knight

# Learning Outcomes

  Hands-on experience building collaborative filtering recommendation systems

  Understanding retrieval vs ranking models

  Working with TensorFlow Recommenders on real-world datasets

  Evaluating models with Recall@K and other metrics

# References

TensorFlow Recommenders Guide: https://www.tensorflow.org/recommenders

MovieLens Dataset: https://grouplens.org/datasets/movielens/

