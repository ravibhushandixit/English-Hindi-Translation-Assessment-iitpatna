# English-Hindi Translation Assignments

## Overview
This repository contains the implementation of **Assignment 1 and Assignment 2** for English-Hindi dataset processing and translation tasks.

- **Assignment 1**: Dataset Processing and Analysis
  - Extract English and Hindi sentences from the dataset.
  - Compute word counts for each sentence.
  - Filter sentences based on length (5–50 words) and word count difference (-10 to +10).
  - Save the cleaned dataset to Excel.

- **Assignment 2**: Translation using LLM
  - Translate 100 English sentences from the cleaned dataset into Hindi using a Large Language Model (**Helsinki-NLP/opus-mt-en-hi**).
  - Evaluate translations using **BLEU, CHRF, and TER** metrics.
  - Save translations and evaluation metrics.

---



## How to Run

1. **Open the notebook in Google Colab**.  
2. **Mount Google Drive**:
```python
from google.colab import drive
drive.mount('/content/drive')
