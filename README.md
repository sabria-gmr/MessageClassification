# MessageClassification
Spam Message Classification Using Multinomial Naive Bayes
This repository contains a dataset and implementation for classifying SMS messages as either "spam" or "ham" (non-spam) using the Multinomial Naive Bayes (MultinomialNB) model.

# Dataset
The dataset consists of labeled SMS messages, where each message is either categorized as spam or ham. The data is preprocessed and ready for training the model. It includes features such as word frequencies, which are useful for the Naive Bayes classifier.

# Model
The classification model used in this project is the Multinomial Naive Bayes (MultinomialNB) algorithm, which is effective for discrete count data, such as word counts in text classification tasks.

# Key Steps:
Data Preprocessing: The dataset is cleaned and tokenized, with text converted into a numerical format using techniques like TF-IDF or CountVectorizer.
Model Training: The MultinomialNB classifier is trained on the preprocessed text data.
Model Evaluation: The model's performance is evaluated using common metrics such as accuracy, precision, recall, and F1-score.
How to Use:
Clone the repository to your local machine.
Install necessary dependencies from requirements.txt.
Run the script spam_classifier.py to train the model on the dataset and classify new SMS messages.
# Requirements:
Python 3.x
Scikit-learn
Pandas
Numpy
