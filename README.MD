 Twitter Sentiment Analysis on Entities

This project analyzes and visualizes sentiment patterns in social media data using the [Twitter Entity Sentiment Analysis Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis). The goal is to understand public opinion towards specific topics and brands.

 Dataset
- Source: Kaggle
- File: `twitter_training.csv`
- Fields: Tweet ID, Entity (brand/topic), Sentiment, Tweet Text

 Features
- Clean tweets (remove hashtags, mentions, URLs)
- Visualize sentiment distribution using Seaborn
- Generate word clouds for Positive, Negative, and Neutral tweets
- (Optional) Train a logistic regression model for sentiment classification

 Sample Visuals
- Word Clouds by Sentiment
- Bar Plot for Sentiment Distribution
- Classification Report (if ML is applied)

 How to Run

1. Install dependencies:
```bash
pip install pandas matplotlib seaborn wordcloud scikit-learn
