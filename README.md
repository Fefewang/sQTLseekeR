sQTLseekeR
==========

sQTLseekeR is a R package to detect spicing QTLs (sQTLs), which are variants associated with change in 
the splicing pattern of a gene. Splicing patterns are modeled by the relative expression of the transcripts
of a gene.

### Installation

To install the latest development version: `devtools::install_github("jmonlong/sQTLseekeR")`. 

This requires `devtools` package (more information [here](https://github.com/hadley/devtools)) 
which can be easily installed with `install.packages("devtools")`. 

### Running in clusters

`sQTLseekeR` can easily be used on a cluster using package `BatchJobs`. An example of an analysis using `BatchJobs` can
be found in the folder `scripts`.

### Publication

Monlong, J. et al. Identification of genetic variants associated with alternative splicing using sQTLseekeR. Nat. Commun. 
5:4698 doi: [10.1038/ncomms5698](http://www.nature.com/ncomms/2014/140820/ncomms5698/full/ncomms5698.html) (2014).
