---
title: "Predicting"
layout: about
image: /assets/images/Math_1.jpg
---

The historical data collected from Detroit Lake includes measurements of temperature, humidity, wind
speed, nutrient levels, algal and toxin concentrations. Now the question is, what can be done with
these data? Methods from applied mathematics and computer science, for example Machine Learning,     have been used for predicting harmful algal blooms in other lakes (here in the US, and around the    world). Our goal is to use these cutting edge methods to predict harmful algal blooms in Detroit     Lake, and also advance new algorithms to give us the best possible predictions. Importantly, the City of Salem asked for three products:

1) Predictions: from daily to weekly predictions of algal concentrations and toxin levels in the     lake

2) Estimates of uncertainty: for any risk management problem, like managing the impacts of harmful   algal blooms, requires estimates of uncertainty. That is, predictions of algal concentrations a week
from now should also be accompanied by a probability of this happening.

3) Informed sampling: this is where the mathematical models can help identify the key       processes creating a harmful algal bloom in Detroit Lake. This will help in deciding where to go and
when, to collect water for analysis.

Our solution for achieving these goals was to use a well-tested mathematical approach for predicting  harmful algal blooms -- [Bayesian Model Averaging](https://docs.pymc.io/notebooks/model_averaging.html) -- as well as develop a new approach from Machine Learning, called [Bayesian Neural Networks](https://medium.com/neuralspace/bayesian-neural-network-series-post-1-need-for-bayesian-networks-e209e66b70b2). The two approaches complement each other, and explicitly target the three goals above: predictions with estimates of uncertainty, and information that can be used to direct future sampling. For a detailed description of the mathematical and Machine Learning approach we have created for Detoit Lake, we are developing a technical whitepaper that will be published soon.





