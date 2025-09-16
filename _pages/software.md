---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

## LaMa

<img src ="../images/Logo_LaMa_surf.png" align = "right" width = "180"/>

I wrote the R package `LaMa` for flexible model building and fast estimation of **latent Markov models**. It makes building such models much more convenient (kinda feels like stacking lego blocks) and allows for significant speed gains, so give it a try!

* Check out the package website <a href = "https://janoleko.github.io/LaMa/" target = "_blank">here</a>
* or get started with the vignette <a href = "https://janoleko.github.io/LaMa/articles/Intro_to_LaMa.html" target = "_blank">Intro to LaMa</a>
* The package is motivated by the unification of various latent Markovian models developed in <a href = "https://arxiv.org/abs/2406.19157" target = "_blank">this paper</a>

## RTMBdist

<img src ="https://github.com/janoleko/RTMBdist/blob/master/man/figures/RTMBdist_hex.png" align = "right" width = "160"/>

I created the R package `RTMBdist`, a library of probability distributions compatible with automatic differentiation delivered by the <a href = "https://kaskr.r-universe.dev/RTMB" target = "_blank">`RTMB`</a> package. 
While `RTMB` allows flexible, fast likelihood-based modelling in R, many existing distributions break automatic
differentiation. `RTMBdist` fills this gap, enabling reliable and efficient model development.

* Check out the package website <a href = "https://janoleko.github.io/RTMBdist/" target = "_blank">here</a>
* <a href = "https://github.com/janoleko/RTMBdist" target = "_blank">Github</a>

## EgoCor
I assisted <a href = "https://www.uni-bielefeld.de/fakultaeten/wirtschaftswissenschaften/lehrbereiche/stats/team/julia-dyck-(m.sc.)/" target="_blank">Julia Dyck</a> in developing the R package `EgoCor` as a user-friendly interface based on the R package `gstat` to fit exponential parametric models to empirical semi-variograms to model the spatial correlation structure of health data.

* <a href = "https://cran.r-project.org/web/packages/EgoCor/index.html" target="_blank">CRAN</a>
* <a href = "https://github.com/julia-dyck/EgoCor" target = "_blank">Github</a>
* <a href = "https://arxiv.org/abs/2309.12979" taget = "_blank">Publication</a>
