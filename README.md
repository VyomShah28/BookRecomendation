# Book Recomendation Engine using K Nearest Neighbour Classifier 
In this challenge, i have created a book recommendation algorithm using K-Nearest Neighbors.

I have used the Book-Crossings dataset. This dataset contains 1.1 million ratings (scale of 1-10) of 270,000 books by 90,000 users.

After importing and cleaning the data, use NearestNeighbors from sklearn.neighbors to develop a model that shows books that are similar to a given book. The Nearest Neighbors algorithm also measures distance to determine the “closeness” of instances.

The data returned from get_recommends() is a list. The first element in the list is the book title passed in to the function. The second element in the list is a list of five more lists. Each of the five lists contains a recommended book and the distance from the recommended book to the book passed in to the function.
