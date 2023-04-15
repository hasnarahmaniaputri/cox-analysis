## Survival Analysis
Survival analysis is one of the statistical procedure for data analysis for which the outcome variable of interest is time until an event occurs. Event can refer
to death, disease, recovery, or any designated experience that happen to an individual.
We have three options for modeling the survival function: parametric, semiparametric, and nonparametric.

A parametric model is one in which survival time is assumed to follow a known distribution (exponential, weibull, lognormal, etc).
In a nonparametric model, we make no assumptions about the functional form of hazard. The Kaplan–Meier Curve is the Maximum Likelihood Estimator in this case. It is a little bit like using a scatter plot to understand the effect of a covariate.
This repository will be discussing Cox Proportional Hazards (PH) as a semiparametric model. This approach is referred to as a semiparametric because while the hazard function is estimated nonparametrically, the functional form of the covariates is parametric.
Cox PH regression is popular because the results from using the Cox model will closely approximate the results for the correct parametric model
