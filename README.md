# ArchR

ArchR is a R based software suite for the analysis of single-cell chromatin accessibility (scATAC) data. It is written by the Greenleaf lab, the original pioneers of the ATAC-seq method. The original paper describing ArchR has done some benchmarking to other scATAC software, such as Signac and SnapATAC. It is important to note that although ArchR seems to perform better, ArchR has not been updated for a while (v1.0.2 in Jul 1 2022). Both Signac and SnapATAC2 (successor of SnapATAC) are being actively maintained.

## Requirements
1. fragments.tsv.gz: The fragment file that is typically created at the end of a 10x genomics run of scATAC-seq. This file is often large and **unfortunately** frequently omitted by authors that submit the original data onto public databases, such as the Gene Expression Omnibus (GEO).
2. Bam (used instead of fragments.tsv.gz file):

## Links
1. [Original Publication](https://www.nature.com/articles/s41588-021-00790-6) 
2. [Github](https://github.com/GreenleafLab/ArchR/)
3. [Brief Tutorial](https://www.archrproject.com/articles/Articles/tutorial.html)
4. [Full Manual](https://www.archrproject.com/bookdown/index.html)