# Treasure Maps

This repository is a collection of additional figures of our work published in the Astrophysical Journal.
If you are using any of the figures printed in the paper in any derived work, please ask for our permission. Other figures from this repository can be used in derived works. In any case, please cite our work via entries from

- [Inspirehep.net](https://inspirehep.net/literature/2173102)
- [ADS](https://ui.adsabs.harvard.edu/abs/2022arXiv221015885G/abstract)

# Contents

## [1. GZK Horizon](1_GZK_Horizon)

Contains the PDF files of Figs. 1, 2 and A1. 

The subfolder [tables](1_GZK_Horizon/tables) contains the tabulated values for the curves shown in the figures for injected power-law spectra of different composition (H, N, Fe), a power-law index of 2.5, a maximal energy of 3 ZeV as defined by Eq. (1).

## [2. Source catalogs](2_Source_catalogs)

Sky maps of the source catalogs used in the paper and shown in Fig. 3 for different maximal distances from the Milky Way in Mpc. One set of figures for all three catalogs, and one set for SBG and Jetted AGN only. 

## [3. Treasure maps](3_Treasure_Maps/)

All variations of sky maps shown in Fig. 5, 6, 7 and B2.

*The first level sub-folders* identify the magnetic field model. The models used are implemented in [CRPropa3](https://crpropa.github.io/CRPropa3/api/classcrpropa_1_1MagneticField.html#exhale-class-classcrpropa-1-1magneticfield):

- **JF12**: Jansson-Farrar 12 with default settings from CRPropa3 including strided and turbulent magnetic fields switched on
- **JF12regular**: Jansson-Farrar 12 with default settings from CRPropa3, only regular component, no random magnetic fields
- **JF12Planck**: Jansson-Farrar 12 with parameters tuned by the Planck Collaboration as implemented in CRPropa3, strided and turbulent component switched on
- **TF17**: Terral-Ferriere 17 with default settings from CRPropa3. No random fields are available in the model.

The next level of sub-folders is named `[gmf_model]_[composition]_[energy]` assumed when computing the back-tracked sky maps.

The files at the final sub-folder level follow the naming scheme 

    `[initial_exposure_function]_gmf_delay_[gmf_model]_[composition]_[A_obs]_[B_egmf]ng_[energy]`.pdf

The magnification factor is shown in the files named 
    
    `[initial_exposure_function]_MF_[gmf_model]_[composition]_[energy]`.pdf


## [4. Doublet Host Candidate Counts](4_Doublet_Host_Candidate_Counts/)

Host candidates counts as shown in Figs. 8 and B3 for EGMF strengths of 0.1 and 1 nG, respectively.

## [5. Hotspot](5_Hotspot/)

Telescope Array Hotspot related Figs. 10 and B4.

## [6. Temporal and Angular Ordering](6_Temporal_and_Angular_ordering/)

Fig. 9 from the paper.
