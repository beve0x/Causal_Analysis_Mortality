# Causal_Analysis_Mortality
# Causal Analysis of MLDA on Mortality Rates

## Overview

This repository is dedicated to a causal analysis of the Minimum Legal Drinking Age (MLDA) on mortality rates, particularly focusing on motor vehicle accidents (MVA), a leading cause of death among young adults. Using R, this project employs a regression discontinuity design to estimate the causal effect of reaching the MLDA on mortality rates, a robust method in causal inference studies.

## Table of Contents

- [Introduction](#introduction)
- [Data Source](#data-source)
- [Causal Inference Approach](#causal-inference-approach)
- [Methodology](#methodology)
  - [Data Preparation](#data-preparation)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Regression Discontinuity Design](#regression-discontinuity-design)
- [Results](#results)
- [Visualizations](#visualizations)
- [Getting Started](#getting-started)
- [Contributing](#contributing)

## Introduction

The goal of this analysis is to evaluate the causal impact of the MLDA on mortality rates using statistical methods that can provide insights into policy effectiveness. This study may help policymakers understand and improve current laws related to drinking age and public health.

## Data Source

The dataset used in this analysis, `all.dta`, originates from a large-scale public health study and is read into R using the `haven` package.

## Causal Inference Approach

This project utilizes a quasi-experimental design, specifically a regression discontinuity design, to assess the causal relationship between MLDA and mortality rates. This method provides a credible estimation of causal effects by exploiting the cutoff at which individuals legally reach the drinking age.

## Methodology

### Data Preparation

Data is transformed to reflect mortality rates standardized by population and age.

### Exploratory Data Analysis

Initial exploratory analysis computes mean mortality rates for individuals just below and just above the MLDA, highlighting potential causal effects of the law.

### Regression Discontinuity Design

A detailed regression analysis is conducted to estimate the causal effect at various bandwidths around the MLDA threshold. This includes linear models with and without interaction terms to capture the complexity of the law's impact across different ages.

## Results

The findings suggest a significant change in mortality rates at the MLDA threshold, which is consistent with the presence of a causal effect of the MLDA law on mortality rates.

## Visualizations

Scatter plots are provided to visually represent the distribution of mortality rates in relation to the MLDA threshold, aiding in the interpretation of the regression discontinuity analysis.

## Getting Started

Instructions to set up the R environment, install necessary packages, and run the analysis scripts are provided, ensuring replicability of the study.

## Contributing

Guidelines for how to contribute to the project are outlined, welcoming further analysis, methodological enhancements, and discussions.

