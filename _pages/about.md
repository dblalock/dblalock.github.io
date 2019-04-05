---
layout: single
title: About
permalink: /about/
---

<!-- I'm a machine learning PhD student at MIT. I make machine learning algorithms that don't need good (or any) labels and are really, really, fast. -->
I'm a computer science PhD student at MIT. I make fast machine learning algorithms.

I do this because 1) I'm good at it, and 2) I claim that it's extremely important. The reason it's important is that speed helps us get all the other qualities we like in machine learning, such as accuracy, privacy, fairness, and safety. It does this in three ways:

 1. **It directly lets you get more of these qualities** through usage of larger models, exploration of more architectures or hyperparameters, [slower but privacy-preserving training](https://arxiv.org/abs/1610.05492), [slower but adversarially robust inference](https://arxiv.org/abs/1902.02918), etc.
 <!-- 1. However, just making better models *possible* is insufficient. Fortunately, **greater speed also improves incentives**.  -->
 1. A corollary is that **it improves incentives.** The history of technology shows that desirable features take a back seat to essential features. <!-- E.g., no one was worried about the Ford Model-T not having airbags, as long as it took you places better than a horse. --> In machine learning today, we're seeing model accuracy and inference time dominate desirable traits like safety and privacy. By making it easy to obtain high-quality models in the essential respects, we make it worthwhile to consider the "non-essential" respects as well.
 1. **It facilitates research**, especially in academia. The bottleneck in a great deal of machine learning research, particularly for those of us who lack tech-giant-level resources, is experiment time. Faster machine learning means faster research progress. The disproportionate aid to academics also (at least in theory) disproportionately facilitates research on socially desirable aspects of machine learning such as privacy, safety, and fairness that private companies may have less incentive to pursue.
 <!-- 1. **It reduces the cost of doing the "right" thing. Data-hungry models that are expensive to train and deploy incentivize collecting as much data about people as possible and storing it in cleartext (or with keys you control) in datacenters with tons of compute. This is a -->

<!-- In short, if model training and inference were instantaneous, we could select a model that comes within <1% of the best possible accuracy, but trained with strong privacy practices, abundant checks for fairness, adversarially-robust inference procedures, etc. And research -->

There's more specific reasoning behind my individual projects, but these points hopefully give you a taste of why I think speed is important.

I've had a lot of failures in pursuing this, but also some successes. My favorite successes so far include:

 - Learning to recognize spoken words from five unlabeled examples in under two seconds [1]
 - Training on data at 5GB/s in a single thread [2]
 - Multiplying matrices 10x faster than a matrix multiply (with some approximation error) [3]
 - Nearest-neighbor searching through billions of images per second in one thread with no  indexing [3]

[1] [https://arxiv.org/abs/1609.09196](https://arxiv.org/abs/1609.09196)
<br/>[2] [https://arxiv.org/abs/1808.02515](https://arxiv.org/abs/1808.02515)
<br/>[3] [https://arxiv.org/abs/1706.10283](https://arxiv.org/abs/1706.10283)

 <!-- 1. The history of technology shows that desirable features take a back seat to essential features. E.g., no one was worried about the Ford Model-T not having airbags, as long as it took you places better than a horse. In machine learning today, we're seeing model accuracy and inference time dominate desirable traits like security, fairness, privacy, and safety. By making it easy to obtain "good enough" models in the essential respects, -->
 <!-- 1. A -->



### More Info
 - My CV is [here](/assets/misc/cv-2019.pdf).
 - I was [profiled in UVA Today](https://news.virginia.edu/content/two-uva-engineering-students-net-prestigious-goldwater-scholarships) after winning a [Goldwater scholarship](https://en.wikipedia.org/wiki/Barry_M._Goldwater_Scholarship).
 - If you need something official-looking to say about me, here's a bio:

    > "Davis Blalock is a PhD student at MIT, advised by Professor [John Guttag](https://en.wikipedia.org/wiki/John_Guttag). His primary work is designing high-performance machine learning algorithms, with the goal of eliminating tradeoffs between speed, accuracy, privacy, and safety in machine learning. He received his M.S. from MIT in 2016 and his B.S. from the University of Virginia in 2014. He is a Qualcomm Innovation Fellow, NSF Graduate Research Fellow, and Barry M. Goldwater Scholar."

    <!-- of turning streams of medical, smart phone, and wearable sensor data into useful pictures of people’s health. He received his M.S. from MIT in 2016 and his B.S. from the University of Virginia in 2014. He is an NSF Graduate Research Fellow, Qualcomm Innovation Fellow, and Barry M. Goldwater Scholar." -->
