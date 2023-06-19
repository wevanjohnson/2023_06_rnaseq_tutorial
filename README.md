# RNA-Seq Tutorial 6/20/2023
This is an RNA-seq tutorial taught at Makerere University on June 2023

You will first need R and RStudio:

https://www.r-project.org

https://posit.co/download/rstudio-desktop/

You will need to install the following R packages:

	if (!requireNamespace("BiocManager", quietly = TRUE))
		install.packages("BiocManager")
	BiocManager::install("Rsubread")
	BiocManager::install("Rsamtools")

You may also want to install the following for downstream analysis: 

	install.packages("devtools")
	devtools::install_github("wevanjohnson/singleCellTK")

