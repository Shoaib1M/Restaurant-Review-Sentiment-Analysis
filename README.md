# 🍽️ Restaurant Review Sentiment Analysis

This project demonstrates a simple **sentiment analysis model** that classifies restaurant reviews as positive or negative. It uses a **Naive Bayes classifier** trained on a dataset of restaurant reviews, leveraging **natural language processing (NLP)** techniques for text preprocessing and feature extraction.

---

## 🚀 Features

- **Data Preprocessing**: Cleans raw text reviews by removing non-alphabetic characters, converting to lowercase, removing stopwords, and applying stemming.
- **Bag-of-Words Model**: Converts text into numerical features using Count Vectorization.
- **Naive Bayes Classifier**: Applies Gaussian Naive Bayes for binary sentiment classification.
- **Model Evaluation**: Assesses performance using a **confusion matrix** and **accuracy score**.

---

## ⚙️ Installation

To run this project, you'll need Python and several libraries.

### 1. Clone the repository
```bash
git clone https://github.com/your-username/restaurant-review-sentiment-analysis.git
cd restaurant-review-sentiment-analysis
 ```
📊 Dataset
The project uses a TSV file named Restaurant_Reviews.tsv.

Format:

Review	Liked
Wow... Loved this place.	1
Crust is not good.	0
Not tasty and the texture was just nasty.	0
Stopped by during the late May bank holiday... loved it.	1
The selection on the menu was great and so were prices.	1

Ensure the file is placed in the same directory as the Python script.

▶️ Usage
Save the Python script as sentiment_analyzer.py

Make sure Restaurant_Reviews.tsv is in the same folder.
