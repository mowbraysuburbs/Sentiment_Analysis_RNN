# Sentiment Analysis

This was one of the Capstone projects that was required by the HyperionDev Data Science Bootcamp. For this task, a small portion of the Multi-Domain Sentiment Dataset was used for building a recurrent neural network model to predict the sentiment of user reviews. This dataset contains product reviews from Amazon. 

The full dataset containsreviews for products under the categories: kitchen, books, DVDs, and electronics, but we will only be looking at reviews for the book category. We have two files, positive.txt and negative.txt, containing the reviews. Each review is associated with a number of fields. The only field we are interested in is the “title” field, which contains the title of the review. We are going to use this title to predict the sentiment of the review. We could have used the review text itself, however, as this is a lot longer than the title, this is a much harder task

