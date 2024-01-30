Introduction
In this small project I have analyzed a small dataset of Restaurant Reviews, and by using machine learning algorithms to build a sentiment classifier.

Data Description
The dataset contains two columns, one contains the user reviews and one contains whether user liked it or not which is represented using 0s and 1s. The dataset only have 1000 entries and the dataset is there inside '/Data'.

Libraries Used
Several Python libraried are used: Pandas, nltk, spacy, scikit-learn etc.

Project Description
First the dataset is analysed and several features are extracted like number of characters, number of words in the reviews also the average word length in each review. Then from the text data bag of words matrix as well as term frequency inverse document frequency(TF-IDF) is created and combined with the original datset and the data is stored as an excel file inside '/Data' folder. Finally the preprocessed data is used to build the machine learning models for sentiment analysis, I have used Multinomial Naive Bayes, Bernoulli Naive Bayes and Random Forest.

Conclusion
For a large dataset more features can be extracted also for TF-IDF bi-gram, tri-gram can be extracted and the model accuracy will be more.
