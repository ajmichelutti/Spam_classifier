# Spam_classifier
This project provides a detailed walkthrough on building a spam classifier with Scikit-Learn in Python.

Each row of the data corresponds to a text message which has either been labled 'spam' or 'ham'. 
In order to make the text message strings more useful as features for determining this label. 
I make use of Scikit-Learn's count vectorizer which returns from each string, a vector of numbers which 
represent unique words in the entire feature's vocabulary.
