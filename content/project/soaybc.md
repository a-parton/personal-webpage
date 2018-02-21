+++
# Date this page was created.
date = "2016-04-27"
  
# Project title.
title = "Inference via ABC for the Soay sheep population"
  
# Project summary to display on homepage.
summary = ""
  
# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "soay.jpg"
  
# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["soay-abc"]
  
# Optional external URL for project (replaces project detail page).
external_link = ""
  
# Does the project detail page use math formatting?
math = false
  
# Optional featured image (relative to `static/img/` folder).
[header]
image = "sheep_model.jpg"
caption = "A dynamic energy budget model"
  
+++

## Individual energy budgets, life histories and population dynamics in natural populations.
**Leverhulme Research Project Grant (RPG-2015-049): 2016-2019.**

* Paul Blackwell
* Dylan Childs (Primary Investigator)
* Mark Rees

All animals must acquire energy by consuming food, which is then allocated to different physiological processes such as growth, reproduction and tissue maintenance. Patterns of resource allocation over an organism’s lifetime determine their life history -- the age of maturation, frequency of reproduction, size and number of offspring produced, and so on, through to age-at-death. Allocation strategies therefore underpin the demography (rates of mortality and reproduction) and hence, Darwinian fitness of individuals. Since resources are finite and take time and energy to acquire, evolution should optimize allocation decisions, effectively trading off the costs and benefits associated with different components of fitness to maximize the success of individuals.

In a population context, organisms must compete with one another for limited resources. These resources inevitably fluctuate through time in response to environmental conditions and changes in the number and composition of competing individuals. This creates environment-mediated interdependencies between the life history of individuals, changes in abundance (i.e. population dynamics), and natural selection. Ecologists have developed a rich array of models, collectively known as Physiologically Structured Population Models, to explore these kinds of relationships. An important class of such models uses fundamental principles of bioenergetics to link individual- and population-level processes. The resulting theory has provided insight into many different phenomena of fundamental and applied importance, such as the emergence of population cycles, mechanisms of population regulation, and consequences of harvesting.

The goal of this project is to apply an underused statistical approach known as Approximate Bayesian Computation (ABC) to (formally) learn about the processes governing the individual energy budget and population dynamics of a model ungulate, the feral Soay sheep of St Kilda, Scotland. This well-studied population is thought to be experiencing, and responding to, changes in climate and vegetation. We aim to construct a data-driven Physiologically Structured Population Model (PSPM) for the Soay sheep using an ABC approach. We will then analyze the resulting model using tools from demography and mathematical evolutionary biology. Ultimately, this will enable us to investigate the fundamental mechanisms determining the life history and population dynamics of Soays, as well as explore the past and future consequences of environmental variation.

We will meet two broad objectives to address our aims. Our first is to develop a robust ABC framework to estimate the parameters of PSPMs from observational data. To achieve this we will: 1) construct a suite of computer simulation models that use bioenergetics principles to encode key features of ungulate life histories and population dynamics; 2) use ABC methodology to estimate and quantify uncertainty in the parameters of these models, using over 30 years of individual- and population-level census data from the St Kilda population. We will then use the resulting model as a research tool to understand our system. Our second objective is therefore, to investigate how environmental variation and competition for food structure population dynamics. To achieve this we will: 1) determine how environmental variation influences the dynamics of trait variation and population abundance, 2) predict how future changes in climate and vegetation productivity may influence the ecology and evolution of our model system.