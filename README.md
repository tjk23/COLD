Codon Optimal Likelihood Discoverer

COLD is a flexible software package for simulating and fitting certain phylogenetic models of evolution to molecular sequence data. It has been most extensively developed and tested with codon models, but the flexible framework can be used for nucleotide or amino acid models. The models are based on user-defined log-transformed additive components in the substitution matrix. It has features to allow parameters to vary between sites in a customisable way with certain common options built in.

Installation Instructions

Download the package. 
Unzip the package (It was zipped using Gnu zip)
Extract all the files.
This will extract a directory "Documentation", which contains files with more detailed instructions.
Run "make" in the directory containing the files. (Usually, this just involves typing "make"). You may wish to set some compilation options at this point (in particular, the directory in which you want to install the data files) - see cold.info for details. Note that you will need to have a c++ compiler for this step.
If it works, you can install the program by typing "make install". This should mean that the program is available to be run from anywhere on your system. Note that the installation directory should be set when running the first make command, as this compiles the correct directories for file-searching into the program. These settings are saved during compliation, and automatically used when you type make install

Documentation
The documentation files are all included in the package, in the directory Documentation.
