# Recommender-Systems

This is a Recommender System.

Given some CSVs with a List of Books , Users and User Ratings on Books, it runs some preprocess based on each book's title 
turning it to Keywords.Then for 5 random Users using the generated Keywords and some Similarity calculations(Publication Year,
Author,Jaccard Similarity,Dice Coefficient), it recommends up to 10 books to each user based on 2 alternative similarities and 
exports them to CSV files.

It also calculates two different kinds of Overlap
The first is based on the two kinds of similarity and the second is based on a "Golden Standard" lists which are a merge of the 
two similarity lists and sorted by the number of times a book appears in those lists.
