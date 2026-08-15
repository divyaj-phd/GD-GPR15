# Gamma Delta Analysis Scripts

Repository containing code used to analyze single-cell RNA-seq data published in<br>
Raw single-cell data will be available upon request <br>


## Software & Packages

<table>
  <tr>
    <td valign="top">
<b>Single-Cell Analysis</b><br>
<a href="https://www.r-project.org/"><img src="https://img.shields.io/badge/R-v4.2.0-4e9af1?style=flat-square&logo=r&logoColor=white"/></a> 
<a href="https://satijalab.org/seurat/"><img src="https://img.shields.io/badge/Seurat-v5.1.0-0288d1?style=flat-square"/></a> 
<a href="https://portals.broadinstitute.org/harmony/"><img src="https://img.shields.io/badge/harmony-v1.2.4-276DC3?style=flat-square"/></a><br><br>
<b>Pathway Enrichment</b><br>
<a href="https://bioconductor.org/packages/release/bioc/vignettes/clusterProfiler/inst/doc/clusterProfiler.html"><img src="https://img.shields.io/badge/clusterProfiler-v4.12.6-26a69a?style=flat-square"/></a>
<a href="https://igordot.github.io/msigdbr/"><img src="https://img.shields.io/badge/msigdbr-v25.1.1-00897b?style=flat-square"/></a><br><br>
    </td>
    <td valign="top">
<b>Cell Frequency</b><br>
<a href="https://www.stat.boogaart.de/compositions/"><img src="https://img.shields.io/badge/compositions-v2.0.8-f57c00?style=flat-square"/></a>
<a href="https://rvlenth.github.io/emmeans/"><img src="https://img.shields.io/badge/emmeans-v1.10.4-ef6c00?style=flat-square"/></a><br><br>
<b>Visualisation</b><br>
<a href="https://ggplot2.tidyverse.org/"><img src="https://img.shields.io/badge/ggplot2-v4.0.1-e91e63?style=flat-square"/></a>
<a href="https://jokergoo.github.io/ComplexHeatmap-reference/book/"><img src="https://img.shields.io/badge/ComplexHeatmap-v2.14.0-c2185b?style=flat-square"/></a>
<a href="https://svglite.r-lib.org/"><img src="https://img.shields.io/badge/svglite-v2.1.3-ad1457?style=flat-square"/></a>
    </td>
  </tr>
</table>


## Repository Structure

```
GD-GPR15/
├── R Scripts/
│   ├── 01_QC_integration_clustering            # QC filtering, Batch correction, Global clustering, annotation
│   ├── 02_Subclustering                        # Sub-clustering workflow
│   ├── 03_DEGs_ GSEA_CLR_cell_frequency        # DEGs + GSEA+ CLR cell-frequency analysis + forest plots
│   ├── 04_Figure_plots                         # Bubble plots+ Heat maps
│   └── sessionInfo.md                          # Full R session information and package versions                     
└── README.md
```

