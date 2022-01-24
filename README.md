# News Article Classification with Topic Summarizer
Natural Language Processing (CSE4022) J Component
## 
● The project aims to build a system that can accurately classify previously unseen news articles into the appropriate category. The news articles are categorized using different models into the predefined categories (business, sports, entertainment, politics, tech).\
● The pre-processing steps, document indexing, feature selection, and news headlines classification are performed on the BBC_news dataset. Stop word filtering using a frequency-based stop words removal approach is also done.\
● To find the best model for the training data, we used random forest, logistic regression, K Neighbors Classifier, Decision tree, and Gaussian Naive Bayes classification algorithms. On applying hyperparameter tuning for all models, we inferred that logistic regression is the best model with the highest accuracy.\
● The summarization of topics is implemented using the extractive summarization approach. The summary of these articles is then added to a separate column in the dataset and displayed. Apart from this, we have given random news articles as text and summarized them using the TextRank algorithm with the help of spacy and gensim packages.
