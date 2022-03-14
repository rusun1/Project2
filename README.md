# Project2

In this repository, the following files are needed to run the code:
1) The jupyter notebook: Project2D.ipynb
2) cyp_p450.fasta
3) 1w0g.pdb

cyp_p450.fasta is a fasta file containing the sequences of the 13 cytochrome P450 enzymes that were analyzed: CYP1A1, CYP1A2, CYP1B1, CYP2A6, CYP2C8, CYP2C9, CYP3A4, CYP3A5, CYP2D6, CYP2C19, CYP2E1, CYP2B6, CYP2J2. The sequences were obtained from uniprot (https://www.uniprot.org/) and downloaded into a single fasta file.
 
1w0g.pdb is a protein structure of the CYP3A4 enzyme (https://www.rcsb.org/structure/1W0G). This was obtained from RCSB by searching for CYP3A4. I chose to use the 1W0G crystal structure and downloaded the pdb file.

Packages to be installed with the following commands:
pip install biopython

The output of this code gives a heatmap using the pairwise sequence alignment data. A movie in pymol was also created from the homology modeling, which can be found here: https://www.youtube.com/watch?v=sIhZQJG-P6o

The notebook for running all the code was written in Python
