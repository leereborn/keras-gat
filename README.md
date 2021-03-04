# Keras Graph Attention Network
*This is a Keras implementation of the Graph Attention Network (GAT) model by Veličković et al. (2017, [[arXiv link]](https://arxiv.org/abs/1710.10903)).
*Commments are added in the code for easier understanding the code and the model.
## Installation
To install as a module:
```
$ git clone https://github.com/danielegrattarola/keras-gat.git
$ cd keras-gat
$ pip install .
$ python
>>> from keras_gat import GraphAttention
```

Or you can just copy and paste `graph_attention_layer.py` into your project.

## Replicating experiments
To replicate the experimental results of the paper, simply run:
```sh
$ python examples/gat.py
```
