## plantago seed microbiome

Companion repository for the paper The microbial diversity and composition of seeds from Plantago lanceolata changes along a plant diversity gradient Yuri Pinheiro 1, 2; Michael Schloter 1, 2; Wolfgang Weisser 3; Yuanyuan Huang4,5, Stefanie Schulz 1*

1 - Helmholtz Zentrum München, Research Unit Comparative Microbiome Analysis, Neuherberg, Germany
2 - Technische Universität München, TUM School of Life Science, Chair of Environmental Microbiology, Neuherberg, Germany
3 - Technische Universität München, TUM School of Life Science, Chair of Terrestrial Ecology, Freising, Germany
4 - German Centre of Integrative Biodiversity Research (iDiv) Halle-Jena-Leipzig, Germany 
5 - Institute of Biology, Experimental Interaction Ecology, Leipzig University, Germany 
*corresponding author: stefanie.schulz@helmholtz-muenchen.de
ORCID IDs:
Yuri Pinheiro Alves de Souza: 0000-0001-9854-6383
Stefanie Schulz: 0000-0001-5520-8106
Yuanyuan Huang: 0000-0002-6990-8864
Wolfgang Weisser: 0000-0002-2757-8959
Michael Schloter:  0000-0003-1671-1125

Contains:

KnitR_Plantago_experiment.html: this is the primary script authored by Yuri Pinheiro for the analyses of the amplicon sequences 

metadata.xlsx: the metadata file with the independe variables in the experiment 

asvs.xlsx: ASVs count table 

taxonomy.xlsx: taxonomic anotation of ASVs


Experiment description 
We conducted a field experiment at the Jena Experiment field site (https://the-jena-experiment.de/), investigating the effects of increasing plant diversity on the Plantago lanceolata seed endophytic bacterial community. We sampled seeds from 12 plots where Plantago lanceolata was growing in monoculture, in 4, 8, and 16 species diversity combinations. Samples were taken at blossom level, with each individual consisting of 3 blossoms and each plot consisting of 3 individuals, totaling 108 samples.

We surface sterilized the seeds using sodium hypochlorite, ethanol, and tween (see methods session for detailed information) and proceeded with DNA extraction using the phenol chloroform DNA extraction protocol. 20 ng of the resulting DNA was used for amplicon sequencing using chloroplast, excluding primers targeting the V3 and V4 regions.

High-quality DNA was diluted to 4 nM and sequenced on Illumina MiSeq using the MiSeq Reagent v3 (600 Cycle) kit. After sequencing, samples were uploaded to the European Galaxy server, where samples were denoised and taxonomic assignment was conducted against the Silva database version 138. Raw samples were updated to the NCBI SRA database under the bio project number PRJNA937585, bio sample SAMN33409010.

Here we demonstrated the processing and plotting of the reeds after Galaxy.
