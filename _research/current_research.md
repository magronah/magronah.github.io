---
layout: single
title: "Current Research"
collection: research
date: "2014-01-01" 
permalink: /research/current_research/
venue: ' '
type: This session contains a list of all current research
location: City, Country
classes: wide
---


### A Reduced Rank Poisson Model for Longitudinal Microbiome Data: Accounting for Taxa Correlations

*Summary* 

Modelling associations between longitudinal microbiome data and other covariates aids in understanding how microbial communities change over time and how these changes differ between treatment groups (eg. control vs. treatment). Such longitudinal microbiome analysis also aid in understanding disease progression in patients and microbial responses to dietary interventions, antibiotics, and environmental changes. Just as in a non-longitudinal microbiome study, taxa within
subjects in a longitudinal design are correlated. Accounting for these correlations may lead to improved precision in effect size estimates. However, modelling these correlations in a longitudinal design is more challenging because taxa can co-vary in different ways over time. Similar to a non-longitudinal design, modeling correlations in longitudinal design also require estimation of thousands or hundreds of parameter estimates for microbiome data, which is computationally impossible to fit. Due to this complexity, most existing models analyze individual taxa separately. In this paper, we propose a Longitudinal Reduced Rank Mixed Model (LRRMM), which extends the Reduced Rank Mixed Model proposed in an earlier paper for non-longitudinal designs. LRRMM is designed to analyze associations between microbiome data and covariates by modeling all taxa jointly, while accounting for correlations among taxa within subjects over time. We used the reduced rank functionality available in the glmmTMB package to reduce the number of parameter estimates required for modeling correlations between taxa. We demonstrate that LRRMM provides more precise estimates of effect sizes compared to both the Negative Binomial and Zero-Inflated Negative Binomial mixed models implemented in the NBZIMM R package.


### Beyond Independence: Joint Modeling of Microbiome Taxa with Reduced-Rank Correlation Structures

*Summary*

Data obtained from hemagglutination-inhibition (HI) assay plays an instrumental role in influenza survellance. The HI data is influenced by two main parameters: antigenic and non-antigenic parameters. A key problem of this data is the presence of non-antigenic parameters which hinder a correct
interpretation of the data. This research shows how antigenic and non-antigenic parameters can be systematically decoupled using a previously published model and the bayesian statistical inference.

