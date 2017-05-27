+++
date = "2017-05-26T00:14:56+05:30"
draft = false
title = "Glimpses of Re-Work Deep Learning Summit - Singapore, 2017"
tags = ["deep-learning", "conference"]
+++

Last week of April 2017, I was attending [Re-work Deep Learning Summit](https://re-work.co/events/deep-learning-summit-singapore-april-2017) in Singapore. I was representing Qure.ai and speaking about some of the work we have been doing in this field. The conference had speakers from [Google Deepmind](https://deepmind.com), [Baidu Silicon Valley AI Lab](http://research.baidu.com/silicon-valley-ai-lab/), [Facebook](http://facebook.com); startups such as [Kata.ai](http://www.kata.ai), [SmartCow.ai](http://www.smartcow.ai); investor firms such as [Zeroth.ai](https://www.zeroth.ai), etc. In this post, I will introduce to you about all the impressive ideas I learned about in the conference.

In a talk demonstrating use-case of [PAI - Platform for AI](https://intl.aliyun.com) via AliMe, two ideas that caught me up where:

- Lazy Multiplication for Communication Optimization in Cloud
- Beam Search Decoders for Seq2Seq models

In another talk by [Li Chen](https://www.linkedin.com/in/crischenli/) on Datacenter-Scale Deep Learning, I learned that

- Tensorflow uses gRPC which is quite slow for tensor communication across the network. This [issue](https://github.com/tensorflow/tensorflow/issues/6116) highlights the problem
- This can be solved by augmenting tensorflow with [RDMA transport layer protocol over RoCE](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/rdma_sigcomm2016.pdf)

This insight was useful to understand that open-sourced tensorflow might have a lot of suboptimal code pieces. Small changes like mentioned, can lead to speed up of more than 6x. Also, it might be the case that internally Google uses a different version of tensorflow than what is open sourced.

One of the reassuring ideas I encountered is of unsupervised pre-training. Initializing the weights of the network using unsupervised learning. This for further emphasized by [Vikramank Singh](https://www.linkedin.com/in/vikramanksingh) from Facebook in his talk on NLP in Deep Learning. [Semantic Compositionality through recursive matrix-vector spaces](http://www.socher.org/index.php/Main/SemanticCompositionalityThroughRecursiveMatrix-VectorSpaces) mentioned by Vikramank was pretty impressive, as it goes beyond word vectors towards word matrices.

[Amit Kushwaha](https://www.linkedin.com/in/yardstick17/), Zomato explained about their work in assessment of image aesthetics using [Spatial Pyramid Pooling](https://arxiv.org/abs/1406.4729).

[Anuroop Sriram](https://www.linkedin.com/in/anuroopsriram/), Baidu SVAIL gave some pretty interesting ideas on End-to-End Speech Recognition. Some interesting concepts introduced included

- SortaGrad Layer
- CTC or Connectionist Temporal Classification Loss

The details about it can be found in [this](https://arxiv.org/pdf/1512.02595.pdf) paper. Another idea he mentioned is of [per-channel energy normalization](https://arxiv.org/pdf/1607.05666.pdf) to improve robustness to loudness variation.

[Ritchie Ng](http://www.ritchieng.com) introduced us to the idea of Hyperparameter Optimization using LSTMs. It is a work his team is going to publish in coming months. It can help us get rid of scheduling LR, momentum, etc. without compromising on accuracy or speed of convergence.

[Brian Cheung](https://www.linkedin.com/in/brian-cheung-79480779/), Ph.D. student at UC Berkeley presented his work in relation to adversarial component analysis

- Adversarial Independent Component Analysis to improve training of autoencoders
- Domain adaptation as adversarial problem
- Overfitting as adversarial problem

This work will be published soon. Another [work](https://arxiv.org/abs/1611.09430) Brian has published is an architecture for attention models which works very similar to fovea in our eyes for image sampling.

[Jeffrey De Fauw](https://www.linkedin.com/in/jeffreydf/), Research Engineer at Deepmind gave us a peek into their work via [Diabetic Retinopathy challenge](https://www.kaggle.com/c/diabetic-retinopathy-detection) hosted on Kaggle in 2016. Few interesting things I noticed from his presentation regarding Deepmind and his project in particular:

- They spend a good time analyzing the data, cases where model fails and preprocessing. I believe this is the key take away - rather than trying newer models and fancier architectures, more time must be spent on data and error analytics.
- Oversampling is not same as loss weights
- One of the really cool findings of data analytics was, the camera used for taking photos of an eye can itself produce some artifacts. But these artifacts will be at the same position for both left and right eye. So training the net with an input as a six-channel image (3-channels per eye) will lead to better accuracy.
- Using [non-decomposable objective](https://arxiv.org/abs/1608.04802) functions for measuring loss
- Log-max ensembling rather than simply majority vote
- Using dropouts during test, inspiration from [this](http://biorxiv.org/content/early/2016/10/28/084210) paper

[Nicolas Papernot](https://papernot.fr), Google Ph.D. Fellow in Security presented his work in Security and Privacy in Machine Learning. [Cleverhans](http://www.cleverhans.io/about/) is an open-source library for benchmarking the vulnerability of machine learning models to adversarial examples. Its created by [Ian Goodfellow](http://www.iangoodfellow.com), Research Scientist at OpenAI and Nicolas.

My talk was on how important is to build trust with doctors for deep learning models in medical imaging. And few approaches we are trying at [Qure.ai](www.qure.ai), results we have obtained and the future directions. Another idea my friend [Jia Qing Yap](https://www.linkedin.com/in/yapjiaqing/), Executive Lead and Deep Learning Engineer at OpenSourceSDC was of [recurrent rolling convolutions](https://arxiv.org/abs/1704.05776).

It was a great experience, thanks to Re-work team for inviting me. You must checkout [Re-Work DL Summit Montreal](https://re-work.co/events/deep-learning-summit-montreal-canada-track1-2017). The lineup is super awesome.

For any comments, suggestions or appreciations tweet [@shubhamjain0594](https://twitter.com/shubhamjain0594).
