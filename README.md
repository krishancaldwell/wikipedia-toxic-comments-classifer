# Wikipedia Toxic Comment profiler

I wanted to get started with NLP, so this is a very basic project to do that.

I started by using the data publicly posted on last year's Kaggle Competition - https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge.

The competition itself required people to categorise comments on Wikipedia into various buckets of toxicity.

I took a simplified approach and just labelled them as either toxic or non-toxic. Then, using a Jupyter Notebook and the FastAI libraries I had a go at categorising the data.

The Jupyter Notebook runs through the steps to train a basic model to then recognise these.

It achieves approximately ~68% accuracy in categorisation, struggling particularly with sarcastic comments.

One of the final lines in the scripts allows you to test your own written comments and see how strongly the classifier rates them.


## Required Software
1. Conda
2. The FastAI library - instructions can be found here https://docs.fast.ai/install.html

## Future
In the future I'll probably look deeper into the AI libraries rather than rely on the abstraction that the FastAI libraries provide.
