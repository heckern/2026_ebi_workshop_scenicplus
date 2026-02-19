# Identification of regulatory drivers in a medulloblastoma model using single cell multiomics data

Gene regulatory networks (GRNs) govern the identity of cells and are drivers of disease progression including tumorigenesis. Transcription factors, enhancers, and their target genes form the core blocks of GRNs, also known as eRegulons. Understanding the activity of eRegulons helps us to characterize healthy and pathological cell states, and to identify potential targets for intervention. 

In this project, we will investigate gene regulatory drivers of healthy and tumor cells based on a single cell multiome (ATAC + gene expression) dataset of a medulloblastoma mouse model [1]. The SCENIC+ framework [2] will be used to infer eRegulons, visualise their activity, and assess their specificity for healthy and tumor cells.

---
The tutorial contains two parts:
1) SCENIC+ - eRegulon analysis: [scenicplus_analysis.ipynb](https://github.com/heckern/2026_ebi_workshop_scenicplus/blob/main/scenicplus_analysis.ipynb)
2) SCENIC+ - prediction of TF perturbation effects: [scenicplus_perturbation.ipynb](https://github.com/heckern/2026_ebi_workshop_scenicplus/blob/main/scenicplus_perturbation.ipynb)

Prior to the tutorial the data has been processed. The following notebooks show the different processing steps:
* Scanpy - procession of the gene expression modality: [scanpy_rna_processing.ipynb](https://github.com/heckern/2026_ebi_workshop_scenicplus/blob/main/scanpy_rna_processing.ipynb)
* pycisTopic - processing of the ATAC modality: [pycistopic_atac_processing.ipynb](https://github.com/heckern/2026_ebi_workshop_scenicplus/blob/main/pycistopic_atac_processing.ipynb) 
* pycisTarget - TF binding site motif score database: [pycistarget_tfmotif_database.ipynb](https://github.com/heckern/2026_ebi_workshop_scenicplus/blob/main/pycistarget_tfmotif_database.ipynb)
* SCENIC+ - pipeline for inferring eRegulons: [scenicplus_pipeline.ipynb](https://github.com/heckern/2026_ebi_workshop_scenicplus/blob/main/scenicplus_pipeline.ipynb)
---
## Reference:

[1] Shiraishi, R. & Cancila, G. et al. (2024). Cancer-specific epigenome identifies oncogenic hijacking by nuclear factor I family proteins for medulloblastoma progression. Dev. Cell , 59:2302-2319.

[2] Bravo González-Blas & C., De Winter, S. et al. (2023). SCENIC+: single-cell multiomic inference of enhancers and gene regulatory networks. Nat. Methods, 20:1355-1367.
