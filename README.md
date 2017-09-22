# Finches
Scripts and Instructions from !["Genomic variation at the tips of the adaptive radiation of Darwin's finches"](http://onlinelibrary.wiley.com/doi/10.1111/mec.13743/full)

### labProtocols
Contains detailed lab protocols for constructing the dRAD Illumina library, including all primer and adapter sequences.

### RAD_Pipeline_Info
Detailed instructions and all scripts used in the pipeline to process the raw dRADseq data into SNP files.  Note that this protocol was originally written for assembling RAD tags with no reference genome, but for the Darwin's finches we used the (2012 version) of the reference genome available at the ![UCSC genome browser](https://genome.ucsc.edu/) instead of a *de novo* consensus reference.  

### snpAnalysis
Contains detailed instructions and Perl scripts for performing population genetics analyses on dRAD SNP data.  This includes scripts for calculating Fst as well as for converting into STRUCTURE input format.

### LDanalysis
A separate set of R scripts and instructions for calculating LD with the R genetics package.

### GWAS_Pipelines
Detailed instructions for running several GWAS pipelines.  For this paper, we used the GEMMA BSLMM pipeline specifically.
