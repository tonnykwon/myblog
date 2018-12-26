---
title: "Normal Samples"
permalink: /bayesian/
date: 2018-12-22 15:24:00 -0400
categories: Bayesian
---
## Frequentist
Suppose we roll a fair dice. Then, P(6) indicates the probability of getting 6. In frequentist view, we see relative frequency of events. In case of the dice, we can think about rolling dice infinite number of times. If it is a fair dice, P(6) equals 1/6. \
Thus, in the frequentist paradigm, it tries to be objective in defining probabilities.

## Bayesian
On the contrary, bayesian paradigm defines probabilities in personal perspective. For instance, P(6) may be different, if you have different information. That is P(6) would be a random variable between 0 and 1, and, based on your data of rolling dice, you update the probability of getting 6.

### Notation
y = *data* (observed) \
&theta; = *parameter* \
In Bayesian analysis, &theta; is considered to be random. It represents uncertainty about its value.\

$$&p(\theta)$$ 
*prior distribution*: marginal distribution of &theta;. Our state of knowledge(uncertainty) prior to observing y. \

$$&p(y|\theta)$$ 
*sampling distribution*: conditional distribution of y given &theta;. How the data would be generated when &theta; is given. \

$$&p(\theta | y)$$ 
*posterior distribution*: conditional distribution of &theta; given y.

### Bayes' Rule
Derive posterior distribution from the Bayesian model: \
$$&p(\theta |y) = \frac{p(\theta, y)}{p(y)} = \frac{p(\theta)p(y|\theta)}{p(y)} $$
p(y) is called *normalizing factor* as it makes $p(\theta|y) $ is a density in $\theta$ \

 h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x
$\theta $
$$\theta $$
### Reference
