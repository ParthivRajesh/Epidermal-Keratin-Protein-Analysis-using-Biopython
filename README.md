# Epidermal-Keratin-Protein-Analysis-using-Biopython

## Project Description

The objective of this project was to perform fundamental protein sequence analysis starting from a FASTA file obtained from the NCBI database. The script reads and processes the epidermal keratin protein sequence, extracts biologically relevant information, and applies sequence-level analysis methods commonly used in computational biology.

In addition, the project integrates NCBI BLAST to compare the protein sequence against known databases, enabling functional inference and evolutionary insight based on sequence similarity. This mirrors real-world bioinformatics pipelines used in protein characterization and annotation.

## Data Source

Protein sequence retrieved from NCBI:  
https://www.ncbi.nlm.nih.gov/nuccore/J00124.1

## Features

- Parsing and handling protein FASTA sequences using Biopython
- Extraction of sequence metadata and length
- Amino acid composition analysis
- Basic protein sequence quality control/check
- BLAST search using NCBI’s online services
- Parsing and interpretation of BLAST alignment results

## File Structure

- `EpidermalKeratin.fasta` – FASTA file containing the epidermal keratin protein sequence  
- `epidermal_keratin_biopython_proj.py` – Python script implementing the analysis pipeline
- 'nblast_result_protein.xml' - Contains the NCBI BLAST Output in XML format

## Requirements

- Python 3.x  
- Biopython  

Install dependencies using:

```bash
pip install biopython

## How to Run?

- In the terminal type,
- python epidermal_keratin_biopython_proj.py



