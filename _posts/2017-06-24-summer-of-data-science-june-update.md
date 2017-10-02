---
title:  "Summer of Data Science June Update: A Greek Tragedy"
date:  2017-06-26 16:25:32
categories: professional development, data science
tags: datascience
---

In my last blog post, I discussed my goals for the Summer of Data Science ([#SoDS17][#SoDS17]). I had grand plans to start investigating machine learning because I’m hoping to build a model from scratch using video of fish behaviour this winter.  Unfortunately, instead of emerging as a deep learning prodigy, I now know your pain, [Icarus][Icarus].

![icarus](/assets/images/june_update/icarus.jpg)

(is that a bit dramatic? Nah.)

I decided to begin my foray into deep learning with the [DataCamp Deep Learning in Python][datacamp deep] course and felt comfortable with the first chapter, covering the theory. At the same time, I continued to work on the preliminary fish behaviour model I’m building in Python. Now, I’d taught myself Python basics using the [DataCamp Intro to Python][datacamp intro] and [DataQuest Python Introduction][dataquest] courses and I thought I had a handle on the language. I’d taught myself R previously by working out each problem I came across (with help from google) and I figured I could do the same with Python. I, however, hit a wall with what felt like a very basic problem. 

I’ve been using an agent-based modelling framework called [Mesa][mesa], which is nifty because it allows you to collect data at each step of the model and store it in a dataframe. A lot of other frameworks don’t allow seamless data collection. I’ve successfully developed a couple of indicators of cohesion for my simulated fishes, collected and displayed step-wise. Yet, I cannot, for the life of me, figure out how to get position data (x, y coordinates) for each agent at each step of the model. This feels like a basic programming issue, as I know how I want the output to be structured. Nothing makes you feel quite as thick as spending a couple of days googling a problem you can’t even explain fully. I couldn’t find the answers I needed and could barely read the ones I found. I decided that, before I tackle machine learning, I’d better get my python ducks in a row.

So, I’ve gone back to basics. I first looked into the DataCamp [Python Data Science Toolbox (Part 1)][datacamp tool], but still felt a little out of my depths and went back to their [Intermediate Python for Data Science][datacamp inter] course. The intermediate material was thankfully, mercifully familiar and it helped build my confidence. I’m going forward with the Data Science Toolbox now and though I’d much rather forge ahead without reading the directions, as it were, I know I’d end up with a mess.

![chair](/assets/images/june_update/chair.jpg)

I’ve concluded that, at least for the moment, I’ll have to walk before I can run (or fly). I’m hopeful that we can finally do some deep learning in July.

Onwards!


[#SoDS17]: https://twitter.com/search?q=%23SoDS17&src=tyah&lang=en
[Icarus]: https://en.wikipedia.org/wiki/Icarus
[datacamp deep]: https://www.datacamp.com/courses/deep-learning-in-python
[datacamp intro]: https://www.datacamp.com/courses/intro-to-python-for-data-science
[dataquest]: https://www.dataquest.io/subject/learning-python
[mesa]: https://github.com/projectmesa/mesa
[datacamp tool]: https://www.datacamp.com/courses/python-data-science-toolbox-part-1
[datacamp inter]: https://www.datacamp.com/courses/intermediate-python-for-data-science