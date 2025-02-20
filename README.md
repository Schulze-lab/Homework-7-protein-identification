# Assignments Week 7
# Introduction
The goal of this assignment is to perform a protein database search for one of the publicly available datasets for Streptococcus mutans. This search should identify a range of peptides and their corresponding proteins. In the lab, we will go through the usage of the Python framework Ursgal, but you are welcome to use any protein database search that you see fit.
# Input data
You can use the .mzML files from the PXD019825 datasets that have been transferred to the Oedipus server already, or you can download and convert any other S. mutans dataset, e.g. one that is useful for your group project. In addition, you will need a .fasta file for the corresponding reference proteome (downloaded from UniProt).
# Tasks and output files
1)	Generate a target-decoy database for the reference proteome that you are working with (together with the cRAP database of common contaminants)
2)	Use the .mzML files (might require converting .raw files to .mzML if you use a different dataset) together with the target-decoy database as input for a protein database search (using a tool of your choice, e.g. Ursgal, SearchGUI, MaxQuant, FragPipe, …).
3)	Use statistical postprocessing (e.g. Percolator, Philosopher, MaxQuant, …) to calculate FDRs and/or PEPs for the peptide-spectrum matches generated in 1). Filter for a PEP (or FDR) of 1%.
4)	Count the number of identified peptides and their corresponding proteins based on the generated result file(s).
5)	For one of the identified peptide spectrum matches (PSMs), calculate the theoretical b- and y-ions of the identified peptide, and match them to the peaks in the spectrum. Use the matching peaks to plot an annotated spectrum for this PSM (a spectrum that contains all measured peaks and that highlights the peaks that correspond to matching b- and y-ions). 
6)	Make sure to comment your code, so that others can read and understand it easily. 
7)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
8)	Commit your scripts to your GitHub Classroom repository. Do NOT commit large input files (like .raw, .mzML, etc)! The result files should be stored in your folder on the Oedipus server.
# Additional MS student tasks (bonus credit for BS students)
9)	Repeat the protein database search and include a common post-translational modification (e.g. lysine acetylation). Find a PSM that has this modification and plot an annotated spectrum. Specifically highlight the b- and y-ions that have a shifted m/z due to the modification.
# Submission
You must submit the assignment through GitHub Classroom by 8 am ET on Feb 27 to get full credit. 




