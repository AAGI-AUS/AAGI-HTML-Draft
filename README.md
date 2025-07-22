# AAGI HTML Draft

This package (repository) enables users to generate HTML reports by executing pre-built templates. After downloading the repository from GitHub, reports can be rendered locally with minimal configuration. The aim of this repository is to be able to combine this with the AAGITemplates package available in the AAGI-AUS repository

## Install instructions

Install this R package on RStudio with:

```r
if(!require("remotes")) install.packages("remotes") 
remotes::install_github("AAGI-Org-AU/AAGI-HTML-Draft", upgrade = FALSE)
```

Once this has been installed, we can find the template added onto RStudio. The name of the package is *AAGIHTML* and this can be found under File --> New File --> RMarkdown --> From Template

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/d666c055-3358-4bde-a039-85e0e2be1d34" />

