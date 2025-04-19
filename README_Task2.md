# Task 2: Sentiment Analysis on X (Twitter) Data

This notebook performs **Sentiment Analysis** using the `VADER` analyzer from the NLTK library.

## ✅ Objectives:
- Classify tweets into Positive, Neutral, Negative
- Evaluate accuracy and visualize results
- Identify model limitations

## 📂 Dataset:
- `X data.csv` (provided by ShadowFox)
- Columns: `clean_text`, `category` (-1.0 = Negative, 0.0 = Neutral, 1.0 = Positive)

## 📈 Outputs:
- Confusion matrix heatmap
- Classification report (precision, recall, F1-score)
- Accuracy ~57% using VADER

## ⚠️ Limitations of VADER:
- Rule-based, not context-aware
- Cannot detect sarcasm
- Limited in political/complex sentiment

📁 File: `Sentiment_Analysis_X.ipynb`
