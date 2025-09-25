## Sentiment Analysis for persian text
I fine tuned two LLMs: 

- ***BERT-BASE-PARSBERT-UNCASED*** which is a monolingual language (Persian) model based on Google’s BERT architecture with the same configurations as BERT-Base.
- ***XLM-ROBERTA-BASE*** which is a multilingual version of RoBERTa. It is pre-trained on 2.5TB of filtered CommonCrawl data containing 100 languages.

on 
- ***ArmanEmo dataset*** which is a human-labeled emotion dataset of more than 7000 Persian sentences labeled for seven categories.
  - Anger
  - Fear
  - Happiness
  - Hatred
  - Sadness
  - Wonder
  - Other

for persian sentiment analysis task.
