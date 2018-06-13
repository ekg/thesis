# Graphical pangenomics

100-150 pages, ~25k words

Outline annotated with expected effort and length:

------

# introduction
*0.5p 1.5h*

## review of reference sequence literature
*0.5p 1h*
### brief retrospective on DNA sequencing and references
*2p 3h*
### the reference bias problem
*2p 2h*
### alt-aware references and their limits
*2p 3h*

## review of uses of graphs in sequence analysis
*0.5p 0.5h*
### MSAs
*1p 1h*
### assembly graphs
*3p 3h*
#### overlap assembly graphs
#### debruijn graphs (colored in particular)
### RNA splicing graphs
*1p 1h*
### variant representation (VCF encodes a DAG)
*0.5p 0.5h*

# the variation graph
*1p 1h*
## data models
*0.5p 1h*
### the graph itself
*1p 1h*
### edits to the graph
*1p 1h*
### alignments and translations
*1p 1h*
### bubbles and variant calls
*2p 2.5h*

## graph construction
*0.5p 0.5h*
### progressively (vg msga)
*1p 1h*
### from variants (VCF)
*1.5p 1h*
### from gene models (GFF)
*1p 4h*
### from MSAs
*0.5p 0.5h*
### from overlap graphs (assemblies)
*2p 1.5h*
### from pairwise alignments
*2p 4h*
### from other sources (e.g.g cactus)
*0.5p 0.5h*

## index structures
*0.5p 0.5h*
### XG index
*2p 3h*
### GCSA2 index
*1p 2h*
### haplotype indexes
*1.5p 2h*
### generic disk backed indexes
*0.5p 0.5h*
### coverage index
*1p 1h*

## local and global alignment
*0.5p 0.5h*
### POA and GSSW
*2p 2h*
### banded global alignment
*0.5p 0.5h*
### MEM finding
*2p 2h*
### X-drop DP
*0.5p 0.5h*

## collinear chaining
*0.5p 0.5h*
### distance estimation
*1p 1h*
### MEM chaining
*2.5p 3h*
### chunked alignment
*1p 1h*

## visualization
*0.5p 0.5h*
### hierarchical layout
*0.5p 0.5h*
### force directed models
*1p 1.5h*
### linear time visualization
*1p 2h*

## graph mutating algorithms
*0.5p 0.5h*
### edit
*1p 1h*
### pruning
*2.5p 3h*
### sort
*1p 1h*
### simplification
*0.5p 0.5h*

## graphs as basis spaces for sequence data
*2p 2h*
### coverage maps
*1p 1h*
### variant calling
*3p 2h*
### bubble decompositions and likelihood spaces
*2p 4h*
### MEM matching to the bidirectional GBWT
*1p 3h*

# applications
*0.5p 1h*

## yeast
*0.5p 0.5h*
### a SNP-based SGRP2 graph
*1p 1h*
### cactus progressive assembly
*0.5p 0.5h*
### constructing and comparing variation graphs from whole genome assemblies
*3p 2.5h*

## human
*0.5p 0.5h*
### 1000GP graph construction and indexing
*1.5p 1h*
### simulations based on phased HG002
*2p 2.5h*
### whole genome variant calling experiments
*1p 2h*
### HGSVC from VCF and progressive alignment of human chromosomes
*2.5p 5h*

## aDNA
*0.5p 0.5h*
### simulations with human origins panel
*1p 2h*
### using 1000GP graph for samples from Martiniano et al 2016
*2p 4h*
### evaluation of a high-coverage Botai sample
*2p 4h*

## neoclassical bacterial pangenomics
*0.5p 0.5h*
### e. coli pangenome from illumina reads
*2p 4h*
### evaluating the core and accessory pangenome
*2p 4h*

## metagenomics
*0.5p 0.5h*
### arctic viral metagenome
*2p 1.5h*
### human gut microbiome
*2p 4h*

## RNAseq
*0.5p 0.5h*
### yeast
*1p 2h*
### nematode
*2p 5h*
### human
*2p 6h*

# discussion and conclusion
*3p 4h*
## vg in the context of modern sequence analysis
*2p 1.5h*
## limitations of current approaches
*2p 2h*
## next steps
*4p 5h*
