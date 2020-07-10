# YelpRatings

Project that predicts the rating of a given Yelp review for a restaurant. The purpose of the report is to understand the performance of various machine learning models and is not focused on building the best performing model.

# Note 

Please read the report for more information and for the results of the project. The Jupyter Notebook provides the graphs, results and code for the report.

# Data

The datasets provided were:
- Raw restaurant reviews
- Meta dataset 
- Sparse Matrix (Word Counts for each review)
- Doc2Vec representations of the reviews

Doc2Vec representations were not investigated.

# Improvements

One of the big areas for improvement is the model performance. The best performing model had an accuracy of 81.7%, which can be greatly improved on. Such approaches would be using tailored data pre-processing methods instead of directly using the provided text representations. Also, advanced methods such as bagging (random forests), boosting, ensemble learners or even neural networks were not investigated and could improve the model performance.

Another aspect for improvement is to research different approaches for classification on an unbalanced dataset. Evaluation metrics such as precision, recall and confusion matrices were not implemented. Hence, the model could have high bias towards the most popular label, which would result in lower performance on the other class labels. Using these metrics would provide more depth into the error analysis and would improve the "credibility" of the models.

