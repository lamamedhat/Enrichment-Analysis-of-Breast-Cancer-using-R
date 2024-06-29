# Enrichment-Analysis-of-Breast-Cancer-using-R
This repository provides comprehensive enrichment analysis using a gene expression dataset for breast cancer research. The raw gene gexpression data was obtained from the following [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8762060/). Utilizing the clusterProfiler package, the analysis identifies enriched Gene Ontology (GO) terms, KEGG pathways, and Reactome pathways associated with the dataset. The results are visually represented using the pathview package for pathway visualization and the ggplot2 package for customizable plots, enabling detailed exploration and interpretation of biological insights related to breast cancer gene expression profiles.

# Run
You can install dependencies recorded in the lockfile using the following command:
```bash
renv::restore()
```

# Sample Input
[Gene_Expression](https://raw.githubusercontent.com/lamamedhat/Enrichment-Analysis-of-Breast-Cancer-using-R/main/Data/GSE183947_fpkm.csv)

[metadata](https://raw.githubusercontent.com/lamamedhat/Enrichment-Analysis-of-Breast-Cancer-using-R/main/Data/metadata.csv)

# Sample Output
[Enrichment_Analysis_pipeline_PDF](https://github.com/lamamedhat/Enrichment-Analysis-of-Breast-Cancer-using-R/blob/main/outputs/Enrichment_analysis_pipeline.pdf)

[Enrichment_Analysis_Figures_PDF](https://github.com/lamamedhat/Enrichment-Analysis-of-Breast-Cancer-using-R/blob/main/outputs/Enrichment%20Analysis%20Figures%20of%20Breast%20Cancer.pdf)
