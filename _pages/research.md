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


## Ph.D. research

When modeling real-world data, it is easy to come across datasets that contain inherently non-Gaussian features, such as sudden jumps or spikes. Often, these features adversely affect the inferences and predictions from a latent Gaussian model (LGM). However, methodological and computational challenges hinder the use of more robust latent non-Gaussian models (LnGMs). In this line, my research dealt with:

1. Constructing an intuitive framework that allows extending LGMs to LnGMs.
2. Deriving fast and scalable algorithms to fit the LnGMs, based on variational Bayes and Laplace approximations.
3. Developing easy-to-use tools for Stan and R-INLA to fit these models. 
 
These tools allow users to fit LnGMs by adding a single line of code to previous implementations of LGMs in Stan and R-INLA.

Resources:
- Short vignette on non-Gaussian models, how are they defined and why use them: [Link](https://rawcdn.githack.com/stan-dev/connect22-space-time/9861468cbfcec939c25c88c81693b5055134e7a6/resources/Speaker%203%20-%20Rafael%20Cabral/vignette/stanconnect.html).
- Bookdown with relevant theory and several spatial and temporal models implemented in Stan: [Link](https://rafaelcabral96.github.io/nigstan/).
- Fast and scalable implementation in R-INLA: [Link](https://github.com/rafaelcabral96/ngvb).

Papers: See Publications tab.

### Examples

| ![](/assets/time_series.png)|
|:--:|
| <b>Observations of a quantity related to a patient's kidney function and predictions using an LGM (green) and an LnGM (red).</b>|


This [paper](https://rss.onlinelibrary.wiley.com/doi/10.1111/rssc.12405) considered measurements related to the kidney function of several patients recorded over time. LGMs did not adapt well to sudden drops in measurements, as shown in the previous figure, which was problematic since these drops are an example of “acute kidney injury”, which should prompt an immediate medical intervention. The red curve shows a prediction based on an LnGM, which clearly is more accurate.

| ![](/assets/spatial_2.png)|
|:--:|
| <b>Sample paths of a non-Gaussian Matérn model in two dimensions, driven by normal inverse-Gaussian noise.</b>|


The previous image shows spatial Matérn sample paths driven by non-Gaussian noise with increasing levels of long-tailedness. We can see that that localized spikes start to appear. This feature can be found on several real-world data, such as pressure data (see this [paper](https://projecteuclid.org/journals/bayesian-analysis/advance-publication/Controlling-the-Flexibility-of-Non-Gaussian-Processes-Through-Shrinkage-Priors/10.1214/22-BA1342.full)).

## Other projects

During my Master's degree, I worked with extreme value theory, namely evaluating temporal trends and spatial homogeneity in extremes accounting also for spatial dependence. The methods were used to study precipitation and wind extremes in north-western Germany.

Resources:
- Paper on precipitation extremes: See Publications tab.
- Thesis on wind extremes: [Link](https://drive.google.com/file/d/1Tdhf-0Bn4pg9wLtmiJK43IeaDMgL7Zg3/view?usp=share_link).
- Extended abstract of the thesis: [Link](https://drive.google.com/file/d/1uPfrD7tVOUpLKzbDkx0gbFub0-IRuh9U/view).
