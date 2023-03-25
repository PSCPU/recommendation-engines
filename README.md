# apriori_recommendation-engine: apriori_exercise.ipynb
This exercise takes a movie dataframe, uses the apriori algorithm, and computes the support, confidence and lift parmeters for pairs of movies. 
The movie pairs, along with their association parameters are then stored in a pandas dataframe. 
# Content based recommendation engine: content_based_filtering_exercise.ipynb
This engine takes a dataframe containing item ids and their descriptions, computes the item to item cosine similarity, creates tuples containing item indices and their consine similarities, matches the index of each item in the id column of the df dataframe with the index of the cosine similarity matrix, and then stores the indices of the sorted items in the results dictionary according to the ids (reason why we use i+1). Once we have the results dictionary having ids of items sorted according to their cosime similarity scores for each item, we use a function that takes the id of the item for which the similarity score has to be calculated, and the number of similar items that need to be printed, and then return the ids of the similar items.
# Memory-based collaborative filtering recommendation engine: CF_memory_based_exercise.ipynb
This is an application of K-nearest neighbor method to find similarities between items using euclidean distance as a parameter. We take the name of a book, find its ISBN, use item based collaborative filtering method using KNN to recommend the next five similar movies based on their ratings.
# Memory-based collaborative filtering recommendation engine: CF_model_based_exercise.ipynb
This is an application of SVD method to build a collaborative recommendation engine. After initially training the model, the hyperparamters are then tuned using the grid search method. 
