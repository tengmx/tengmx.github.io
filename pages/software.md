---
layout: page
title: Software Packages
---

#### In Release

- [**ComplexDiff**](https://github.com/tengmx/ComplexDiff) - 
An R-package to normalize and estimate differential DNA bindings
of protein complexes with ChIP-seq data. This package considers several
unique features of protein complexes and provides better performance compared
to tools developed for generic differential binding analysis.

- [**gcapc**](https://bioconductor.org/packages/gcapc/) - 
An R/Bioconductor package for ChIP-seq peak calling with adjustment of
potential GC-content bias. GC bias is first estimated with generalized
linear mixture models using effective GC strategy, then applied into 
peak significance estimation. The package also provides option to remove
GC bias for a given list of genomic sites. Package is also available 
on [GitHub](https://github.com/tengmx/gcapc).

- [**rnaseqcomp**](https://bioconductor.org/packages/rnaseqcomp) - 
An R/Bioconductor package providing evaluation and visualization of several
quantitative benchmarks for RNA-seq quantification pipelines, accompanied with an
easy-to-use [web tool](http://rafalab.rc.fas.harvard.edu/rnaseqbenchmark).
Quantifications of genes, transcripts, junctions or exons in two compared
conditions by each pipeline with necessary meta information should be
organized into numeric matrices in order to proceed the evaluation.
Package is also available on [GitHub](https://github.com/tengmx/rnaseqcomp).

- [**regSNPs**](https://github.com/tengmx/regSNPs) -
An R implemented informatics strategy that integrates several established
bioinformatics tools for prioritizing regulatory SNPs, i.e. the SNPs 
in the promoter regions that potentially affect phenotype through 
changing transcription of downstream genes. regSNPs considers degenerative
features of binding motifs by calculating the differences on the binding
affinity caused by the candidate variants and integrates potential
phenotypic effects of various transcription factors.
