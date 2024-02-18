# Fake_News_Detection
A Machine Learning model to classify news as 'fake' or 'not fake' using NLP,  various ML algorithms like Multinomial Naive Bayes, Logistic Regression, Decision Tree Classifier and some preprocessing techniques like Stemming, Lemmetization, TF/IDF Vectorization and Count Vectorization achieving a maximum accuracy of 75.44%.
## Accuracy:-
| Text Preprocessing Type              | Multinomial NB | Logistic Regression | Decision Tree |
|--------------------------------------|----------------|---------------------|---------------|
| TFIDF Vectorization                  | 53.42%         | 53.42%              | 70.38%        |
| Count Vectorization                  | 69.11%         | 57.47%              | 75.44%        |
| TFIDF Vectorization + Stemming       | 53.42%         | 53.42%              | 70.13%        |
| Count Vectorization + Stemming       | 70.38%         | 57.72%              | 75.44%        |
| Count Vectorization + Lemmatization  | 70.89%         | 57.72%              | 69.62%        |
| TF/IDF Vectorization + Lemmatization | 53.42%         | 53.42%              | 73.16%        |
## Dataset:-
The dataset used is the WELFake Dataset by Kaggle, McIntire, Reuters and BuzzFeed. You can directly download it from [here](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification).
###### Note:- I used top 500 records in this model since my system's memory limit exceeded after that. You can use more if you would like.
