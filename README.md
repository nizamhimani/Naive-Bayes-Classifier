Preprocess the data.
Divide the dataset into 60 percent training set,20 percent testing set  and 20 percent development set.
Build a vocabulary of all words in training set.
Calculate probability of occurance of each word in training set.Conditional probability based on sentiment is calculated,smoothing is applied to prevent zero probabilities when a word is not present in particular class.
Classify function uses naive bayes algorithm to classify review as "fresh" or "rotten".
Calculate accuracy using model predictions on development set.
Different values of smoothing parameters are experimented to evaluate their impact on model performance.
Evaluate model on test set.
