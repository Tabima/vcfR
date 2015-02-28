Functions created to work with vcf files.

*vcf.R* - S4 class to contain a vcf file as well as functions to load this object.

*vcf_v1.R* - Non-formal functions to read in a vcf file.

*chromR.r* - S4 class to contain data from a sequence file (fasta), an annotation file (gff3) and a feature file (vcf).  Includes functions for loading object and display as a genome browser.

While this project is in development it can be installed through github:

    library(devtools)
    install_github(repo="knausb/vcfR")
    library(vcfR)


The development version (which may not be stable) can also be installed:

    library(devtools)
    install_github(repo="knausb/vcfR@devel")
    library(vcfR)


