---
layout: default
---

# How to learn to code

*This is going to be a legacy project for [OII SDP 2016](http://sdp.oii.ox.ac.uk). It will contain a step-by-step guide with ressources relevant to scientific programming and data analysis.*

## Table of Contents

1. TOC
{:toc}

## How to use and contribute to this guide

This guide is meant to be dead simple to follow and using the best resources we know to be out there. Just work it through line by line and skip steps if you think you are already familiar with them.

### Problems following this guide?

Raise *any* issue you have with this guide, may it be understanding, or technical problems [here](https://github.com/OII-SDP-2016/how-to-learn-to-code/issues). Try to make sure that you search for your issue, before you create a new one. You will need a Github account for this, which is free. You will want to have one later on anyway ;)

### I want to help writing!

Great! If you want to help us writing, contact one of the [contributors of this repository](https://github.com/OII-SDP-2016/how-to-learn-to-code/graphs/contributors) if you want to become one. Don't be afraid if you're not technically inclined. Helping us to reformulate and correct text is very welcome and easy to do with the approach we're using. It's almost as easy as writing in Word.

## Let's start

### 1. Learning Python

[Python](https://python.org) is a easy to learn programming language and quite effective for data analysis, that's why we are starting with Python.

**Complete the course at [Codecademy](https://www.codecademy.com/tracks/python). If you're lucky, this will take you one rainy weekend. If you're unlucky, the sun will come out. Nobody said it's going to be easy ;)**

<sup>Codecademy follows a freemium model, so you can pay for additional quizzes and projects during the course. If you want you can do those, but actually we think you don't really need it. The free stuff is enough to give you a good foundation.</sup>

### 2. Installing Python on your computer

* First it is important to get used to the command line [here](https://www.codecademy.com/courses/learn-the-command-line), if you aren't already.
* Then it is time to install Python. There are tons of ways to do it but one of the easiest is to use [Anaconda](https://www.continuum.io/anaconda) — a package that includes a lot of useful tools for data analysis. Go to their [download page, and choose the Python **3.5** distribution for your operational system](https://www.continuum.io/downloads). For convenience use the graphical installer, if available.
* Install it using their installer and following their install instructions.
* Now open a command line application (e.g. the preinstalled Terminal on Mac OS X) and type `which python`. Hit Enter. You should get an output along the lines of this:

```
$ which python
/Users/YOURUSERNAME/anaconda/bin/python
```

* If you enter `python` (hitting Enter will be omitted from now on ;) ) you should see a Python shell as you had it in the Codecademy course.
* Try things out you've learned in the course.
* When you're finished hit <kbd>ctrl</kbd> + <kbd>D</kbd>. You will see the command line again.

### 3. Get a good text editor
A good text editor will make your live much more convenient.

There are a lot of pretty ideological discussions about which text editor to use. You don't have to think about this right now. Just use Atom for the moment: [Get it here.](https://atom.io/)

<sup>We consider it a good choice for beginners, because it is possible to extend it's functionality with a great variety of packages, so it's popular with experienced programmers, while it still is easy to configure and intuitively to use. Furthermore it is made by Github, the largest collaboration and version control network out there (more about this later), and therefore integrates very well with it.</sup>

### 4. Write your first script
[...]

### 5. Get familiar with Jupyter Notebook
[...]

### 6. Learn pandas to work with data in Python
Pandas is a Python package that makes your life more pleasant when working with data in tables (and also more complicated stuff). Just think about everything you could do in Excel, then add speed, flexibility and control. Yet you already have Pandas installed together with Anaconda — that's great, isn't it?

Even though we don't like to offer too many options in this guide we have to provide two here, only because one of them is a paid resource:

* [DataCamp](https://www.datacamp.com/) is actually one of the best resources out there. It's also great for learning R (a programming language that's mainly intended to be used for data analysis and statistics). Problem is that what matters for us the intermediate course which is not open for non subscribers. <br>
You can [try the beginners course for free](https://campus.datacamp.com/courses/intro-to-python-for-data-science/chapter-1-python-basics?ex=1), it might be a good revision for you. But **if you are willing to pay $9/month** (you can cancel it any month) for a [student subscription](https://www.datacamp.com/enroll-student) we do recommend their [intermediate course](https://www.datacamp.com/courses/intermediate-python-for-data-science).
* **If you're not willing to pay** you can jump directly to the Pandas documentation and try their [10 Minutes to Pandas](http://pandas.pydata.org/pandas-docs/stable/10min.html). It will most likely take you more than 10 minutes but it  introduces you to the  basic concepts.

## What next?

Here are a few things you could find useful on your further journey:

### Python Resources

* [Python Documentation](https://docs.python.org/3.5/library/multiprocessing.html): Here you can look up every built-in function of Python in detail.
* [The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/): A good thing to read through over time to understand how to become a decent Python programmer.
* [Think Python: How to Think Like a Computer Scientist](http://www.greenteapress.com/thinkpython/thinkpython.html): A great reference to learn Python for general purposes

### Learn TDD

Test Driven Development, or TDD, is a great approach to development, that will save you hours of debuging.

1. Start with [Beginning Test-Driven Development in Python](http://code.tutsplus.com/tutorials/beginning-test-driven-development-in-python--net-30137)
2. If you want to go deeper in tests, take a look in this early version of [Test-Driven Development with Python](http://chimera.labs.oreilly.com/books/1234000000754/index.html) for free
