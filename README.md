# single_cell_rna_seq
Workflow for processing single cell RNA seq data 

@author: Dr Jasmine Wilson 

## **Workflow contents:** 
    Quality control
        - Scaling data 
        - Query clustering parameters for dimensionality reduction 
            - *Jackstraw & Elbow plot* 
    - Variance modelling
    - Automated PC choice tools 
        - Clustertree
        - Cluster similarity
        - Cluster stability
        - Silhouette plot
    - Clustering function 
    - Query cluster identities by plotting key gene markers 
        - Calculate positive high discrimination markers across all cluster
            - heatmap 
            - dotplot 
        - Find variable features of specific clusters or cluster comparisons
        - Define selected features to annotate cluster
            - A) Upload your find markers file (which should be an RDS file) 
            - B) Upload your own CSV of genes 
            - C) Define your own in markdown 
        - Plot selected features:
            - Dotplot  
            - Density plot 
            - Violin plot 
            - Heatmap top features 
            - Heatmap selected features 
            - Column plot
        - Automated cluster annotation
            - scCatch - another program to annotate clusters 
        - Assigning cell types
            - Rename clusters 
            - Assigning cell type based on selected markers 
    - Analysis of single cell populations 
        - Calculate abundance
        - Sub-clustering
        - Differential analysis
            - Volcano plot 
            - GO analysis 
            - GSEA plot 
            - CNET plot 
            - Tree plot 





