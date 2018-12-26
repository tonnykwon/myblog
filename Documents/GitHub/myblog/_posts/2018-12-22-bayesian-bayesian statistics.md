---
title: "Bayesian Statistics"
permalink: /bayesian/
date: 2018-12-22 15:24:00 -0400
categories: Bayesian
---
## Frequentist
Suppose we roll a fair dice. Then, P(6) indicates the probability of getting 6. 
In frequentist view, we see relative frequency of events. In case of the dice, we can think about rolling dice infinite number of times. 
If it is a fair dice, P(6) equals 1/6. \n
Thus, in the frequentist paradigm, it tries to be objective in defining probabilities.

### Binomial Example
We filped coiend 100 times, and we got 40 heads and 60 tails. Based on the central limit theorem the 100 flips sum of the x of i's will approximately follow a normal distribution.
$$  $$

## Bayesian
On the contrary, bayesian paradigm defines probabilities in personal perspective. 
For instance, P(6) may be different, if you have different information. 
That is P(6) would be a random variable between 0 and 1, and, based on your data of rolling dice, you update the probability of getting 6.

### Notation
y = *data* (observed) \n
&theta; = *parameter* \n
In Bayesian analysis, &theta; is considered to be random. It represents uncertainty about its value.\n

&p(\theta)
*prior distribution*: marginal distribution of &theta;. Our state of knowledge(uncertainty) prior to observing y. \

&p(y|\theta)
*sampling distribution*: conditional distribution of y given &theta;. How the data would be generated when &theta; is given. \

$$&p(\theta | y)$$ 
*posterior distribution*: conditional distribution of &theta; given y.

### Bayes' Rule
Derive posterior distribution from the Bayesian model: \n
&p(\theta |y) = \frac{p(\theta, y)}{p(y)} = \frac{p(\theta)p(y|\theta)}{p(y)} 
p(y) is called *normalizing factor* as it makes $p(\theta|y) $ is a density in $\theta$ \n
Since data is given, we can use unnormalized form instead:
&p(\theta, y) \propto p(\theta)p(y|\theta)

### Binomial Example
Suppose we start a business, and conducted survey. Survey results tell 20 out of 2 people are interested in your business. \
Then, \theta = proportion of population who are interested in your business \ 
n = size of a random sample from population \
y = number in sample who are interested in the business. \ 

Sampling distribution looks like: \
$$ y| \theta \sim Bin(n, \theta) $$
Sampling density: \
$$ p(y|\theta) = (n y) \theta^y (1-\theta)^{n-y}, y=0, ..., n $$
Thus, the likelihood would be:
p(y=2 | \theta) = (20 2) \theta^2 (1-\theta)^{20-2} \propto \theta^2 (1-\theta)^18
We only need to know the likelihood to the proportionality of theta. \


 h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x
$\theta $
$$\theta $$
### Reference
