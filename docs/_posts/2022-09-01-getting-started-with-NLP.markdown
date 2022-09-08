---

layout: post
title:  "Getting Started with NLP"  
date:   2022-09-01 
categories: Tutorials 

---

## NLP??

NLP means Natural Language Processing and it is the collection of all those tasks based on natural language. Sentiment classification, Named Entity Recogniction, Part Of The Speech Tagging, Summarization, Question Answering, and so on. They are all NLP downstream tasks. The core point of all of them is find a way to let the computer understand what is written.

The transformer neural networks [1], thanks to their self-attention mechanism, completely revolutionized the NLP field with their ability to create relationships between words in a sentence. I won't dig into their architecture, but you can get an excellent visual explanation [here](https://jalammar.github.io/illustrated-transformer/).


How is it complex to use these technologies? 

## Getting started

Leverage such tools, is easier than you think! What you need are:

* Hardware (RAM + GPU) enough powerful to handle such models
* Runtime environment to run the code
* The code
* The data
* The models

It could seem hard. If you are reading this blog from your old pc with an integrated GPU and 2GB of RAM, well, here is the good news, you can still do it!

### Google Colaboritory

[Google colaboritory](https://colab.research.google.com/) is a cloud environment that lets you to use a machine equiped with all hardware needed for AI. The interface is notebook-style, which means you have two type of cells *text* and *code* avalable. The first supports markdown, the second supports python.
By default you have a CPU instance without any GPU. You can change that easily in the *Runtime* menu.

### Pytorch and Huggingface

Now, you have hardware and environment, but you need the frameworks to work with NLP. The most importants are `pytorch` and `huggingface` which contain prebuild functions and tools ready-to-run to use AI in many tasks.

### Try your self

It is time to run some code! Check the [notebook](https://colab.research.google.com/drive/1mvPdYUwlPw_aQjQT3RLrJsSSKhc4WcZd?usp=sharing) I have prepared.  

### Where to learn?

Probably you are wondering: "This stuff is incredible! But I can't enroll in a Data Science Master". You do not need it! Cmon!! We are in 2022, and everything is online. Let me give you some hints to start:

* [python foundamental](https://www.pythontutorial.net/python-basics/)
* [deep learning](https://www.deeplearningbook.org/) Really Amazing!
* [pytorch foundamental 1](https://pytorch.org/tutorials/beginner/basics/intro.html)
* [pytorch foundamental 2](https://docs.microsoft.com/en-us/learn/paths/pytorch-fundamentals/)
* [huggingface foundamental](https://huggingface.co/course/chapter1/1)

There are a lot of resources online! You have no excuses!


See you soon!


`Valgi0`


[1] Vaswani, Ashish, et al. "Attention is all you need." Advances in neural information processing systems 30 (2017).

PS. Following posts will be more advanced, more technical. I will go deep in some advanced topics of NLP and AI.
