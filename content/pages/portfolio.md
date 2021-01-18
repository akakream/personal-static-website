---
title: "Portfolio"
template: "page"
socialImage: "/media/MMD_model.jpg"
---

## CCML: Consensual Collaborative Multi-label Learning

As a part of my Bachelor's Thesis, I developed a co-training method for the accurate classification of multi-label remote sensing images under noisy labels. The method consists of two convolutional neural networks that run simultaneously exchanging loss informations to correct each other when they make mistakes. The networks enhance their classification performance by ranking the training samples at the end of every epoch and excluding the ones that contain severe label noise. And the [code](https://gitlab.tubit.tu-berlin.de/rsim/CCML) is open source! You can also see the paper for it [here](https://arxiv.org/pdf/2012.10715.pdf).

![CCML model](/media/MMD_model.jpg)

---

## noisifier

While writing my Bachelor's Thesis, I needed a flexible tool that can easily insert different kinds of label noise in the training set. I could not find anything that I like. That is why I decided to create a python library called [noisifier](https://github.com/akakream/noisifier) that can add label noise to image labels. Check out [noisy-labels-in-rs.org](https://noisy-labels-in-rs.org/) for more information. 

![noisifier figure](/media/noisifier_figure.jpg)

---

## TUBjobs

I made a twitter bot that tweets new job posts and ending jobs from my university's job database. The bot scrapes the official webpage of the Technical University of Berlin and tweets once a day if there is a new job posting or if an already published job is ending. For scraping I used Beautiful Soup, and to access the Twitter API, I used a python library called Tweepy.

![Screenshot of the twitter bot](/media/tubjobsTwitter.png)
