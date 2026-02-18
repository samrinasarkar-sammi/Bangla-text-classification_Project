# Bangla-text-classification_Project
Project Overview

This project presents a supervised machine learning approach for classifying Bangla sentences into three structural categories: Simple (Sorol Bakko), Complex (Jotil Bakko), and Compound (Jougik Bakko). Given the morphological richness and structural complexity of the Bangla language, automatic sentence structure identification remains a challenging task in Bangla Natural Language Processing (BNLP).

A dataset of 2,727 Bangla sentences was collected from blogs, social media, and academic textbooks. After preprocessing and cleaning, 2,703 labeled samples were used for training and evaluation. The text data was vectorized using n-gram features (unigram, bigram, trigram) through CountVectorizer.

Six supervised machine learning algorithms were implemented and compared: Logistic Regression, Decision Tree, Random Forest, KNN, SVM, and SGD. Among them, the Decision Tree classifier achieved the highest accuracy of 93.72%.

This work contributes to Bangla NLP by providing a structured classification framework for sentence-type identification using classical machine learning techniques.


The main objectives of this project are:

To develop a supervised machine learning model capable of automatically classifying Bangla sentences as simple, complex, or compound

To construct and preprocess a clean, labeled dataset suitable for multi-class classification

To compare the performance of multiple machine learning algorithms using accuracy, precision, recall, and F1-score

To analyze model behavior through confusion matrix evaluation

To contribute toward structured sentence analysis in low-resource language settings
