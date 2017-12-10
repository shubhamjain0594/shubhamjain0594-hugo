+++
date = "2017-11-15T12:00:00+05:30"
draft = false
title = "Contributions so far"

+++

## Interpreting Neural Networks, Qure.ai

{{% fluid_img src="/img/work/interpretability.png" caption="Interpreting Neural Networks" class="pure-u-1-1 center-img" %}}

Interpretability of neural networks is a major challenge and is as well an integral component of the Chest X-Rays diagnostic solution at Qure.ai. I developed an internal library implementing various papers on interpretability to generate heatmaps and ensuring that these algorithms are compatible with all the models being developed. Our paper, in regards to this work, was presented in [RSNA 2017](https://rsna2017.rsna.org/) which is the largest radiology conference in the world with 50k+ attendees. The paper received [Roadie 2017 award](http://www.auntminnie.com/index.aspx?sec=road&sub=aic_2017&pag=dis&itemId=118767) for the most popular abstract by page views by *auntminnie.com*. The work has been very well summarised in [this blog](http://www.auntminnie.com/index.aspx?sec=sup&sub=aic&pag=dis&ItemID=119347#_=_) post.

Another blog post, written by my team, introducing various visualization algorithms can be found [here](http://blog.qure.ai/notes/visualizing_deep_learning).

## Kaggle Ultrasound Nerve Segmentation Challenge, Qure.ai

{{% fluid_img src="/img/work/kaggle.png" caption="Kaggle Ultrasound Nerve Segmentation Challenge" class="pure-u-1-1 center-img" %}}

My first [Kaggle competition](https://www.kaggle.com/competitions) and first experience with deep learning. We finished [28th on the leaderboard](https://www.kaggle.com/c/ultrasound-nerve-segmentation/leaderboard) out of 923 participants. Our solution was an ensemble of modified [U-Net](https://arxiv.org/abs/1505.04597) and [Fully Connvolutional Networks for Semantic Segmentation](https://arxiv.org/abs/1605.06211). We released a [tutorial on torchnet](http://blog.qure.ai/notes/ultrasound-nerve-segmentation-using-torchnet) which can be used to start with this competition.

## X-Scan, Automated Chest X-Ray Diagnosis, Hack InOut 4.0 Winners

{{< fluid_imgs "pure-u-1-2|/img/work/arbitrium.png|Arbitrium" "pure-u-1-2|/img/work/hackinout.jpg|Hack InOut 4.0" >}}


## Real-Time Air Quality Monitoring Network, 2015-16, IIT Bombay

{{% fluid_img src="/img/work/20150914_233922.jpg" caption="Building Real-Time Air Quality Monitors" %}}

I developed a low-cost air quality monitoring network of sensors during my undergraduate thesis. This project was funded by [Development Impact Lab, UC Berkeley](http://dil.berkeley.edu/technology-portfolio/dil-explore/) and was done under the guidance of [Prof. Bhaskaran Raman](http://www.cse.iitb.ac.in/silmaril/br/doku.php), CSE Dept., IIT Bombay. I collaborated with [Ph.D. students in UC Berkeley](http://bets.cs.berkeley.edu/) and Professors in [Environmental Science](http://www.cese.iitb.ac.in/people/facinfo.php?id=vsethi) and [Geographic Information Systems](https://www.linkedin.com/in/jitendra-shah-07b2094/) at IIT Bombay across different phases of the project. During the course of the project, we built hardware and drivers to measure and transmit data, backend server exposing secured APIs to record and serve data, applications built over these APIs for consuming the generated data and lastly, we designed validation experiments to compare our sensors alongside the standard monitors used by the government agencies.

[Dylos Sensors](http://www.dylosproducts.com/ornodcproair.html) were used with [Raspberry Pi](https://www.raspberrypi.org/products/raspberry-pi-1-model-b/) and [GPRS board](http://www.rhydolabz.com/wireless-gsm-gprs-c-130_185/sim-900-gsmgprs-module-p-969.html). The drivers on the raspberry pi were built over python and [sMAP](https://github.com/SoftwareDefinedBuildings/smap), implementation can be found [here](https://github.com/dhruti96shah/AirQualityMonitoring). The backend APIs were built using [Django](https://www.djangoproject.com/) over [Berkeley Tree Database](https://github.com/BTrDB) and [Giles](https://github.com/gtfierro/giles2). The implementation of the backend can be found [here](https://github.com/shankari/Real-Time-Air-Quality-Sensoring-Network).

The project was presented to then Hon. Minister of Environment, Mr. Prakash Javadekar via [IIT Bombay Global Business Forum 2015](http://iitbaa-gbf.com/). Presentations, Reports and Articles published in relation to the project are listed below:

- [Enabling air quality analysis using Berkeley software](https://amplab.cs.berkeley.edu/enabling-air-quality-analysis-using-berkeley-software/) - By K. Shankari, Amplab, UC Berkeley
- [BRAS update: Air quality graphs and twitter feed](https://amplab.cs.berkeley.edu/bras-update-air-quality-graphs-and-twitter-feed/) - By K. Shankari, Amplab, UC Berkeley
- [RAQMN Twitter Channel](https://twitter.com/raqmniitb)
- [Project Report](https://drive.google.com/open?id=0BwIYmc6VHuwhOEo1UDNPQnpNd1V6b0RZUGRFZlVxNERScmZF)
- [IITBAA GBF 2015 Presentation](https://drive.google.com/open?id=1zSG9ACQcN4D22vZkyvSwRhY164-5ST1xqobdeEiR2xY)
- [Project Presentation](https://drive.google.com/open?id=1PXKFrf1XnFhm0Qxv92xDreDl6p8PyXAMN4vsAkWURi4)


## Comparison of Evolutionary Strategies for Othello, IIT Bombay

## Halite and Hack-man, Self Project
