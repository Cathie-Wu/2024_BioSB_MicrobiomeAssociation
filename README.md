# 2024_BioSB_MicrobiomeAssociation

This repository contains materials for the Wednesday morning practical session of the Computational Metagenomics module for the BioSB Advanced course! This session will cover the following key topics:

- **Loading and Preparing Data**: Loading microbiome species abundance and phenotype data, cleaning taxonomy names, and rescaling data.
- **Alpha Diversity**: Calculating Shannon diversity and species richness metrics, followed by statistical testing.
- **Beta Diversity**: Performing Principal Coordinates Analysis (PCoA) to visualize differences in microbiome composition.
- **PERMANOVA**: Estimating variance explained by different factors.
- **Filtering and CLR Transformation**: Filtering species based on abundance and prevalence, and applying centered log-ratio transformation.
- **Sequencing Depth Adjustment**: Evaluating sequencing depth influence on diversity and species abundance.
- **Association Analysis**: Conducting unadjusted and adjusted association analyses between microbial species and phenotypes.
- **Mediation Analysis**: Exploring the relationship between fruit intake, species abundance, and glucose levels.

## Questions

Run the code and think about the interpretation of the plots and model output. Try to answer the following:

1. What is the purpose of **rescaling** the microbiome table (total species abundance sum to 1), and how might it impact subsequent analyses?
2. In the **beta diversity** analysis, why is **Principal Coordinates Analysis (PCoA)** used, and what information do the first two principal coordinates provide?
3. In **PERMANOVA**, does the order of the variables matter? How might changing the order of the variables affect the interpretation of the results?
4. What criteria did we use to filter species before conducting association analysis? Why is it important to filter out less abundant and less prevalent species?
5. What are the **ACME** (Average Causal Mediation Effect) and **ADE** (Average Direct Effect), and what do they tell us about the relationship between fruit intake, *Eubacterium eligens*, and glucose levels?
