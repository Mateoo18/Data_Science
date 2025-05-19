# Assignment 3 (Advanced) – Predicting Dow Jones Index from News Headlines

This notebook explores whether it's possible to predict movements of the **Dow Jones Industrial Average** (DJIA) based on the **top 25 news headlines** from each day between 2008 and 2016. The project combines natural language processing (NLP) with machine learning to simulate a financial prediction pipeline.

## 📊 Datasets Used

1. **News_Data_1**  
   - Daily top 25 news headlines (2008–2016)  
   - Contains a `Label` column indicating market movement:  
     - `1` → Positive movement  
     - `0` → Negative movement  
   - Used for training machine learning models.

2. **Stock_Data**  
   - Contains daily DJIA closing prices.  
   - Used for simulating trading decisions based on predictions.

3. **News_Data_2**  
   - Additional news data for testing the trained models.  
   - Enables evaluating performance on unseen data.

## 📌 Contents

- Data cleaning and handling missing values  
- Text preprocessing (lowercasing, removing punctuation, combining news headlines)  
- Feature extraction using Bag-of-Words and TF-IDF  
- Training and evaluation of multiple classifiers:
  - Logistic Regression  
  - Random Forest  
  - Naive Bayes  
  - Support Vector Machine (SVM)  
  - XGBoost

- Model performance evaluation using:
  - Accuracy  
  - Precision, Recall, F1-score  
  - AUC-ROC

- Final simulation of predictions on the test dataset to simulate "buy/sell/hold" signals.

## 🧠 Techniques Used

- Natural Language Processing (NLP)
- Text vectorization (CountVectorizer, TF-IDF)
- Supervised learning for binary classification
- Evaluation with classification metrics
- Application of predictions in financial trading context

## 🛠️ Tools & Libraries

- Python
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn
- nltk

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mateoo18/Data_Science.git
   cd Data_Science/Exercise_3_advanced
