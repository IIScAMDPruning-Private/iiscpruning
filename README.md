# IISc MLLab Model Compression 

Welcome! In this page, we describe the work we've done on model compression, including links to useful github repositories.  More details in the sequel.

# Projects
## TVSPrune - A New Distributional approach to pruning
In this work, we propose a new paradigm for pruning, which we call *distributional pruning*. This work probes the distributional discrepancy between class-conditional features in order to identify useful filters. Our reasoning is that filters (in classifiers) with class-conditional features that are well separated are *discriminative*, and therefore useful for classification. Our work proposes new ways to identify discriminative filters, and use them for structured pruning.

This work is published at: https://openreview.net/forum?id=sZI1Oj9KBKy

Our code is available at: https://github.com/chaimurti/TVSPrune/

## DFPC - Pruning Complex Coupled Connections for Efficient Inference
In this work, we investigate the relationship between sparsity and inference time. Our key observation is that coupled connections, such as residual connections in ResNets, consume the majority of the inference time. These connections are also difficult to prune. We propose new methods for enumerating and pruning these complex networks, and achieve state-of-the-art speedups on classification tasks.

This work is published at: https://openreview.net/forum?id=mhnHqRqcjYU

Our code is available at: https://github.com/TanayNarshana/DFPC-Pruning

## More to come, so watch this space!

# Team

1. Prof. Chiranjib Bhattacharyya
2. Chaitanya Murti
3. Tanay Narshana 
