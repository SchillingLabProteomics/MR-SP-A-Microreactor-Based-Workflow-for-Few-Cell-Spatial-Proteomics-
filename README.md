This repository contains the Jupyter notebook and all associated files used for the data analysis presented in:

“MR-SP²: A Microreactor for Upward Pressure-catapulting Laser Microdissection for Mass Spectrometry-Based Spatial Proteomics at Single-Cell Resolution.”

The goal of this repository is to provide transparent, reproducible, and fully documented analysis code accompanying the manuscript.

.
├── MR-SP2_Analysis.ipynb      # Main analysis notebook
├── environment.yml            # Conda environment used for all analyses
├── data/                      # Processed raw data in the used in the manuscript plus the required annotation
│   ├── MR_SP2_withMBR/                # Summary tables of DIANN searches per condition that ran with MBR being applied (int = MR-SP2, PCR = Conventional)
└── README.md                  # This file

Contents of the Analysis Notebook
The notebook MR-SP2_Analysis.ipynb contains:
Import of all required Python packages
Data loading (processed quantification tables, metadata, annotations)
Data processing and filtering steps
Statistical analyses used in the manuscript
Generation of all plots included in the publication
Export of summary tables and figure files into the /data directory
Raw mass spectrometry data are not included in this repository.
They are deposited separately on MassIVE (link will be provided upon publication).



Requirements & Environment
All analyses were performed using a reproducible conda environment.
The full specification is given in:
environment.yml
To recreate the environment:
conda env create -f environment.yml
conda activate mr-sp2


Data Availability:
Processed output files used by the notebook are stored in the /data directory, including:
Quantitative peptide and protein matrices
Sample metadata tables
Statistical outputs
Intermediate results
Final figure exports used for the manuscript
Raw LC–MS/MS data and search engine outputs are available on MassIVE:
(Accession will be added once released)
