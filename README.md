<img src="swiss-votes-logo.png" width="200" alt="An icon combining the red Swiss shield with a white cross and a ballot box indicating a vote.">

# 175 Years of Direct Democracy: A Quantitative Analysis of Swiss Federal Votes

[![View Live Project](https://img.shields.io/badge/View-Live_Project-blue?style=for-the-badge&logo=github)](https://alex-is-busy-coding.github.io/swiss-votes-viz/)

## Overview

This repository contains the source code, data analysis, and visualization scripts for a Quarto book project exploring the history and patterns of Swiss Direct Democracy.

Unlike standard representative democracies, Switzerland allows citizens to vote directly on federal laws and constitutional amendments up to four times a year. Utilizing the **Swissvotes** dataset, this project analyzes over 175 years of voting data (since 1848) to investigate:

  * Voter participation trends over time.
  * The frequency of "Double Majority" conflicts (People vs. Cantons).
  * The relationship between government recommendations and voter outcomes.
  * The influence of campaign finance in the modern era.

## Academic Context

This work was produced as the **Final Project** for the Fall 2025 graduate course:

  * **Course:** GR5702 Exploratory Data Analysis & Visualization
  * **Institution:** Columbia University
  * **Instructor:** [Joyce Robbins](mailto:jtr13@columbia.edu)

##  Tech Stack

This project is built using the **R** ecosystem and **Quarto** for publishing.

  * **Language:** R
  * **Framework:** [Quarto](https://quarto.org/) (HTML Book format)
  * **Hosting:** GitHub Pages

## Repository Structure

```text
├── docs/                   # Rendered HTML files (Published to GitHub Pages)
├── scripts/                # R scripts for data cleaning and scraping
├── swiss-votes-favicon.png # Project icon
├── swiss-votes-logo.png    # Project logo
├── index.qmd               # Introduction & project scope
├── data.qmd                # Data sourcing, description, and cleaning
├── results.qmd             # Main analysis and visualizations
├── conclusion.qmd          # Summary of findings
└── _quarto.yml             # Quarto configuration
```

## Local Setup

To run this project locally on your machine:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/alex-is-busy-coding/swiss-votes-viz.git
    cd swiss-votes-viz
    ```

2.  **Open in RStudio:**
    Open the `quarto-edav-template.Rproj` file.

3.  **Render the Book:**
    You can render the entire project via the terminal or R console:

    ```bash
    quarto render
    ```

## Author

The code and quantitative analysis for this project were developed by [Alexander Vassilev](https://github.com/alex-is-busy-coding).

