# CAMDA

The data has been normalized using RMA.

Please install the below packages before running the notebook.

### Update all R packages
update.packages(ask = FALSE, repos = 'https://cran.rstudio.org')

### Packages to be installed
install.packages("openxlsx") <br/>

### Mutation Part
install.packages("dplyr") <br/>

### Packages for RMA Normalization
source("https://bioconductor.org/biocLite.R") <br/>
biocLite("limma") <br/>
biocLite("affy") <br/>
biocLite("hgu133acdf") <br/>
biocLite("hthgu133acdf")

### Package to unzip the files
install.packages("R.utils") <br/>
