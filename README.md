# DMML2020_Tissot
# Group Project : Real or Not? NLP with Disaster Tweets

## Project description
Twitter has become a popular social network for many users. However, it is also used to relay fake news.

The goal of this project is to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.

To train the model, we have access to a dataset of 6,471 tweets that were already classified (0 = fake news, 1 = real news).

## Progress of the project

### Week 1
- Github
  - Repository initialisation and structure
  - Documentation README

- Notebook
  - Modules importation
  - Tokenizer function
  - Simple pipeline model
  - Exploration 

### Week 2
- Notebook
  - Tokenizer optimization
  - Model finetuning
  - Text cleaning

### Week 3
- Notebook
  - Vector and classifier optimization
  - Start of the un-text cleaning (because of the over cleaning we did on week 2) 

### Week 4
- Notebook
  - Un-text cleaning
  - Model fine tuning --> best model
  - Try of a custom model

## Results 
- 78 submissions in AIcrowd 
- Best accuracy : 0.832 on the 64 submission 
- Best model : Logistic Regression , Tfidf

![](https://github.com/deborahhernandez/DMML2020_Tissot/blob/main/documents/HistPrec.png)

## Lessons learned
- Beware of over text cleaning
- Emojis are important 
- Base rate rebalancing is not always good 
- In this project: better to predict 0 than 1 (2x more false positives than false negatives) 
