# Multiclass Sentiment Analysis with BiGRU + Attention

This project focuses on building and evaluating deep learning models for **sentiment analysis** on textual data.  
The objective was to classify text into three sentiment categories — **positive, negative, and neutral** — using advanced sequence modeling techniques.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/your-repo/blob/main/sentiment_analysis.ipynb)

---

## Project Overview
- Explored multiple architectures, starting from classical baselines to recurrent neural networks.  
- Implemented a **BiGRU with Attention mechanism**, which outperformed simpler models like UniGRU.  
- Incorporated **pre-trained GloVe embeddings** and a **custom preprocessing pipeline** to boost performance.  

---

## Key Features
- **Preprocessing Pipeline**: tokenization, lemmatization, and tailored stopword removal for sentiment-critical words.  
- **Deep Learning Model**: BiGRU with an attention layer to capture contextual importance in text sequences.  
- **Word Embeddings**: 300-dimensional pre-trained **GloVe embeddings** for rich semantic representation.  
- **Training Setup**: Adam optimizer, learning rate 0.001, batch size 32, trained for 14 epochs.  

---

## Results
- Achieved an **F1 Score of 0.62** on the test set.  
- BiGRU with Attention showed clear improvements over simpler baselines (e.g., UniGRU ~0.47–0.49 F1).  
- Custom stopword list significantly improved performance by retaining sentiment-bearing words.  

---

## Error Analysis & Future Work
- Struggled with ambiguous or sarcastic sentences containing mixed sentiments.  
- Potential improvements include integrating **POS tagging**, **domain-specific embeddings**, or **transformer-based models** for better semantic understanding.  

---

## Files
- `sentiment_analysis.ipynb` → Main Colab notebook with preprocessing, model training, and evaluation.  
  

