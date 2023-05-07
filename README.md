# sph-plants-grasslands
DOI: https://doi.org/10.5281/zenodo.7886325

Scripts and dataset from the paper Cavalheiro et al. "Evolutionary history and ecological traits shape a mutualistic plant-hawkmoth interaction network" (in review). Also available at supplemental material from Lautenschleger et al. 2020 (https://doi.org/10.1111/een.12961).


FILES:

	Data.xlsx is a multiple worksheets file that contains hawkmoth and plant interactions, morfological, phenological and evolutionary data collected at Pampa grasslands from Southern Brazil from November 2015 to April 2017.

		Interaction Network: Hawkmoth-plant mutualistic network from Southern Brazil. Each cell of the matrix represent the number of visits (interaction frequencies) of each hawkmoth species on each plant species during the study.
		Sampling effort: Total sampling effort (hours of focal observation) on each plant species of the study.
		Morphology: Corolla depth and proboscis length (mean ± sd) of plants and hawkmoths that interacted in Southern Brazil. Open or brush shape flowers were considered to have depth = 0.1 cm as virtually any hawkmoth have proboscis long enough to access the nectar.
		Phenology: Flowering and hawkmoth temporal occurrrence (i.e. phenology) of plant species visited by hawkmoths during the study.
		Abundance: Abundances of flower and hawkmoth species that interact in Southern Brazil. Plant species abundance were quantified fortnightly from January 2016 to December 2016, and hawkmoths were collected from November 2015 to April 2017.
		Evolutionay history: Values of originality QE-based index for plants and hawkmoths that interact in Southern Brazil.

	plants-tree.new file contais a phylogenetic tree on newick format showing the evolutionary relationships among the plant species that interact with hawkmoths during the study.

	sphingidae-tree.nex file contains the evolutionary tree of the hawkmoth species of the study on the nexus format.
	
	Scripts folder contain all scripts and necessary files to run the following steps: 
		sph tree: constructing phylogenetic trees of the sphingidae species occurring in the community.
		plants tree: constructing phylogenetic trees of the plant species visited by the hawkmoths.
		processes: evaluating qe-based index for hawkmoth and plants for the community, building probabilistic matrices of interaction based on ecological traits and evolutionary history of each specie, and running the likelihood analyses of each scenario.
		pcps cwm: testing the phylogenetical signal and running the pcps and the cwm analises.

For methodological information please acess the papers above, and in case of using this dataset, please cite the papers and this dataset.
