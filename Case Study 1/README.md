Case Study 1 - by Troy McSimov and Katon Pang

Review the R Markdown files (Project-DataExploration-Week8-tmm-1.*) for problem statements, code summary, and results.

Below is the sessionInfo from the client running R.

## R version 4.3.1 (2023-06-16 ucrt)
## Platform: x86_64-w64-mingw32/x64 (64-bit)
## Running under: Windows 11 x64 (build 22621)
## 
## Matrix products: default
## 
## 
## locale:
## [1] LC_COLLATE=English_United States.utf8 
## [2] LC_CTYPE=English_United States.utf8   
## [3] LC_MONETARY=English_United States.utf8
## [4] LC_NUMERIC=C                          
## [5] LC_TIME=English_United States.utf8    
## 
## time zone: America/Chicago
## tzcode source: internal
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
##  [1] class_7.3-22     caret_6.0-94     lattice_0.21-8   scales_1.2.1    
##  [5] kableExtra_1.3.4 knitr_1.43       corrr_0.4.4      ggpubr_0.6.0    
##  [9] ggplot2_3.4.3    stringr_1.5.0    dplyr_1.1.2     
## 
## loaded via a namespace (and not attached):
##  [1] tidyselect_1.2.0     viridisLite_0.4.2    timeDate_4022.108   
##  [4] farver_2.1.1         fastmap_1.1.1        pROC_1.18.4         
##  [7] digest_0.6.33        rpart_4.1.19         timechange_0.2.0    
## [10] lifecycle_1.0.3      survival_3.5-5       magrittr_2.0.3      
## [13] compiler_4.3.1       rlang_1.1.1          sass_0.4.7          
## [16] tools_4.3.1          utf8_1.2.3           yaml_2.3.7          
## [19] data.table_1.14.8    ggsignif_0.6.4       labeling_0.4.2      
## [22] plyr_1.8.8           xml2_1.3.5           abind_1.4-5         
## [25] withr_2.5.0          purrr_1.0.2          stats4_4.3.1        
## [28] nnet_7.3-19          grid_4.3.1           fansi_1.0.4         
## [31] colorspace_2.1-0     future_1.33.0        globals_0.16.2      
## [34] iterators_1.0.14     MASS_7.3-60          cli_3.6.1           
## [37] crayon_1.5.2         rmarkdown_2.24       generics_0.1.3      
## [40] rstudioapi_0.15.0    future.apply_1.11.0  reshape2_1.4.4      
## [43] httr_1.4.7           cachem_1.0.8         splines_4.3.1       
## [46] parallel_4.3.1       rvest_1.0.3          vctrs_0.6.3         
## [49] hardhat_1.3.0        webshot_0.5.5        Matrix_1.6-1.1      
## [52] jsonlite_1.8.7       carData_3.0-5        car_3.1-2           
## [55] rstatix_0.7.2        listenv_0.9.0        systemfonts_1.0.4   
## [58] foreach_1.5.2        gower_1.0.1          tidyr_1.3.0         
## [61] jquerylib_0.1.4      recipes_1.0.8        parallelly_1.36.0   
## [64] glue_1.6.2           codetools_0.2-19     lubridate_1.9.2     
## [67] stringi_1.7.12       gtable_0.3.4         munsell_0.5.0       
## [70] tibble_3.2.1         pillar_1.9.0         htmltools_0.5.6     
## [73] ipred_0.9-14         lava_1.7.2.1         R6_2.5.1            
## [76] evaluate_0.21        highr_0.10           backports_1.4.1     
## [79] broom_1.0.5          bslib_0.5.1          Rcpp_1.0.11         
## [82] svglite_2.1.1        nlme_3.1-162         prodlim_2023.08.28  
## [85] mgcv_1.8-42          xfun_0.40            ModelMetrics_1.2.2.2
## [88] pkgconfig_2.0.3
