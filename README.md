This repository contains a pipeline for testing the inclusivity of PCR primers. The pipeline uses Jupyter Notebook to perform a local BLAST analysis on DNA/RNA sequences downloaded from NCBI, and pandas to analyze the data and count the number of mismatches between the primers and the target sequences.

Requirements
Python 3
Jupyter Notebook
Biopython
Pandas

Usage
Clone this repository to your local machine.
Install the required packages using pip.
Open PCR_Primer_Inclusivity.ipynb in Jupyter Notebook.
Follow the instructions in the notebook to perform the analysis.

Inputs
The pipeline requires the following inputs:

A FASTA file containing the DNA/RNA sequences to test the primers against.
A CSV file containing the primer sequences in the following format: name,sequence.
Outputs
The pipeline generates the following outputs:

A CSV file containing the number of mismatches between each primer and the target sequences.
A list of new primer sequences that align to the conserved regions of the target sequences.
Contributing
If you would like to contribute to this pipeline, please fork the repository and submit a pull request with your changes.
