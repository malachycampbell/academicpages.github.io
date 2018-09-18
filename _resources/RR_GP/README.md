<h1 align="center">
  <img alt=" Utilizing random regression models for genomic prediction of a longitudinal trait derived from high-throughput phenotyping platforms" width = "1711.846" height = "200" src = Title.svg>
</h1>

[Malachy Campbell](https://malachycampbell.github.io/), [Harkamal Walia](http://cropstressgenomics.org/), [Gota Morota](http://morotalab.org/)

## Abstract
The accessibility of high-throughput phenotyping platforms in both the greenhouse and field, as well as the relatively low cost of unmanned aerial vehicles, have provided researchers with an effective means to characterize large populations throughout the growing season. These longitudinal phenotypes can provide important insight into plant development and responses to the environment. Despite the growing use of these new phenotyping approaches in plant breeding, the use of genomic prediction models for longitudinal phenotypes is limited in major crop species. The objective of this study is to demonstrate the utility of random regression (RR) models using Legendre polynomials for genomic prediction of shoot growth trajectories in rice (*Oryza sativa*). An estimate of shoot biomass, projected shoot area (PSA), was recored over a period of 20 days for a panel of 357 diverse rice accessions using an image-based greenhouse phenotyping platform. A RR that included a fixed second-order Legendre polynomial, a random second-order Legendre polynomial for the additive genetic effect, a first-order Legendre polynomial for the environmental effect, and heterogeneous residual variances was used to model PSA trajectories. The utility of the RR model over a single time point (TP) approach, where PSA is fit at each time point independently, is shown through four prediction scenarios. In the first scenario, the RR and TP approaches were used to predict PSA for a set of lines lacking phenotypic data. The RR approach showed a 11.6% increase in prediction accuracy over the TP approach. Much of this improvement could be attributed to the greater additive genetic variance captured by the RR approach. The remaining scenarios focused forecasting future phenotypes using a subset of early time points for known lines with phenotypic data, as well new lines lacking phenotypic data. In all cases, PSA could be predicted with high accuracy (*r*: 0.79 to 0.89 and 0.55 to 0.58 for known and unknown lines, respectively). This study provides the first application of RR models for genomic prediction of a longitudinal trait in rice, and demonstrates that RR models can be effectively used to improve the accuracy of genomic prediction for complex traits compared to a TP approach.

## Background
This repo contains all the code and data used for the manuscript: "Utilizing random regression models for genomic prediction of a longitudinal trait derived from high-throughput phenotyping". Check out the preprint [here](https://www.biorxiv.org/content/early/2018/05/11/319897). To run the genetic analyses, users should have [ASREML](https://www.vsni.co.uk/downloads/asreml/) installed. All the code is presented in Rmarkdown, and the '.as' files used for ASREML are included as snippets in the .Rmd files. The contents are layed out according to the order presented in the paper. All input and output is provided in [DataandCode.zip](DataandCode.zip). Refer to the README for a brief description of the contents.  

## Table of Contents

* **1. Preparation of Phenotypic Data**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/HTMLoutput/1.Phenoprep.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/1.Phenoprep.Rmd)
* **2. Preparing the 44k SNP Data**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/HTMLoutput/2.Genoprep.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/2.Genoprep.Rmd)
* **3. Selection of Random Regression Model**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/HTMLoutput/3.RRmodelselection.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/3.RRmodelselection.Rmd)
* **4. Estimating Heritability and Genetic Correlation of Shoot Growth**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/HTMLoutput/4.Heritability.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/4.Heritability.Rmd)
* **5. Scenario A: Genomic Prediction Using Random Regression and Single Time Point gBLUP**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/HTMLoutput/5.ScenarioA.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/5.ScenarioA.Rmd)
* **6. Scenarios B and C: Forecasting Future Phenotypes with Random Regression Models**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/HTMLoutput/6.ScenariosBandC.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/6.ScenariosBandC.Rmd)
* **7. Scenario D: Forecasting Future Phenotypes in an Independent Study with Random Regression Models**
  - [html output](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/HTMLoutput/7.ScenarioD.html)
  - [.Rmd File](https://rawgit.com/malachycampbell/Utilizing-random-regression-models-for-genomic-prediction-of-a-longitudinal-trait-derived-from-HTP/master/Rmarkdownfiles/7.ScenarioD.Rmd)

## Funding
*Funding for this project was provided by the National Science Foundation through the Plant Genome Reasearch Program grant [(#1238125)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1238125) awarded to HW and a Research Infrastructure Improvement (RII) Track-2 Focused EPSCoR grant [(#1736192)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1736192) awarded to HW and GM.*

[![DOI](https://zenodo.org/badge/138613689.svg)](https://zenodo.org/badge/latestdoi/138613689)
---

<img align = "left" alt="WRCHR" src = WRCHR.png width = "200" height = "65.43491">
<img align = "left" alt="NSF" src = nsf_logo.png width = "65.43491" height = "65.43491"/>
