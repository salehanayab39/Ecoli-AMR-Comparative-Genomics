# Ecoli-AMR-Comparative-Genomics
Comparative genomic analysis of AMR-associated annotations in 10 Escherichia coli genome assemblies using QUAST and NCBI AMRFinderPlus
Project Overview
This project presents an in-silico comparative genomic analysis of ten Escherichia coli genome assemblies obtained from NCBI BioProject PRJNA293615.
The study investigates basic genome assembly characteristics and screens for antimicrobial resistance (AMR)-associated genetic annotations using bioinformatics tools.

Objectives

- Assess genome assembly characteristics using QUAST.
- Identify AMR-associated genetic annotations using NCBI AMRFinderPlus.
- Compare genome size and GC content across selected assemblies.
- Construct a presence/absence matrix of reported genetic variants.
- Examine the distribution of reported annotations among the genomes.

Dataset

Ten genome assemblies were selected from NCBI BioProject PRJNA293615.

Assembly accessions:

- GCF_022493115.1
- GCF_022493195.1
- GCF_022493235.1
- GCF_022493275.1
- GCF_022493315.1
- GCF_022493435.1
- GCF_022493515.1
- GCF_022493535.1
- GCF_022493855.1
- GCF_022493875.1

"NCBI BioProject PRJNA293615" (https://www.ncbi.nlm.nih.gov/bioproject/PRJNA293615)

Tools and Resources

- NCBI Datasets: Genome sequence retrieval.
- Galaxy: Bioinformatics workflow environment.
- QUAST: Genome assembly quality assessment.
- NCBI AMRFinderPlus: Identification of AMR-associated genetic determinants.
- Google Sheets: Data organization and visualization.

Methodology

1. Retrieved ten E. coli genome assemblies from NCBI.
2. Downloaded genome sequences in FASTA format.
3. Assessed genome assembly characteristics using QUAST.
4. Screened each genome separately using AMRFinderPlus.
5. Recorded reported element symbols and annotations.
6. Constructed a binary presence/absence matrix.
7. Generated comparative figures for genome size, GC content, and reported AMRFinderPlus hits.

Key Findings

- Genome lengths ranged from approximately 4.98 Mb to 5.13 Mb.
- GC content ranged from 50.52% to 50.81%.
- Five out of ten genomes had at least one reported AMRFinderPlus annotation.
- Five different element symbols were recorded:
  - "parE-D475E"
  - "ompF-N52K"
  - "marR-S39N"
  - "marR-S3N"
  - "uhpT-E350Q"

Genome 4 contained two reported annotations, while genomes 2, 6, 7, and 9 each contained one.

Repository Structure

Ecoli-AMR-Comparative-Genomics/
│
├── README.md
│
└── Results/
    ├── Comparative_Genomics_Ecoli_AMR_Analysis.pdf
    ├── Figure_1_AMRFinderPlus_Hits.png
    ├── Figure_2_Ecoli_Genome_Size.png
    ├── Figure_3_Ecoli_GC_Content.png
    └── Ecoli_AMR_Comparative_Data.xlsx

Important Limitations

AMRFinderPlus-reported annotations do not independently establish phenotypic antimicrobial resistance. The detected protein variants require further interpretation and experimental validation.

The study is limited to ten genome assemblies and does not include phenotypic antimicrobial susceptibility testing or phylogenetic analysis.

Project Outcome

This project demonstrates the application of bioinformatics tools in bacterial comparative genomics, genome assembly assessment, and computational screening of AMR-associated genetic annotations.

References

- Feldgarden et al. (2021). Scientific Reports. https://doi.org/10.1038/s41598-021-91456-0
- Gurevich et al. (2013). Bioinformatics. https://doi.org/10.1093/bioinformatics/btt086



Author: Saleha Nayab
Field: Biotechnology
Project type: In-silico comparative genomic analysis
