+++
date = "2016-09-12T16:15:55+05:30"
draft = false
title = "About"
+++

I am Shubham Jain, Research Assistant and Ph.D. student at [Computational Privacy Group](https://cpg.doc.ic.ac.uk/), [Imperial College London](https://www.imperial.ac.uk/) working with [Dr. Yves-Alexandre de Montjoye](http://demontjoye.com). My work spans across privacy, engineering and fairness.

Prior to this I was working at [Qure.ai](http://qure.ai) as an AI Scientist and Founding Member of the team. I graduated in Computer Science from [IIT Bombay](http://www.iitb.ac.in/) in 2016. 

This blog is to record and share my learnings, some good blog posts I come across and my experiences. I like building things, reading, traveling and watching sports. You can get in touch with me through [twitter](https://twitter.com/shubhamjain0594) or email shubhamjain0594\[at\]gmail\[dot\]com.

### Publications

Complete list with number of citations on [Google Scholar](https://scholar.google.co.uk/citations?user=ME0tnoIAAAAJ&hl=en)

1. Jain, S., Bensaid, E. and de Montjoye, Y.A., 2019, May. UNVEIL: Capture and Visualise WiFi Data Leakages. In The World Wide Web Conference (pp. 3550-3554). ACM. [Link](https://spiral.imperial.ac.uk:8443/handle/10044/1/70380)
2. Patravali, J., Jain, S. and Chilamkurthy, S., 2017, September. 2D-3D fully convolutional neural networks for cardiac MR segmentation. In International Workshop on Statistical Atlases and Computational Models of the Heart (pp. 130-139). Springer, Cham. [Link](https://arxiv.org/pdf/1707.09813.pdf)

## Projects

### Testing the data crawlers

We deployed a website at [this link](https://demontjoye.com/test/) to test the effectiveness of data crawlers.

### [UNVEIL: Capture and Visualise WiFi data leakages](https://spiral.imperial.ac.uk:8443/handle/10044/1/70380)

#### Abstract

In the past few years, numerous privacy vulnerabilities have been discovered in the WiFi standards and their implementations for mobile devices. These vulnerabilities allow an attacker to collect large amounts of data on the device user, which could be used to infer sensitive information such as religion, gender, and sexual orientation. Solutions for these vulnerabilities are often hard to design and typically require many years to be widely adopted, leaving many devices at risk.

In this paper, we present UNVEIL - an interactive and extendable platform to demonstrate the consequences of these attacks. The platform performs passive and active attacks on smartphones to collect and analyze data leaked through WiFi and communicate the analysis results to users through simple and interactive visualizations.

The platform currently performs two attacks. First, it captures probe requests sent by nearby devices and combines them with public WiFi location databases to generate a map of locations previously visited by the device users. Second, it creates rogue access points with SSIDs of popular public WiFis (e.g. \_Heathrow WiFi, Railways WiFi) and records the resulting internet traffic. This data is then analyzed and presented in a format that highlights the privacy leakage. The platform has been designed to be easily extendable to include more attacks and to be easily deployable in public spaces. We hope that UNVEIL will help raise public awareness of privacy risks of WiFi networks.


### [OPAL Project](https://www.opalproject.org/)

OPAL (for "Open Algorithms") is a non-profit socio-technological innovation developed by a group of partners around the MIT Media Lab, Imperial College London, Orange, the World Economic Forum and Data-Pop Alliance, aiming to unlock the potential of private sector data for public good purposes by “sending the code to the data” in a safe, participatory, and sustainable manner. It is designed to provide a far better picture of human reality to official statisticians, policymakers, businesses, and citizens, while fostering inclusion and inputs of all on the kinds and uses of analysis performed on data about them.

### Interpreting Neural Networks

{{% fluid_img src="/img/work/interpretability.png" caption="Interpreting Neural Networks" class="pure-u-1-1 center-img" %}}

Interpretability of neural networks is a major challenge and is as well an integral component of the Chest X-Rays diagnostic solution at Qure.ai. I developed an internal library implementing various papers on interpretability to generate heatmaps and ensuring that these algorithms are compatible with all the models being developed. Our paper, in regards to this work, was presented in [RSNA 2017](https://rsna2017.rsna.org/) which is the largest radiology conference in the world with 50k+ attendees. The paper received [Roadie 2017 award](http://www.auntminnie.com/index.aspx?sec=road&sub=aic_2017&pag=dis&itemId=118767) for the most popular abstract by page views by *auntminnie.com*. The work has been very well summarised in [this blog](http://www.auntminnie.com/index.aspx?sec=sup&sub=aic&pag=dis&ItemID=119347#_=_) post.

Another blog post, written by my team, introducing various visualization algorithms can be found [here](http://blog.qure.ai/notes/visualizing_deep_learning).

### [2D-3D fully convolutional neural networks for cardiac MR segmentation](https://link.springer.com/chapter/10.1007/978-3-319-75541-0_14)

#### Abstract

In this paper, we develop a 2D and 3D segmentation pipelines for fully automated cardiac MR image segmentation using Deep Convolutional Neural Networks (CNN). Our models are trained end-to-end from scratch using the ACD Challenge 2017 dataset comprising of 100 studies, each containing Cardiac MR images in End Diastole and End Systole phase. We show that both our segmentation models achieve near state-of-the-art performance scores in terms of distance metrics and have convincing accuracy in terms of clinical parameters. A comparative analysis is provided by introducing a novel dice loss function and its combination with cross entropy loss. By exploring different network structures and comprehensive experiments, we discuss several key insights to obtain optimal model performance, which also is central to the theme of this challenge.

### Kaggle Ultrasound Nerve Segmentation Challenge

{{% fluid_img src="/img/work/kaggle.png" caption="Kaggle Ultrasound Nerve Segmentation Challenge" class="pure-u-1-1 center-img" %}}

My first [Kaggle competition](https://www.kaggle.com/competitions) and first experience with deep learning. We finished [28th on the leaderboard](https://www.kaggle.com/c/ultrasound-nerve-segmentation/leaderboard) out of 923 participants. Our solution was an ensemble of modified [U-Net](https://arxiv.org/abs/1505.04597) and [Fully Connvolutional Networks for Semantic Segmentation](https://arxiv.org/abs/1605.06211). We released a [tutorial on torchnet](http://blog.qure.ai/notes/ultrasound-nerve-segmentation-using-torchnet) which can be used to start with this competition.

### Real-Time Air Quality Monitoring Network

{{% fluid_img src="/img/work/20150914_233922.jpg" caption="Building Real-Time Air Quality Monitors" %}}

I developed a low-cost air quality monitoring network of sensors during my undergraduate thesis. This project was funded by [Development Impact Lab, UC Berkeley](http://dil.berkeley.edu/technology-portfolio/dil-explore/) and was done under the guidance of [Prof. Bhaskaran Raman](http://www.cse.iitb.ac.in/silmaril/br/doku.php), CSE Dept., IIT Bombay. I collaborated with [Ph.D. students in UC Berkeley](http://bets.cs.berkeley.edu/) and Professors in [Environmental Science](http://www.cese.iitb.ac.in/people/facinfo.php?id=vsethi) and [Geographic Information Systems](https://www.linkedin.com/in/jitendra-shah-07b2094/) at IIT Bombay across different phases of the project. During the course of the project, we built hardware and drivers to measure and transmit data, backend server exposing secured APIs to record and serve data, applications built over these APIs for consuming the generated data and lastly, we designed validation experiments to compare our sensors alongside the standard monitors used by the government agencies.

The project was presented to then Hon. Minister of Environment, Mr. Prakash Javadekar via [IIT Bombay Global Business Forum 2015](http://iitbaa-gbf.com/). Presentations, Reports and Articles published in relation to the project are listed below:

- [Enabling air quality analysis using Berkeley software](https://amplab.cs.berkeley.edu/enabling-air-quality-analysis-using-berkeley-software/) - By K. Shankari, Amplab, UC Berkeley
- [BRAS update: Air quality graphs and twitter feed](https://amplab.cs.berkeley.edu/bras-update-air-quality-graphs-and-twitter-feed/) - By K. Shankari, Amplab, UC Berkeley
- [Project Report](https://drive.google.com/open?id=0BwIYmc6VHuwhOEo1UDNPQnpNd1V6b0RZUGRFZlVxNERScmZF)
