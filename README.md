# Webapp-SMS-Spam-Classification
This is a web application that classifies an email or SMS as "Spam" or "Not Spam" using a machine learning model. The app is built with Streamlit, and the model is trained using a text preprocessing pipeline and a machine learning algorithm.

## Features

- **Text Preprocessing** : The input message is preprocessed by converting to lowercase, removing stopwords and punctuation, and stemming the remaining words.
- **Vectorization** : The preprocessed text is transformed using TF-IDF vectorization.
- **Prediction** : The transformed text is then fed into a pre-trained machine learning model to predict whether the message is "Spam" or "Not Spam".

## Installation

### Clone the Repository

    git clone https://github.com/yourusername/spam-classifier.git
    cd spam-classifier

### Install Dependencies
  Make sure you have Python installed on your system. 

### Usage
  Run the Streamlit app by executing the following command in your terminal:
        
      streamlit run app.py

This will start a local server. Open your web browser and go to http://localhost:8501 to access the app.

### Input
    Enter the text of an email or SMS in the provided text area.
### Output
    The app will classify the input text as either "Spam" or "Not Spam".

### Model Training
The machine learning model was trained using a dataset of labeled email/SMS messages. The following steps were involved in training:

1. **Text Preprocessing** : Lowercasing, tokenization, removal of stopwords and punctuation, and stemming.
2. **Vectorization** : Using TF-IDF vectorizer.
3. **Model** : A machine learning algorithm (e.g., Naive Bayes, SVM) trained on the preprocessed and vectorized data.

### Dependencies
  - Python 3.7+
  - Streamlit
  - NLTK
  - Scikit-learn
  - Pickle

### Acknowledgements
  - The Streamlit framework for building the web app.
  - The NLTK library for text processing.
  - Scikit-learn for model building and vectorization.
