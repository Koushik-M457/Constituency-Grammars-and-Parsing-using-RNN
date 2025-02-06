# Constituency-Grammars-and-Parsing-using-RNN
Constituency parsing is the process of analyzing the syntactic structure of a sentence, breaking it down into constituent parts such as noun phrases (NP), verb phrases (VP), and others. It is a crucial task in Natural Language Processing (NLP) for understanding sentence structure and syntax.  In this project, we build a Constituency Parsing.



# Constituency Parser Using Recursive Neural Networks (RNN)

This project implements a **Constituency Parser** using **Recursive Neural Networks (RNNs)**. The parser is designed to analyze sentences, break them down into constituent structures, and identify grammatical components such as noun phrases (NP), verb phrases (VP), etc. This project leverages the **Penn Treebank** dataset for training and evaluation, and the model is deployed as a web application using **Streamlit**.

## Objective

The main goal of this project is to:
- Implement a **Constituency Parser** using an RNN-based model.
- Evaluate the parser’s performance in terms of **precision**, **recall**, and **F1 score** using a treebank dataset.
- Deploy the parser as a **web application** using Streamlit, allowing users to input sentences and see their syntactic structure.

## Features
- **RNN-Based Parsing**: The parser uses an RNN architecture to analyze sentence structures.
- **Treebank Dataset**: Utilizes the Penn Treebank corpus for training and testing the parser.
- **Web Application**: A user-friendly Streamlit interface for interacting with the parser.
- **Evaluation Metrics**: Evaluation of the model using standard metrics: **Precision**, **Recall**, and **F1 score**.

Model Architecture
The parser is based on a Recursive Neural Network (RNN), which is capable of handling hierarchical data structures like sentences in natural language. The model consists of the following components:

Embedding Layer: Converts words into dense vectors.
RNN Layer: Processes the input sequences to learn sentence structures.
Output Layer: Produces the predictions for each word in the sentence.
The model is trained using labeled data from the Penn Treebank dataset, which includes syntactic trees for sentences. The model outputs a tree structure for a given sentence.

Evaluation
The parser's performance is evaluated using the following metrics:

Precision: The proportion of correctly predicted constituents over the total predicted constituents.
Recall: The proportion of correctly predicted constituents over the total actual constituents.
F1 Score: The harmonic mean of Precision and Recall.
These metrics are calculated using a test set of sentences from the Penn Treebank corpus.
