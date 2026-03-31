# Token-Level Part-of-Speech Tagging using RNN Models

This project performs **Part-of-Speech (POS) tagging** on the POS 1 dataset using recurrent neural network architectures.

## Models Used
- Simple RNN  
- LSTM  
- GRU  
- BiLSTM  

## Dataset
- POS 1 dataset  
- Training sentences: 19,183  
- Testing sentences: 4,796  
- Total POS tags: 41 unique tags  

## Preprocessing
- Removed sentences with token-tag mismatch  
- Tokenized words using Keras Tokenizer  
- Encoded POS tags using LabelEncoder  
- Applied padding to fixed sentence length  

## Training Setup
- Embedding dimension: 300  
- Recurrent units: 32  
- Batch size: 256  
- Optimizer: Adam  
- Early stopping applied  

## Result
**BiLSTM achieved the best performance**
- Accuracy: 97%  
- Macro F1-score: 0.85  

## Files Included
- `report.pdf` → Project report  
- `project.ipynb` → Implementation notebook  
