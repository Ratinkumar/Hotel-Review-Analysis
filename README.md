In this Project Hotel review analysis,covers data preprocessing, feature extraction using Doc2Vec and TF-IDF, training a Random Forest Classifier, and evaluating the model using ROC and Precision-Recall curves. It also includes visualizations such as word cloud for the review data and sentiment distribution for positive and negative reviews.

Tool Required : Jypter Notebook / Google Colab.

Language Used : Python 3.11.4

Libraries : NLTK ,Gensim ,Scikit-learn ,WordCloud , Seaborn. 

**Methodology :-**

The sentiment analysis code consists of the following major components:

1.Data Preprocessing:

Read the hotel reviews dataset using pandas.
Append the positive and negative text reviews into a single "review" column.
Create a binary label "is_bad_review" (1 for negative reviews and 0 for positive reviews).
Apply text preprocessing steps, such as tokenization, stop word removal, and lemmatization using nltk.

2.Feature Extraction:

Extract features from the preprocessed text using Doc2Vec vectors and TF-IDF (Term Frequency-Inverse Document Frequency).

3.Random Forest Classifier:

Train a Random Forest Classifier using the extracted features and the target label.
Display feature importance scores to understand the most influential features in predicting sentiment.

4.Model Evaluation:

Evaluate the classifier using the ROC curve to assess its performance in distinguishing between positive and negative reviews.
Plot the Precision-Recall curve and calculate the average precision score to assess performance, especially in imbalanced datasets.

**Results and Visualization**

The code provides visualizations for the following evaluation metrics:

ROC curve: To assess the classifier's ability to discriminate between positive and negative reviews.
Precision-Recall curve: To evaluate the classifier's precision-recall trade-off, especially in imbalanced datasets.

**Usage**

You can customize the code to work with other datasets or modify the classifier and feature extraction techniques based on specific project requirements. The provided code serves as a foundation for sentiment analysis projects and can be extended to handle various text classification tasks.
