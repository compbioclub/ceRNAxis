# ceRNAxis

Welcome to the official documentation of **ceRNAxis**!

## Overview

**ceRNAxis** detects ceRNA network `LncRNA-miRNA-mRNA triplet axis` from RNA expression profiles.

We have manually curated a reference ceRNA network by integrating `TargetSCAN 8.0`, `miRTarBase 9.0`, `miRDB 6.0`, `NPInter 4.0`, `ENCORI/starBase 2.0`, `miRWalk V3`, and `RNAInter in 2020`. 

To run ceRNAxis with full reference ceRNA network, please download the full file [`ceRNA_ref.csv`](https://doi.org/10.5281/zenodo.15848890), and place it into `cernatax/data`.

## Getting Started

Want to start using it immediately? Check out the [Installation Guide](installation.md).


## Tutorial Guide
The followings are AS Paper scripts on how to use **ceRNAxis** on the SCZ and GDM cohort:

-   [Basic operations and stats for the reference ceRNA network](tutorial/reference_ceRNA_network.ipynb)
-   [SCZ - Use DEG to get cohort-specific and disease relatated ceRNA axis from SCZ data](tutorial/SCZ_ceRNA_axis_from_DEG.ipynb)
-   [GDM - Use DEG to get cohort-specific and disease relatated ceRNA axis from GDM data](tutorial/GDM_ceRNA_axis_from_DEG.ipynb)
-   [SCZ - ceRNA expression visualization for a cohort](tutorial/SCZ_plot_ceRNA_exp_for_cohort.ipynb)
-   [SCZ - ceRNA-axis correlation analysis for a cohort](tutorial/SCZ_ceRNA_correlation_analysis.ipynb)
-   [SCZ - GWAS analysis for ceRNA-axis](tutorial/SCZ_ceRNA_gwas_analysis.ipynb)

## Citation

If you use **ceRNAxis** in your research, please cite the following paper:

```
X. Gong, L. Chen, X. Guo, et al. LncRNA THUMPD3-AS1 Regulates Behavioral and Synaptic Structural Abnormalities in Schizophrenia via miR-485-5p and ARHGAP8. Adv. Sci. (2025): e08867. https://doi.org/10.1002/advs.202508867
```

BibTeX format:

```bibtex
@article{https://doi.org/10.1002/advs.202508867,
author = {Gong, Xiaojuan and Chen, Lingxi and Guo, Xin and Jiang, Anna and He, Yayi and Yan, Chunxia and Ma, Liang and Gao, Jiayang and Zhang, Jinyu and Zhang, Bao},
title = {LncRNA THUMPD3-AS1 Regulates Behavioral and Synaptic Structural Abnormalities in Schizophrenia via miR-485-5p and ARHGAP8},
journal = {Advanced Science},
pages = {e08867},
keywords = {noncoding RNA regulation, Rho GTPase signaling, schizophrenia, synaptic pathology},
doi = {https://doi.org/10.1002/advs.202508867},
url = {https://advanced.onlinelibrary.wiley.com/doi/abs/10.1002/advs.202508867},
}
```

<div style="display:none;">
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=n&d=s_zp3a_kJX2eHlUNurnH4Jti8lf7sMFpJyhQQnn21MU'></script>
<script defer src='https://static.cloudflareinsights.com/beacon.min.js' data-cf-beacon='{"token": "aec36b862a47431a979dc263a1f98d74"}'></script>
</div>
