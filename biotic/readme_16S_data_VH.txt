Output of DADA2 pipeline, analysis of the 16S (bacterial) data
# raw_count_data_16S; rarefied and alpha diversity assessed
# normalized_phyla_count_data_16S; percentage abundance assesesed
# normalized_ASV_count_data_16S; unique and overlapping ASVs, top 10 most abundant ASVs, beta diversity, PERMANOVA + pairwise PERMANOVA

-------------------------------------------------------------------------
raw_count_data_16S

Input files 
# extradata_16S_VH.csv (metadata; sample information such as succession and field)
# raw_count_data_16S_VH.csv (output of DADA2, counts per ASV)
RMarkdown
# raw_count_data_16S_VH.rmd

-------------------------------------------------------------------------
normalized_phyla_count_data_16S

Input files 
# extradata_16S_VH.csv (metadata; sample information such as succession and field)
# CSS_normalized_phyla_16S_VH.csv (CCS normalized bacterial count data per phyla)

RMarkdown
# normalized_phyla_16S_VH.rmd

-------------------------------------------------------------------------
normalized_ASV_count_data_16S

Input files 
# extradata_16S_VH.csv (metadata; sample information such as succession and field)
# CSS_normalized_ASV_16S_VH.csv (CCS normalized bacterial count data per ASV)
# raw_count_data_16S_VH.csv (output of DADA2, counts per ASV)

RMarkdown
# normalized_ASV_16S_VH.rmd

