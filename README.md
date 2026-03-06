Comprehensive Assessment: Puerto Rico Hurricane Mortality
=========================================================
Introduction
------------
On September 20, 2017, Hurricane María made landfall on Puerto Rico. It was the worst natural disaster on record in Puerto Rico and the deadliest Atlantic hurricane since 2004. However, Puerto Rico's official death statistics only tallied 64 deaths caused directly by the hurricane (due to structural collapse, debris, floods and drownings), an undercount that slowed disaster recovery funding. The majority of the deaths resulted from infrastructure damage that made it difficult to access resources like clean food, water, power, healthcare and communications in the months after the disaster, and although these deaths were due to effects of the hurricane, they were not initially counted.

In order to correct the misconception that few lives were lost in Hurricane María, statisticians analyzed how death rates in Puerto Rico changed after the hurricane and estimated the excess number of deaths likely caused by the storm. This analysis suggested that the actual number of deaths in Puerto Rico was 2,975 (95% CI: 2,658-3,290) over the 4 months following the hurricane, much higher than the original count.

This project demonstrates the use of data wrangling skills to extract actual daily mortality data from Puerto Rico and investigate whether the Hurricane María had an immediate effect on daily mortality compared to unaffected days in September 2015-2017.

_**Note:** This project was originally constructed and submitted towards completion of requirements for the [**HarvardX PH125.6x Data Science: Wrangling**](https://www.edx.org/learn/data-science/harvard-university-data-science-wrangling) certificate, in March 2026._

Installation and Setup
======================
Codes and Resources
-------------------
- **Editor:** RStudio 2026.01.0 Build 392
- **R Version:** 4.5.0 (2025-04-11 ucrt)

R Packages Used
---------------
The following libraries and options are required to complete the assignment

> `library(dslabs)`
> 
> `library(tidyverse)`
> 
> `library(pdftools)`
> 
> `options(digits = 3)  # report 3 significant digits`

Data
====
Source Data
-----------
The source data for this project can be found in the `extdata` directory of the **dslabs** package, which contains the daily mortality data for Puerto Rico from Jan 1, 2015 to May 31, 2018.

Data Acquisition
----------------
Once the dslabs package is installed, the file is located in the package's external data directory, accessed in R using a command like this:

>`fn <- system.file("extdata", "RD-Mortality-Report_2015-18-180531.pdf", package="dslabs")`

Data Preprocessing
------------------
The source data is not presumed to meet [**tidy data** standards](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html). Additional data wrangling will likely be required.







