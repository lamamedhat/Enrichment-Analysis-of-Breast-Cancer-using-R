"Enrichment-Analysis-of-Drosophila-melanogaster-using-R" 

This repository provides comprehensive enrichment analysis using a significant gene expression dataset for Drosophila melanogaster. The raw gene expression data was obtained from the following [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3032923/). Utilizing the clusterProfiler package, the analysis identifies enriched Gene Ontology (GO) terms, KEGG pathways, and Reactome pathways associated with the dataset. The results are visually represented using the pathview package for pathway visualization and the ggplot2 package for customizable plots, enabling detailed exploration and interpretation of biological insights related to Drosophila melanogaster gene expression profiles.

# Run
You can install dependencies recorded in the lockfile using the following command:
```bash
renv::restore()
```

# Sample Input
[Significant_genes_of_Drosophila_melanogaster](https://raw.githubusercontent.com/lamamedhat/Enrichment-Analysis-of-Breast-Cancer-using-R/Drosophila_melanogaster/Data/Significant%20genes.csv)

# Sample Output
[Enrichment_Analysis_of_Drosophila_melanogaster_PDF]()

[Drosophila_melanogaster_Figures_PDF](https://github.com/lamamedhat/Enrichment-Analysis-of-Breast-Cancer-using-R/blob/Drosophila_melanogaster/outputs/Enrichment%20Analysis%20Figures%20of%20Drosophila%20melanogaster.pdf)




