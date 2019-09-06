---
title: "IEA 2019 Poster - It's wrong but is it useful? Validating theoretical models of fish collective behaviour"
data: 2019-01-03 10:48:01
tags: conferences academics
image: /assets/images/IEA19/iea_poster.png
---

I'm writing this post to accompany a poster presented at the [Irish Ecological Association][IEA] conference in Galway, January 2019.

You can access a copy of the poster [here][poster]. Below you'll find a link to my theoretical model and the video of stickleback fish that I'm using as a comparison for my model.

{% include image.html img="assets/images/IEA19/iea_poster.png" title="Poster title" caption="Click to see the full poster!" url="https://drive.google.com/open?id=1znj1eAU97AoXrNSR5SGrQ7u9kwk5bENX" %}

<br>

### My theoretical model in Python

I have built a Boids model of shoaling behavior in Python 3.6 using [Mesa][mesa], a modelling framework. You can access, download, and run my code via my [github repository][git].

<br>

### Incorporating video of real fish


To start working with real-world data, I digitized video of stickleback fish. These fish are gregarious, forming schools, and a colleague had incidentally collected some in light traps. He thought I might be interested in video of them moving around the bottom of the collection container. What's particularly useful about the video is that the fish are  more or less constrained to two dimensions, as is my model (at the moment).

To track the fish in the video, I used [LoggerPro][lp]. While you can track the position of each individual fish in each frame of video, since I am interested in overall position instead of questions of leadership and individual decision-making, I simply recorded the position of all fish (nose and tail so I could determine their direction), for each step of the video. In this example, ignore the colors. The program only has a limited set of colors, so all of the tracks are green after a point.

<iframe width="560" height="315" src="https://www.youtube.com/embed/CXHi9ycQY9c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>

<br> 

Please get in touch if you want to know more, or discuss my work further!



[IEA]: https://www.britishecologicalsociety.org/membership-community/irish-ecological-association/
[poster]: https://drive.google.com/open?id=1znj1eAU97AoXrNSR5SGrQ7u9kwk5bENX
[lp]: https://www.vernier.com/products/software/lp/
[mesa]: https://mesa.readthedocs.io/en/master/
[git]: https://github.com/sowasser/fish-shoaling-model