# Exploring — Tokenizers & Data Loaders 🚀

When I started my NLP journey, I was fascinated by how **raw text** magically turns into **numbers that models understand**. So in this notebook, I decided to explore and experiment with **different tokenization libraries** 🧰 and **data loading techniques** 📦 to get a strong practical foundation.

This repository documents that learning journey — from basic tokenization to efficient batching with data loaders!

---

## ✨ What I Explored

### 🔤 **Tokenization Libraries & Techniques**

I experimented with several popular NLP libraries to understand how they break down text:

- 📝 **NLTK** — classic word tokenization, n-grams & frequency distributions  
- 🧬 **spaCy** — powerful multilingual tokenization (English & French models)  
- 🤗 **Hugging Face Transformers** —  
  - `BertTokenizer` → based on the **WordPiece algorithm**, which breaks words into subword units to handle rare or unknown tokens efficiently.  
  - `XLNetTokenizer` → uses **SentencePiece** with a **Unigram language model**, enabling language-independent, unsupervised subword tokenization.  
- 🔡 **SentencePiece** — standalone subword tokenization library used internally by several modern NLP models.  
- 🧠 **TorchText** — `basic_english` tokenizer and vocabulary building utilities for quick text processing.

This hands-on exploration helped me see **how different tokenizers segment text**, **what kind of tokens they produce**, and how **tokenization choices affect downstream NLP tasks**.

---

### 🧰 **Data Loading & Batching**

Alongside tokenization, I explored how to **feed data efficiently to models** using **PyTorch’s DataLoader**:

- 📦 **Batching** — loading data in mini-batches to speed up training  
- 🔄 **Shuffling** — ensuring models don’t overfit to sequence order  
- 🧠 **Memory Management** — preventing memory overflow during training with efficient loaders

---

## 📚 Why This Matters

Tokenization and data loading are **the first steps of every NLP pipeline**. Mastering them early helps you:

- Understand how text becomes model input 🧠  
- Improve performance and training efficiency ⚡  
- Build solid foundations for future NLP projects 🚀

---

