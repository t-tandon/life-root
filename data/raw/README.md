# Raw Data
This folder contains the **raw input data** used for rooting the tree of life using ancient gene duplications (ATP synthase subunits, COG0055 and COG0056). 
Due to file size limitations, **raw data files are not included in the repository**. Please follow the instructions below to manually download them.

1. COG Database (2024 Release)
- **Files needed**:
  - `COGorg-2024.faa` – All protein sequences
  - `cog-20.cog.csv` – Functional annotations
 - **Source**: [NCBI FTP](https://ftp.ncbi.nlm.nih.gov/pub/COG/COG2020/data/)
 - **Downloaded on:** June 2025
 - **Download instructions**:
    ```bash
    wget ftp://ftp.ncbi.nlm.nih.gov/pub/COG/COG2024/data/COG2024-*.faa.gz
    wget ftp://ftp.ncbi.nlm.nih.gov/pub/COG/COG2024/data/cog-24.cog.csv
