# Biomedical-Text-Analysis
## 📄 Overview
This project presents a comprehensive pipeline for summarizing clinical notes from the **MT Samples** dataset using Natural Language Processing (NLP) techniques. Our goal is to generate concise, medically relevant summaries from transcriptions, which can assist healthcare professionals in rapid decision-making.

We apply a series of models ranging from traditional extractive methods to cutting-edge transformer-based abstractive summarization approaches, and evaluate them using metrics such as ROUGE and BERTScore.

---

## 📊 Dataset

- **Source**: MT Samples
- **Fields Used**:
  - `transcription`: Full clinical notes.
  - `medical_specialty`: Category of the note.
  - `keywords`: Manually annotated key terms.

---

## 🧠 Models & Techniques

### 🧹 Preprocessing
- Tokenization
- Stopword removal
- Lemmatization
- Punctuation removal
- Lowercasing

### 🧪 Embeddings
- **TF-IDF** and **Bag-of-Words**
- Pretrained embeddings:
  - GloVe
  - FastText
  - Word2Vec
  - ClinicalBERT
  - SciBERT
  - BioBERT

### 🏷️ Named Entity Recognition
- **Med7**
- **MedicalNER**

### 📝 Classification Techniques

- **Decision Tree**
- **Random Forest**
- **Naives Bayes**
- **SVM**
- **XGBoost**

---

## 🧪 Evaluation Metrics

- **Precision, Recall, F1, Accuracy**

---

### 📝 Summarization Techniques

- **BART**
- **T5**
- **Pegasus**
- **BioGPT**

---

## 🧪 Evaluation Metrics

- **ROUGE** (ROUGE-1, ROUGE-2, ROUGE-L)
- **BERTScore** (Precision, Recall, F1)

---


## 🛠 Future Work

- Fine-tune domain-specific models more aggressively (e.g., SciBERT, BioGPT).
- Incorporate reinforcement learning with human feedback.
- Develop a user interface for clinical usage.
