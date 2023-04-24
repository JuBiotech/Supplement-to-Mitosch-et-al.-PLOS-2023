Supplementary information to

# Pathogen-specific isotope tracing approach reveals metabolic activities and fluxes of intracellular Salmonella

Karin Mitosch<sup>1</sup>, Martin Beyß<sup>2,3</sup>, Prasad Phapale<sup>4</sup>, 
Bernhard Drotleff4, Katharina Nöh<sup>2\*</sup>, Theodore Alexandrov<sup>4,5,6,7\*</sup>,
Kiran Patil<sup>5,8\*</sup>, Athanasios Typas<sup>1,5\*</sup>
<sup>1</sup> Genome Biology Unit, European Molecular Biology Laboratory, Heidelberg, Germany
<sup>2</sup> Institute of Bio- and Geosciences, IBG-1: Biotechnology, Forschungszentrum Jülich GmbH, Jülich, Germany
<sup>3</sup> RWTH Aachen University, Computational Systems Biotechnology, Aachen, Germany
<sup>4</sup> Metabolomics Core Facility, European Molecular Biology Laboratory, Heidelberg, Germany
<sup>5</sup> Structural and Computational Biology Unit, European Molecular Biology Laboratory, Heidelberg, Germany
<sup>6</sup> Molecular Medicine Partnership Unit, European Molecular Biology Laboratory, Heidelberg, Germany
<sup>7</sup> Skaggs School of Pharmacy and Pharmaceutical Sciences, University of California San Diego, La Jolla, CA, USA
<sup>8</sup> Medical Research Council Toxicology Unit, University of Cambridge, Cambridge, UK

<sup>*</sup> Corresponding authors: 
- k.noeh@fz-juelich.de (KN)
- theodore.alexandrov@embl.de (TA)
- kp533@cam.ac.uk (KP)
- typas@embl.de (AT)

## Raw data

The raw data is available on zenodo [doi:10.5281/zenodo.7859058](https://doi.org/10.5281/zenodo.7859058) 
It contains the results of the MCMC sampling (i.e. fluxes) as well as the simulated MS measurements.


## Reproducing figures and tables

The jupyter notebook can be executed top down to reproduce all figures and tables.
If the raw data is not present it will be fetched from zenodo

### Figure 4

- The notebook generates the file `out/Fig_4_omix.csv`.
- Open Omix (the free Light version is sufficient) and open `ressources/STm_Omix.omx`
- In the _Property Editor_ on the right hand sight, find the entry _Input File_ and set it to `Figure 4/omix.csv`
- Chose _Start Bisualization_ on the top
- By using the slider next to _Select Row_ you can switch between the low (row 0) and high (row 1) glucose concentration
- Figure 4 is generated with the low glucose concentration
