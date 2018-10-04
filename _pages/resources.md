---
title: "Data and Research Resources"
permalink: /resources/
author_profile: true
---

## [Random regression genomic prediction](http://malachycampbell.github.io/resources/RR_GP)

The objective of this study was to demonstrate the utility of random regression (RR) models using Legendre polynomials for genomic prediction of shoot growth trajectories in rice (Oryza sativa). This repo contains all the code and data used for the manuscript: "Utilizing random regression models for genomic prediction of a longitudinal trait derived from high-throughput phenotyping". Check out the preprint [here](https://www.biorxiv.org/content/early/2018/05/11/319897). To run the genetic analyses, users should have [ASREML](https://www.vsni.co.uk/downloads/asreml/) installed. All the code is presented in Rmarkdown, and the '.as' files used for ASREML are included as snippets in the .Rmd files. The contents are layed out according to the order presented in the paper. All input and output is provided in DataandCode.zip. Refer to the README for a brief description of the contents.

## [Random regression GWAS](http://malachycampbell.github.io/resources/RR_GWAS)

This study builds off the approach used for our 2018 Plant Direct paper where we used RR for genomic prediction of shoot growth trajectories. Breifly, this approach estimates marker effects from breeding values obtained using a random regression model, and estimates the marker variance and corresponding p-values. The pipeline uses both ASREML and R. To predict the breeding values, users should have ASREML installed. Alternativly, you can just use the ".sln" files that are provided. All the code is presented in Rmarkdown, and the '.as' files used for ASREML are included as snippets in the .Rmd files. The contents are layed out according to the order presented in the methods section of the paper. All input and output is provided in DataandCode.zip. Refer to the README for a brief description of the contents.

**More to come**
