# Single-Cell RNA and ATAC-Seq Analysis for MLL-AF9 Leukemic Model

\================================================================

This repository contains code for single-cell RNA and ATAC-Seq analysis of the MLL-AF9 leukemic model across different time points. The analysis is performed using **Scanpy** and **Seurat/Signac**.

# Key Features:

* * *

*   **Data Import & Preprocessing**: Loading datasets and filtering low-quality cells
*   **Doublet Removal**: Identifying and removing doublets
*   **Cell Type Annotation**: Assigning cell identities
*   **Cell Population Analysis**: Investigating MSC and bone marrow cell populations
*   **Chromosomal Status Changes**: Analyzing genomic alterations
*   **Cell-Cell Interaction Analysis**: Studying intercellular communication
*   **Genome Modification & Processing**: The genome was modified by introducing **oncogenic fusion MLL-AF9** and **human HNGFR receptor genes** via retroviral expression. This modified genome was used for **Cell Ranger** processing to generate single-cell gene expression and chromatin accessibility data.

This repository provides a comprehensive workflow for exploring leukemic progression at the single-cell level.

