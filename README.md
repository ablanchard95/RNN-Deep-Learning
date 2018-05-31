# RNN-Deep-Learning
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
