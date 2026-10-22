# NgramTwitterBot

This is a Python Twitter Bot that utilizes an ngram model to produce tweets 
that are subsequently posted by the bot account.

The bot file does all of the work, where the file containing the model
is used to run the model and nothing more.

The model is initilized using 3,200  tweets, acquired
through the use of tweepy. Then, the script "watches" a Twitter
account. Whenever it posts a new tweet, the bot will add the tweet to the model,
produce a new randomly generated tweet, and post the tweet to the bot account's
Twitter profile. 

All tweets produced and posted are 100% computer generated, and are no indication
of any of the thoughts and opinions of anyone involved with the project.

Link to Twitter Account: https://twitter.com/ngrmDonaldTrump
