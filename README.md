# Co-Purchase Network Analysis

This project models the DataCo Supply Chain dataset as a weighted co-purchase network, where nodes are products and edges represent how often two products appear in the same order. The goal is to describe the network structure, detect latent product groups, and identify the product/order characteristics that drive joint purchasing.

## Contents 

- **Descriptive analysis**: degree and strength distributions, centrality measures (strength, betweenness), density and transitivity.
- **Sampling sensitivity**: comparison of induced, incident, and snowball sampling against the full-network average strength.
- **Stochastic Blockmodel (SBM)**: binary SBM to detect latent product groups based on co-purchase connection profiles.
- **Exponential Random Graph Model (ERGM)**: Poisson-reference ERGM to model how price, discount, category, and scheduled delivery time affect co-purchase frequency.

## Requirements
 - **R** ≥ 4.2.0
```r
install.packages(c(
  "dplyr", "tidyr", "readr", "janitor", "purrr",
  "ggplot2", "gridExtra",
  "igraph", "network", "intergraph",
  "sbm", "ergm", "ergm.count"
))
```

## Source

https://data.mendeley.com/datasets/8gx2fvg2k6/5

## Contributors

- Lorenzo Galli
- Matteo Giuseppetti
- Gabriele Trentin
