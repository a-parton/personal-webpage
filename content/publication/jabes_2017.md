+++
title = "Bayesian inference for multistate ‘step and turn’ animal movement in continuous time"
date = "2017-06-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**A. Parton**", "P.G. Blackwell"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Journal of Agricultural, Biological and Environmental Statistics (JABES)"
publication_short = "In *JABES*"

# Abstract and optional shortened version.
abstract = "Mechanistic modelling of animal movement is often formulated in discrete time despite problems with scale invariance, such as handling irregularly timed observations. A natural solution is to formulate in continuous time, yet uptake of this has been slow. This lack of implementation is often excused by a difficulty in interpretation. Here we aim to bolster usage by developing a continuous-time model with interpretable parameters, similar to those of popular discrete-time models that use turning angles and step lengths. Movement is defined by a joint bearing and speed process, with parameters dependent on a continuous-time behavioural switching process, creating a flexible class of movement models. Methodology is presented for Markov chain Monte Carlo inference given irregular observations, involving augmenting observed locations with a reconstruction of the underlying movement process. This is applied to well-known GPS data from elk (*Cervus elaphus*), which have previously been modelled in discrete time. We demonstrate the interpretable nature of the continuous-time model, finding clear differences in behaviour over time and insights into short-term behaviour that could not have been obtained in discrete time."
abstract_short = "Methodology is presented for Markov chain Monte Carlo inference given irregular observations of a multi-state, continuous-time movement process, involving augmenting observed locations with a reconstruction of the underlying movement process. This is applied to well-known GPS data from elk (*Cervus elaphus*), which have previously been modelled in discrete time."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["movement_phd"]
tags = ["animal-movement"]

# Links (optional).
url_pdf = "https://link.springer.com/article/10.1007/s13253-017-0286-5"
url_project = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "jabes.jpg"
caption = "Reconstructing step-and-turn movement"

+++

