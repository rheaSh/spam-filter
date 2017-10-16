# spam-filter
Uses tokenization to achieve >90% accurate spam filtering on enron dataset over a range of sklearn classifiers.

1. Showcases the performance of different NaiveBayes classifiers on the iris dataset.
2. Finds all files containing the spam files and ham files. (Need to be modified according to the user's file system.)
3. Extracts all words in all files, removes stopwords and tokenizes using nltk's tokenizer and stopwords.
4. Counts all words to create a counter of the number of times each word occurs. 3000 of the most commonly occuring words will be used as features.
5. Feature matrices that show whether one of the 3000 words(features) occurs in a mail or not are made. Dataset is split into training(3/4th) and test(1/4th) sets.
6. Classifiers from sklearn are trained on training set, tested on test set and a confusion matrix is made. Accuracy is >90% for each.
