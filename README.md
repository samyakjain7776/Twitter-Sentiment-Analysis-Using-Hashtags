# Twitter Sentiment Analysis Using Hashtags
The project aims to predict the sentiment of any hashtag given as an input to the program. The program first scrapes the relevant tweets related to the hashtag. The no. of tweets to be extracted are customizable, hence making the analysis more efficient and diverse. The project uses Convolutional Neural Network to predict the sentiment of any sentence. The main components that the project requires are -  Twitter Tweepy API CNN model for predictions Sentiment Analysis (Positive, Negative and Neutral) Graphical representation of the results


## Twitter API credentials

Set `TWITTER_CONSUMER_KEY`, `TWITTER_CONSUMER_SECRET`, `TWITTER_ACCESS_TOKEN`,
and `TWITTER_ACCESS_TOKEN_SECRET` in the environment before launching Jupyter.
The notebooks read these variables rather than storing credentials in source.
`.env.example` lists the variable names; dotenv files are not loaded automatically.
Keep credentials and notebook checkpoints out of Git.
