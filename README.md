Hantavirus sequence alignments, phylogenetic trees and mutational spectra used in "Hantavirus mutagenesis is impacted by mutagens and host antiviral proteins"

This repository is organised by virus so each hantavirus species has its own directory named with the common virus name. Within each virus directory are the following files:
* The _aligned.fasta file contains the sequence alignment for the virus
* The _rooted.nwk file contains the rooted phylogenetic tree for the virus. Note that these files include outgroup sequences that were excluded from MutTui runs
* The _rooted_labelled.nwk file is the labelled tree for the virus where a labelled tree was employed
* The conversion.txt file is the position conversion file used by MutTui. Note that all sites were included in the alignment so this file contains all sites
* The reference.fasta file contains the reference file used by MutTui
* The _SBS.csv file is the unscaled SBS mutational spectrum for the virus; this file contains raw mutation counts
* The _mutation_types.csv file is the unscaled mutation type spectrum for the virus
* The _SBS_tree_rescaled.csv file is the tree rescaled mutational spectrum for the virus; these spectra are recorded as proportions of mutational burden
* The _mutation_types_tree_rescaled.csv file is the tree rescaled mutation type spectrum for the virus

Note that mutational spectra have been reversed as hantaviruses have a negative strand genome while sequence data is stored in the positive strand orientation. The mutational spectra for Puumala virus and Muju virus were calculated using a labelled tree of the same dataset; they therefore have the same alignment, phylogenetic tree, labelled phylogenetic tree, conversion file and reference, but different mutational spectra

A summary of the complete dataset is included within hantavirus_dataset_summary.csv within the main repository directory

Complete catalogues containing mutational spectra for all analysed viruses are included within all_hantavirus_spectra. This directory also contains cladograms for the relationships between hantavirus species and between host species
