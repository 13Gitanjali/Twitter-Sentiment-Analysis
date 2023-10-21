# Twitter-Sentiment-Analysis

## Project Overview
This project aims to build a sentiment analysis model that can classify tweets into different categories based on their sentiment: positive, negative, or neutral. This can be useful for businesses to understand 
customer opinions and reactions towards their products or services in real time.

## Getting Started

### Prerequisites
- Python 3.7+
- Libraries: tweepy, pandas, numpy, scikit-learn, nltk

### Installation
1. Clone the repo:
   ```
   git clone https://github.com/13Gitanjali/twitter-sentiment-analysis.git
   ```
2. Install Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
Run the main script to start the analysis:
```
python main.py
```

## Dataset
The dataset used in this project is obtained from Twitter's API. It consists of tweets related to various topics.

## Model
We use a Naive Bayes classifier for this sentiment analysis task. The model is trained on a preprocessed dataset where tweets are tokenized and cleaned for stop words and punctuation.

## Results
The model's performance is evaluated using accuracy, precision, recall and F1-score.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
