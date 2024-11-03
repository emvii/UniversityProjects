# BIOL0042 Plant Evolution and Ecology Temperate Zone Workshop Assignment

## Objective
This repository contains code and data for analysing convergent versus non-convergent plant traits in temperate biogeographic regions. The project evaluates morphological traits of plant species from RBG Kew's Temperate House to investigate patterns of evolutionary convergence. The code provided processes quantitative and qualitative leaf measurements, comparing trait averages and variances across regions.

When knit, the code outputs statistical analyses and visualizations of trait distribution across sampled species, supporting hypotheses on adaptive convergence. Detailed findings and methodology are documented in `Temperate-Zones-Convergence-REPORT.pdf`.

## Requirements
The code was developed and tested in RStudio version 2023.12.1 with R version 4.1.2 (2021-11-01)

### Data
The repository includes the CSV file `cleaned_traits_file.csv`, which contains quantitative and qualitative measurements for each plant species sampled. This file should be kept in the `data/` folder for the code to run properly. 

### Dependencies
List of required packages:

- stats
- ggplot 2
- gridExtra
- dplyr
- lmtest
- boot
- knitr
- stats

## Installation
To get the code running on your local machine, follow these steps:

- Clone the repository or download the source code.
- Navigate to the code directory.

## Usage
To execute the code: Open Rstudio, then open `plant_evo_eco_ver4.Rmd` and run all chunks.

(This work was completed as part of the UCL year 3 module titled BIOL0042 Plant Evolution and Ecology)
