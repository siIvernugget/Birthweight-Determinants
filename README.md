# Econometrics Case Study: Determinants of Birth Weight
This repository contains an econometric analysis, as part of a university project, of factors influencing infant birth weight, based on data from the 1989 National Natality-Mortality Detail files (Almond, Chay, and Lee, 2005). The analysis is performed using R and compiled into a LaTeX report using knitr.

## Overview
* **`birthweight.Rnw`**: The main source file. Contains LaTeX code for the report and R code for the analysis (Knits to PDF).
* **`sources.bib`**: The bibliography file containing references in BibTeX format.
* **`birthweight_smoking.xlsx`**: The raw dataset used for the analysis.
* **`Task Description.pdf`**: Task Description.
* **`birthweight.pdf`**: The final compiled report.

## Prerequisites
To run the analysis and compile the PDF, make sure to install and run the following packages:

    ```r
    install.packages(c("tidyverse", "readxl", "knitr", "formatR", "tinytex"))
    ```

## How to Compile
To compile the PDF, follow these steps:
1.  Make sure your compiler is set to "knitr". To do that go to Tools-> Global Options-> Sweave-> Select: "Weave Rnw files using **knitr**" and "Typeset LaTeX into PDF using **pdfLaTeX**
1.  Open `birthweight.Rnw` in RStudio.
2.  Click the **Compile PDF** button.
