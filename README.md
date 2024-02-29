# Assignments Week 7
# Introduction
The goal of this assignment is to perform a protein database search for one of the datasets that you are working with for your group project. This search should identify a range of peptides and their corresponding proteins.
# Input data
You can use the .raw files from any of the Neisseria datasets, which can be downloaded from PRIDE. In addition, you will need a .fasta file for the corresponding reference proteome (downloaded from UniProt).
# Tasks and output files
1)	Generate a target-decoy database for the reference proteome that you are working with (together with the cRAP database of common contaminants)
2)	Convert the downloaded .raw files into .mzML files.
3)	Use the .mzML files together with the target-decoy data as input for a protein database search (using a tool of your choice, e.g. Ursgal, SearchGUI, MaxQuant, FragPipe, …).
4)	Use statistical postprocessing (e.g. Percolator, Philosopher, MaxQuant, …) to calculate FDRs and/or PEPs for the peptide-spectrum matches generated in 1). Filter for a PEP (or FDR) of 1%.
5)	Count the number of identified peptides and their corresponding proteins based on the result file generated.
6)	Make sure to comment your code, so that others can read and understand it easily. 
7)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
8)	Commit your scripts, and final result files to your GitHub Classroom repository. Do NOT commit large input files (like .raw, .mzML, etc)
# Additional MS student tasks (bonus credit for BS students)
9)	Plot an annotated spectrum for any of the identified peptide spectrum matches. 
# Submission
You must submit the assignment through GitHub Classroom by 8 am Mar 7 to get full credit. 
