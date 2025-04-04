# Movie Recommendation System

## Overview
This project implements a Movie Recommendation System using the MovieLens dataset. The system utilizes two main techniques: **Collaborative Filtering** and **Content-Based Filtering** to provide personalized movie recommendations to users.

## Features
- **Collaborative Filtering**: Recommends movies based on user ratings and similarities between users.
- **Content-Based Filtering**: Recommends movies based on the attributes of the movies, such as genres.
- **Cold Start Handling**: Provides recommendations even for new users with limited ratings by leveraging content-based filtering.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- NumPy

## Dataset
The project uses the [MovieLens dataset](https://grouplens.org/datasets/movielens/) for movie ratings and metadata. Make sure to download the `ml-latest-small.zip` file and extract it to the project directory.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/avulahemalatha-12/Movie-Recommendation-system
   cd Movie-Recommendation-System
   ```

2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn
   ```

3. Download the MovieLens dataset and place the `ratings.csv` and `movies.csv` files in the `ml-latest-small` directory.

## Usage
To run the recommendation system, execute the following command in your terminal:
```bash
python MovieRecommendationSystem.ipynb
```

## Acknowledgments
- [MovieLens](https://grouplens.org/datasets/movielens/) for providing the dataset.
- The open-source community for the libraries used in this project.
