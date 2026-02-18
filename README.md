# Bangla-text-classification_Project
Project Overview:

This project presents a supervised machine learning approach for classifying Bangla sentences into three structural categories: Simple (Sorol Bakko), Complex (Jotil Bakko), and Compound (Jougik Bakko). Given the morphological richness and structural complexity of the Bangla language, automatic sentence structure identification remains a challenging task in Bangla Natural Language Processing (BNLP).
A dataset of 2,727 Bangla sentences was collected from blogs, social media, and academic textbooks. After preprocessing and cleaning, 2,703 labeled samples were used for training and evaluation. The text data was vectorized using n-gram features (unigram, bigram, trigram) through CountVectorizer.
Six supervised machine learning algorithms were implemented and compared: Logistic Regression, Decision Tree, Random Forest, KNN, SVM, and SGD. Among them, the Decision Tree classifier achieved the highest accuracy of 93.72%.
This work contributes to Bangla NLP by providing a structured classification framework for sentence-type identification using classical machine learning techniques.


Objectives:

1. To develop a supervised machine learning model capable of automatically classifying Bangla sentences as simple, complex, or compound
2. To construct and preprocess a clean, labeled dataset suitable for multi-class classification
3. To compare the performance of multiple machine learning algorithms using accuracy, precision, recall, and F1-score
4. To analyze model behavior through confusion matrix evaluation
5.To contribute toward structured sentence analysis in low-resource language settings


Dataset

Language: Bangla
Task: Text classification / Sentiment analysis
Size: 2,727
Train/Test split: (e.g., 80/20)

Preprocessing steps included:
Tokenization
Stop-word removal
Text normalization
TF-IDF vectorization
Padding and sequence encoding (for deep learning models)


Models Implemented:

1. Classical ML Models:- Logistic Regression, Support Vector Machine (SVM), Random Forest, Decision Tree, KNN, SGD
3. Libraries used: Python, scikit-learn, TensorFlow / Keras, NumPy, Pandas

Evaluation Metrics:- Accuracy, Precision, Recall, F1-score

Results Summary:-

Model                   	Accuracy
Logistic Regression      	 84.84%
Random Forest              91.68%
Decision Tree              93.72%
SVM                        85.95%
KNN                        73.94%
SGD                        87.06%


Error Analysis:

Despite strong overall performance, several consistent error patterns were observed:- 
1. Misclassification of sarcastic or mixed-sentiment sentences
2. Reduced accuracy on very short informal texts
3. Difficulty handling rare or dialect-specific words
These errors likely result from limited contextual representation and insufficient exposure to low-frequency vocabulary. 


Future Improvements:- 
1. Use pretrained transformer models (e.g., mBERT, XLM-R)
2. Perform hyperparameter optimization
3. Increase dataset size
4. Apply data augmentation techniques
