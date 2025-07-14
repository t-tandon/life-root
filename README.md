# Rooting the Tree of Life using Ancient Gene Duplications

This project investigates the rooting of the tree of life by analyzing ancient gene duplications across a diverse set of bacterial and archaeal genomes.

## Project Overview
**Goal:** Reconstruct phylogenetic trees using ancient paralogs to root the tree of life 

**Paralog pair used:**
- COG0056: ATP synthase, alpha subunit
- COG0055: ATP synthase, beta subunit

## Directory Structure
- `data/`: Raw and processed input data
- `genomes/`: Genomes and predicted protein sequences
- `results/`: Alignments, HMMER hits, and phylogenetic trees
- `scripts/`: Bash scripts for reproducible workflow

## Workflow Steps
- Identify ancient paralogs suitable for rooting
- Obtain and align protein sequences
- Select high-quality representative genomes
- Perform HMM-based homology searches
- Construct phylogenetic trees


## Tools used: 
`wget`, `gunzip`, `seqtk`, `cd-hit`, `mafft`, `prodigal`, `hmmer`, `alan_dt`, `iqtree`, `fasttree`

## Reference
[PNAS 1989](https://www.pnas.org/doi/10.1073/pnas.86.23.9355)
