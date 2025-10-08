# 🧬 Orthologous Genes of *Tribolium castaneum* and *Drosophila melanogaster*

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![BMC Genomic Data](https://img.shields.io/badge/Journal-BMC%20Genomic%20Data-blue.svg)](https://www.biomedcentral.com/journals/genomicdata)

This repository contains the data and scripts produced for the paper:

> **“Orthologous genes of the red flour beetle *Tribolium castaneum* and the vinegar fly *Drosophila melanogaster*”**  
> *Submitted to BMC Genomic Data*

---

## 📖 Table of Contents
- [Repository Overview](#repository-overview)
- [File Descriptions](#file-descriptions)
  - [1. OrthoFinder_orthology.tsv](#1-orthofinder_orthologytsv)
  - [2. Eggnog6_orthology.tsv](#2-eggnog6_orthologytsv)
  - [3. Manually_checked_genes.zip](#3-manually_checked_geneszip)
  - [4. Comparison_one-to-one_orthologs.xlsx](#4-comparison_one-to-one_orthologsxlsx)
- [Citation](#citation)
- [License](#license)
- [Contact](#contact)

---

## 🧾 Repository Overview

This repository provides orthology data and supporting files generated for the comparison between *Drosophila melanogaster* and *Tribolium castaneum*.  
The datasets and scripts facilitate reproduction of the results and independent analysis of orthologous relationships.

---

## 📂 File Descriptions

### 1. `OrthoFinder_orthology.tsv`
Orthologs identified using **OrthoFinder** between *Drosophila melanogaster* and *Tribolium castaneum*.

- Plain text, tab-separated format for easy parsing and scripting.
- Also available via **[iBeetleBase](https://ibeetle-base.uni-goettingen.de/)** as a visually searchable database.

---

### 2. `Eggnog6_orthology.tsv`
Orthologs retrieved from the **eggNOG v6** database.

- Plain text format for easy viewing and automation.
- Data also accessible in **iBeetleBase** for visual exploration.

---

### 3. `Manually_checked_genes.zip`
A compressed archive containing phylogenetic trees and all supporting files required to reproduce them.

**Contents include:**

| File | Description |
|------|--------------|
| `0.Ncbi_genome_used_to_build_trees.tsv` | List of organisms, taxonomic information, proteome IDs, and source databases. |
| `1.Scripts_for_building_trees.py` | Python script used to generate phylogenetic trees. |
| `2.Methods.txt` | Detailed explanation of software, parameters, and methodological decisions. |
| `3.Manually_checked_genes.xlsx` | Table summarizing manually analyzed genes, including comparison between OrthoFinder and eggNOG results. |
| `<Gene>.pdf` | Individual phylogenetic trees in PDF format, each named after the corresponding *Drosophila* gene. |

---

### 4. `Comparison_one-to-one_orthologs.xlsx`
Contains information on **one-to-one orthologs** computed by both OrthoFinder and eggNOG for direct comparison.

---

## 🧾 Citation

If you use this repository or its contents, please cite the following paper once it is published:

> *“Orthologous genes of the red flour beetle Tribolium castaneum and the vinegar fly Drosophila melanogaster.”*  
> *BMC Genomic Data (in review).*

You may also cite the dataset directly via its DOI (Preprint):

> **DOI:** [https://doi.org/10.21203/rs.3.rs-5259973/v1](https://doi.org/10.21203/rs.3.rs-5259973/v1)


---

## 📜 License

This repository is released under the **[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**.  
You are free to share and adapt the material, provided appropriate credit is given.

---

## 📬 Contact

For questions, suggestions, or data requests, please contact:

**Noel Cabañas**  
University of Göttingen,
Dept. of Evolutionary Developmental Genetics  
📧 ncabanas@uni-goettingen.de  


---

*Last updated: October 2025*
