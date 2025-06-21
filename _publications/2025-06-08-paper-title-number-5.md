---
title: "A Reduced Rank Poisson Model for Longitudinal Microbiome Data: Accounting for Taxa Correlations"
collection: publications
category: manuscripts
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: ' '
date: 2025-02-17
venue: 'Forthcoming paper currently a manuscript'
paperurl: 'https://drive.google.com/file/d/11t-2Tn-PpUDdEP4nJbXW3GSRvnBV4Fb_/view?usp=sharing'
citation: ' '
---

# Abstract 
Modelling associations between longitudinal microbiome data and other covariates aids in understanding how microbial communities change over time and how these changes differ between treatment groups (eg. control vs. treatment). Such longitudinal microbiome analysis also aid in understanding disease progression in patients and microbial responses to dietary interventions, antibiotics, and environmental changes. Just as in a non-longitudinal microbiome study, taxa within
subjects in a longitudinal design are correlated. Accounting for these correlations may lead to improved precision in effect size estimates. However, modelling
these correlations in a longitudinal design is more challenging because taxa can
co-vary in different ways over time. Similar to a non-longitudinal design, modeling correlations in longitudinal design also require estimation of thousands or
hundreds of parameter estimates for microbiome data, which is computationally
impossible to fit. Due to this complexity, most existing models analyze individual taxa separately. In this paper, we propose a Longitudinal Reduced Rank
Mixed Model (LRRMM), which extends the Reduced Rank Mixed Model pro-
posed in an earlier paper for non-longitudinal designs. LRRMM is designed to
analyze associations between microbiome data and covariates by modeling all
taxa jointly, while accounting for correlations among taxa within subjects over
time. We used the reduced rank functionality available in the glmmTMB package
to reduce the number of parameter estimates required for modeling correlations
between taxa. We demonstrate that LRRMM provides more precise estimates of
effect sizes compared to both the Negative Binomial and Zero-Inflated Negative
Binomial mixed models implemented in the NBZIMM R package.

