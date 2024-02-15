# RawRMSDCalculator
A simple function to calculate the raw RMSD for two protein structures that are the same length.

Given two pdb files that contain structures of proteins that both have the same number of residues, this script will calculate the RMSD value considering all atom types for each of the residues.  Since the residues for each protein can be different, there will be different atoms in the pdb file for each so the mean x,y and z are calculated for all of the atoms for each residue and used as the mean position for the residue itself.  In my experience, this way to caculate RMSD provides a better overall indication of the similarity of two protein structures that using just the backbone atoms does.
