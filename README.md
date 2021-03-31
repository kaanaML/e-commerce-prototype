# e-commerce-prototype
This prototype gives us an idea for possible depression/psychological disorder detection system.
# How does it work?
The program cleans the given review from the numbers,special characters and end of the line breaks. Then we extract 2000 features from the review using the TFIDF vectorizer. After that, we add 9 additional features. How many words, special characters and stopwords are counted before the sentiment analysis applied to the inspection and cleaning takes place. Using the deep neural network with dense layers, we can predict whether the overview will be classified as good or bad.
# Interpretation of the results:
predictions are in the form of sigmoid function output which can be between 0 and 1
where the numbers closer to one means that the prediction is "good" and if the numbers are closer to zero means it's highly probable that the prediction is "bad",note that the predictions "bad" and "good" doesn't mean that the model is performing bad or good but they are the classifications of the model.

# Possible improvements
optimizing the hyperparameters of the neural network and create our own dictionary which is related to better classify the good and bad reviews.

# Methodology to implement prototype on depression/psychological disorder detection system

# Possible constraints

# How to overcome with it
