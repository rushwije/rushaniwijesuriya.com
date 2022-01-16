---
date: "2021-08-11T00:00:00Z"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
slides: example
summary: Doctor of Philosophy - Medicine, Dentistry and Health Sciences
tags:
- Biostatistics
- Multiple Imputation
- Three-level Data
- Missing data
title: PhD thesis
url_code: ""
url_pdf: "http://hdl.handle.net/11343/293059"
url_slides: ""
url_video: ""
---

Three-level data structures are common in modern epidemiological research. The Childhood to Adolescence Transition Study (CATS), where repeated measures from individuals are clustered within schools, is one such example. While almost all research suffer from missing data, it can be particularly problematic in longitudinal cohorts.Although MI is a popular approach for handling missing data, its validity depends on appropriate tailoring of the imputation model to the substantive analysis, so as to ensure congeniality between the imputation and analysis models. In the context of a three-level substantive analysis with incomplete data, this means the imputation model should account for the multilevel structure, in addition to any other features in the substantive analysis such as non-linear relationships and/or interaction effects.  

A number of MI approaches including (i) pragmatic adaptations of the widely accessible single-level MI approaches using dummy indicators (DIs) for the higher-level clusters and imputing repeated measures in wide format, (ii) pragmatic adaptations of two-level MI approaches with DIs for the higher-level clusters or imputing repeated measures in wide format, and (iii) MI approaches using three-level imputation models, can be used to handle incomplete three-level data. However, there are limited evaluations of these approaches in the literature. In particular, with complex substantive analyses involving interactions, non-linear terms, and time-varying higher-level cluster memberships conducting MI appropriately ensuring congeniality remains challenging.

The current research investigated the performance of MI approaches for handling incomplete three-level data, to provide guidance in the contexts of: a three-level random intercept model, a three-level random intercept model involving interactions or non-linear terms, and a static-effects cross-classified random effects model (CCREM) accounting for time-varying higher-level cluster memberships. In each context, the MI approaches were implemented using joint modelling (JM) and fully conditional specification (FCS). Substantive model compatible (SMC) MI that automatically tailors the imputation model to the substantive analysis, was also considered where relevant. The approaches were evaluated using simulation studies based on CATS, conducted under a number of scenarios by varying factors such as the number of clusters, cluster sizes, missing data proportions, missing data mechanisms and the intra-cluster correlations (ICCs). The methods were also illustrated using CATS data. 

Results indicated the pragmatic adaptations of the standard single-level MI approaches are adequate for handling incomplete three-level data in most substantive analyses, namely when the substantive analysis is a random intercept only model, a random intercept model with an interaction between the time-varying exposure and time, or a static-effects CCREM.  However, in each substantive setting if the data are sparse due to large amounts of missing data and/or small cluster sizes, or the ICCs are small, the two-level MI approaches imputing repeated measures in wide format or three-level MI approaches should be used, with the latter being the only option if the repeated measures are also irregularly measured. If the analysis model contains interactions between the time-varying exposure and baseline variables or non-linear terms, the three-level SMC-MI approach (available in software Blimp) is recommended. 

The findings of this PhD provide initial guidance on how best to impute incomplete three-level data in three different substantive contexts. Further evaluation of these approaches across a range of contexts and studies are needed to develop guidance in other settings.