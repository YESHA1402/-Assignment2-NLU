# Assignment 2 – Natural Language Understanding

**Name:** Yesha Shah  
**Roll No:** B22CS067  

---

## Overview
This assignment focuses on two core NLP tasks:
1. Corpus creation from real-world IIT Jodhpur documents  
2. Name generation using a character-level RNN  

---

## Problem 1: Corpus Creation
A corpus was constructed using multiple IIT Jodhpur documents including:
- Curriculum (B.Tech, M.Tech)
- Academic regulations
- Course descriptions
- Board of Governors records
- Student council documents  

### Preprocessing Steps
- Text extraction using pdfplumber  
- Lowercasing and cleaning using regex  
- Tokenization using NLTK  
- Stopword removal  
- Frequency analysis  

The resulting corpus is clean, diverse, and suitable for NLP tasks.

---

## Problem 2: Name Generation using RNN
A character-level RNN model was implemented to generate Indian names.

### Model Details
- Vanilla RNN  
- Hidden size: 64  
- Optimizer: Adam  
- Loss: CrossEntropy  

The model learns character patterns and generates new names with reasonable diversity.

---

## Results
- Successfully created a large corpus (~400k+ characters)
- Generated multiple new names after training
- Observed meaningful character patterns in output  

---

## How to Run
1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. Outputs will be generated in the notebook  

---

## Note
Due to time constraints, a Vanilla RNN was implemented instead of more complex architectures. However, it effectively demonstrates sequence learning.
