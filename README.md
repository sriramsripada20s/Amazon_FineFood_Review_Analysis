# Amazon FineFood Review Analysis

**This was a part of my personal project where I worked on Building A NLP Model to Classify the reviews from Amazon**

**Objective:** To classify reviews as positive (Rating of 4 or 5) or negative (rating of 1 or 2) based on the text/reviews provided by various users on Amazon using Machine Learning and Natual Language Processing Techniques

**Amazon Fine Food Reviews Analysis Data Source:** https://www.kaggle.com/snap/amazon-fine-food-reviews

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

**Number of reviews:** 568,454 Number of users: 256,059 Number of products: 74,258 Timespan: Oct 1999 - Oct 2012 Number of Attributes/Columns in data: 10

**Attribute Information:**

**Id ProductId** - unique identifier for the product 
**UserId** - unqiue identifier for the user ProfileName 
**HelpfulnessNumerator** - number of users who found the review helpful (no of people who said this review is helpful) 
**HelpfulnessDenominator** - number of users who indicated whether they found the review helpful or not ((no of people who said this review is helpful + (no of people who said no this review is not helpful)). So 
**HelpfulnessDenominator** should be greater than HelpfulnessNumerator> Score - rating between 1 and 5 Time - timestamp for the review Summary - brief summary of the review Text - text of the review 


**How to determine if a review is positive or negative?**

We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
