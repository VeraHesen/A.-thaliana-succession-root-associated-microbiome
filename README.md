# A.-thaliana-succession-root-associated-microbiome

Data analysis associated with the paper "Pioneer Arabidopsis thaliana spans the succession gradient revealing a diverse root-associated microbiome" (Hesen et al., 2023, Environmental Microbiome, DOI: 10.1186/s40793-023-00511-y). Raw 16S and ITS sequence data is deposited in European Nucleotide Archive (ENA) under accession PRJEB59993.

RMarkdown files are provided to process the abiotic and biotic data. Input files are provided per section

# Abiotic
Analysis and plotting of soil abiotic factors (PO4, SOM, C%, N% and CN) through ANOVA + Tukey post hoc, PCA, MANOVA and LDA

# Biotic
Analysis and plotting of 16S and ITS count data (output of DADA2 and PIPITS respectively). 16S and ITS data are analysed seperately

## 16S_data
- raw_count_data_16S; rarefied and alpha diversity assessed
- normalized_phyla_count_data_16S; percentage abundance assesesed
- normalized_ASV_count_data_16S; unique and overlapping ASVs, top 10 most abundant ASVs, beta diversity, PERMANOVA + pairwise PERMANOVA
## ITS_data
- raw_count_data_ITS; rarefied and alpha diversity assessed
- normalized_phyla_count_data_ITS; percentage abundance assesesed
- normalized_OTU_count_data_ITS; unique and overlapping OTUs, top 10 most abundant OTUs, beta diversity, PERMANOVA + pairwise PERMANOVA

# Abiotic Biotic
Analysis of abiotic data together with the biotic data through Mantel tests and Canonical Correspondance Analysis (CCA).
