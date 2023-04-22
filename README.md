# Spam Ham Classifier
This is a web application that uses a trained Naive Bayes model to classify text as either spam or ham. Users can input text and get a prediction of whether it is spam or not spam.

## Installation
1. Clone the repository:
```sh
git clone https://github.com/yourusername/spam-ham-classifier.git
```

2. Change into the project directory:
```sh
cd spam-ham-classifier
```

3. Install the required packages:
```sh
pip install -r requirements.txt
```

## Usage
To run the application, you need to install the required packages listed in the requirements.txt file. Once you have installed the requirements, you can run the application using the following command:


```sh
streamlit run app.py
This will start the application and open it in your default web browser.
```

## Files
The application consists of the following files:

- main.py: This is the main file that contains the Streamlit application code.
- spam_not_spam_nb_trained_model.sav: This is the trained Naive Bayes model that is used for classification.
- count_vectorizer.pkl: This is the CountVectorizer object that is used for text preprocessing.
- requirements.txt: This file contains a list of Python packages required to run the application.

## Credits
This application was created by Manish Khatik using the Streamlit library and the scikit-learn library.