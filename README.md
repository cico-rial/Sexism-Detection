# Sexism Detection in Online Content

This repository contains solutions to two assignments for the NLP exam addressing the **detection and classification of sexism in online content**, specifically social media posts. Both assignments focus on different datasets and methodologies, providing a comprehensive look at **traditional machine learning pipelines** as well as **Large Language Model (LLM) prompting techniques**.

Authors: Leonardo Chiarioni, Federico Faccioli, Shariq Mohd Ansari

---

## 📂 Repository Structure

### 📁 Assignment 1 - EXIST Task
- **Task:** sEXism Identification in Social neTworks (EXIST)
- **Dataset:** Collection of tweets annotated for the presence of sexism.
- **Objective:** Classify tweets into *sexist* or *non-sexist* categories.
- **Pipeline Overview:**
    - **Preprocessing:** Text cleaning, tokenization, lemmatization, stopword removal.
    - **Embedding:** Tweets encoded using **GloVe** word embeddings.
    - **Models Used:**  
        - **BiLSTM-based models** with varying complexity.  
        - **Transformer-based classifier** using **Twitter-RoBERTa** from HuggingFace.

---

### 📁 Assignment 2 - EDOS Task
- **Task:** Explainable Detection of Online Sexism (EDOS), Task A
- **Dataset:** English-language dataset sourced from **Gab** and **Reddit**, annotated for sexist content across multiple levels:
    - **Level A:** Binary classification – *sexist* vs. *non-sexist*.
    - **Level B:** If sexist, classify into **direct sexism**, **indirect sexism**, or **incitement**.
    - **Level C:** Further classify into specific categories (e.g., **stereotyping**, **threats**, etc.).
- **Objective:** Use **prompting techniques** to detect sexism.
- **Methodology:** 
    - **Large Language Models (LLMs)** from **HuggingFace** were used.
    - Experiments conducted with:  
        - **Zero-shot prompting** (no training examples provided).  
        - **Few-shot prompting** (limited training examples provided).

---

## 📥 Download & Setup

To clone this repository, run:

```bash
git clone https://github.com/cico-rial/Sexism-Detection.git
```
