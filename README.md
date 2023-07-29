# A scalable unsupervised learning of scRNAseq data detects rare cells through integration of structure-preserving embedding, clustering and outlier detection
A scalable unsupervised learning of scRNAseq data detects rare cells through integration of structure-preserving embedding, clustering and outlier detection

Single-cell RNA-seq analysis has become a powerful tool to analyse the transcriptomes of individual cells. In turn, it has fostered the possibility of screening thousands of single cells in parallel. Thus, contrary to the traditional bulk measurements that only paint a macroscopic picture, gene measurements at the cell level aid researchers in studying different tissues and organs at various stages. However, accurate clustering methods for such high-dimensional data remain exiguous and a persistent challenge in this domain. Of late, several methods and techniques have been promulgated to address this issue. In this article, we propose a novel framework for clustering large-scale single-cell data and subsequently identifying the rare-cell sub-populations. To handle such sparse, high-dimensional data, we leverage PaCMAP (Pairwise Controlled Manifold Approximation), a feature extraction algorithm that preserves both the local and the global structures of the data and Gaussian Mixture Model to cluster single-cell data. Subsequently, we exploit Edited Nearest Neighbours sampling and Isolation Forest/One-class Support Vector Machine to identify rare-cell sub-populations. The performance of the proposed method is validated using the publicly available datasets with varying degrees of cell types and rare-cell sub-populations. On several benchmark datasets, the proposed method outperforms the existing state-of-the-art methods. The proposed method successfully identifies cell types that constitute populations ranging from 0.1 to 8% with F1-scores of 0.91 0.09.

https://doi.org/10.1093/bib/bbad125
