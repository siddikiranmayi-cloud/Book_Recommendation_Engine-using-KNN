# 📚 Book Recommendation Engine using K-Nearest Neighbors (KNN)

A machine learning project built as part of the **freeCodeCamp Machine Learning with Python Certification**. This project recommends similar books using the **K-Nearest Neighbors (KNN)** algorithm based on user rating patterns from the Book-Crossings dataset.

## 📌 Project Overview

This recommendation engine analyzes user ratings to find books that are similar to a selected book. It uses collaborative filtering with the KNN algorithm and cosine similarity to generate recommendations.

## 🚀 Features

- Recommends 5 books similar to a given book
- Uses K-Nearest Neighbors (KNN)
- Cosine similarity for measuring book similarity
- Filters inactive users and rarely rated books
- Efficient sparse matrix implementation using SciPy

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Google Colab

## 📂 Dataset

This project uses the **Book-Crossings Dataset**, containing:
- 1.1 million book ratings
- 270,000+ books
- 90,000+ users

Dataset provided by freeCodeCamp:
https://cdn.freecodecamp.org/project-data/books/book-crossings.zip

## ⚙️ How It Works

1. Load the books and ratings datasets.
2. Remove users with fewer than 200 ratings.
3. Remove books with fewer than 100 ratings.
4. Create a user-book rating matrix.
5. Convert the matrix into a sparse matrix.
6. Train a KNN model using cosine similarity.
7. Recommend the five most similar books for a given title.

## ▶️ Example

Input:

```python
get_recommends("Where the Heart Is (Oprah's Book Club (Paperback))")
```

Output:

```python
[
  "Where the Heart Is (Oprah's Book Club (Paperback))",
  [
    ["Recommended Book 1", distance],
    ["Recommended Book 2", distance],
    ["Recommended Book 3", distance],
    ["Recommended Book 4", distance],
    ["Recommended Book 5", distance]
  ]
]
```

## 📁 Repository Structure

```
├── fcc_book_recommendation_knn.ipynb
├── README.md
└── LICENSE
```

## 🎯 Learning Outcomes

- Data preprocessing
- Collaborative filtering
- Recommendation systems
- Sparse matrices
- K-Nearest Neighbors (KNN)
- Cosine similarity
- Machine Learning with Python

## 🏆 Certification

This project was completed as part of the **freeCodeCamp Machine Learning with Python Certification**.

## 👩‍💻 Author

**Siddi Kiranmayi**

GitHub: https://github.com/your-username

---

⭐ If you found this project useful, consider giving it a star!
