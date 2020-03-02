# zebrafish_bipolarity

**This repository contains all the scripts that are required to reproduce results from the single-cell analysis study of zebrafish neuromasts from:
Kozak et al., "Epithelial planar bipolarity emerges from Notch-mediated asymmetric inhibition of Emx2", Current Biology, 2019**

Description for the notebooks are as follows:

- scRNA_seq_preprocessing_qc_merged_main_analysis_clustering.ipynb --> This notebook consists of quality control and other preprocessing steps for the raw count matrices for 10X hair and supporting cells along with calculation of embeddings and cell annotations
- scRNA_seq_mcSCRBseq_comparison.ipynb --> This notebook consists of quality control and preprocessing steps of the mcSCRBseq hair cells data that are additionally compared with the processed, filtered young hair cells from 10X for differential expression tests
- scRNA_seq_integration.ipynb --> This notebook consists of scripts for the integration of 10X with Lush et al and to reproduce figures in our manuscript for the mapping between UHCPs

The data has been deposited in GEO under accession numbers GSE143663 and GSE144827.

Please note that all the analyses were performed using Scanpy v1.4.4. To know versions of other packages used in this analysis please either check the respective notebooks or consult the methods and key resource table in the manuscript. Since packages are constantly upgraded as part of maintenance certain results may vary slighly based on versions and dependencies.

In case you use the code and results mentioned in this repository for your own research, please consider citing the above publication.
