# Digest
My contribution to an educational Python group project (created as part of an MSc course). Digest is part of a proteomics analysis pipeline that performs an in silico digest of theoretical peptides, using one of a variety of user-specified enzymes. The overall pipeline takes as input a bacterial genome and outputs a set of theoretical peptides from enzyme digests and relevant summary statistics. 

# Input
Standard FASTA file format containing protein open-reading frames (generated from bacterial genome sequence). 

# Options
Choice of four enzymes for digest: trypsin, endoproteinase Lys-C, endoproteinase Arg-C, V8 proteinase (Glu-C). <br />
Ability to select for the possibility of 'missed cleavages' where peptides are generated under the assumption that the enzyme can miss up to a specified number of cleavage sites. 

# Error Catching
Inputs are tested for validity, error trapping also catches unusual amino acids (B,O,U,J,Z) and unknown amino acids (X) and produces relevant warnings. 

# Output
Individual peptides after digestion in FASTA format.

# Acknowledgements
This project was set as coursework for and supported by the University of Manchester MSc Bioinformatics and Systems Biology course staff. 
