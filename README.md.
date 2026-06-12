# Smart Legal AID

ML pipeline for legal case retrieval and judgment outcome prediction, built as part of the Smart India Hackathon 2022 (National Finalist, DRDO problem statement).

---

## Problem

Courts in India handle a large backlog of cases, many of which have precedents in prior judgments. This project builds a system to retrieve similar prior cases for a given query case, predict judgment outcomes, and estimate case timelines using NLP and deep learning.

---

## Notebooks

| File | What it does |
|---|---|
| `BM25_similar_case_retrieval.ipynb` | BM25 retrieval combined with BERT and LegalBERT embeddings for similar case search |
| `similar_case_various_models.ipynb` | Comparison of BM25, Doc2Vec, TF-IDF, LegalBERT base, and LegalBERT small across the AILA 2019 dataset with precision and recall scoring |
| `Judgement_Prediction__1_.ipynb` | Judgment outcome classification using transformer-based models |
| `Judgement_prediction_Bigru__1_.ipynb` | BiGRU-based sequence model for judgment prediction |
| `timeline_retrieval__2_.ipynb` | Case timeline estimation from legal text |

---

## Dataset

AILA 2019 (Artificial Intelligence for Legal Assistance):
- 2,914 prior case documents
- 50 query cases
- Relevance judgments for evaluation

---

## Methods

**Similar Case Retrieval:**
- BM25 (Okapi) with tokenized corpus
- Doc2Vec with tagged documents
- TF-IDF with cosine similarity
- LegalBERT base and small (nlpaueb) with pooled embeddings
- BERT sentence transformers

**Judgment Prediction:**
- Transformer-based classification
- BiGRU sequence model with NLTK preprocessing

**Evaluation:**
- Precision and Recall computed against AILA 2019 relevance judgments (top-10 retrieved per query)

---

## Tech Stack

Python, PyTorch, TensorFlow, Hugging Face Transformers, LegalBERT, sentence-transformers, rank-bm25, Gensim, Scikit-learn, NLTK, Pandas, NumPy

---

## Context

Built for Smart India Hackathon 2022 under the DRDO problem statement on legal AI. The team reached the National Finals.

---

## Team

**Team:** Puneeth Ram P, Shreevarshan B, Sri Likhita Adru, Sunil B, Surya J, Yashwant B

**Mentors:** D.M. Divya, Subha I

R.M.K Engineering College, India
