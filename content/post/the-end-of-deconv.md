+++
date = "2016-11-13T17:28:22+05:30"
draft = false
title = "The End of Deconvolutions"
tags = ["deep-learning"]
+++

Deconvolutions were introduced in 2014 in ["Fully Convolutional Networks for Semantic Segmentation"](https://arxiv.org/abs/1411.4038) and has been extensively used in Semantic Segmentation and Generative Adversarial Networks. But its saturated now and the problems involved with it including checkerboard effects play a huge role in the error it produces. [This](http://distill.pub/2016/deconv-checkerboard/) blog post goes down the journey of deconvolutions and problems associated with it. It also suggests some solutions and how it can be replaced by better alternatives such as [subpixel-cnn](https://arxiv.org/abs/1609.05158). If you are doing segmentation or working with generative networks, its time to move away from deconv.
