===============
Getting Started
===============

Requirements
-----------------

| snakemake>=3.5
| python>=3.3
| biopython>=1.77
| diamond BLAST version>=0.9.32
| mafft>=7.429
| fasttree>=2.1.10 and/or:
| iqtree>=1.6.11
| ncbi-genome-download>=0.3.0

Python scripts from this github folder

Installation
-----------------------

| Use conda to install snakemake to a Linux or Mac OSX environment:
| To install conda:

| Install conda here https://conda.io/en/latest/miniconda.html
| Install dependencies *via* conda 

| Install snakemake:

| conda install -c conda-forge mamba
| mamba create -c conda-forge -c bioconda -n snakemake snakemake

| conda activate snakemake
| snakemake --help

| Install the ribosomal protein tree workflow from github:
| git clone XXX
| cd XXX



