# CAMDA

The data has been normalized using RMA.

Please install the below packages before running the notebook.

### Update all R packages
update.packages(ask = FALSE, repos = 'https://cran.rstudio.org')

### Packages to be installed
install.packages("openxlsx") <br/>
install.packages("pbkrtest", dependencies = TRUE) <br/>
install.packages("rpart") <br/>
install.packages("caret") <br/>

### These packages only for the visualization of data clearning part

install.packages("magrittr") <br/>
install.packages("kableExtra") <br/>
install.packages("formattable") <br/>
install.packages("knitr")


### Packages for PC3 Data Setup
source("https://bioconductor.org/biocLite.R") <br/>
biocLite("limma") <br/>
biocLite("affy") <br/>
biocLite("hgu133acdf") <br/>
biocLite("hthgu133acdf")


### Package to unzip the files
install.packages("R.utils") <br/>
