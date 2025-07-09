This project is part of the course **Artificial Intelligence II** in the Department of Informatics and Telecommunications, National and Kapodistrian University of Athens for the **2024**.

The project explores and compares different binary Sentiment Analysis Classifiers. It reads text(tweets) extracted from twitter.com and classifies them as either positive or negative. It consists of 3 different assignments.

## Assignments

1. **TF-IDF vectorization** and a **Logistic Regression** model using the Scikit-learn library.  
2. **Pre-trained GloVe embeddings** (`glove-twitter-200d`) and a **Feed Forward Neural Network** model using the PyTorch library.  
3. **Transformer-based models**: `BERT` and `DistilBERT` (`bert-large-uncased` and `distilbert-base-uncased`).

Summary of Results:

| Model                                             | Validation Accuracy |
| ------------------------------------------------- | ------------------- |
| TF-IDF with Logistic Regression                   | 0.80640             |
| GloVe Embeddings with Feed Forward Neural Network | 0.800901            |
| BERT                                              | 0.86388             |
| DistilBERT                                        | 0.84890             |
