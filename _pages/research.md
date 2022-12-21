---
title: "Research"
permalink: /research/
author_profile: yes
output:
  html_document:
    df_print: paged
---

My research interest are mainly in Applied and Computational Statistics:
 - Spatial and temporal models
 - Gaussian and non-Gaussian stochastic processes
 - Approximate inference with Markov Chain Monte Carlo, Variational Bayes, and Laplace approximations
 - Statistical robustness and model checking


### Ph.D. research

It is easy to find datasets that contain inherently non-Gaussian features, such as sudden jumps or spikes, that adversely affect the inferences and predictions made from a latent Gaussian model (LGM). 
However, methodological challenges prevent more robust latent non-Gaussian models (LnGMs) from being part of mainstream statistical practice. In this line, my research dealt with the following developments:

1. Intuitive framework that allows extending LGMs to LnGMs.
2. Fast and scalable algorithms to fit the LnGMs.
3. Easy-to-use software.

Resources:
- Short vignette on non-Gaussian models, how are they defined and why use them. [Here](https://rawcdn.githack.com/stan-dev/connect22-space-time/9861468cbfcec939c25c88c81693b5055134e7a6/resources/Speaker%203%20-%20Rafael%20Cabral/vignette/stanconnect.html)
- Bookdown with theory and several spatial and temporal models implemented in Stan. [Here](https://rafaelcabral96.github.io/nigstan/)
- Fast and scalable implementation in R-INLA. [Here](https://github.com/rafaelcabral96/ngvb)

Papers: See Publication section

### Other projects

During my Master's degree, I also worked with extreme value theory, namely evaluating temporal trends and spatial homogeneity in extremes accounting also for spatial dependence. 
The methods were used to study precipitation and wind extremes in north-western Germany.

Paper on precipitation extremes: See Publication section
Thesis on wind extremes: [Here](https://drive.google.com/file/d/1Tdhf-0Bn4pg9wLtmiJK43IeaDMgL7Zg3/view?usp=share_link)
Extended abstract of the thesis: [Here](https://drive.google.com/file/d/1uPfrD7tVOUpLKzbDkx0gbFub0-IRuh9U/view)
