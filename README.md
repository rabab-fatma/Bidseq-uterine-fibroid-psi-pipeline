# BID-seq Ψ Detection in Uterine Fibroids

> Status: In active development (internal use). Public release planned once the workflow is finalized and associated manuscript is submitted.

This repository will host a **Snakemake pipeline** for processing BID-seq and paired RNA-seq data to detect pseudouridine (Ψ) sites in uterine fibroid samples.

The pipeline is designed for **HPC environments** and currently supports:

- FastQ QC and trimming  
- Genome index management  
- Alignment with STAR  
- BID-seq–specific Ψ site quantification  
- Sample-level and gene-level summary reports  

---

## Planned contents

Once ready for public release, this repository will include:

- `Snakefile` and modular workflow rules  
- `config/` with example YAML configs for different experiments  
- `envs/` with conda environment definitions  
- `scripts/` for custom processing and plotting  
- `docs/` with usage instructions and example run commands  
- Optional small **toy dataset** or synthetic example

---

## Data availability

This project uses **sensitive clinical RNA-seq / BID-seq data**, which **cannot be shared** in this repository.

When the code is released, it will be accompanied by:

- Instructions for users to run the pipeline on their own data  
- Optionally, a very small synthetic or simulated dataset for testing

---

## Current status (internal)

- [x] Working Snakemake workflow for 14+ samples on internal HPC  
- [x] Initial QC, alignment, and Ψ quantification modules  
- [ ] Generalized configuration for arbitrary sample sets  
- [ ] Documentation and example configs for public users  
- [ ] Synthetic test dataset and tutorial notebook
