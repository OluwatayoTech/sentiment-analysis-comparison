# Sentiment Analysis Comparison: Tokenization → Statistics → Semantics

Compares custom tokenization, TF-IDF + Logistic Regression, and sentence
embeddings + Logistic Regression on IMDB movie review sentiment classification.

## Results
| Model | Accuracy | F1 |
|---|---|---|
| Statistical (TF-IDF + LogReg) | 0.866 | 0.868 |
| Semantic (Embeddings + LogReg) | 0.811 | 0.812 |

See `sentiment_analysis.ipynb` for full analysis, tokenizer comparison, and error analysis.
