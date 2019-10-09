# Simple-python-scripts
This repository contains python scripts to accomplish simple bioinformatics tasks.

# Dot plot matrices
In bioinformatics a dot plot is a graphical method for comparing two biological sequences and identifying regions of close similarity. 
Introduced by Gibbs and McIntyre in 1970, a dot plot can be defined as a two-dimensional matrix having the sequences being compared along the vertical and horizontal axes. 
For a simple visual representation of the similarity between two sequences, individual cells in the matrix can be shaded black if residues are identical, so that matching sequence segments appear as runs of diagonal lines across the matrix. 
Given two sequences (DNA, RNA or Proteins) dot_plot_matrix.py returns on screen the corresponding dot plot matrix.

Usage:

python dot_plot_matrix.py [Seq1] [Seq2]
