# Classfier_Model_Youtube_Comments_using_Naive-Bayes-Theory

#### Multnomial Naive Bayes Classifier - the YouTube Dataset

The project task was to develop and apply a Naive Bayes Theory Classifier model to determine good(ham) and harmful(spam) comments in YouTube comment datasets. This project was completed using Python and Jupyter Notebooks. Beginning with data preprocessing and validation and checking for null values using panda's classes. Next, I was able to define the inputs and the target. Creating the train-test split, that evaluates the performance of our Naive Bayes Classifier. Using feature extraction and model selection I was able to tokenize strings and count occurrences of each token in the comments. To perform the classification, I used MultinomialNB and performed evaluation on the test dataset. The model inference contained columns representing True negative as 167, False positives as 23, False negatives as 5 and correctly predicted and identified all spam messages hence True Positives: 196.

Using the classification_report class from sklearn metrics, to measure the quality of predictions from our classification algorithm and model set output. Our model produced a precision of 97% for Ham and 96% for Spam.
Final output is on a Probability Distribution Display that checks the spread of comments detected as ham and spam.
