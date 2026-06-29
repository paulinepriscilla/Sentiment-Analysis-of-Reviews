SENTIMENT ANALYSIS OF REVIEWS

Project Overview

The Sentiment Analysis of Reviews project is a Machine Learning project that predicts the sentiment of customer reviews as **Positive**, **Negative**, or **Neutral** based on the review text.

This project uses Natural Language Processing (NLP) techniques to clean and process text data before training Machine Learning models for sentiment classification.

This project is developed as part of an AI & Machine Learning Internship.

Objective

The main objective of this project is to:

- Analyze customer reviews.
- Classify reviews into Positive, Negative, or Neutral sentiments.
- Learn text preprocessing using NLP.
- Train Machine Learning models.
- Evaluate model performance.

Dataset

The dataset used in this project contains customer reviews along with their corresponding sentiment labels.

Dataset Features

- Review Text
- Sentiment Label (Positive / Negative / Neutral)

The dataset is used to train the Machine Learning model for sentiment prediction.

Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- TF-IDF Vectorizer

Machine Learning Models

The following Machine Learning algorithms were used:

- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)

The best-performing model was selected based on accuracy.

Data Preprocessing

The following preprocessing steps were performed:

- Removed missing values
- Converted text to lowercase
- Removed punctuation
- Removed stop words
- Tokenized text
- Converted text into numerical features using TF-IDF Vectorization

Data Visualization

The project includes:

- Sentiment Distribution
- Word Frequency Analysis
- Bar Chart
- Word Cloud (Optional)
- Confusion Matrix

These visualizations help understand the sentiment distribution in customer reviews.

Project Workflow

1. Load the dataset
2. Clean the text data
3. Perform text preprocessing
4. Convert text into numerical features
5. Split the dataset
6. Train Machine Learning models
7. Evaluate model performance
8. Predict review sentiment

Output

The project displays:

- Dataset information
- Sentiment distribution
- Accuracy score
- Confusion Matrix
- Classification Report
- Predicted sentiment of reviews

Project Files


Sentiment-Analysis-of-Reviews/
│
├── reviews.csv
├── sentiment_analysis.ipynb
├── sentiment_model.pkl
├── README.md
└── requirements.txt


How to Run

1. Download the review dataset.
2. Open Google Colab or Jupyter Notebook.
3. Upload the dataset.
4. Run all the code cells.
5. View the accuracy and graphs.
6. Enter a review to predict its sentiment.

Future Improvements

- Improve model accuracy using Deep Learning.
- Build a web application using Streamlit.
- Use larger datasets for better prediction.
- Deploy the model using Flask or Streamlit.

Author

Pauline Priscilla C

AI & Machine Learning Internship Project

Acknowledgement

This project is developed for educational and internship purposes using Machine Learning and Natural Language Processing (NLP). The dataset used is intended for learning sentiment analysis techniques.
