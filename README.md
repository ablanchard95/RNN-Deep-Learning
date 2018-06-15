# RNN-Deep-Learning

Tweet Generator: eric_branch

## How to run the program

To run this program you will need to have PyCharm installed. 

In PyCharn open the provided terminal and type: `python`
Then type: `from textgenrnn import textgenrnn`

Once the import statement has completed type:

`textgen = textgenrnn('RealDonaldTrump_twitter_weights.hdf5')`

** Your file inside the textgenrnn statement might be different than mine if you decide to
user different twitter accounts **

Then type:

`textgen.generate_samples(samples per temperature, list of temperatures)`

Success! You have now generated random tweets

** Note: ** In the `config.yml` file, you will need to enter your own Twitter API keys. This can
be easily acquired by creating your own Twitter account and look for a developer section within
the site.
