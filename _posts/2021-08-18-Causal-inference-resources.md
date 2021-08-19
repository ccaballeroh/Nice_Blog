---
layout: post
title: Resources for Learning Causal Inference
date: 2021-08-18
author: Christian
categories: ["Causal Inference"]
tags: [Causal Inference, Resources]
published: true
finished: false
---

> _Had the pandemic happened last year, would there be so many awesome and **new** resources on Causal Inference?_


That statement is a counterfactual: a question we ask about the **current** state of affairs in the world **if** something would have been different in the past.

According to Judea Pearl, a leading figure in causal inference, there are three rungs in the ladder of causation (more and more I see this model referred to as "Pearl's Causal Hierarchy"). 

The first (lowest) rung deals only with **associations** (sometimes, wrongly bounded to only correlations&mdash;which are only linear) in the data. This is the level where ALL machine learning works.

The second rung entails **interventions**. In this second level, we can know what will happen when we change (force) something. Babies and some animals deal with this level when they _interact_ with the world. In order to deal formally with this level, Pearl developed an extension to probability theory called "do-calculus".

Lastly, the third (and highest) rung in the ladder is the **counterfactual**. At this level, we need imagination to guess what the world would be had something been different in the past. As far as we know, we humans are the only living animals capable of doing this. (I will have much more to say about this in a future post relating this ability to human language and its computational properties).

Apparently, it is not so easy to _define_ what is a cause even though we all have an intuition for it. Philosophers have taken a stab at it for centuries (if not millenia), so I won't say that the issue is settled, but I do like one definition I have come across by Prof. Pearl himself and it goes something like this:

> Having both $a$ and $$b$$ occurred, we can say that $a$ is a cause for $b$, if and only if, had not $a$ happened, $b$ would not have happened. 

I like this definition over others that deal with interventions precisely because it relies on counterfactuals&mdash;the highest and probably uniquely human level in the ladder. Let's see an example that for some reason I have present whenever causality comes up in a conversation.

Let's say that we see that whenever we have soup for supper, it is followed by steak. One of the earliest attempts to define causality dealt with this kind of situations: _a_ is always followed by _b_, so _a_ must cause _b_. Well, our common sense tells us that there is no way that the soup is the cause of the steak, but all the past _empirical_ evidence shows that there is, at least, an _association_. So this definition does not suffice.

Now, let's apply our preferred definition. Let's imagine that we already ate. Would have we eaten steak if there had not been any soup? Yes! So the soup cannot be the cause for the steak. Another example, had the sun risen if the rooster hadn't crowed? Yes! So the rooster does not cause the sun to rise every morning even though we see that first the rooster crows and then the sun rises.

After all this digression about the three rungs in the ladder of causality, the main objective of this post is to collect (mainly) free resources to learn causal inference. Most of these resources are brand new! Amazing timing for me who just picked up the subject last year as my research area to get my doctoral degree in computer science.

Causal inference is able to answer causal questions from _observational_ data 🤯. For me, this was mind-blowing when I first learned it. By the way, that's less than two years ago, in 2019 when Amazon suggested me _The Book of Why: The New Science of Cause and Effect_ by Judea Pearl and Dana Mackenzie.

I couldn't believe that I hadn't heard about it before. I mean, I was getting a master's in computer science and Pearl himself is a Turing Award winner for his work in causal inference and artificial intelligence. I got to grad school to learn about machine learning and AI in general; I was IN the AI lab of the research center and yet not only me but no one I asked knew about all this amazing work. Unbelievable.

So back to the topic again. This last year I have been following the right people on Twitter. That has been a gold mine. Apparently, people can be productive and giving during a pandemic! I will update the following list whenever I come across with more stuff. But for now, there's plenty. And if by any chance any of the following authors reads this: Thank you so much for your time and generosity!

## Books

- [Hernán MA, Robins JM (2020). _Causal Inference: What If_. Boca Raton: Chapman & Hall/CRC.](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)

    - The PDF file is available for free at Miguel Hernán's website.
    - The authors are epidemiologists.
    <br>

- [Cunningham, S. (2021). _Causal Inference: The Mixtape_. New Haven: Yale University Press.](https://mixtape.scunning.com/)

    - Beautiful free online version of the book.
    - The author is an economist.
    <br>

- [Peters, J., Janzing, D., & Schölkopf, B. (2017). _Elements of causal inference: foundations and learning algorithms._ The MIT Press.](https://mitpress.mit.edu/books/elements-causal-inference)

    - The PDF file is available for free through the Open Access tab on MIT Press website.
    - The authors are mathematicians and computer scientists working in intelligent systems.
    - This is NOT a pandemic book, but it's great and free.
    <br>

- [Huntington-Klein, N. (2022). _The Effect: An Introduction to Research Design and Causality_. Boca Raton: Chapman & Hall/CRC.](https://theeffectbook.net/)
    
    - Another beautiful free online version of a forthcoming book.
    - The author is an economist.
    <br>

- [Matheus Facure, & Michell Germano. (2021)._Causal Inference for The Brave and True_](https://matheusfacure.github.io/python-causality-handbook/)

    - Reference: [Matheus Facure, & Michell Germano. (2021). matheusfacure/python-causality-handbook: First Edition (v1.0). Zenodo. https://doi.org/10.5281/zenodo.4445778](https://doi.org/10.5281/zenodo.4445778)
    - The authors are (very young!) data scientists
    <br>

- [Neal, B. (2022?) _Introduction to Causal Inference from a Machine Learning Perspective_. Boca Raton: Chapman & Hall/CRC.](https://www.bradyneal.com/causal-inference-course#course-textbook)
    - Currently, these are lecture notes of a forthcoming book. I will update the info when I learn any updates.
    - The author is a PhD student in causal inference and machine learning.
    <br>

- [Osazuwa, R. (2022?). _Causal AI_\[?\]](https://newsletter.altdeep.ai/p/tiger-moms-bach-and-reichenbach)
    - I learned that Robert Osazuwa Ness is writing a book on Causal AI. This blog post is an excerpt from one of the chapters of the forthcoming book.
    - The author is a statistician and machine learning specialist.
    <br>
    
## MOOCs

## Blog Posts

## Conferences and Workshops

## Programming Frameworks

[CausalImpact](https://google.github.io/CausalImpact/CausalImpact.html)
