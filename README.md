# EHRtemporalVariability-shiny

`EHRtemporalVariability-shiny` is an R Shiny app for delineating temporal dataset shifts in Eletronic Health Records. This app uses and complements the R `EHRtemporalVariability` package (https://github.com/hms-dbmi/EHRtemporalVariability).

## What is this repository for?

The `EHRtemporalVariability-shiny` R Shiny app provides a graphical user interface to delineate temporal dataset shifts in Electronic Health Records through the projection and visualization of differences among data temporal batches. This is done through the estimation of data statistical distributions over time and their projection in non-parametric statistical manifolds uncovering the patterns of the data latent temporal variability. Results can be explored through visual analytics formats such as Data Temporal heatmaps and Information Geometric Temporal (IGT) plots [1,2,3]. The supporting [EHRtemporalVariability R package](https://github.com/hms-dbmi/EHRtemporalVariability) can be used for more detailed and personalized analysis by users experienced in R coding.

Note that there are two shiny app R files:

* __EHRtemporalVariabilityShinyAppForLocalUse.R__: Besides the embedded demo and the loading of .RData files, it includes the loading and processing of csv files with raw data at individual level.
* __EHRtemporalVariabilityShinyAppForPublicUse.R__: It does not include the csv functionality.

## On line demo

An on line demo of the EHRtemporalVariability shiny app is available at http://ehrtemporalvariability.upv.es/

## Package Status

* __Version__: 1.0.1
* __Authors__: Carlos S�ez (UPV-HMS), Alba Guti�rrez-Sacrist�n (HMS), Isaac Kohane (HMS), Juan M Garc�a-G�mez (UPV), Paul Avillach (HMS)
* __Maintainer__: Carlos S�ez (UPV-HMS)
 
Copyright: 2019 - Biomedical Data Science Lab, Universitat Polit�cnica de Val�ncia, Spain (UPV) - Department of Biomedical Informatics, Harvard Medical School (HMS)

## Citation

A paper describing the EHRtemporalVariability package has been submitted. If you use EHRtemporalVariability, please cite:

S�ez C, Guti�rrez-Sacrist�n A, Kohane I, Garc�a-G�mez JM, Avillach P. EHRtemporalVariability: delineating temporal dataset shifts in Electronic Health Records. (Submitted)

The original methods and case studies using the approach are described here:

[1]: S�ez C, Rodrigues PP, Gama J, Robles M, Garc�a-G�mez JM. Probabilistic change detection and visualization methods for the assessment of temporal stability in biomedical data quality. Data Mining and Knowledge Discovery. 2015;29:950–75. https://doi.org/10.1007/s10618-014-0378-6

[2]: S�ez C, Zurriaga O, P�rez-Panad�s J, Melchor I, Robles M, Garc�a-G�mez JM. Applying probabilistic temporal and multisite data quality control methods to a public health mortality registry in spain: A systematic approach to quality control of repositories. Journal of the American Medical Informatics Association. 2016;23:1085–95. https://doi.org/10.1093/jamia/ocw010

[3]: S�ez C, Garc�a-G�mez JM. Kinematics of Big Biomedical Data to characterize temporal variability and seasonality of data repositories: Functional Data Analysis of data temporal evolution over non-parametric statistical manifolds. International Journal of Medical Informatics. 2018;119:109–24. https://doi.org/10.1016/j.ijmedinf.2018.09.015

