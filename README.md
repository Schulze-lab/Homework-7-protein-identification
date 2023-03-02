# Assignments Week 3
# Introduction
The goal of this assignment is to mimic part of a typical proteomics sample processing workflow on the bioinformatic side. The two steps that will be covered by this assignment are (i) protein digestion, and (ii) chromatographic separation of peptides.
# Input data
The reference proteome of an organism of your choice should be used as input file. The same .fasta file as in HW1 can be used.
Tasks and output files
1)	Perform an in silico digest of all proteins within the input .fasta file. Use trypsin as proteolytic enzyme. You can use existing modules (like pyteomics’ parser.cleave() function) or write your own function that takes into account tryptic cleavage sites (cleaves after K and R, unless followed by P). Save the resulting peptides as a csv file.
2)	For the resulting peptides, determine the percentage of peptides that could originate from different proteins (i.e. peptides that are not specific to a single protein). What is the distribution of peptide lengths for these so called non-proteotypic peptides (a graphical representation would be best)?
3)	Calculate the theoretical retention time (on a standard C18 RP-HPLC) for all peptides using either an additive model (e.g. pyteomics’ achrom module) or a machine learning based model (e.g. DeepLC, or AutoRT). Plot the resulting retention times.
4)	Make sure to comment your code, so that others can read and understand it easily. 
5)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
6)	Commit all your input files, scripts, and result files to your GitHub Classroom repository.
# Submission
You must submit the assignment through GitHub Classroom by 8 am Feb 9 to get full credit. 
# Bonus Credit
7)	When plotting the retention time of all peptides (task 3), take into account that peptides elute ideally with a Gaussian distribution (see image below). Let’s assume that the peak width is 30 seconds, and the maximum retention time is 60 min. What is the percentage of peptides that have theoretically overlapping elution peaks? How does that number of overlapping peaks change if we increase the maximum retention time to 120 min (with in increase in peak width to 35 seconds due to increased diffusion)? 
