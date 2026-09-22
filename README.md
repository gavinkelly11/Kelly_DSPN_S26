# Real-Time Drink Preferences in Context: An EMA Study
## Overview
Main file: Kelly_DSPN_S26_FinalProject.ipynb. An R-based analysis of 950,000+ real-time choices exploring how environmental context shapes preferences for alcoholic vs. non-alcoholic beverages using Ecological Momentary Assessment (EMA).

## Background
Traditional EMA alcohol use studies typically reduce drinking behavior to simple quantity measures, overlooking the nuanced decision-making process behind what and when people drink. Because real-world choices are often constrained by availability, drinking behavior alone does not completely capture true preferences.

This project explores preference patterns in natural contexts to understand how environmental, social, and emotional factors shape the decision to drink beyond a simple "drink/don't drink" binary.

## Methodology & Data
To separate preference from availability, we utilized an experimental hypothetical choice task during EMA assessments.

Participants: 250 individuals.

Assessments: 160 choices between alcoholic and non-alcoholic drinks per assessment.

Total Dataset: 951,028 unique choices combined with rich contextual data.

By presenting diverse choices across varying baseline preference levels, the dataset allows for unprecedented examination of which contexts lead individuals to reverse their baseline preferences.

## Repository Contents
This repository contains the R-based Jupyter Notebook (Kelly_DSPN_S26_FinalProject.ipynb) used for the final project analysis, featuring:

Descriptive Statistics: Baseline preference levels and context-specific summaries.

Data Visualizations: Mapping preference shifts across different social and emotional contexts.

Statistical Analyses: Evaluating the functions different drinks serve (e.g., stress relief, social lubrication) and identifying when non-alcoholic alternatives are most likely to curtail drinking.

## Implications
Understanding these real-time preference patterns provides benchmark data for future research into the functions of different drinks and lays the groundwork for highly adaptable, context-aware interventions for Alcohol Use Disorder.

## Tech Stack
Language: R

Environment: Jupyter Notebook

Key Libraries: lme4, tidyverse, ggplot2, dplyr
