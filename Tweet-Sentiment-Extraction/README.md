# Extracting Support for Tweet Sentiment Labels

The goal of this competition is to construct a model that takes the labeled sentiment for a given tweet and figure out which word of phrase best supports it. Details on the competition can be found [here](https://www.kaggle.com/c/tweet-sentiment-extraction/overview).

For my final submission, I created an ensemble of two RoBERTa (bi-directional transformer) models. **The code for my submission can be found on Kaggle** [**here.**](https://www.kaggle.com/panthonies/roberta-ensemble-top-6)

Files in this folder:
- *analysis-tweet-sentiment.Rmd:* source code for data exploration and modeling (written in R markdown)
- *train.csv:* training data
- *test.csv:* test data
- *sample-submission.csv:* a sample submission file

My submission scores in the top 6% of results out of 2,227 teams. [**View the final HTML rendering of my analysis here**](https://anthonypan.com/kaggle/tweet-sentiment-extraction).