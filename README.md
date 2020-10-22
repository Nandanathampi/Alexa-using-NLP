# Alexa-using-NLP


Amazon Alexa Review analysis is a project that analyses reviews by users of Amazon’s Alexa products. Also by using Natural Language Processing on the product reviews and some additional features, a machine learning model is tried to build which is able to predict if the feedback is positive (1) or negative (0). The data set is from kaggle and the source is amazon’s website. By using this data we can analyse Amazon’s Alexa product, discover insights into consumer reviews and assist with machine learning models. Also we can train our machine models for sentiment analysis and analyze customer reviews like how many positive reviews?, how many negative reviews? Etc. 
This dataset consists of a nearly 3150 Amazon customer reviews (input text), star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots, Alexa Firesticks etc. for learning how to train Machine for sentiment analysis.
Number of observations : 3150
Number of attributes : 5 which includes,
    • Rating – The star ratings given by the customers. It falls between 1 and 5
    • Date – The date in which the review done
    • Variation – Different variations of amazon alexa. Here 16 variants of alexa is taken which includes Black Dot, Charcoal Fabric, Configuration: Fire TV Stick, Black  Plus, Black Show, Black, Black Spot, White Dot, Heather Gray Fabric, White Spot,              White, Sandstone Fabric, White Show, White  Plus, Oak Finish, Walnut Finish. 
    • Verified reviews – Reviews given by the customers which is a text.
    • Feedback – it says positive or negative review. It has 2 values 0 for negative and 1 for positive. The ratings 1 and 2 are considered as negative feedback and ratings 3, 4, 5 as positive feedback. According to the same the feedback value is stored.
Language and editor used : Python 3,  Jupiter notebook   
Algorithms used : Random Forest classifier, Naïve Bayes classifier, logistic regression, Support Vector Machine(SVM), K Neighbors classifier (KNN), Gradient boosting classifier.
Output : Different Analysis on the review and model is tried to build which classifies the review as positive or negative reviews from the text. That is, output is 0 or 1, 0 for negative feedback and 1 for positive feedback.
         
