# 8-mer-peptides-TcdB
This repository contains the data and codes associated with the paper-Development of Peptide Glucosyltransferase Inhibitors with Comprehensive Coverage across Clostridioides difficile Toxin B Sub-Types. 

# Requirement and Installation
The source codes are in /code/. Compiler such as gfortran or ifort is required

# Getting Started
/src/-This directory contains the following files and directories:
1. main.f90-source code
2. /lib/-This directory contains the forcefield and rotamer parameters of all the 20 natural amino acids
3. comp.pdb-An example of the input PDB file needed to start the design
4. input.txt-Input file to start design
5. pdbfiles-This is an empty directory where the pdbfiles will be stored of the new peptides that are designed

# Data for paper
/SB1 to SB7, LSB5/-These directories contains the following files:
1. SB1-SB7: Each folder contains the topology file and final PDB file from a 100 ns simulation for runs 1 to 3
2. LSB5: Each folder contains the topology file and final PDB file from a 100 ns simulation for runs 1 to 3
