Output of PIPITS pipeline, analysis of the ITS (fungal) data
# raw_count_data_ITS; rarefied and alpha diversity assessed
# normalized_phyla_count_data_ITS; percentage abundance assesesed
# normalized_ASV_count_data_ITS; unique and overlapping ASVs, top 10 most abundant ASVs, beta diversity, PERMANOVA + pairwise PERMANOVA

-------------------------------------------------------------------------
raw_count_data_ITS

Input files 
# extradata_ITS_VH.csv (metadata; sample information such as succession and field)
# raw_count_data_ITS_VH.csv (output of DADA2, OTU counts per OTU)
RMarkdown
# raw_count_data_ITS analysis.rmd

-------------------------------------------------------------------------
normalized_phyla_count_data_ITS

Input files 
# extradata_ITS_VH.csv (metadata; sample information such as succession and field)
# CSS_normalized_phyla_ITS_VH.csv (CCS normalized fungal count data per phyla)

RMarkdown
# normalized_phyla_ITS_VH.rmd

-------------------------------------------------------------------------
normalized_ASV_count_data_ITS

Input files 
# extradata_ITS_VH.csv (metadata; sample information such as succession and field)
# CSS_normalized_ASV_ITS_VH.csv (CCS normalized fungal count data per OTU)
# raw_count_data_ITS_VH.csv (output of DADA2, OTU counts per OTU)

RMarkdown
#  normalized_OTU_ITS_VH.rmd
