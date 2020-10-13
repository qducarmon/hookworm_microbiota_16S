# Hookworm infection and gut microbiota

This study profiled the gut microbiota using 16S rRNA gene amplicon sequencing of 20 volunteers who were voluntarily infected with Necator americanus larvae and followed over time at five time points.
A link to the paper will be inserted here
In case you'd prefer to start analyzing from the raw sequence data yourself, you can find all raw sequence data under PRJEB36316.

## Requirements
- R version 3.6.1 ("Action of the Toes").
- All packages and dependencies loaded in the different markdown scripts. 

## Worfklow
- Start by loading the phyloseq objects in the "Data_preparation_cleaning.Rmd". These files serve as input for all further analyses. In addition, you need to download the hookworm_phyloseq.rds (this contains the phyloseq object)
- In principle, now all other markdown files are standalone, apart from specific figures.
- Some multipanel figures (Figure 3 and 4) require figures from other markdown files, so if these multipanel figures are not generated, have a look whether you have made all figures belonging to these figures.
- The names of the markdown files indicate which analyses are performed in that specific markdown, so that should be self-explanatory (I hope) :) .
- The metalonda analyses take some time on a standard machine with 1000 permutations, keep that in mind. In addition, the output table from metalonda has been provided, this is necessary to make the final figure.

## Contact
In case you have any questions about the code/analyses, you can contact me, [Quinten Ducarmon](mailto:q.r.ducarmon@lumc.nl)! 