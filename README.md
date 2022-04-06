# CIBERSORT-DATA
 CIBERSORT data

```R
rm(list = ls())

##### 肿瘤免疫微环境CIBERSORT #####

source("https://gist.githubusercontent.com/SiYangming/89b45538f412e8cf807c396ed6c72cb8/raw/fb4ea344e4df5436629fb14c1bb71c0967d0e245/CIBERSORT.R")
results = CIBERSORT("inst/CIBERSORT/LM22.txt",
                    "data-raw/CIBERSORT-input.txt",
                    perm = 100, QN = TRUE)
```

