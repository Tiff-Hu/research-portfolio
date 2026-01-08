# Financial Market Prediction with News Sentiment + ML/NLP

## Summary
This project studies whether financial news sentiment and text-derived features can help predict next-day market direction (binary up/down). I combine NLP feature extraction (TF-IDF, BERT embeddings, sentiment scores) with market data and evaluate multiple ML and deep learning models.

## Data
- Financial news + sentiment: Alpha Vantage API (includes sentiment scores). 
- Market data: Yahoo Finance (global indices); labels defined as daily trend from Open vs Close. 

## Methods
- Text preprocessing (stopwords/lemmatization) + TF-IDF features
- Contextual text representations via BERT embeddings
- Models evaluated: Naive Bayes, SVM, Random Forest, LSTM, BERT, and an ensemble stacking approach

## Results (high level)
Multiple approaches reached ~70% accuracy (e.g., Naive Bayes/SVM/LSTM/BERT), and the stacking ensemble also achieved comparable performance, illustrating the value of combining diverse models and representations.

## Files
- `financial_text_market_prediction_report.pdf` — full write-up (methods, results, discussion)
- `financial_text_market_prediction_notebook.html` — code (exported notebook)

## Notes on reproducibility
Some paths in the code may reference local files (e.g., `/Users/...`). If sharing publicly, replace these with relative paths (e.g., `data/alpha_vantage_news.json`) and add brief instructions for obtaining the data via Alpha Vantage/Yahoo Finance.
