# amazon-fine-food-reviews-senti-analysis
given a new text review, the algorithm predicts whether the review is positive or not
the dataset was loaded and text preprocessing was performed by removing the html text, stop words and all the letters were converted into 
lower case, 
4-types of word embeddings were used to featurize the text and the knn algo was implemented for each of those featurizations
the optimal k was chosen through 10-fold cross validation, i.e.the k-value for which the misclassification error was the lowest ,
an accuracy of over 90% was achieved for each of the featurizations, don't worry the accuracy was achieved on the test data, don't worry about 
over fitting.
the improved model has been added to the repository.
