# Amazon Alexa Reviews Analysis
### Sentiment Analysis/NLP performed to classify reviews given to Alexa as positive or negative.

# Business Case
Using Natural Language Processing (NLP) - Sentiment analysis techniques to predict customer sentiment from Amazon Echo customer reviews.

Sentiment analysis will help companies to automatically predict whether their customers are happy or not.

The process could be done automatically without having humans manually review thousands of customer reviews.

To identify the sentiments quickly to provide feedback to sales and production team. 

# Introduction to the Dataset
This dataset consists of a 3150 verified Amazon customer reviews .


## Explanation of variables.

Ratings: This is the ratings given by customers for various Amazon Alexa models. Ratings range from 1 to 5.
Date: The date on which the customers wrote the review.

Variation: This reflects the different types of Amazon Alexa models

Verified reviews: This is the review given by customers who purchased the product and the purchase was verified by Amazon.

Feedback: Has two values 1 and 0

1 indicates positive feedback and 0 indicates negative feedback

# Sentiment Analysis Work Flow
Loading Data

Exploratory data analysis (EDA)

Data Preprocessing using RegEx, tokenize it, and eliminate stop words

Implementing lemmatization.

Feature Engineering

Model building

Evaluate model performance

# Conclusion:

**Random Forest Classifier** is slightly better in terms of accuracy and recall on the test set. This model can be preferred if the objective is to correctly identify as many positive cases as possible (high recall).

**XGBoost Classifier** shows slightly better precision on the test set. This model might be preferred if the goal is to minimize false positives (high precision).

However, false positives are particularly costly in our application, so we can lean towards the XGBoost Classifier due to its higher precision.
