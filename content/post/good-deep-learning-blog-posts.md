+++
date = "2016-09-12T18:50:05+05:30"
draft = false
title = "Good deep learning posts"
tags = ["deep-learning"]
+++

I am an avid reader and spend a lot of time commuting between home and work. I use this time to read blogs, news and papers. In this article I present some cool blog posts that I found and a very short summary. I will add more links as time permits. I have divided blog posts based on the audience it caters to, beginners and intermediate. I believe experts would dive directly into reading papers and won't spend much time reading blogs. Also, are some really good non-technical articles as deserts and some random posts relating to AI as side dishes.

## Starters

### [A brief overview of deep learning - Ilya Sutskever](http://yyue.blogspot.in/2015/01/a-brief-overview-of-deep-learning.html)

This blog post by [Ilya Sutskever](http://www.cs.toronto.edu/~ilya/), also a research director at [OpenAI](https://openai.com) is one of the must read posts for any one diving into deep learning for practical applications. It gives you an insight into why it works, some things you must keep in mind for practical purposes and if you love it, you can just dive into comments section for some cool conversation between [Bengio](http://www.iro.umontreal.ca/~bengioy/yoshua_en/index.html) and Ilya.

## Main Course

### [An overview of gradient descent optimization algorithms](http://sebastianruder.com/optimizing-gradient-descent/)

If you have just started deep learning and have run a model over MNIST, then this is a must read post. Last few years have seen number of optimization algorithms for learning weights of a neural net. From Gradient Descent to Adaboost, we are left with many choices. This post lists down all the optimization algorithms, some mathematics and intuition behind it and the default parameters you may like to play with. A very comprehensize survey, it is again a must read article if you are doing applied deep learning for something serious.

## Desserts

### [Hyperparameter optimization by efficient configuration evaluation](http://www.argmin.net/2016/06/23/hyperband/)

One of the major challenges in deep learning is how you select the hyper-parameters for your training or for post processing in some cases. There are numerous techniques for hyper-parameter search, [random-search optimization](http://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf) by Bergstra et.al'12 is one of the heavily used techniques. [This](https://papers.nips.cc/paper/4443-algorithms-for-hyper-parameter-optimization.pdf) paper by Bergstra, Bengio highlights some of the algorithms used. In this blog, author introduces a new algorithm known as Hyperband which uses random search algorithm and uses simple technique of divide and rule to optimize. The results by the optimization are promising and is a very simple algorithm to understand and implement. One can find the complete paper [here](https://people.eecs.berkeley.edu/~kjamieson/hyperband.html).

## Side dishes

### [The extraordinary link between deep neural networks and the nature of the universe - Henry Lin (Harvard) and Max Tegmark (MIT) ](https://www.technologyreview.com/s/602344/the-extraordinary-link-between-deep-neural-networks-and-the-nature-of-the-universe/)

"Why deep learning works?" - This is one of the most intriguing questions for all involved in deep learning. We try to convince ourselves giving various answers for the question, similarity with the eye structure, universal approximator, etc. Our friends from MIT and Harvard have come up with a much better, mathematical but still a bit vague explanation for the success of deep learning, by comparing the laws used to predict physical phenomenons and how we can derive complete physics using few rules and parameters, thus explaining the whole world around us. For similar reasons, all visual information can be explained/derived from small parameters. The blog gives a beautiful insight into this relation and for more mathematical treatment one can look into the [paper](http://arxiv.org/abs/1608.08225).
