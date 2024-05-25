# Introduction
This lab explores spatial statistics techniques using R, focusing on analyzing heavy metal concentrations in topsoil data. The analysis includes tasks such as exploring spatial patterns, fitting regression models, variogram calculations, kriging, and model diagnostics.

## Getting Started
To reproduce the analysis and visualize the results, follow these steps:

1. Make sure you have R and RStudio installed on your computer.
2. Download the R Markdown file (`Lab 9 Solutions.Rmd`) from this repository.
3. Open the R Markdown file in RStudio.
4. Install any required R packages mentioned in the code.
5. Run each code chunk sequentially to execute the analysis and generate plots.

## Contents
1. [Exploratory Data Analysis](#exploratory-data-analysis)
2. [Linear Regression](#linear-regression)
3. [Inverse Distance Weighted Interpolation](#inverse-distance-weighted-interpolation)
4. [Variogram Calculations](#variogram-calculations)
5. [Cutoff, Lag Width, Direction Dependence](#cutoff-lag-width-direction-dependence)
6. [Variogram Modelling](#variogram-modelling)
7. [Classify Directions](#classify-directions)
8. [Kriging](#kriging)
9. [Model Diagnostics](#model-diagnostics)
10. [Conclusion](#conclusion)

## Exploratory Data Analysis
In this section, we explore the spatial distribution of zinc concentrations and their relationship with distance to the river.

## Linear Regression
A linear regression model is fitted to examine the relationship between zinc concentration and distance to the river. Maps with fitted values and residuals are plotted.


## Inverse Distance Weighted Interpolation
IDW interpolation is performed to estimate zinc concentrations across the study area.


## Variogram Calculations
Variograms are calculated to analyze spatial dependence and autocorrelation in the data.


## Cutoff, Lag Width, Direction Dependence
Variograms are plotted with different cutoffs and directional dependence.

## Variogram Modelling
Variogram modelling is performed to fit theoretical models to the empirical variogram.


## Classify Directions
Variogram directions are classified into intervals to analyze directional dependence.

## Kriging
Simple, ordinary, and universal kriging techniques are applied to interpolate zinc concentrations.

## Model Diagnostics
Cross-validation is performed to assess the predictive performance of the kriging models.


## Conclusion
In this lab, we conducted a comprehensive analysis of heavy metal concentrations in topsoil data using spatial statistics techniques. The results indicate a significant relationship between zinc concentration and distance to the river. Additionally, kriging proved to be an effective method for spatial interpolation. Further research could explore additional factors influencing heavy metal distribution and refine the predictive models.
