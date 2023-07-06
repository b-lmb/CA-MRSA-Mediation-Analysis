# CA-MRSA_Mediation

This paper used the difference method for regressions with a binary outcome as outlined by VanderWeele, 2016 (https://www.annualreviews.org/www.annualreviews.org/doi/full/10.1146/annurev-publhealth-032315-021402#_i21) implemented in R-INLA to account for spatial dependency.

The main hypothesis is that area-level poverty is associated with CA-MRSA presenting in California Emergency Departments and can be mediated or explained through other area-level predictors. The outcome is observed at the individual level, and we have information available at a higher level of aggregation (MSSA) (2-2-1 mediation analysis)

This paper’s objectives are as follows:

1) Fit a Bayesian multilevel model with area-level as the main covariate where the outcome is observed at the individual level
2) Evaluate the influence of three potential mediators by including group-level covariates
3) Examine the influence of spatial autocorrelation

   
