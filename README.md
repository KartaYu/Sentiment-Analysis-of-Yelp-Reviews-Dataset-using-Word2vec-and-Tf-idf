# Sentiment Analysis of Yelp Reviews Dataset using Word2vec and Tf-idf
### Data Sourece
- Link : <https://www.kaggle.com/omkarsabnis/yelp-reviews-dataset>
### Data preprocessing
1. Map the value of stars between 0 and 1
2. Split text and remove stopwords
    * Remove stopwords with CountVectorizer and split text,
3. TfidfTransform
    * Turn words to frequency data with TfidfTransformer.
    ![image]
4. Word2vec
    * Tuen words to vector with Word2vec.
    ![image]

### Model 
- RandomForestClasssifier
### Evaluation
- Using k fold cross validation
- Accuracy of Word2Vec : 0.694
- Accuracy of -Tf-Idf : 0.7805
