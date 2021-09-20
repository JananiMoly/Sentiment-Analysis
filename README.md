User Content Generation is redefining the business game altogether. A visible effect of user content generation is how it shaped the customer's mentality to buy products based on reviews and ratings. Businesses now strive to get good customer ratings and reviews. But going over huge corpus of text to decipher intent and sentiment of a customer is challenging and cumbersome. 

I have obtained the dataset of customer reviews and ratings for the Tripadvisor Company from Kaggle. Using packages from NLTK library I preprocessed the data and used Decision Tree and Random Forest classifier to classify the sentiments into either of 3 buckets - positive, negative or neutral. 

Preprocessing text corpus entailed tokenizing them and converting the tokens to input vectors. The input vectors are then fit into a supervised classification machine learning algorithm - Decision Tree and Random Forest classifier.

The model had a better accuracy percentage when RandomForest classifier was used, attributing to the computational intelligence and complexity of random forest classifiers over that of decision trees.

*Functions in NLTK library:* tokenize.TweetTokenize, nltk.stopwords, feature_extraction.text.TFIDF Vectorizer

*Functions in Sklearn library:* preprocessing.model_selection, metrics.accuracy_score, mertics.classification_report

*ML Algorithm:* sklearn.tree.DecisionTreeClassifier, sklearn.ensemble.RandomForestClassifier
