# One Shot Learning using Memory-Augmented Neural Networks in Tensorflow. 

## Overview

This is the code for [this](https://youtu.be/tChcZpBbTTA) video on Youtube by Siraj Raval as part of the Udacity Deep Learning nanodegree. We're going to use a [Memory Augmented Neural Network](https://arxiv.org/abs/1605.06065) in Tensorflow to perform one-shot learning on the omniglot dataset. That means we'll be able to classify images by their labels after training on just a few samples. 

The benchmark dataset is [Omniglot dataset](https://github.com/brendenlake/omniglot). All the datasets should be placed in the [`data/`](data/) folder.

## Dependencies

* tensorflow (Written for Tensorflow v0.12. Yet to add support for Tensorflow v1*.)
* numpy
* time

Install dependencies using [pip](https://pip.pypa.io/en/stable/)

## Usage

run `python omniglot.py` in terminal to train the model after installing the necessary dependencies.

## Credits

The credits for this code go to [hmishra2250](https://github.com/hmishra2250) i've merely created a wrapper to get people started. 
