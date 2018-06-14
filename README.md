# RNN-Deep-Learning
<<<<<<< HEAD
Tweet Generator: brandon_branch

## How to run the program

To run this program you will need to have PyCharm installed. 

In PyCharn open the provided terminal and type: `python`
Then type: `from textgenrnn import textgenrnn`

Once the import statement has completed type:

`textgen = textgenrnn('BarackObama_D_DeGea_twitter_weights.hdf5')`

** Your file inside the textgenrnn statement might be different than mine if you decide to
user different twitter accounts **

Then type:

`textgen.generate_samples()`

Success! You have now generated random tweets

** Note: ** In the `config.yml` file, you will need to enter your own Twitter API keys. This can
be easily acquired by creating your own Twitter account and look for a developer section within
the site.
=======
Tweet Generator

(tweet tweet)

Requirements:
  -tensorflow
  -textgenrnn
  -tweepy
  
 Be sure to include your Twitter credentials in the config.yml file, and also the users you watn to use for the program.
 If you do not have the Twitter credentials i.e. your Consumer or Access key, simply go to apps.twitter.com and create an app.
 After doing so your keys should be available.

>>>>>>> d99ed09b18a850b2c1e4bd1b9891a27be99a92d6
