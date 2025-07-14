# Raw Data
This folder contains the **raw input data** used for rooting the tree of life using ancient gene duplications (ATP synthase subunits, COG0055 and COG0056), downloaded June 2025. 
Due to file size limitations, **some raw data files are not included in the repository**. Please follow the instructions below to manually download them.

### COG Database (2024 Release)
- **Files needed**:
  - `COGorg-2024.faa` – All protein sequences
  - `cog-20.cog.csv` – Functional annotations
 - **Source**: [NCBI FTP](https://ftp.ncbi.nlm.nih.gov/pub/COG/COG2020/data/)
 - **Download instructions**:
    ```bash
    wget ftp://ftp.ncbi.nlm.nih.gov/pub/COG/COG2024/data/COG2024-*.faa.gz
    wget ftp://ftp.ncbi.nlm.nih.gov/pub/COG/COG2024/data/cog-24.cog.csv
    gunzip COGorg24.faa.gz

### GTDB Representative Genome Metadata
- **Files needed**:
  - `GTDB-Bacteria-domain-GTDB-rep-metadata.tsv`
  - `GTDB-Archaea-domain-GTDB-rep-metadata.tsv`
- **Source**: [Genome Taxonomy Database (GTDB)](https://gtdb.ecogenomic.org/).
- **Download instructions**:
  ```bash
  wget https://data.gtdb.ecogenomic.org/releases/release214/214.0/bac120_metadata.tsv 
  wget https://data.gtdb.ecogenomic.org/releases/release214/214.0/ar53_metadata.tsv 
Note that these files must be filtered by >90% completeness and <5% contamination to obtain high-quality representative genomes. 
