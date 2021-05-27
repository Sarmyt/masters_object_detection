# TensorFlow-Slim image classification model library

[TF-slim](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/slim)
is a new lightweight high-level API of TensorFlow (`tensorflow.contrib.slim`)
for defining, training and evaluating complex
models. This directory contains
code for training and evaluating several widely used Convolutional Neural
Network (CNN) image classification models using TF-slim.
It contains scripts that will allow
you to train models from scratch or fine-tune them from pre-trained network
weights. It also contains code for downloading standard image datasets,
converting them
to TensorFlow's native TFRecord format and reading them in using TF-Slim's
data reading and queueing utilities. You can easily train any model on any of
these datasets, as we demonstrate below. We've also included a
[jupyter notebook](https://github.com/tensorflow/models/blob/master/research/slim/slim_walkthrough.ipynb),
which provides working examples of how to use TF-Slim for image classification.
For developing or modifying your own models, see also the [main TF-Slim page](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/slim).

## Contacts

Maintainers of TF-slim:

* Nathan Silberman,
  github: [nathansilberman](https://github.com/nathansilberman)
* Sergio Guadarrama, github: [sguada](https://github.com/sguada)

## Citation
"TensorFlow-Slim image classification model library"
N. Silberman and S. Guadarrama, 2016.
https://github.com/tensorflow/models/tree/master/research/slim
