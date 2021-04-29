# Amazon-Reviews-Classifier
Sentiment Classifier for Amazon Reviews on Books (Positive or Negative)

Created a sentiment classifier for book reviews on Amazon using the following tools and methods:
- Pandas, numpy, and json to load, manipulate, and prepare the data for training
- Bag of words vectorization was used for training using the TFIFD vectorizer provided in the Sci-kit learn library
- Used SVC, Decision Tree, Gaussian Naive Bayes, and Logistic Regression as base models before tuning.
- GridSearchCV for hyperparameter tuning for the SVM model as it performed the best at base  
- Pickle for exporting the model
