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

### Too Few or Too Many? Sample Size Estimation for Differential Abundance Studies

*Summary* 

Determining an appropriate sample size for a study is a crucial step in planning scientific research. Appropriate sample
sizes avoid both inflated and inadequate sample sizes. Collecting too many samples wastes resources, time and effort of human subjects, and lives of experimental animals. Collecting too few samples, a much more common problem, wastes even more resources through the inability to detect biologically meaningful differences and encourages questionable research practices like p-hacking. Microbiome studies are particularly challenged by sample size, particularly in studies of human subjects or expensive animal models. In practice, the statistical power of taxa within a differential abundance study is influenced by the effect size (fold change), mean abundance of individual taxa and the number of samples. We present a novel approach for sample size calculation for differential abundance studies as a function of effect size, mean abundance and statistical power. We applied our model for sample size calculation using estimates of mean abundance and fold change of taxa obtained from real microbiome data. Our results showed that differential abundance microbiome studies require larger sample sizes than are currently prevalent in the literature to achieve adequate statistical power. Our framework will help researchers make informed decisions about appropriate sample sizes. 

### A Reduced Rank Poisson Model for Longitudinal Microbiome Data: Accounting for Taxa Correlations

*Summary* 

Modelling associations between longitudinal microbiome data and other covariates aids in understanding how microbial communities change over time and how these changes differ between treatment groups (eg. control vs. treatment). Such longitudinal microbiome analysis also aid in understanding disease progression in patients and microbial responses to dietary interventions, antibiotics, and environmental changes. Just as in a non-longitudinal microbiome study, taxa within
subjects in a longitudinal design are correlated. Accounting for these correlations may lead to improved precision in effect size estimates. However, modelling these correlations in a longitudinal design is more challenging because taxa can co-vary in different ways over time. Similar to a non-longitudinal design, modeling correlations in longitudinal design also require estimation of thousands or hundreds of parameter estimates for microbiome data, which is computationally impossible to fit. Due to this complexity, most existing models analyze individual taxa separately. In this paper, we propose a Longitudinal Reduced Rank Mixed Model (LRRMM), which extends the Reduced Rank Mixed Model proposed in an earlier paper for non-longitudinal designs. LRRMM is designed to analyze associations between microbiome data and covariates by modeling all taxa jointly, while accounting for correlations among taxa within subjects over time. We used the reduced rank functionality available in the glmmTMB package to reduce the number of parameter estimates required for modeling correlations between taxa. We demonstrate that LRRMM provides more precise estimates of effect sizes compared to both the Negative Binomial and Zero-Inflated Negative Binomial mixed models implemented in the NBZIMM R package.


### Beyond Independence: Joint Modeling of Microbiome Taxa with Reduced-Rank Correlation Structures

*Summary*

Human microbiome data is crucial for understanding the mechanism of diseases and treatment
effectiveness. Researchers often aim to describe how counts of taxa differ among discrete groups
(such as control versus treatment) or according to other factors. Most existing models analyze
each taxon separately, assuming no correlation between taxa within an individual. In reality,
counts of taxa within subjects are correlated. Treating these counts as independent ignores the
underlying biological structure in the data and may make it harder to accurately estimate changes
in abundances of particular taxa. We developed a model that jointly models all taxa, accounting
for the correlations between them. Typical microbiome datasets contain hundreds or thousands
of taxa and require thousands or even millions of parameter estimates for the variance-covariance
matrix, making it computationally impractical. To address this, we applied rank reduction to the variance-covariance matrix, reducing the number of parameter to be estimated. We conducted
simulation studies and real data analysis, comparing our reduced-rank model with three existing
models: the negative binomial model in the DESeq R package, and the the negative binomial
mixed and zero-inflated negative binomial mixed models in the NBZIMM R package. Our results
show that modeling all taxa together and accounting for correlations between taxa improves
accuracy in effect estimates, reduces bias, narrows confidence intervals, and increases statistical
power compared to modeling taxa independently.
