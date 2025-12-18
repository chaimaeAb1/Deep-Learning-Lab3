# Deep Learning Lab 3 – Sequence Models & Transformers for NLP

**Abdelmalek Essaadi University**  
**Faculty of Sciences and Techniques of Tangier**  
**Computer Engineering Department – Master SITBD**  
**Module:** Deep Learning  
**Professor:** Pr. ELAACHAK LOTFI  
**Student:** ABABRI Chaimae  

---

## Objective

The objective of this lab is to become familiar with Natural Language Processing (NLP) using PyTorch.
The lab focuses on sequence models (RNN, BiRNN, GRU, LSTM) and Transformer-based models (GPT-2).

---

## Part 1 – Text Classification / Regression

### Preprocessing
- Text cleaning
- Tokenization
- Vocabulary building
- Padding and truncation

### Models Implemented
- RNN
- Bidirectional RNN
- GRU
- LSTM

### Training Setup
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam
- Epochs: 30

### Evaluation Metrics
- MSE
- MAE
- BLEU score (used for comparison as required by the lab)

### Results

| Model | MSE | MAE | BLEU |
|------|-----|-----|------|
| RNN | 0.183 | 0.389 | 0.171 |
| BiRNN | 0.194 | 0.353 | 0.162 |
| GRU | 0.189 | 0.365 | 0.182 |
| LSTM | 0.175 | 0.345 | 0.186 |

---

## Part 2 – Transformer (GPT-2)

A pre-trained GPT-2 model was loaded and fine-tuned on a custom dataset.
The model was then used to generate text based on a given prompt.

**Prompt:**
Artificial intelligence will be much more powerful than it is today.

---

## What I Learned – Personal Synthesis

During this lab, I learned to:
- Collect and preprocess Arabic text data for Natural Language Processing tasks
- Implement sequence models (RNN, BiRNN, GRU, LSTM) in PyTorch for text relevance prediction
- Fine-tune Transformer models such as GPT-2 for text generation
- Handle challenges related to Arabic language processing without specialized NLP libraries
- Manage small datasets and reduce overfitting in deep learning models

**Key takeaways:**  
LSTM and GRU architectures outperform basic RNNs for sequence modeling tasks, while Transformer-based models are powerful for text generation but require careful fine-tuning and data preparation.

---

