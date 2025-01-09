# Time Trees of Birds in China and Their Nearest Relatives
This data package includes the time trees used for analysis in:

Cai, T., Lei, F., Zhen, Y. et al. 2024. Evolutionary history of the avian fauna of China. xxx

## Trees

(1) A time tree estimated using treePL based on the best Maximum Likelihood (ML) tree.

(2) 100 time trees estimated using treePL based on 100 RAxML bootstrap trees.

## Methods
The dataset includes 2,651 bird species, encompassing 1,455 species from China (96.8% of its avifauna) and their closest relatives (1,196 species). We used 12 genes (3 mitochondrial and 9 nuclear) to construct the species tree. For phylogenetic inference, the family-level topology was constrained based on the genomic species tree by Germain et al. (2023, Nature). Using RAxML, we applied the GTR+Gamma model with partitioning by gene type (nuclear vs. mitochondrial) and performed 100 bootstrap replicates to generate 100 bootstrap trees and one best Maximum Likelihood (ML) tree. Time calibration of the ML tree was conducted using treePL, with divergence times from Germain et al. (2023, Nature) as calibration points.
