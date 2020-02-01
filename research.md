---
layout: page
title: Research
permalink: /research/
---

### Integrating common and rare variant genetics to understand primary immunodeficiency.

I am an analyst on the [NHBR-RD](https://bioresource.nihr.ac.uk/rare-diseases/rare-diseases/) primary immunodeficiency (PID) cohort. I was responsible for analytical strategies for prioritising rare, highly penetrant non-coding variants that might modulate PID risk, where I used a combination of epigenetic and PCHi-C data in order to prioritise candidates. To identify novel coding variants responsible for PID, I used and integrative approach, first finding that common PID variants were enriched in certain immune-mediated diseases, and then developing a prioritisation strategy based on these relationships to suggest genes that might contain a rare causal variant. This identified two candidates that were subsequently functionally validated, thus providing not only novel causes of PID but shedding light on the function of these genes and how this might pertain to more common immune-mediated disease phenotypes. This work is under review but a preprint is available [here](https://doi.org/10.1101/499988).

### Shared and distint genetic architectures in immune-mediated disease.

Whilst GWAS has been transformative in complex diseases where cohorts with sufficient sample size are available, its application to rarer diseases is more problematic. Working with Chris Wallace, I have developed a method for deriving a lower-dimensional representation of the association patterns across a group of related traits. Rarer or more clinically heterogeneous diseases can then be projected into this space in order to learn how they relate to the original traits. I have used immune-mediated diseases (e.g. Type 1 diabetes, Crohn's disease etc.) to build such a representation and then investigated how it can be used to shed light on rarer immune-mediated diseases (e.g. Juvenile dermatomyositis, Neuromyelitis optica) or clinically heterogeneous diseases (e.g. Juvenile idiopathic arthritis, ANCA associated vasculitis). This work is under review but a preprint is available [here](https://www.biorxiv.org/content/10.1101/2020.01.14.905869v2).


###  Integrating Promoter Capture Hi-C (PCHI-C) with GWAS summary statistics to prioritise candidate disease genes and tissues.

We tend to  think of DNA as a linear sequence, however it a has complex and dynamic three dimensional structure that is important to function. In order to better understand its role in gene regulation and haematopoeisis [Peter Fraser's](http://www.babraham.ac.uk/our-research/nuclear-dynamics/peter-fraser) group has generated high resolution interaction maps detailing high confidence promoter interactions across 17 primary human cell types.  In collaboration with Chris Wallace, I have developed [statistical methods](https://github.com/ollyburren/rCOGS) to use these maps to connect putative risk variants in 32 publicly available GWAS studies to causal genes and tissues  described in more detail [here](https://www.sciencedirect.com/science/article/pii/S0092867416313228) In order to facilitate access to these datasets we have developed a novel tool - [CHiCP](http://bioinformatics.oxfordjournals.org/content/early/2016/04/08/bioinformatics.btw173.abstract).

### Understanding the genomics of CD4+ T Cell activation and their role in autoimmunity.

Previous autoimmune disease research has hilighted the importance of CD4+ T cell activation in disease pathology. Working collaboratively with Chris Wallace, Tony Cutler, Arcadio Rubio Garcia, Linda Wicker and John Todd we sought to better understand the genomics of this process in humans by carrying out deep genomic phenotyping of pooled samples of matched CD4+ activated and nonactivated T cells that included CHiP-Seq, total RNA-Seq and PCHi-C. We used this rich dataset to characterise the genomic events that underpin the activation process and used cutting edge fine mapping techniques to link causal variants in autoimmune disease to prioritise causal genes and tissue contexts. The results of this study are described in detail [here](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-017-1285-0).

### ImmunoBase - A curated database for the genetics of autoimmune disease susceptibility.

Working with Tim Carver, Ellen Schofield and Prem Acuthan, we have developed a database that brings together carefully curated content of the genetics of autoimmune susceptibility. This includes full summary statistics for a number of autoimmune disease GWAS and ImmunoChip studies. With the  departure of John Todd's group to Oxford this project has been taken on by [OpenTargets](https://genetics.opentargets.org/immunobase).
