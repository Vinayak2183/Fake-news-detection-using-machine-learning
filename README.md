
# Fake News Detector

This project aims to build a machine learning-based Fake News Detector. It classifies news articles as either `Fake` or `Real` using natural language processing (NLP) techniques. The implementation is demonstrated in a Jupyter Notebook and utilizes the provided dataset.

---

## Features

- **Data Preprocessing:**
  - Cleaning and tokenizing text data.
  - Removing stopwords and unnecessary punctuation.

- **Model Training:**
  - Trained a classification model using machine learning algorithms.
  - Evaluated model performance using accuracy, precision, recall, and F1-score metrics.

- **Predictive Analysis:**
  - Accepts user input to classify whether the news article is `Fake` or `Real`.

---

## Dataset

The project uses the `fake_or_real_news.csv` dataset, which contains the following columns:
- `title`: The headline of the news article.
- `text`: The main content of the article.
- `label`: The target label, either `FAKE` or `REAL`.

## Results
Achieved a classification accuracy of 96.61%.

## Future Improvements
- Integrate more advanced NLP models like BERT or GPT for better accuracy.
- Deploy the model as a web application for real-time usage.
- Expand the dataset for better generalization.
