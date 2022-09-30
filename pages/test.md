---
layout: page
title: Software Packages
---

[**DASE**](https://github.com/tenglab/DASE)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/sedynamics.jpg">

An R/GitHub package for detecting internal structural alterations of super 
enhancers (SE) based on ChIP-seq data. Four types of internal alterations
in addition to overall activity changes of SEs can be identified with this
tool. In our publication, we have demostrated the distinct functional 
[characteristics of the different SE alterations](https://doi.org/10.1093/nar/gkac141).
This tool has high sensitivity on detecting SE internal alterations, 
thus is highly recommended if you are interested in comparing super 
enhancer profiles between similar cell conditions.

---

[**gcapc**](https://bioconductor.org/packages/gcapc/)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/gccontent.jpg">
 
An R/Bioconductor package for ChIP-seq peak calling with adjustment of
GC-content bias. GC-content bias is firstly estimated with [generalized
linear mixture models](https://doi.org/10.1101/gr.220673.117) using 
effective GC strategy, then applied to the estimation of peak enrichment.
This package also provides alternative option to correct GC-content 
bias for a given list of genomic regions across multiple samples. 
Package is also [available on GitHub](https://github.com/tenglab/gcapc).

---

[**rnaseqcomp**](https://bioconductor.org/packages/rnaseqcomp)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/rnaseqbenchmark.jpg">

An R/Bioconductor package providing evaluation and visualization of several
quantitative [benchmarks for RNA-seq quantification](https://doi.org/10.1186/s13059-016-0940-1)
pipelines, accompanied with [an easy-to-use
web tool](http://rafalab.rc.fas.harvard.edu/rnaseqbenchmark).
Quantifications of genes, transcripts, junctions or exons in two compared
conditions by each pipeline with necessary meta information should be
organized into numeric matrices in order to proceed with the evaluation.
Package is also [available on GitHub](https://github.com/tenglab/rnaseqcomp).

---

[**regSNPs**](https://github.com/tengmx/regSNPs)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/regsnps.jpg">

An R implemented computational algorithm that integrates several established
bioinformatics tools for [prioritizing regulatory SNPs](https://doi.org/10.1093/bioinformatics/bts275),
i.e., the SNPs in the promoter regions that potentially affect phenotype
through transcription alteration. regSNPs considers degenerative features
of binding motifs. It calculates the differences on transcription factor
binding affinity caused by candidate variants and integrates potential
phenotypic effects of various transcription factors.
