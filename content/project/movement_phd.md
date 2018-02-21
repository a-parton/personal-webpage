+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Inference for continuous-time movement"

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "reind_corner.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["animal-movement"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "recon.jpg"
caption = "Reconstructed reindeer movement"

+++
## Bayesian inference for continuous-time step-and-turn movement models with noisy observations.
**PhD thesis: 2014-2018.**

* Paul Blackwell (supervisor)

This PhD thesis concerns the statistical modelling of animal movement paths given observed GPS locations. With observations being in discrete time, mechanistic models of movement are often formulated as such. This popularity remains despite an inability to compare analyses through scale invariance and common problems handling irregularly timed observations. A natural solution is to formulate in continuous time, yet uptake of this has been slow, often excused by a difficulty in interpreting the `instantaneous' parameters associated with a continuous-time model. 

The aim here was to bolster usage by developing a continuous-time model with interpretable parameters, similar to those of popular discrete-time models that use turning angles and step lengths to describe the movement process. Movement is defined by a continuous-time, joint bearing and speed process, the parameters of which are dependent on a continuous-time behavioural switching process, thus creating a flexible class of movement models. Further, we allow for the observed locations derived from this process to have unknown error. Markov chain Monte Carlo inference is presented for parameters given irregular, noisy observations. The approach involves augmenting the observed locations with a reconstruction of the underlying continuous-time process. 

Example implementations showcasing this method are given featuring simulated and real datasets. Data from elk (*Cervus elaphus*), which have previously been modelled in discrete time, demonstrate the interpretable nature of the model, finding clear differences in behaviour over time and insights into short-term behaviour that could not have been obtained in discrete time. Observations from reindeer (*Rangifer tarandus*) reveal the effect observation error has on the identification of large turning angles---a feature often inferred in discrete-time modelling. Scalability to realistically large datasets is shown for lesser black-backed gull (*Larus fuscus*) data.