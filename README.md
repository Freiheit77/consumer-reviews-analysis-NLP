# consumer-reviews-analysis-NLP
This project applied texting mining, natural language processing, logistic regression, PCA, and other machine learning techniques to analyze 500k product reviews on amazon. This analysis could also be further developed to build the recommendation system with user similarity and product similarity.

This analysis involves the following steps: 

First, the text preprocessing is conducted, which includes lower case transformation, stop words removal, negation handling, and words stemming. 

Second, the word frequency table is created and the top 500 words are selected as the bag-of-words. 

Third, the Euclidean distance and PCA are used to measure reviewer similarities. 

Fourth, the lasso logistic regression is used to predict overall ratings. Some sentiment scores are added to the model to measure reviewers' emotions when writing texts.

Fifth, the product similarty is calculated based on ratings, helpful votes, and texts. 
