# Playing around with the Seattle Pet Licenses data.
[Link to the data source](https://data.seattle.gov/Community/Seattle-Pet-Licenses/jguv-t9rb)

I wanted to play around a little more with generative neural networks, and I thought of using the Seattle Pet License data to do this.

[Here's a blog post](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) that goes into this kind of neural net and its application in detail.

The [tutorial I followed] (https://github.com/spro/practical-pytorch/blob/master/char-rnn-generation/char-rnn-generation.ipynb).

I developed 3 models, to generate dog names, cat names, and dog breeds.
The training data used are Seattle area names and breeds only, so we'll be generating names and breeds uniquely "Seattle," at least according to the neural net.

## Dog Names
A few interesting dog names:
  - Zora
  - Toomy
  - Augh
  - Pepsey
  - Zebby
  - Ornagicor
  - Lola Louise
  - Chickon
  - Kollie

## Cat names
A few interesting cat names:
  - Ire
  - Little Cettla
  - Silven
  - GLex
  - Ziva
  - Hominus
  - Starora
  - Dalsie Samine

## Dog breeds
A few interesting dog breeds:
  - Norwegian Buhund
  - Gillman Retriever
  - Beerian Bullnese
  - Rotterhound
  - Barbet
  - Perium Dog
  - Basco Hound
  - Beaglo
  - Saint Hound
