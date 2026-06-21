# -basic-data-analysis-tasks-performed-in-R
This report presents basic data analysis tasks performed in R on biological datasets. The aim was to practice data cleaning, transformation, and simple analysis using real-world biological data.

## Analysis of piRNA pathway gene data

A dataset containing gene counts related to the piRNA pathway was analyzed. Missing values were replaced with zeros to ensure proper calculations.
A new variable (total_genes) was created by summing the expression levels of selected genes (AGO1, AGO2, Piwi, AGO3) for each observation.
This allowed for a simplified overview of total gene activity across samples.

## Structural variant analysis

A dataset of structural variants was analyzed, focusing on translocation events (TYPE = "TRANS").
A new variable (shift_bp) was calculated as the difference between query start and reference start positions. Based on this value, a categorical variable (direction) was created to indicate whether the shift was forward or backward.
This simple transformation demonstrates how genomic positional data can be processed and interpreted.
