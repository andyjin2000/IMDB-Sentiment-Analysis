# IMDB-Sentiment-Analysis

In this project, we investigate the IMDB dataset, which is a repository of movie reviews and their sentiments. 
A positive sentiment means the user left a high (4 or 5) rating, whereas a negative sentiment means the user left a low 
(1 or 2) rating. The goal is to build a binary classifier such that for a new movie review, the algorithm will correctly 
classify it as positive or negative. The sentiment_analysis_imdb.ipynb file presents an Multi-Layer Perceptron (MLP) 
algorithm that attains over 90% on this task.

Note: the raw datasets are not provided on this GitHub repo since their file sizes are too big.

The second goal of the project is to build a web server for sentiment classification based on user input. To run this 
(powered by Flask), run "python runserver.py" and then type a sentence on the form. This algorithm uses Naive Bayes
to determine the sentiment and also highlight key words that contributed to that sentiment scoring.
