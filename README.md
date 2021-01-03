# Pointers-Assignment

The Solution to the assignment can be found in Assignment.ipynb file

Started off with reading the PDF file and extracting the text from it.
Composing a csv file from the text using a delimiter. 

#1. Senitment Analysis 
* First Carried out Sentiment Analysis using VADER Settiment module that predicts the text sentiment as positive, negative or neutral
* It also Calculates a compund score.

#2. Entity and Keyword Extraction using Spacy

#3. Emotion Analysis
* Emotion analysis using a labelled emotion classier dataset which classifies text as joy, anger, sadness and fear.
* Cleaned text using stemming, lemmatizing and stopwords removal.
* Used RegEx to remove unwanted characters and punctuations.
* Designed NLP pipeline using CountVectorizer, Tfidf Vectorizer and MultiniomialNB Classifier.
* Achieved accuracy of over 80%.
* Used the john review dataframe and testing set and predicted the emotion corresponding to the text.

#4. Topic Modelling
* Used NMF to predict the topics within the document
* fitting the document term matrix to NMF algorithm.
* Predicting the top 15 words in each topic. (number of topics = components given while training)
* the following are most accurate 4 topics based on keyword extraction:
Skill
Competency
Need Improvement
Good Teamplayer

* Finally added another column to the original df which contains the corresponding topics to each text.
