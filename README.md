# Unsupervised NLP Analysis of IMDB Movie Reviews

**Author:** Shane Hans Uy  
**Institution:** University of Santo Tomas (UST)  
**Project Type:** Academic Data Science Project  

## Description

This project was developed as part of an Artificial Intelligence course requirement. It applies unsupervised natural language processing techniques to discover hidden patterns in IMDB movie reviews. The workflow includes text preprocessing, TF-IDF vectorization, K-Means clustering, LDA topic modeling, and evaluation metrics to compare whether the discovered clusters and topics align with sentiment labels or capture broader review themes.

## Project Goal

The goal of this project is to explore how unsupervised learning methods identify patterns in movie review text without directly using sentiment labels during training.

## Methods Used

- Text preprocessing
- TF-IDF vectorization
- K-Means clustering
- TruncatedSVD visualization
- LDA topic modeling
- Topic coherence evaluation
- Document-topic distribution analysis
- ARI and NMI evaluation against sentiment labels

## Key Results

| Method | Silhouette | ARI | NMI | Coherence |
|---|---:|---:|---:|---:|
| K-Means | 0.0024 | 0.0900 | 0.0688 | N/A |
| LDA | N/A | 0.0949 | 0.0755 | 0.3071 |

## Key Findings

K-Means produced clusters that showed partial alignment with sentiment labels, but the clusters were not clearly separated. LDA topic modeling provided more interpretable themes and slightly better alignment with sentiment based on ARI and NMI scores. However, both methods showed that unsupervised learning is better for discovering hidden themes and text structure than directly predicting positive or negative sentiment.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Gensim
- Matplotlib
- Seaborn
