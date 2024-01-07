# durham-place-names
In this repository we learn to generate new place names in County Durham using various machine learning algorithms, from simple bigram models to neural networks with transformers. County Durham has many colourful place names such as Pity Me and Killhope, and we generate similar place names using many of the ideas from the [lecture series(https://www.youtube.com/watch?v=PaCmpygFfXo) by Andrej Karpathy.
## Preparing the data
We create a corpus of place names based on a dataset from the Office of National Statistics to train our models on. The corpus is saved as the file `place_names_durham.txt`.
## Generating new places in County Durham with bigrams
We build a bigram language model to generate new place names in County Durham to serve as a baseline for later models.
## Generating new places in County Durham with neural networks
We build a multi-layer perceptron in the spirit of [Bengio et al](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf) to generate new place names in County Durham that outperforms the simple bigram language model.
## Generating new places in County Durham with WaveNet
We build a more sophisticated neural network based on the [WaveNet](https://www.deepmind.com/blog/wavenet-a-generative-model-for-raw-audio) architecture that greatly improves upon the multi-layer perceptrion approach. 
