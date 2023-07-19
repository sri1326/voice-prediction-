# voice-prediction-
The goal of this project is to build a machine learning model that can accurately predict the gender of a person based on their voice recordings. Voice-based gender recognition has various applications, such as personalization in voice assistants, speech-based authentication systems, and market research. We will use a Support Vector Machine (SVM) classifier, a popular and powerful supervised learning algorithm, to achieve this task.

Dataset available on Kaggle --> https://www.kaggle.com/primaryobjects/voicegender

Contents of repo:

genderByVoice.py is the file which implements the classifier.
voice.csv is the dataset.
Only the following 6 features out of 20 were considered:

meanfreq
sd
centroid
meanfun
IQR
median
The dataset contained 3168 records, 2376 of which were used as training set and the rest as test set.
