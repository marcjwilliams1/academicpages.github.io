---
title: 'Quantification of subclonal selection in human cancers'
date: 2018-03-06
permalink: /quantifying-selection #/posts/2018/03/quantifying-selection
tags:
  - software
  - publications
---
This post will detail the software used in our recent publication "Quantification of subclonal selection in human cancers". For this publication we used a combination of mathematical and computational modelling, Bayesian inference and bioinformatics. We have tried to make the software/scripts for each of these components freely available (via github) and (hopefully) easy to use so that the results are as reproducible as possible and so that similar analyses can be performed with different datasets.

## Frequentist based rejection of neutral evolution
As part of our study we first wanted to see what parameters of the evolutionary process in cancer we may feasibly be able to see in typical cancer sequencing datasets. Rather than go for the fully Bayesian approach we adopt later (which is very computationally expensive) we developed some new test statistics based on a model of neutral evolution we published previously (Williams et al. Nat Gen. 2016). These test statistics as well as some plotting functionality have been made available in an R package called [neutralitytestr](https://github.com/marcjwilliams1/neutralitytestr).


As an example the package will produce figures like the following.
<figure>
    <img src="{{ site.url }}/images/ng2018/1overftest.png" alt="neutralitytestr plot" width="240px">
</figure>


## Quantifying evolution in human cancers


## Bayesian inference


## Cancer modelling


## Bioinformatics
