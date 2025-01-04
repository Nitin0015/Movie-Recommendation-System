# **Movie Recommendation System**

This repository contains a Jupyter Notebook that demonstrates how to build a content-based movie recommendation system using machine learning techniques. The dataset used in this project includes metadata about movies such as genres, keywords, and overviews.

---

## **Overview**

Recommender systems are an essential part of modern applications, helping users discover items they might like based on their preferences. This project uses a **content-based filtering approach** to recommend movies to users based on their similarity to a selected movie. The similarity is calculated using **TF-IDF Vectorization** and **cosine similarity**.

The dataset includes features such as movie titles, genres, and descriptions, which are used to compute similarities between movies.

---

## **Dataset**

- **Source**: The dataset appears to be related to publicly available movie metadata datasets.
- **Features**:
  - `title`: Title of the movie.
  - `genres`: Genres associated with the movie.
  - `keywords`: Keywords describing the movie.
  - `overview`: A brief description of the movie's plot.
  - `cast`: Main cast members of the movie.
  - `crew`: Crew members involved in the movie's production.
  - `director`: Director of the movie.

---

## **Project Workflow**

1. **Data Loading**:
   - The dataset (`movies.csv`) is loaded into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics and data structure are examined.
3. **Data Preprocessing**:
   - Text data (e.g., genres, keywords, overview) is cleaned and preprocessed for vectorization.
4. **Feature Extraction**:
   - TF-IDF Vectorization is applied to convert textual data into numerical features.
5. **Similarity Calculation**:
   - Cosine similarity is used to calculate pairwise similarity scores between movies based on their features.
6. **Recommendation System**:
   - A function is implemented to recommend movies similar to a selected movie based on their similarity scores.

---

## **Dependencies**

To run this project, you need the following Python libraries:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install these dependencies using pip:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

---

## **How to Run**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/MovieRecommendationSystem.git
   cd MovieRecommendationSystem
   ```

2. Ensure that the dataset file (`movies.csv`) is in the same directory as the notebook.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Movie-Recomend.ipynb
   ```

4. Run all cells in the notebook to execute the code.

---

## **Results**

The recommendation system provides a list of movies similar to a selected movie based on its content attributes (e.g., genres, keywords, overview). The results can be further improved by incorporating collaborative filtering or hybrid approaches.

---

## **Acknowledgments**

- The dataset was sourced from publicly available movie metadata datasets or repositories.
- Special thanks to Scikit-learn for providing robust machine learning tools.

---
