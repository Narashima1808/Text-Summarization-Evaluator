# Text-Summarization-Evaluator


**Comparative Study of Extractive vs Abstractive Summarization using ROUGE Metrics**

## 📌 Overview

This project implements and evaluates two fundamental approaches to automatic text summarization:

* **Extractive Summarization** (TF-IDF based sentence ranking)
* **Abstractive Summarization** (Transformer-based models via HuggingFace)

The goal is not just implementation, but **systematic evaluation and analysis** of when and why each method performs better.

---

## 🎯 Objectives

* Build a lightweight extractive summarizer from scratch
* Leverage pretrained transformer models for abstractive summarization
* Evaluate both using **ROUGE metrics (ROUGE-1, ROUGE-2, ROUGE-L)**
* Perform qualitative analysis across:

  * Short vs long documents
  * Technical vs narrative text
  * Information density

---

## 🧠 Key Insights Explored

* When does extractive summarization outperform abstractive?
* Trade-offs between **faithfulness vs fluency**
* Impact of document length on summarization quality
* Limitations of ROUGE as an evaluation metric

---

## ⚙️ Methodology

### 1. Extractive Summarization

* Sentence tokenization
* TF-IDF vectorization
* Sentence scoring and ranking
* Top-k sentence selection

### 2. Abstractive Summarization

* Pretrained transformer models (BART/T5)
* HuggingFace pipeline (no training required)

### 3. Evaluation

* ROUGE scoring
* Comparative analysis
* Case-based interpretation

---



---

## 🛠️ Tech Stack

* Python
* NLTK / spaCy
* scikit-learn
* HuggingFace Transformers
* rouge-score
* pandas, matplotlib

---




## 📈 Future Work

* Add BERTScore for semantic evaluation
* Multi-document summarization
* Domain-specific summarization (finance, legal)

---

## 👨‍💻 Author

Narashimamurthy
