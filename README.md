# Topology-of-Diffusion-Models

This repository contains code with some ongoing experiments aimed at understanding how well generative diffusion models learn the underlying topology of the data. Unsurprisingly, the persistence homology seems to be an invariant of a diffusion model, but it is interesting how rigid this invariant is. It is simple to make a diffusion model that generates datapoints that do not lie in the actual distribution, but these models still typically compute the same persistence homology. 

For example, a score based diffusion model seems to learn the underlying homology of the data distrubution even from a small sample size.
