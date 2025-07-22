# AAGI HTML Draft

This package (repository) enables users to generate HTML reports for analytics projects as part of the AAGI initiative. After installing the package from GitHub, dynamic and reproducible reports can be rendered locally, compliant with AAGI templating guidelines. This repository is intended as a working draft for a report template designed to integrate with the AAGITemplates package from the AAGI-AUS repository. (https://github.com/AAGI-AUS/AAGITemplates)

## Install instructions

Install this R package on RStudio with:

```r
if(!require("remotes")) install.packages("remotes") 
remotes::install_github("AAGI-AUS/AAGI-HTML-Draft", upgrade = FALSE)
```

Once this has been installed, we can find the template added onto RStudio. The name of the package is *AAGIHTML* and this can be found under File --> New File --> RMarkdown --> From Template

<p align="center">
  <img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/d666c055-3358-4bde-a039-85e0e2be1d34" />
</p>

## Acknowledgments

This package was developed based on the original work by Dr. Dongwen Luo, a Senior Researcher at AgResearch, New Zealand. We gratefully acknowledge his contributions.

## Logo Rights

Please note that the logo of the AAGI project and the logos for the GRDC and AAGI strategic partners do not fall under the MIT License. AAGI retains full rights to the AAGI logo. The GRDC and the AAGI strategic partners—Curtin University, the University of Queensland and the University of Adelaide/Adelaide University—retain full rights to their own logos respectively.

```
📦 AAGI-HTML-DRAFT
├─ DESCRIPTION
├─ NAMESPACE
├─ README.md
└─ inst
   └─ rmarkdown
      └─ templates
         └─ AAGI HTML
            ├─ skeleton
            │  ├─ UQtstyles.css
            │  ├─ header.html
            │  ├─ images
            │  │  ├─ AAGI.png
            │  │  └─ Partners.png
            │  └─ skeleton.Rmd
            └─ template.yaml
```
