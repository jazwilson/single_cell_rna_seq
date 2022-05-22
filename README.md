# single_cell_rna_seq
Workflow for processing single cell RNA seq data 

@author: Dr Jasmine Wilson <br />

**Workflow contents:** <br />
    - Quality control <br />
    - Scaling data <br />
    - Query clustering parameters for dimensionality reduction <br />
    *Tabspace*- *Jackstraw & Elbow plot* <br />
    *Tabspace*- *Variance modelling* <br />
    - Automated PC choice tools <br />
        - *Clustertree* <br />
        - *Cluster similarity* <br />
        - *Cluster stability* <br />
        - *Silhouette plot* <br />
    - Clustering function <br />
    - Query cluster identities by plotting key gene markers <br />
        - *Calculate positive high discrimination markers across all cluster* <br />
            - heatmap <br />
            - dotplot <br />
        - *Find variable features of specific clusters or cluster comparisons* <br />
        - *Define selected features to annotate clusters* <br />
            - A) Upload your find markers file (which should be an RDS file) <br />
            - B) Upload your own CSV of genes <br />
            - C) Define your own in markdown <br />
        - *Plot selected features:" <br />
            - Dotplot  <br />
            - Density plot <br />
            - Violin plot <br />
            - Heatmap top features <br />
            - Heatmap selected features <br />
            - Column plot <br />
        - *Automated cluster annotation* <br />
            - scCatch - another program to annotate clusters <br />
        - *Assigning cell types* <br />
            - Rename clusters <br />
            - Assigning cell type based on selected markers <br />
    - Analysis of single cell populations <br />
        - *Calculate abundance* <br />
        - *Sub-clustering* <br />
        - *Differential analysis* <br />
            - Volcano plot <br />
            - GO analysis <br />
            - GSEA plot <br />
            - CNET plot <br />
            - Tree plot <br />





