# Prodigy_DS_04

# Tweet Sentiment Analysis

**Project Overview:**
This project analyzes sentiments expressed in tweets using the VADER sentiment analysis tool and a Logistic Regression model. The goal is to classify sentiments as positive, neutral, or negative based on the text of the tweets.

**Data Description:**
The dataset used contains tweets labeled with sentiments. It includes columns for the target sentiment, tweet ID, date, and the tweet text itself. The target sentiment is binary, where 0 indicates negative sentiment and 1 indicates positive sentiment.

**Installation Requirements:**
Ensure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
```

**Usage Instructions:**
1. **Data Preprocessing:**
   - Loaded the tweet sentiment dataset and assigned appropriate column names.
   - Simplified the sentiment labels for easier analysis.

2. **Sentiment Analysis:**
   - Used the VADER sentiment analysis tool to calculate sentiment scores for each tweet.
   - Classified sentiments into positive, neutral, or negative based on the calculated scores.

3. **Visualization:**
   - Visualized the distributions of original sentiment labels and VADER results using count plots.
   - Displayed the distribution of sentiment scores using a histogram.

4. **Model Training:**
   - Vectorized the tweet text using CountVectorizer.
   - Trained a Logistic Regression model to classify sentiments and evaluated model performance using a classification report.

**Results:**
The classification report provides insights into the model's accuracy, precision, recall, and F1-score for each sentiment class.

