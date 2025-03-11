# POS Sequence Tagging

## Project Overview
## This project is part of the NLP course in my masters degree at the GUC. 


This project aims to perform Part-of-Speech (POS) tagging using Natural Language Processing (NLP) techniques. The project is divided into three main milestones, each focusing on different aspects of the POS tagging process, from data preprocessing to building and fine-tuning neural network models.

## Milestone 1: Exploratory Data Analysis and Data Preprocessing

In the first milestone, I performed exploratory data analysis (EDA) and data preprocessing to prepare the dataset for training.

### Data Preprocessing

**Tokenization**:  Splitting text into individual tokens.

**Lemmatization**:  Reducing words to their base or root form.

**Removing Stop Words**:  Eliminating common words that do not contribute to the model's performance.

**Removing Punctuation**: Stripping out punctuation marks.

## Milestone 2: Building a Neural Network Model

In the second milestone, I built a neural network model from scratch without using any pre-trained models. The architecture consists of the following layers:

1) **Embedding Layer**: Converts words into dense vectors of fixed size.
  
2) **Bi-LSTM Layer**: Captures long-term dependencies in the text using Bidirectional Long Short-Term Memory (LSTM) units.

3) **Dense Layer**: Outputs the probability distribution over POS tags.


## Milestone 3: Fine-Tuning with a Pre-Trained Model

In the third milestone, I used a pre-trained BERT model and applied fine-tuning for POS tagging.

### Fine-Tuning with BERT

Leveraged the BERT (Bidirectional Encoder Representations from Transformers) model.

Fine-tuned the model on the POS tagging dataset.


### Model Performance

Achieved an accuracy of 86% on the test dataset.



