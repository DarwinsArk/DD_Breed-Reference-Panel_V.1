# DD_Breed-Reference-Panel_V.1
This panel serves as reference for the breed ancestry assignment pipeline for the Darwin's Dogs project at [Darwin's Ark](https://github.com/DarwinsArk). The ancestry assignment code was written by [Linda Boettger](https://github.com/lindaboettger) (see [lindaboettger/ancestry_assignment](https://github.com/lindaboettger/ancestry_assignment)) and modified for usage in Darwin's Dogs by [Kathleen Morrill](https://github.com/tabbzi). The breed ancestry assignment pipeline infers global and local ancestry of domestic dogs from a reference panel of purebred genotypes and generates chromosome painting, bar, and pie plots.

Version 1 contains 93 breeds with 12 dogs per breed and 148,737 SNP markers.

_V.1 is the most current version used for Genomic Breed Mix results on the Darwin's Ark website; V.2 is in progress._

## Data Sources and Acknowledgments

- Cornell Canine Dataset from _Hayward et al (2016)_ available on [Dryad Digital Repository](https://doi.org/10.5061/dryad.266k4)
- The Darwin's Dogs project on [Darwin's Ark](https://darwinsark.org/)
- Elaine Ostrander

## PLINK Dataset

The RefPan.bed/.bim/.fam files contain all purebred dog genotypes with family IDs corresponding to breed.

## REF Files

These are phased .tped/.tfam files for 6 dogs per breed used as reference files by SupportMix in the breed ancestry assignment pipeline.

## PHASE Files

This PLINK dataset is merged with the target dataset for phasing by EAGLE in the breed ancestry assignment pipeline.
