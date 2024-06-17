# About 
This repository contains a list of my NLP projects.

# Content
- [Article Classification](ArticleClassification/text-classification.ipynb)
In this notebook, we process unstructured text from multiple text files. We load the raw text and create two data frames: one for labeled data and a second one for unlabeled data. We preprocess the data by removing stop words, punctuation, and tokenizing it. Then, we convert the text into its numerical representation using the TF-IDF method.
Next, we use a Multinomial Naive Bayes classifier to train the labeled data. This trained classifier is then used to predict the labels of the unlabeled data.
For insights purposes, we evaluate the performance of the Naive Bayes classifier by comparing its predictions on the training set to the actual labels. The result shows an accuracy of 81%. However, it is a better practice to evaluate a model on a separate test set, which can provide a more realistic estimate of how the model will perform on unseen data.

- [Information Extraction using SpaCy](InformationExtraction/)
The notebooks cover basic operations such as  part of speech tagging, dependency parsing, named entity recognition, noun chunk, and slot filling.