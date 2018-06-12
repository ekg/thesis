# Graphical pangenomics

100-150 pages, ~25k words

Outline annotated with expected effort and length:

------

# introduction

## review of reference sequence literature
### brief retrospective on DNA sequencing and references
### the reference bias problem
### alt-aware references and their limits

## review of uses of graphs in sequence analysis
### MSAs
### assembly graphs
### RNA splicing graphs
### debruijn graphs (colored in particular)
### overlap assembly graphs
### variant representation (VCF encodes a DAG)

# the variation graph

## data models
### the graph itself
### edits to the graph
### alignments and translations
### bubbles and variant calls

## graph construction
### progressively
### from variants (VCF)
### from gene models (GFF)
### from MSAs
### from overlap graphs (assemblies)
### from pairwise alignments

## index structures
### XG index
### GCSA2 index
### haplotype indexes
### generic disk backed indexes
### coverage index

## local and global alignment
### POA and GSSW
### banded global alignment
### MEM finding
### X-drop DP

## collinear chaining
### distance estimation
### MEM chaining
### chunked alignment
### alignment chaining

## visualization
### hierarchical layout
### force directed models
### linear time visualization
### interfacing with third-party tools

## graph mutating algorithms
### edit
### pruning
### simplification
### sort

## graphs as basis spaces for sequence data
### coverage maps
### variant calling

# applications

## yeast
### initial tests with a SNP-based SGRP2 graph
### cactus progressive assembly
### constructing and comparing variation graphs from whole genome assemblies

## human
### 1000GP graph
### simulations based on HG002

## aDNA
### simulations with human origins panel
### using 1000GP graph for samples from Martiniano et al 2016
### evaluation of a high-coverage Botai sample

## neoclassical bacterial pangenomics
### e. coli pangenome from illumina reads
### evaluating the core and accessory pangenome

## metagenomics
### arctic viral metagenome
### human gut microbiome

## RNAseq
### yeast
### nematode
### human

# discussion and conclusion

## vg in the context of modern sequence analysis
## limitations of current approaches
## next steps
