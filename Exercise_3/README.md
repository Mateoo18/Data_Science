# Assignment 3 – Sentiment Classification on Amazon Baby Reviews

This notebook presents a solution to a binary text classification task using natural language processing (NLP). The dataset consists of **Amazon Baby product reviews**, each labeled with a sentiment score. The goal is to classify whether a review expresses a **positive** or **negative** sentiment.

## 📊 Dataset

- **Source**: Amazon Baby Reviews dataset
- **Columns**:
  - `review`: text of the review
  - `rating`: original numeric rating (used to derive sentiment)
- **Target**: Binary sentiment label (positive/negative), derived from rating:
  - Ratings ≥ 4 → positive
  - Ratings ≤ 2 → negative
  - Neutral ratings (3) are excluded

## 📌 Contents

- Data cleaning and filtering neutral reviews
- Text preprocessing (lowercasing, removing punctuation, stopwords, etc.)
- Feature extraction using CountVectorizer (Bag-of-Words)
- Train-test split
- Classification using Logistic Regression
- Evaluation: accuracy, confusion matrix, classification report

## 🧠 Techniques Used

- Binary label generation from multiclass ratings
- CountVectorizer for text representation
- Logistic Regression for classification
- Evaluation using accuracy, precision, recall, and F1-score

## 🛠️ Tools & Libraries

- Python
- pandas
- numpy
- scikit-learn
- nltk
- seaborn
- matplotlib

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mateoo18/Data_Science.git
   cd Data_Science/Exercise_3
