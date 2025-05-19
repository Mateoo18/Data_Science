# Assignment 4 – Document Similarity and Text Representation with Wikipedia Articles

This notebook focuses on exploring **document similarity** using a collection of Wikipedia articles. It demonstrates how to represent documents using Bag-of-Words and TF-IDF techniques, and how different similarity measures affect the notion of document closeness.

## 📊 Dataset

- Abridged Wikipedia dataset.
- Each record includes:
  - A person's name
  - A link to their Wikipedia page
  - The text content of their article (lowercased)

## 📌 Contents

- Construction of a Bag-of-Words matrix using `CountVectorizer`
  - Top 10,000 most frequent words
  - Token pattern includes all word units (even single-letter)
- Finding nearest neighbors of Barack Obama’s article using:
  - Euclidean distance
  - Cosine similarity
  - TF-IDF-weighted vectors
- Ranking and comparing similarity results between raw counts and TF-IDF
- Interpretation and analysis of results

## 🧠 Techniques Used

- Text vectorization: CountVectorizer and TF-IDF
- Distance metrics:
  - Euclidean distance
  - Cosine similarity
- Nearest neighbors analysis
- Matrix operations for large-scale document comparison

## 🛠️ Tools & Libraries

- Python
- pandas
- numpy
- scikit-learn

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mateoo18/Data_Science.git
   cd Data_Science/Exercise_4
