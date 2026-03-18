#  Sentiment Analysis on Airline Tweets

##  Project Overview

This project performs **sentiment analysis on airline tweets** to classify them into **positive, neutral, or negative sentiments** using Machine Learning techniques.

The model is trained on real-world tweet data and uses text preprocessing, feature extraction, and classification algorithms to predict sentiment.

---

##  Objective

The main objective of this project is to:

* Analyze customer opinions from tweets
* Classify sentiments into positive, neutral, and negative
* Build an efficient machine learning model for text classification

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Google Colab

---

##  Dataset

* Dataset: Airline Tweets Dataset
* Contains tweets related to airlines with labeled sentiments
* Columns used:

  * `text` → Tweet content
  * `sentiment` → Sentiment label

---

##  Workflow

1. Data Loading
2. Data Cleaning (removing URLs, mentions, special characters)
3. Text Preprocessing

   * Lowercasing
   * Stopword removal
   * Lemmatization
4. Feature Extraction using TF-IDF
5. Train-Test Split
6. Model Training using Logistic Regression
7. Model Evaluation

---

##  Model Used

* Logistic Regression

---

##  Results

* The model is trained using TF-IDF features
* Achieves good accuracy on test data
* Provides classification report with precision, recall, and F1-score

---

##  Sample Features

* Text cleaning using regex
* Stopword removal using NLTK
* Lemmatization using WordNetLemmatizer
* TF-IDF Vectorization (max_features = 5000)

---

##  How to Run

1. Open the notebook in Google Colab
2. Upload the dataset (`airline_sentiment.csv`)
3. Run all cells step by step
4. Enter custom input to test sentiment prediction

---

## 🔗 Open in Colab
https://colab.research.google.com/drive/1PoV5bA_qhn7IOkLko_5CSmIltOT6Qt__

---

##  Future Improvements

* Use Deep Learning models (LSTM, BERT)
* Improve accuracy with larger datasets
* Deploy as a web application
* Add real-time tweet analysis

---

##  Conclusion

This project demonstrates how machine learning can be used to analyze textual data and extract meaningful insights from customer feedback.

---

## Author

* Manickavasagam R
