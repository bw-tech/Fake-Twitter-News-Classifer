# Twitter-Fake-News-Classifer

## Team

Anirudh Shah - as3947
Bailey Wei - bw489
Howey Qiu - hhq3
Frans Fourie - fjf46
Tom Shanahan - tks46

Thank you to the entire team for the great work.

## Abstract

We address the problem of ‘fake news’ on Twitter by training a model that can identify ‘troll tweets’. The model is trained using a combination of known ‘troll’ tweets and control tweets surrounding political events from 2015 to 2018. The model presented combines Google’s BERT semantic embedding tool that computes the sentiment of tweets from word embeddings, and binary classification models, which use the sentiment score from BERT with other features to indicate a ‘troll’ or ‘not troll’ tweet. The model was able to obtain a 99.81% classification accuracy on our test set, and BERT itself reached 95.4% accuracy, which indicates that there is a clear semantic difference between non ‘troll’ and ‘troll’ tweets. With these results we determined that it is possible to retrospectively identify ‘troll’ tweets that have been made using sentiment analysis, although we also note some potential pitfalls of applying this model on live tweets. 

## Final Results

Our model reached  99.81% classification accuracy on our test set. 

## Future Steps

Initially our results worried us greatly. We figured that this was due to severe overfitting and stepping over key data science principles. However, our team ensured quality of work was consistent. Upon further research we found our results were in line other with comparable techniques. 