
**DeepTrans** is a character level language model for [transliterating](https://en.wikipedia.org/wiki/Transliteration) English text into Hindi. It is based on the attention mechanism presented in [[1]](http://arxiv.org/abs/1409.3215) and its implementation in [Tensorflow's](https://www.tensorflow.org/) [Sequence to Sequence](https://www.tensorflow.org/versions/r0.10/tutorials/seq2seq/index.html) models. This project has been inspired by the translation model presented in tensorflow's sequence to sequence model. This project comes with a pretrained model (2 layers with 256 units each) for Hindi but can be easily trained over the existing model or from scratch. The pretrained models are trained on lowercase words. If you wish to train your own model then feel free to do whatever you want and I would be glad if you could share your results and models with me. I hope to see interesting results.

# Prerequisites
1. [Tensorflow](https://www.tensorflow.org/) (Version >= 0.9)
2. Python 2.7

# References
1. [Sequence to Sequence Learning with Neural Networks](http://arxiv.org/abs/1409.3215)
