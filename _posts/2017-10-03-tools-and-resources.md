---
title: "So You've Started a PhD in a Computational Science: Useful Tools & Resources"
date: 2017-10-03 11:35:00
categories: resources
tags: datascience academics
---

To celebrate starting the second year of my PhD (holy #%@!), I've created list of resources and tools I've been using for Python, version control, managing literature, this website, _etc_. I hope it's useful for anyone starting a computational science project and if you're embarking on a PhD, best of luck; it's a cake walk.


One caveat: I use a Mac because that's how I was raised and therefore all the resources below are tailored to macOS. I'm sorry if you use Windows and this isn't super helpful. If you have any questions, please send me an email, get in touch on Twitter, or call into the wind when it blows in cold from the East. Without further ado:


## Python & Version Control
Installing Python on your computer is deceptively difficult, especially if you're not used to using your computer's command line to install applications and packages. Take your time, read up before you start, and ask for help if you need it. These are the tools I used:

* [Homebrew][HB] is a package manager that helps with installing and upgrading packages from the command line. It's necessary for the following steps.
* Macs don't come with the current version of [Python][python] (3.6.2 at the time of writing, October 2017). Therefore, I use [pyenv][pyenv] to manage the multiple Python versions I have downloaded on my computer.
* Since I'm using pyenv, I also use the [pyenv-virtualenv][py-v] plug-in to create a virtual environment. Basically, this helps keep my project contained separately from the Python versions already installed. That means it's harder to mess up my computer beyond repair. Using pyenv-virtualenv requires changing the bash-profile (for which you'll need to [see hidden files][hidden] on your computer) to the lines provided in the [virtualenv instructions][py-v]. This is by far the trickiest part of the installation.
* Within your virtual environment, you can then use [pip][pip] to install any dependencies.

For the daily running of Python and for version control, I use the following tools:

* For my 'integrated development environment' (IDE), I use [PyCharm][PyCharm]. This is essentially the equivalent of using [RStudio][RS] for R, creating a pleasant working environment where all the aspects you need are in one window. It's free for educational use.
* For version control and to back-up of my code (avoiding the this-one.py, no-this-one.py, this-time-I-mean-it.py nomenclature), I use [GitHub][git]. Essentially, you create a folder on your computer - a repository - that syncs with your account on GitHub. This repository can be open (allowing for collaboration with other researchers) or private (if you have sensitive or proprietary information).
* To streamline the GitHub experience, I use [GitKraken][GK], a 'graphical user interface' (GUI) for Git that makes version control much simpler and is free for students & personal use. I don't have much experience working on a repository with multiple authors, but GitKraken works well as a single author. As a bonus, their logo is a super cute squid.

![GitKraken](/assets/images/tools/gitkraken.jpg){: .center-image }

To learn Python, I've taken courses through [DataCamp][DC] and [DataQuest][DQ]. I went into more depth in my previous [Back to School post][post].


## Writing & Reference Management
Despite my better-half's best efforts, I'm still using Microsoft Word. He recommends [LaTeX][latex], a text editing language that allows for much greater control and is used for most (if not all) journal formatting. I made my CV in it using [Overleaf][overleaf], an online LaTeX editor. My main hold-out with Word is Track Changes. However, [ShareLaTex][SLT], which allows for similar editing to Track Changes and same-time collaboration, is joining Overleaf, so I might be persuaded to jump ship!

I use [Mendeley][M] as my reference manager, a necessary tool, now that I'm reading more papers than ever, for multiple projects. It's similar to EndNote and other technologies, but it's free! You import your papers into a library, which can then be organized into sub-folders, and there's a plugin for Word that automates citation and generates your reference list, with a library of styles from various journals and professional societies. It also provides BibTeX export to use with LaTeX. My other favourite aspect is that they have an app, so all my papers are synced with my phone & tablet and I can read and annotate on the go. Just make sure the labelling is correct when you import your papers into Mendeley and you'll be golden moving forward.

I also keep copies of all the papers I download in [Dropbox][db], which can also be accessed on mobile devices. In fact, I keep all my important Word files in Dropbox as a backup and so I can access my work from my laptop.


## 'Personal-Professional Brand' & Website
There's some debate over [whether personal branding is necessary, or even possible][branding]. Nevertheless, having an online presence showing that you're engaging in your field beyond your personal research, is important for networking and for future job-searching. 

Towards that end, I cannot recommend [Twitter][twitter] highly enough. At least for the communities I engage with (marine science, ecology, conservation biology, data science), Twitter is full of amazing practitioners sharing their work, personal experiences, resources, and jokes. It's a great way to keep tabs on important members of your field and communicate with your peers. I also maintain a [Linked-In][LI] profile, though I use it much less, and I have this website/blog. 

I've developed somewhat of a brand by sticking to discussing science on these platforms, though including a little about your other interests can present a more well-rounded picture. Just keep in mind who follows you and whether they'd be interested in what you're posting, if you're using social media for professional reasons. Therefore, I keep my Facebook and Instagram profiles separate and private.

As for this website, my goal is to maintain a record of my PhD, providing content that I hope is useful and engaging for my peers and shows some verbal facility to future employers. It also provides a professional-looking landing page. To build the website, I'm using: 

* [Jekyll][jekyll], a static website builder. To be completely honest, I got a lot of help with how to install Jekyll, as it's built with Ruby, but they have [guides on their website][j-howto].
* The theme is [jekyll-uno][uno].
* It's hosted using [Amazon Web Services (AWS)][AWS] S3, which ends up costing me about 50¢ a month. Again, I know embarrassingly little about how it works, but it's pretty easy to use. The domain was approximately $12 and I also use my own domain for a custom email address with [FastMail][FM], which is $50 annually.
* To connect to my AWS server, I use [Cyberduck][duck].
* I write my posts in markdown using [MacDown][MD].


## Miscellaneous Tools
More useful programs and resources:

* [iTerm2][iterm] is a replacement for Terminal (command line) for Mac. It's more customizable than Terminal. One tip: you can control the transparency of the window, which makes it easier to read instructions and run code simultaneously. That's really nice when you're not hacker-in-a-movie proficient.
* [Sublime Text][ST] is a text editor, useful if you need to look at a couple files in a programming language that you don't usually use. I use it mostly for JavaScript and HTML

I hope this list has been useful. It's at least been long. Please get in touch if you have any questions about how or why I use these tools, or recommendations for better ones.

Lastly, my final tool is the other students and post-docs around me. We're all working on different projects, but getting to sit down over a pint (of tea or beer!) with other people who are going through or have gone through the same experience is invaluable.

Best,

-Sophia




[HB]: https://brew.sh/
[python]: https://www.python.org/downloads/
[pyenv]: https://github.com/pyenv/pyenv
[hidden]: https://ianlunn.co.uk/articles/quickly-showhide-hidden-files-mac-os-x-mavericks/
[py-v]: https://github.com/pyenv/pyenv-virtualenv
[pip]: https://pip.pypa.io/en/stable/
[PyCharm]: https://www.jetbrains.com/pycharm/
[RS]: https://www.rstudio.com/
[git]: https://github.com/
[GK]: https://www.gitkraken.com/
[DC]: https://www.datacamp.com/home
[DQ]: https://www.dataquest.io/home
[post]: https://sowasser.com/back-to-school-python-resources/
[latex]: https://www.latex-project.org/
[overleaf]: https://www.overleaf.com/
[SLT]: https://www.sharelatex.com/
[M]: https://www.mendeley.com/
[db]: https://www.dropbox.com/?landing=dbv2
[branding]: http://www.bbc.com/capital/story/20170723-the-case-against-personal-brands
[twitter]: https://twitter.com/
[LI]: https://www.linkedin.com/feed/
[jekyll]: https://jekyllrb.com/
[j-howto]: https://jekyllrb.com/docs/home/
[uno]: https://github.com/joshgerdes/jekyll-uno
[AWS]: https://aws.amazon.com/
[FM]: https://www.fastmail.com/
[duck]: https://cyberduck.io/?l=en
[MD]: https://macdown.uranusjr.com/
[iterm]: https://www.iterm2.com/
[slack]: https://slack.com/
[ST]: https://www.sublimetext.com/