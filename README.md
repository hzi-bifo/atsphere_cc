
scripts to reproduce the analysis and figures from Bai et al., 2015

originally by Ruben Garrido-Oter
garridoo@mpipz.mpg.de


This folder contains all scripts necessary to reproduce the results 
obtained from the 16S rRNA profiling of natural communities and isolated
bacterial cultures presented in Bai et al., 2015. It consists of the
following steps:

1. Independent procesing from the different 16S rRNA datasets:

    - current study analysis of root natural communities
    - current study profiling of leaf natural communities
    - Bulgarelli et al., 2012 and Schaeppi et al., 2014 16S datasets (root)
    - Horton et al., 2014 dataset (leaf)
    - profiling of isolated baceterial cultures (root & leaf).

2. Calculation of recovery rates of the root and leaf core culture
collections (At-RSPHERE and At-LSPHERE) with respect to the current
study amplicon profiling as well previous studies.

NOTE:

Steps 1.-4. are very computationally intensive and can only be performed in 
a reasonable time frame using high-performance computing and parallelization.
For this reason, the secondary data generated be these scripts (namely:
assemblies, ORFs, annotations, species tree, WGS taxonomy info., etc.) are
provided here:

The raw data (from the sequencing machine) necessary to run these scripts, as 
well as mapping file, metadata and intermediate results can be downloaded from:

http://www.at-sphere.com/download/culture_collections.tar.gz

If you use any of these scripts, please cite our paper:

CITATION

For any questions regarding these scripts, please contact

Ruben Garrido-Oter
garridoo@mpipz.mpg.de
