---
title: Training convolutional neural networks with megapixel images
authors:
- Hans Pinckaers
- Geert Litjens
date: '2018-01-01'
publishDate: '2024-09-11T12:09:38.772713Z'
publication_types:
- paper-conference
publication: '*Medical Imaging with Deep Learning*'
abstract: To train deep convolutional neural networks, the input data and the intermediate
  activations need to be kept in memory to calculate the gradient descent step. Given
  the limited memory available in the current generation accelerator cards, this limits
  the maximum dimensions of the input data. We demonstrate a method to train convolutional
  neural networks holding only parts of the image in memory while giving equivalent
  results. We quantitatively compare this new way of training convolutional neural
  networks with conventional training. In addition, as a proof of concept, we train
  a convolutional neural network with 64 megapixel images, which requires 97% less
  memory than the conventional approach.
links:
- name: URL
  url: https://arxiv.org/abs/1804.05712
---
