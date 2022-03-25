# IMDB review preduction - NLP with LSTM - BATCH pull from files

In my project i predicted the sentiment of the text from IMDB reviews: positive, natural and negative.

The dataset from KAGGLE was huge, so i run it with generator dataset from tensorflow.

I used the GCP to keep snapshots (vectorize layer and the model after fitting), to make my life easier when I return to work on the project.

In the end, I was able to get a 72 percent accuracy prediction, but you can see that most of the wrong predictions were for the "nearest" label.
