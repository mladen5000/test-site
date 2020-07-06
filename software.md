---
layout: archive
title: Software
image: 
  feature: 
---


### A) MetaLonDA: identifying time intervals of differentially abundant features in metagenomic longitudinal studies
MetaLonDA (METAgenomic LONgitudinal Differential Abundance method) is a method that identifies the significant time intervals of microbial features in longitudinal studies. MetaLonDA has the ability to handle the inconsistencies and common challenges associated with human studies, such as variable sample collection times and uneven number of time points along the subjects’ longitudinal study. The method employs a negative binomial distribution in conjunction with a semi-parametric SS-ANOVA to model the count reads. Then, it performs the significance testing based on unit time intervals using permutation testing procedure.

**Publications:** 
* Metwally AA, Yang J, Ascoli C, Dai Y, Finn PW, Perkins DL, "MetaLonDA: a flexible R package for identifying time 
intervals of differentially abundant features in metagenomic longitudinal studies", Microbiome, 2018. [[paper]](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-018-0402-y)
* Metwally AA, Finn PWF, Dai Y, Perkins DL, "Detection of Differential Abundance Intervals in Longitudinal Metagenomic 
Data Using Negative Binomial Smoothing Spline ANOVA." ACM BCB, 2017. [[paper]](https://dl.acm.org/citation.cfm?id=3107429)


**[MetaLonDA R Package on CRAN](https://CRAN.R-project.org/package=MetaLonDA)**

**[MetaLonDA Source-code on GitHub](https://github.com/aametwally/MetaLonDA)**

<p align="center">
  <img src="../images/metalonda6.jpg">
</p>


<br>

### B) WEVOTE: Weighted Voting Taxonomic Identification Method of Microbial Sequences
WEVOTE (WEighted VOting Taxonomic idEntification) is a method that classifies metagenome shotgun sequencing DNA reads based on an ensemble of existing methods using k-mer based, marker-based, and naive-similarity based approaches. The performance evaluation based on fourteen simulated microbiome datasets consistently demonstrates that WEVOTE achieves a high level of sensitivity and precision compared to the individual methods across different taxonomic levels. The major advantage of the WEVOTE pipeline is that the user can make the choice of which tools to use in order to explore the trade-off between sensitivity, precision, time, and memory. The WEVOTE architecture is flexible so that additional taxonomic tools can be easily added, or the current tools can be replaced by improved ones. Moreover, the score assigned to the taxon for each read indicates the confidence level of the assignment. This information is especially useful for the assessment of false positive annotations at a particular taxonomic level. The classification score given by WEVOTE can be used for any downstream analysis that requires the high confidence of the annotated sequences.

**Publications:** 
* Metwally AA, Dai Y, Finn PW, Perkins DL, "WEVOTE: Weighted Voting Taxonomic Identification Method of Microbial Sequences." PLoS ONE, 2016. [[paper]](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0163527)

**[WEVOTE Source-code on GitHub](https://github.com/aametwally/WEVOTE)**



![WEVOTE](/images/wevote.jpg)
