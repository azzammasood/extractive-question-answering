# Project: Extractive Question Answering using Transformers
Coded in Google Colab, this project features Question Answering (QA) which is a task of natural language processing that aims to automatically answer questions. The goal of extractive QA is to identify the portion of the text that contains the answer to a question. For example, when tasked with answering the question 'When will Jane go to Africa?' given the text data 'Jane visits Africa in September', the question answering model will highlight 'September'.

Phases:
  1. Building a Transformer Network.
  2. Using a pre-trained Transformer model DistilBERT for Question Answering.
  
**Here is an intuitive explanation of how extractive question answering works:**
The input context and question are tokenized and converted into numerical embeddings using a pre-trained transformer-based model such as BERT, RoBERTa, or DistilBERT.
The embeddings of the context and question are combined and fed through a neural network, such as a multi-layer perceptron (MLP), to produce a probability distribution over the start and end positions of the text span that contains the answer.
The network predicts the start and end positions of the answer span based on the probability distribution, and the corresponding text span is extracted from the context.
The extracted text span is returned as the answer to the original question.
