---
layout: page
title: Software Packages
---

More code/packages listed on our [GitHub](https://github.com/tenglab) page
<br><br>

[**qcCHIP**](https://github.com/tenglab/qcCHIP)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/qcchip.jpg">

An R/GitHub package for [estimating quality parameters and filtering
clonal hematopoiesis variants from WES- or targeted-DNAseq-based
mutation calls](https://doi.org/10.1093/bioinformatics/btaf522). The
tool first uses permutation test to determine the optimal parameter
values for a given dataset in CHIP filtering, *e.g.*, VAF cutoffs. It
then implements CH filtering using four groups of data metrics. We
demonstrated its precision and recall by applying it to sequencing
data cohorts across multiple solid cancer types in the ORIEN Network.

---

[**cSEAdb**](https://github.com/tenglab/cSEAdb)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/cancerse.jpg">

An R/GitHub package documenting [high-resolution differences of super 
enhancer (SE) signatures across
cancers](https://doi.org/10.1371/journal.pcbi.1011873). The
sensitivity and specificity of cancer-specific SE identification are
boosted by using mixture
models to evaluate SE consensuses across 60 cell lines from 28 cancer
types. Both cancer-specific-active and -inactive components of SEs are
profiled here, enabling a pan-cancer systematic overview. Visualizing
interface is built in the package to facilitate exploration. 

---

[**DASE**](https://github.com/tenglab/DASE)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/sedynamics2.jpg">

An R/GitHub package for detecting constitutive alterations of super
enhancers (SE) using ChIP-seq. Four novel types of constitutive
alterations as well as overall activity alterations are reported by
this tool. Constitutive alterations usually demonstrate [distinct
functional characteristics](https://doi.org/10.1093/nar/gkac141) in
the way they regulate target genes. This tool elevates the sensitivity
in detecting SE profile changes. It is highly recommended when SE
profiles of similar cell conditions are compared.

---

[**gcapc**](https://bioconductor.org/packages/gcapc/)

<img style="float:right;margin: 0 30px 0 0;width:300px;height:150px;"
src="/assets/themes/twitter/bootstrap/img/gccontent2.jpg">
 
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

An R-based algorithm that integrates multiple
bioinformatics tools/databases for [prioritizing regulatory SNPs](https://doi.org/10.1093/bioinformatics/bts275),
i.e., the SNPs in the promoter regions that potentially affect phenotype
through transcription disruption. regSNPs considers degenerative features
of transcription factor (TF) binding motifs. It calculates SNP-caused
alterations of TF binding and integrates that with the phenotypic effects of
the altered TFs. 
