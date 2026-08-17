```
> sessionInfo()
```

```
R version 4.5.1 (2025-06-13)
Platform: aarch64-apple-darwin20
Running under: macOS Sequoia 15.5

Matrix products: default

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] grid      stats4    stats     graphics  grDevices utils     datasets  methods   base

other attached packages:
 [1] writexl_1.5.4               ggpubr_0.6.3                compositions_2.0-9
 [4] emmeans_2.0.2               msigdbdf_25.1.0             fgsea_1.34.2
 [7] readxl_1.4.5                lubridate_1.9.5             forcats_1.0.1
[10] stringr_1.6.0               purrr_1.2.1                 readr_2.2.0
[13] tidyr_1.3.2                 tibble_3.3.1                tidyverse_2.0.0
[16] org.Hs.eg.db_3.21.0         AnnotationDbi_1.70.0        msigdbr_26.1.0
[19] clusterProfiler_4.16.0      circlize_0.4.18             ComplexHeatmap_2.24.1
[22] SeuratWrappers_0.4.0        DT_0.34.0                   harmony_1.2.4
[25] Rcpp_1.1.1                  hdf5r_1.3.12                SingleCellExperiment_1.30.1
[28] openxlsx_4.2.8.1            shiny_1.13.0                htmltools_0.5.9
[31] htmlwidgets_1.6.4           SummarizedExperiment_1.38.1 Biobase_2.68.0
[34] GenomicRanges_1.60.0        GenomeInfoDb_1.44.3         IRanges_2.42.0
[37] S4Vectors_0.48.0            BiocGenerics_0.54.1         generics_0.1.4
[40] MatrixGenerics_1.20.0       matrixStats_1.5.0           rmarkdown_2.31
[43] cowplot_1.2.0               ggplot2_4.0.2               patchwork_1.3.2
[46] Seurat_5.4.0                SeuratObject_5.3.0          sp_2.2-1
[49] dplyr_1.2.1

loaded via a namespace (and not attached):
  [1] R.methodsS3_1.8.2        goftest_1.2-3            Biostrings_2.76.0        vctrs_0.7.2
  [5] ggtangle_0.1.1           spatstat.random_3.4-5    digest_0.6.39            png_0.1-9
  [9] shape_1.4.6.1            ggrepel_0.9.8            deldir_2.0-4             parallelly_1.46.1
 [13] MASS_7.3-65              reshape2_1.4.5           httpuv_1.6.17            foreach_1.5.2
 [17] qvalue_2.40.0            withr_3.0.2              xfun_0.57                ggfun_0.2.0
 [21] survival_3.8-6           memoise_2.0.1            ggbeeswarm_0.7.3         gson_0.1.0
 [25] tidytree_0.4.7           zoo_1.8-15               GlobalOptions_0.1.3      pbapply_1.7-4
 [29] DEoptimR_1.1-4           R.oo_1.27.1              Formula_1.2-5            KEGGREST_1.48.1
 [33] promises_1.5.0           otel_0.2.0               httr_1.4.8               rstatix_0.7.3
 [37] restfulr_0.0.16          globals_0.19.1           fitdistrplus_1.2-6       rstudioapi_0.18.0
 [41] UCSC.utils_1.4.0         miniUI_0.1.2             DOSE_4.2.0               babelgene_22.9
 [45] curl_7.0.0               ScaledMatrix_1.16.0      polyclip_1.10-7          GenomeInfoDbData_1.2.14
 [49] SparseArray_1.8.1        xtable_1.8-8             doParallel_1.0.17        evaluate_1.0.5
 [53] S4Arrays_1.8.1           hms_1.1.4                irlba_2.3.7              colorspace_2.1-2
 [57] ROCR_1.0-12              reticulate_1.45.0        spatstat.data_3.1-9      magrittr_2.0.5
 [61] lmtest_0.9-40            later_1.4.8              viridis_0.6.5            ggtree_3.16.3
 [65] lattice_0.22-9           robustbase_0.99-7        spatstat.geom_3.7-3      future.apply_1.20.2
 [69] scattermore_1.2          XML_3.99-0.23            scuttle_1.18.0           RcppAnnoy_0.0.23
 [73] pillar_1.11.1            nlme_3.1-169             iterators_1.0.14         compiler_4.5.1
 [77] beachmat_2.24.0          RSpectra_0.16-2          stringi_1.8.7            tensor_1.5.1
 [81] GenomicAlignments_1.44.0 plyr_1.8.9               crayon_1.5.3             abind_1.4-8
 [85] BiocIO_1.18.0            scater_1.35.0            gridGraphics_0.5-1       locfit_1.5-9.12
 [89] bit_4.6.0                fastmatch_1.1-8          codetools_0.2-20         BiocSingular_1.24.0
 [93] GetoptLong_1.1.0         plotly_4.12.0            mime_0.13                splines_4.5.1
 [97] fastDummies_1.7.5        cellranger_1.1.0         knitr_1.51               blob_1.3.0
[101] clue_0.3-68              fs_2.0.1                 listenv_0.10.1           ggsignif_0.6.4
[105] ggplotify_0.1.3          estimability_1.5.1       Matrix_1.7-5             statmod_1.5.1
[109] tzdb_0.5.0               pkgconfig_2.0.3          tools_4.5.1              cachem_1.1.0
[113] RSQLite_2.4.6            viridisLite_0.4.3        DBI_1.3.0                fastmap_1.2.0
[117] scales_1.4.0             ica_1.0-3                Rsamtools_2.24.1         broom_1.0.12
[121] coda_0.19-4.1            BiocManager_1.30.27      dotCall64_1.2            carData_3.0-6
[125] RANN_2.6.2               farver_2.1.2             yaml_2.3.12              bayesm_3.1-7
[129] rtracklayer_1.68.0       cli_3.6.5                lifecycle_1.0.5          uwot_0.2.4
[133] mvtnorm_1.3-6            backports_1.5.1          bluster_1.18.0           BiocParallel_1.42.2
[137] timechange_0.4.0         gtable_0.3.6             rjson_0.2.23             ggridges_0.5.7
[141] progressr_0.19.0         parallel_4.5.1           ape_5.8-1                limma_3.64.3
[145] jsonlite_2.0.0           edgeR_4.6.3              RcppHNSW_0.6.0           bitops_1.0-9
[149] bit64_4.6.0-1            assertthat_0.2.1         xgboost_3.2.1.1          Rtsne_0.17
[153] yulab.utils_0.2.4        spatstat.utils_3.2-2     BiocNeighbors_2.2.0      zip_2.3.3
[157] metapod_1.16.0           GOSemSim_2.34.0          dqrng_0.4.1              spatstat.univar_3.1-7
[161] R.utils_2.13.0           lazyeval_0.2.3           enrichplot_1.28.4        GO.db_3.21.0
[165] sctransform_0.4.3        rappdirs_0.3.4           glue_1.8.0               spam_2.11-3
[169] XVector_0.48.0           RCurl_1.98-1.18          treeio_1.32.0            scran_1.36.0
[173] gridExtra_2.3            igraph_2.2.2             R6_2.6.1                 cluster_2.1.8.2
[177] aplot_0.2.9              DelayedArray_0.34.1      tidyselect_1.2.1         vipor_0.4.7
[181] tensorA_0.36.2.1         car_3.1-5                future_1.70.0            rsvd_1.0.5
[185] KernSmooth_2.23-26       S7_0.2.1                 data.table_1.18.2.1      RColorBrewer_1.1-3
[189] rlang_1.1.7              spatstat.sparse_3.1-0    spatstat.explore_3.8-0   remotes_2.5.0
[193] beeswarm_0.4.0
```
