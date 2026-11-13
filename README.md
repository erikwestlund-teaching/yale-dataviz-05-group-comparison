# AI-Augmented Analytics for Data Visualization, Module 7: Group Comparison

The steps and worked examples are in the module guide on the course page.

## Installation

1. Download and unzip this project, or clone this repository.
2. Install R and Quarto. Open the `.Rproj` file in RStudio, or open the folder in Positron.
3. Run `source("setup.R")` once in the R console.
4. Open `notebooks/05_group-comparison.qmd` and build the figures with your assistant.
5. Render the notebook with `quarto render notebooks/05_group-comparison.qmd` from the project folder.

## Contents

- `notebooks/05_group-comparison.qmd`: the module task.
- `inputs/raw/nhanes_2021_2023_analysis.csv` and its codebook in `inputs/raw/codebooks/`.
- `inputs/raw/prams_2011_selected.csv` and its codebook in `inputs/raw/codebooks/`.
- `setup.R`: required R packages.
- `_quarto.yml`: notebook rendering settings.

PRAMS values are location and subgroup percentages. Alcohol use, binge drinking, depression, and anxiety refer to the three months before pregnancy. The legacy column names contain `birth`.
