---
layout: page
title: Software
---

## [Colate:](https://github.com/leospeidel/Colate)

Colate ([Speidel et al., *Molecular Biology and Evolution* (2021)](https://doi.org/10.1093/molbev/msab174))  is a fast and scalable method for inferring ancestral relationships through time between low-coverage genomes without requiring phasing or imputation.

The method is available at [https://github.com/leospeidel/Colate](https://github.com/leospeidel/Colate).

## [Relate:](https://myersgroup.github.io/relate/)

Relate ([Speidel et al., *Nature Genetics* (2019)](https://doi.org/10.1038/s41588-019-0484-x)) estimates genome-wide genealogies for sequencing data of thousands of individuals. A genealogy connects present-day samples and their most-recent common ancestors (MRCAs) using historical coalescence, recombination, and mutation events. To reconstruct a genealogy, the MRCA relationships are inferred from present-day samples. In principle, they record all available information about the genetic history of a sample, such that genealogy-based inferences are often very powerful. Relate can be used to estimate historical population sizes and mutation rates, or detect evidence of selective sweeps in a population. 

The method is available at [https://myersgroup.github.io/relate/](https://myersgroup.github.io/relate/).

## [MOSAIC:](https://maths.ucd.ie/~mst/MOSAIC/)

MOSAIC infers ancestry segments and characterizes admixture events, which involve an arbitrary number of genetically differentiated groups coming together. This allows inference of the demographic history of the species, properties of admixing groups, identification of signatures of natural selection, and may aid disease gene mapping. The algorithm employs nested hidden Markov models to obtain local ancestry estimation along the genome for each admixed individual. In a range of simulations, the accuracy of these estimates equals or exceeds leading existing methods that return local ancestry. Moreover, and unlike these approaches, we do not require any prior knowledge of the relationship between sub-groups of donor reference haplotypes and the unseen mixing ancestral populations.

For details and to download the software, visit [https://maths.ucd.ie/~mst/MOSAIC/](https://maths.ucd.ie/~mst/MOSAIC/).

## [HapMix:](http://www.stats.ox.ac.uk/~myers/HapmixReleasev2/)
[Price et al. 2009](http://genetics.med.harvard.edu/reich/Reich_Lab/Software_files/2009_PLoSGenetics_Price_HAPMIX.pdf) uses genotyping data from SNP arrays to infer chromosomal segments of distinct continental ancestry in admixed populations. Source code is being maintained on the Alkes Price lab website and can be downloaded [here](http://www.hsph.harvard.edu/alkes-price/software/)
Write to Simon Myers if you have scientific questions and to Mengyao Zhao if you have questions about the software

## [fineSTRUCTURE:](http://www.maths.bris.ac.uk/~madjl/finestructure/finestructure_info.html)

fineSTRUCTURE and the accompanying ChromoPainter are software applications that utilise dense genetic variation datasets of SNP markers, to explore ancestry relationships among individuals, and to perform Bayesian model-based clustering of individuals into genetically similar populations. The method is suitable for sequencing-based or genotyping array data. This approach has greater fine-scale resolution (e.g. finding structure within countries or continents) than previous algorithms. For details, accompanying manuscript and to download the software, visit [paintmychromosomes.com](http://www.paintmychromosomes.com/).

## [GLOBETROTTER:](http://www.maths.bris.ac.uk/~madjl/finestructure/globetrotter.html)

GLOBETROTTER is an R program, originally described in Hellenthal et al (2014), that can identify, date and describe admixture events occurring in the ancestral history of a given target population within the last ~4,500 years.

Unlike similar programs, it requires no a priori specification of surrogates for the original sources involved in the admixture event(s) in the ancestry of the target population. Instead you provide GLOBETROTTER with DNA information (as summarized by companion program CHROMOPAINTERv2) on multiple sampled groups (or “surrogates”) that may or may not be related to ancestral sources of the target population. GLOBETROTTER then uses these sampled groups to identify whether the target population descends from any admixture event(s), and – if so – it determines precisely when the event(s) occurred and the admixing source groups involved. To describe each original admixing source, GLOBETROTTER provides our “best-guess” of the single sampled surrogate group that genetically best represents the admixing source, but also represents the admixing source as a mixture of the the DNA of all sampled surrogate groups (often many of which are inferred not to contribute to the mixture at all), allowing for a richer characterization and subsequent interpretation.

## [RecMin:](http://www.stats.ox.ac.uk/~myers/RecMin.html)

Under certain assumptions the pattern of diversity at a collection of linked sites provides information allowing us to detect historic recombination events. The program RecMin.c calculates a lower bound on the number of recombination events required to construct any history of a sample, under the assumption that each segregating site has mutated only once since the most recent common ancestor of the sample. Such a lower bound is appropriate, since many historical recombinations are typically undetectable. It gives a measure of what extent the sample history differs from a simple tree structure, and can show if there is regional clustering of the detectable recombinations.

## [STITCH:](https://github.com/rwdavies/STITCH)

STITCH is an R program for reference panel free, read aware, low coverage sequencing genotype imputation. STITCH runs on a set of samples with sequencing reads in BAM format, as well as a list of positions to genotype, and outputs imputed genotypes in VCF format.

STITCH works by modelling each chromosome in the set of samples as a mosaic of K unknown founders or ancestral haplotypes. STITCH employs a hidden Markov model, whose parameters are sequentially updated using expectation maximization. Both steps are handled in a read aware fashion done without using external reference haplotype sets.

Contact Robbie Davies

## [Genetic maps (human recombination rates):](http://www.well.ox.ac.uk/~anjali/AAmap/)

Provides additional material associated with “Hinch et al. The landscape of recombination in African Americans. Nature” available [here](http://www.nature.com/nature/journal/v476/n7359/abs/nature10336.html?lang=en).
