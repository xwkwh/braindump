+++
title = "A Distributional Code for Value in Dopamine-based Reinforcement Learning"
author = ["Jethro Kuan"]
lastmod = 2020-01-16T20:46:19+08:00
draft = false
math = true
+++

paper
: [https://www.nature.com/articles/s41586-019-1924-6](https://www.nature.com/articles/s41586-019-1924-6)

related
: [§reinforcement\_learning]({{< relref "reinforcement_learning" >}})


## Abstract {#abstract}

Reward prediction errors are typically represented by a single scalar
quantity, as in temporal-difference learning. In distributional RL,
the reward prediction error consists of a diverse set of channels,
predicting multiple future outcomes. Different channels have different
relative scalings for positive and negative reward prediction errors.
Imbalances between these scalings cause each channel to learn a
different value prediction, and collectively represent a distribution
over possible rewards.


## Resources {#resources}

-   [Distributional RL – Simple Machine Learning](https://mtomassoli.github.io/2017/12/08/distributional%5Frl/)