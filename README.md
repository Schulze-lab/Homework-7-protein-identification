# Assignments Week 3
# Introduction
The goal of this assignment is to perform a protein database search on a result file from an HPLC-MS/MS run. This search should identify a range of peptides and their corresponding proteins.
# Input data
You can use the .mzML file for Haloferax volcanii from the previous assignments, or you can use an MS file that’s relevant to your group project. In addition, you will need a .fasta file for the corresponding reference proteome (downloaded e.g. from UniProt).
Tasks and output files
1)	Generate a target-decoy database and use it, together with the .mzML MS file, as input for a protein database search (using a tool of your choice, e.g. Ursgal, SearchGUI, MaxQuant, FragPipe, …).
2)	Use statistical postprocessing (e.g. Percolator, Philosopher, MaxQuant, …) to calculate FDRs and/or PEPs for the peptide-spectrum matches generated in 1). Filter for an FDR (or PEP) of 1%.
3)	Count the number of identified peptides and their corresponding proteins based on the result file generated.
4)	Make sure to comment your code, so that others can read and understand it easily. 
5)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
6)	Commit all your input files, scripts, and result files to your GitHub Classroom repository.
# Submission
You must submit the assignment through GitHub Classroom by 8 am Mar 2 to get full credit. 
# Bonus Credit
7)	Perform a de novo search on the same MS file and compare the results to the results of the protein database search. What is the percentage of peptides identified by the de novo search that is not part of the Haloferax volcanii proteome?
