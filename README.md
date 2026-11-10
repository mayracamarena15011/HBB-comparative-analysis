# Cross-Species Comparative Analysis and Evolutionary Conservation of Mammalian Beta-Globin (HBB)

**Author:** Mayra Camarena

## Project Overview
This project investigates amino acid conservation across mammalian Beta-Globin (HBB) orthologs using multiple sequence alignment and phylogenetic reconstruction to identify invariant functional positions.

## Dataset
- **Database:** NCBI Protein / RefSeq
- **Scope:** 7 mammalian orthologs (~146–147 amino acids each)
  - Human (*Homo sapiens*, `NP_000509.1`)
  - Chimpanzee (*Pan troglodytes*, `NP_001139433.1`)
  - Rhesus Macaque (*Macaca mulatta*, `NP_001028096.1`)
  - Mouse (*Mus musculus*, `NP_001265090.1`)
  - Dog (*Canis lupus familiaris*, `NP_001003157.1`)
  - Cattle (*Bos taurus*, `NP_776342.1`)
  - Horse (*Equus caballus*, `NP_001075253.1`)

## Repository Structure
- `data/`: Curated multi-sequence FASTA file (`mammalian_HBB_compiled.fasta`) with standardized headers.
- `results/`: Multiple sequence alignments, percent identity matrices, and phylogenetic trees.
- `ai_usage.md`: Documentation of AI tools and verification procedures.
