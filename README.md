# Bioinformatics unit coding challenge

You are to extract and translate several genes with defined coordinates from their chromosome sequences. If you are applying for a position, it is highly recommended to complete the challenge in Python.

Three input files have been provided:

* **`sequences.fasta`** A FASTA file with two chromosome sequences.
* **`intervals.gff`** A GFF file with a set of mRNA coordinates for the sequences in `sequences.fasta`.
* **`standard_code.txt`** A tab delimited table mapping codons to single letter amino acids.

Using these three files, write a *non-interactive* command line tool that:

1. Takes the three files as arguments,
2. Extracts the mRNA sequences from `sequences.fasta` given the coordinates in `intervals.gff`,
3. Translates all six reading frames of the mRNA sequence given the genetic code in `standard_code.txt`,
4. Prints the longest translation of each mRNA sequence to standard output in FASTA file format.

When evaluating the code, special attention will be given to the use of clean coding practices and maintainability. The output for the given input files is can be found in `genes.fasta`. Your solution will also be tested on additional input.
