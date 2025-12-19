# AlphaFold Structure Curation

This repository contains Python workflows for curating AlphaFold protein structure files based on UniProt accession lists.

The scripts automate common preprocessing steps used in structural bioinformatics pipelines, including filtering, renaming, and organizing AlphaFold output files for downstream analysis.

## Overview

The workflows implemented here are designed to:

- Identify AlphaFold structure files that match a curated list of UniProt accessions
- Copy validated structures into a working directory
- Standardize AlphaFold file names to UniProt accession codes

These steps are typically required before structural analysis, domain annotation, or large-scale comparative studies.

## Input Data

- AlphaFold structure files following the standard naming convention  
  `AF-<UniProtAccession>-F1-model_v*.pdb.gz`
- CSV file containing UniProt accession identifiers

## Output

- A curated subset of AlphaFold structures
- Files renamed consistently using UniProt accession codes

## Technologies

- Python  
- os, shutil, csv  
- Jupyter Notebook  

## Use Case

This repository demonstrates practical file-system automation and dataset curation in a structural bioinformatics context, with a focus on reproducibility and scalability.
