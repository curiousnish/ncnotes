---
layout: post
title: AI vs. ML vs. DL vs. DS — A Simple Differentiation Unknown to Many
author: Nishith
categories: [Data Science]
tags: ["Machine Learning", "Artificial Intelligence", "Deep Learning", "Data Science", "Comparison"]
date: 2022-02-19 12:00:00 +0530
---

4 of the Famous Buzzwords of 21st Century and their Difference

What are these abbreviations?

- AI: Artificial Intelligence
- ML: Machine Learning
- DL: Deep Learning
- DS: Data Science

---

**What are all these things?**

Let’s find out!

## What is Artificial Intelligence?

![Desktop View](/assets/img/brain.jpg){: .shadow .rounded-10 w="700" h="400" }
*Powerhouse (Source: Author)*

According to [Wikipedia](https://en.wikipedia.org/wiki/Artificial_intelligence), the definition of AI:

> Artificial intelligence (AI) is intelligence demonstrated by machines, as opposed to natural intelligence displayed by animals including humans.
{: .prompt-info }

Let’s simplify this -

AI is the ability of a machine or a computer program to think, act and learn like humans.

AI can be broadly classified into 2 types:

  1. **Narrow AI**: Task Specific (Self driving cars, chat-bots, etc.)
  2. **General AI**: General Purpose (Like robots that we see in the Movies, Series)

We have not yet achieved the technology (General AI) that can solve a variety of problems with breadth and versatility similar to human/natural intelligence.

## What is Machine Learning?

According to [Wikipedia](https://en.wikipedia.org/wiki/Machine_learning):

> Machine learning (ML) is the study of computer algorithms that can improve automatically through experience and by the use of data.
{: .prompt-info }

Lets understand it with an example -

Consider a student (machine) studying in a school/college learns through books/notes (training data) using different techniques (algorithms) either developed by own or copied from others/toppers or combining 2 or more techniques. He then gives a revision test on the sample papers with answers handy with him (validation data) to perform better in the final exam (test data).

Machine Learning can be classified into three types:

  1. **Supervised and semi-supervised Learning** — When the data fed is along with Target Labels
  2. **Unsupervised Learning** — When the data fed doesn’t contain Target Label
  3. **Reinforcement Learning** — different from the rest; it works exactly like a human , it observes the context, performs tasks and is rewarded if done correctly and punished if done incorrectly. It learns from its mistakes overtime and tries to rectify with a Strategy to earn REWARDS !

![Desktop View](/assets/img/machine-learning.png){: .shadow .rounded-10 w="700" h="400" }
*Image showing classification of Machine Learning and different algortihms ([Source](https://wordstream-files-prod.s3.amazonaws.com/s3fs-public/machine-learning.png))*


## What is Deep Learning?

Deep Learning is a subset of Machine Learning, also referred to as deep understanding of Machine Learning. It includes training of artificial neural networks which is roughly a replica of Human Brain & the Nervous System as a whole to make machines think and work exactly like a human. It includes creation of artificial neurons which act as the basic building blocks of Deep Learning.

![Desktop View](/assets/img/dnn.png){: .shadow .rounded-10 w="700" h="400" }
*Deep Neural Network (Source: [IBM Cloud Education](https://www.ibm.com/cloud/learn/neural-networks))*

An Artificial Neuron (Perceptron) works the same way as a biological neuron. When Data/Signal is fed to a neuron, it processes it by finding patterns, deciphers the information, tries to minimize the loss and gives a satisfactory result.

Deep Learning has a scope to solve larger variety of problems efficiently with certain important conditions, like -

  1. Large amounts of Data — it requires training on huge datasets to produce good results
  2. Creation of Bigger, Complex models — big models gives better results but acts like a blackbox (no idea of how the model is arriving at the results)
  3. Huge Computational Power — to train these big and complex models.

Deep Learning can be divided into :

  1. **ANN** (*Artificial Neural Networks*) — used to solve tasks related to numerical data
  2. **CNN** (*Convolutional Neural Networks*) — used to solve tasks related to image data
  3. **RNN** (*Recurrent Neural Networks*) — used to solve tasks related to textual or time series data

Some of the applications of DL are:

  - Facial Recognition 🧐
  - Image classification/ Object detection 🔍
  - Snapchat Filters 👻
  - Self Driving Cars 🚗

and more!


## What is Data Science?

***Data Science = AI + ML + DL + Math/Stats + Domain Knowledge + Computer Science/Programming***

![Desktop View](/assets/img/dsvenn.png){: .shadow .rounded-10 w="700" h="400" }
*Data Science includes Maths, Computer Science and Domain Knowledge (Source: Author)*


According to [Wikipedia](https://en.wikipedia.org/wiki/Data_science):

> Data science is an interdisciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from noisy, structured and unstructured data, and apply knowledge and actionable insights from data across a broad range of application domains.
{: .prompt-info }

In short…

Data Science is the term for a whole set of tools and techniques to analyze data and extract insights from it. Its goal is to discover hidden patterns in raw data to help businesses improve and increase their profits.

It became a buzzword in 2012, when [Harvard Business Review](https://www.hbs.edu/faculty/Pages/item.aspx?num=43110) called:

> Data Scientist: The Sexiest Job of the 21st Century
{: .prompt-tip }

## The Data Science Life Cycle

A Data Science projects starts with problem discovery/business understanding, then collection and preprocessing of data based on the problem at hand. After preparation of data, we try to understand its distribution using EDA (Exploratory Data Analysis) and create production-ready models using these understandings.

![Desktop View](/assets/img/dslc.png){: .shadow .rounded-10 w="700" h="400" }
*Data Science Life Cycle (Source: [Analytics India Magazine](https://analyticsindiamag.com/a-complete-tour-of-data-science-project-life-cycle/))*

---

## AI vs ML vs DL vs DS

- Artificial Intelligence (AI) is what started it all and there are many things in this field that we are yet to achieve like General AI.
- Machine Learning (ML) is a subset of AI which gives the machines the ability to learn by training algorithms with huge amounts of data. This is great for making predictions without explicitly writing millions of lines of code.
- Deep Learning (DL) is an approach to ML which makes it possible to high performing models (neural networks) using large amounts of data.
- And lastly Data Science (DS) is a combination of all the three along with statistics and domain knowledge. It is a field concerned with extracting insights from data to improve business and solve real world problems. DS always has a human involved (unlike AI, where it is the AI that takes the action).

---

## TL;DR

![Desktop View](/assets/img/venn.png){: .shadow .rounded-10 w="700" h="400" }
*Venn Diagram of all the 4 technologies (Source: Author)*

## Conclusion

Data can be found everywhere and the amount of digital data is increasing at a rapid rate. Many companies find it hard to maintain and gain insights from these huge amounts of data and this is where we Data Scientists shine.

A Quote by [Mike Loukides](https://www.oreilly.com/people/mike-loukides/), Author:

> The Problem isn’t finding data, It’s Figuring out what to do with it.
{: .prompt-tip }