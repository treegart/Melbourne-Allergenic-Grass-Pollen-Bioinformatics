# Melbourne-Allergenic-Grass-Pollen-Bioinformatics

This repository outlines the bioinformatic analysis of Illumina MiSeq files that contribute to the publication '...'.

The input sequences represent two years of weekly air samples from the air of Melbourne, DNA was extracted and two grass-focussed ITS2 primers (2SF and 4unR1) were amplified and sequenced using Illumian MiSeq.

The files in this repository are the following:

1. **Bioinformatic Analysis**
   This is the R script that was used to complete the bioinformatic analysis, using the input of R1 and R2 files, with the output as an ASV table and Taxonomy File

2. **QC Tracking Table**
   This is the .xlsx file that outlines the number of sequences remaining for each sample at the end of the each stage of bioinformatic analysis.

4. **Taxonomy Reclassification**
   This is the .xlsx file that outlines the manual reclassification of the fifty most abundant unclassified-by-UNITE ASVs. Including the NCBI accesssion codes, classification files and justifications for each decision

5. **Molecular Ecology Analysis**
   This is the R script that was used to complete the molecular ecology analysis, using the input files of ASV table, taxonomy table and sample data table. The output is a rarefaction table.

The intput files can be supplies upon resquest by contacting jgolz@unimelb.edu.au
