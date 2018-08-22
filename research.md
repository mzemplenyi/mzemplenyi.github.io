---
layout: page
title: Research
subtitle: 
---

## Causal mediation analysis 
A large portion of my dissertation work focuses on mediation analysis in the presence of unmeasured confounding or measurement error in the mediator. 

##### (1) Estimation of indirect causal effects of a confounded treatment  
+ **Collaborators:** <a href="https://www.cs.jhu.edu/~ilyas/"> Ilya Shpitser </a> and Eric Tchetgen Tchetgen 
+ **Overview:** The goal of this work is to develop methodology to identify and estimate the extent to which the exposure affects the outcome through an intermediate variable in a setting where the exposure-outcome relation may be subject to unmeasured confounding. This is known as the "population intervention indirect effect". 
+ **Paper:** <a href="https://arxiv.org/abs/1711.03611">Robust inference on indirect causal effects</a> *(Under review)*
+ **Software:** <a href="https://isabelfulcher.github.io/frontdoorpiie/"> R package</a>
+ **Conferences:** [ENAR 2018 presentation](img/enar2018); [ACIC 2018 poster](img/acic2018)

<strong style="font-size: 100%;"> (2) Robust inference on natural indirect effects </strong>  
+ **Collaborators:** Xu Shi and Eric Tchetgen Tchetgen 
+ **Overview:** The goal of this paper is two-fold. First, we show that the natural indirect effect can in fact be identified in the presence of unmeasured exposure-outcome confounding provided there is no additive interaction between the mediator and unmeasured confounder(s). Second, we introduce a new estimator of the natural indirect effect that is robust to both classical measurement error of the mediator and unmeasured confounding of both exposure-outcome and mediator-outcome relations under certain no interaction assumptions.
+ **Paper:** <a href="https://arxiv.org/abs/1711.03611">Estimation of natural indirect effects robust to unmeasured confounding and mediator measurement error</a> *(Under review)*

<strong style="font-size: 100%;"> (3) Mediation analysis with censored survival data </strong>  
+ **Collaborators:** Paige Williams and Eric Tchetgen Tchetgen 
+ **Overview:** Mediation analyses have been extended to survival data. In these settings, specifically under accelerated failure time models, it has been suggested that under standard assumptions, the "difference" and "product" methods produce equivalent estimates of the indirect effect of exposure on the survival outcome. We formally show that these two methods may produce substantially different estimates in the presence of censoring or truncation, due to a form of model misspecification.
+ **Paper:** <a href="http://journals.lww.com/epidem/Citation/2017/09000/Mediation_Analysis_for_Censored_Survival_Data.5.aspx">Mediation Analysis for Censored Survival Data Under an Accelerated Failure Time Model</a> *(Epidemiology)*
+ **Conferences:** [JSM 2017 presentation](img/jsm2017)

## Interference / Network data

<strong style="font-size: 100%;"> Estimation and inference of causal treatment effects on a network </strong>  
+ **Collaborators:** Ilya Shpitser and Eric Tchetgen Tchetgen 
+ **Overview:** The proposed method will allow one to estimate causal effects in vaccine trials for infectious diseases on a network of interconnected indiviudals, while acknowledging complex dependencies in the data. These methods can be applied in a variety of settings in the health and social sciences where network data are available
+ **Paper:** <a href="https://arxiv.org/abs/1709.01577">
Auto-G-Computation of Causal Effects on a Network</a> *(In revision)*
+ **Software:** R package coming soon!  