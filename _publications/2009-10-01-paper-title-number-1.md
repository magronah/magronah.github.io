---
title: "Beyond Independence: Joint Modeling of Microbiome Taxa with Reduced-Rank Correlation Structures"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: ' '
date: 2025-10-01
venue: 'Forthcoming paper currently a manuscript'
paperurl: 'https://drive.google.com/file/d/1QPBL-SiFVFI4tRrrotIKdsY2d62r50m5/view?usp=drive_link'
citation: ' '
---

# Abstract

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