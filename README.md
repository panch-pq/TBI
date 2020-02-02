## Spatial transcriptomics analysis of traumatic brain injury model

In this project, we assessed the roles of repopulating microglia in brain repair using mouse models. In this project, we show that removal of microglia from the mouse brain has little impact on the outcome of TBI but inducing the turnover of these cells through either pharmacologic or genetic approaches can yield a neuroprotective microglial phenotype that profoundly aids recovery. As a part of the experimental approaches we perform bulk RNA sequencing experiments to unbiasedly profile the transcriptome of repopulating microglia. We identified unique gene signatures from repopulating microglia cells and infer how these cells modulate the microenvironment after TBI. In addition to the bulk RNA-seq, we performed spatial transcriptomics profiling to compare the localized expression signatures of microglia cells and immune cells in different anatomical regions and distances to the injury sites. We study changes in cell-type composition and transcriptional signatures of responses to injury.


For the data mapping and preprocessing of spatial transcriptomics data, we implemented the the standard pipeline made available by the company that we purchased the experimental kit for generating the spatial transcriptomics data. The website is: <https://github.com/SpatialTranscriptomicsResearch>. The main pipeline includes: st_pipeline and st_analysis (for mapping); st_viewer and st_spot_detector and st_tissue_recognition (for overlaying spot coordinates and tissue images), and st_analysis (for filtering out genes and cells). Custom Python 3.6 code are available in this repository. 

All the sequencing data from this study have been submitted to ArrayExpress repository (https://www.ebi.ac.uk/arrayexpress/). The bulk RNA-seq dataset is available under accession number  E-MTAB-8765. The spatial RNA-seq dataset, accession number E-MTAB-8768, is available upon request, and will be open to public access at ArrayExpress from 15th December 2020. 
