Supplementary information to

# Pathogen-specific isotope tracing approach reveals metabolic activities and fluxes of intracellular Salmonella

[![DOI](https://zenodo.org/badge/629008608.svg)](https://zenodo.org/badge/latestdoi/629008608)


Karin Mitosch<sup>1</sup>, Martin Beyß<sup>2,3</sup>, Prasad Phapale<sup>4,5</sup>, Bernhard Drotleff<sup>4</sup>, Katharina Nöh<sup>2\*</sup>, Theodore Alexandrov<sup>4,6,7,8*</sup>, Kiran R. Patil<sup>6,9*</sup>, Athanasios Typas<sup>1,6*</sup>

<sup>1</sup> Genome Biology Unit, European Molecular Biology Laboratory, Heidelberg, Germany

<sup>2</sup> Institute of Bio- and Geosciences, IBG-1: Biotechnology, Forschungszentrum Jülich GmbH, Jülich, Germany

<sup>3</sup> RWTH Aachen University, Computational Systems Biotechnology, Aachen, Germany

<sup>4</sup> Metabolomics Core Facility, European Molecular Biology Laboratory, Heidelberg, Germany

<sup>5</sup> Current address: Leibniz-Institut für Analytische Wissenschaften – ISAS – e.V., Dortmund, Germany

<sup>6</sup> Structural and Computational Biology Unit, European Molecular Biology Laboratory, Heidelberg, Germany

<sup>7</sup> Molecular Medicine Partnership Unit, European Molecular Biology Laboratory, Heidelberg, Germany

<sup>8</sup> BioInnovation Institute, Copenhagen, Denmark

<sup>9</sup> Medical Research Council Toxicology Unit, University of Cambridge, Cambridge, UK

<sup>*</sup> Corresponding authors: 
- k.noeh@fz-juelich.de (KN)
- theodore.alexandrov@embl.de (TA)
- kp533@cam.ac.uk (KRP)
- typas@embl.de (AT)

## Raw data

The raw data is available on zenodo [doi:10.5281/zenodo.7896186](https://doi.org/10.5281/zenodo.7896186) 
It contains the results of the MCMC sampling (i.e. fluxes) as well as the simulated MS measurements.

## Reproducing figures and tables

The jupyter notebook can be executed top down to reproduce all figures and tables.
If the raw data is not present it will be fetched from zenodo

### Figure 4

- The notebook generates the file `out/Fig_4_omix.csv`.
- Open Omix (the free Light version is sufficient) and open `ressources/STm_Omix.omx`
- In the _Property Editor_ on the right hand side, find the entry _Input File_ and set it to `Figure 4/omix.csv`
- Chose _Start Visualization_ on the top
- By using the slider next to _Select Row_ you can switch between the low (row 0) and high (row 1) glucose concentration
- Figure 4 is generated with the low glucose concentration
