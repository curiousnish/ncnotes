---
layout: post
title: Sampling… The Truth Behind All The Lies
author: Nishith
categories: [Data Science]
tags: ["Sampling", "Data Science", "Statistics", "Mathematics", "Surveying"]
math: true
date: 2022-08-26 12:00:00 +0530
---

![Desktop View](/assets/img/samplingintro.jpg){: .shadow .rounded-10 w="700" h="400" }
*Damn Statistics (Source: [Unsplash](https://unsplash.com/photos/cHhbULJbPwM))*

A quote from Mark Twain:

> There are Lies, Damned Lies and then there are Statistics.
{: .prompt-tip }

All of us may have heard of facts or studies showing — 

*“(Certain) percentage of people likes (certain) things or prefer (certain) people/items/notion.”*

For example -

“A poll has shown that 70% of the Americans are supporting Trump in the 2020 elections”

We all are aware of the outcome…😅

All these studies uses an statistical technique called Sampling and this is the main culprit behind their failures.

## What is Sampling?

**The definition:**

> Sampling is a process used in statistical analysis in which a predetermined representative number of observations are selected from a larger data population.
{: .prompt-info }

To gain appropriate and true results from our analysis of the samples, we need to take into consideration the methodology used to sample from a larger population. The methodology may include simple random sampling or systematic sampling. Irrespective of the sampling method, the sampled data should always be representative of the larger pool from which it is taken.


## Why do we need Sampling?

Imagine you are trying to find the average percentage of people who likes beer over wine, or how much percentage of people likes cricket over football (soccer). You would not be able to reach out to every person in this world and ask your desired question and be sure that they would respond. So to make sure you get an idea of the complete population, you need to get the answers by just taking into consideration a small sample of the population.

Depending on the samples and its size, there may be some difference in the descriptive metrics (mean, mode, variance, etc.), but as you increase the sample size you would get closer to the metrics of a complete population. Therefore, it is a tradeoff between choosing the sample size and the metrics accuracy you are planning to achieve.

![Desktop View](/assets/img/samplingerror.png){: .shadow .rounded-10 w="700" h="400"}
*Sampling Error reduces with Sample Size (Source: Author)*

## Types of Sampling
There a large number of sampling techniques used in different fields/domains, but we will try to keep this discussion short and simple and would focus on the sampling techniques mostly using in Data Science/Machine Learning.

### 1. Random Sampling
> Random sampling is a part of the sampling technique in which each sample is chosen entirely by chance and has an equal probability of being chosen.
{: .prompt-info }

![Desktop View](/assets/img/simple.png){: .shadow .rounded-10 w="700" h="400" }
*(Source: Author)*

This is the most basic and common sampling technique as it does not include any complex assumptions for the population and while selecting the samples. The issue of using this type of sampling is that it may not select enough samples with our characteristics of interest.

### 2. Systematic Sampling
> Systematic sampling is a probability sampling method in which a random sample, with a fixed periodic interval, is selected from a larger population.
{: .prompt-info }

In this type of sampling, we randomly select the first sample and others are selected using a fixed ‘sampling interval’. This sampling interval is given by:

$$ k = \frac{N}{n}$$

k = systematic sampling interval

N = population size

n = sample size

![Desktop View](/assets/img/syssampling.png){: .shadow .rounded-10 w="700" h="400" }
*(Source: Author)*

For example, we have a population of N = 12, and we want to select n = 3 samples, so k comes out to be 4 and it is the sampling interval.

We will select the first sample on random basis, i.e. 3 and then to select the next sample we will move 4 places to the next of the first sample. In our case, it is 7 and similarly for the next sample which is 11.

### 3. Stratified Sampling
> Stratified random sampling is a method of sampling that involves the division of a population into smaller sub-groups known as strata.
{: .prompt-info }

This type of sampling technique tries to minimize the sampling error as we will selecting the samples based on the proportion of their numbers in the population.

![Desktop View](/assets/img/strat.png){: .shadow .rounded-10 w="700" h="400" }
*(Source: Author)*

For this example, we will be selecting 6 samples out of the population of 12. We can divide the population into 3 sub-categories or strata namely — red (4 balls), green (5 balls) and blue (3 balls). Now we can select the samples based on the proportion of the strata.

**This type of sampling is used when we want representation from all the sub-groups or strata of the population.** However, stratified sampling requires proper knowledge of the characteristics of the population.

In the top of the article, I mentioned a poll study which showed 70 % of the Americans are supporting Trump in 2020 elections but this study had a bias towards to set of population with specific characteristics who supported the notion of Mr. Donald Trump.

## Further Reading
In this article we discussed about what is sampling, its need and 3 most commonly used types. But during your journey into Statistics, you may encounter different sampling techniques which may provide a better understanding for your use case.