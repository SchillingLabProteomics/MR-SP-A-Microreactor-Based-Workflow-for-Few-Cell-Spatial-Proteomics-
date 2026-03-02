This repository contains the Jupyter notebook and all associated files used for the data analysis presented in:

“MR-SP²: A Microreactor for Upward Pressure-catapulting Laser Microdissection for Mass Spectrometry-Based Spatial Proteomics at Single-Cell Resolution.”

The goal of this repository is to provide transparent, reproducible, and fully documented analysis code accompanying the manuscript.

- MR-SP2_Analysis.ipynb      # Main analysis notebook
- environment.yml            # Conda environment used for all analyses
-  README.md                 # This file
The notebook MR-SP2_Analysis.ipynb contains:
- Import of all required Python packages
- Data loading (processed quantification tables, metadata, annotations)
- Data processing and filtering steps
- Statistical analyses used in the manuscript
- Generation of all plots included in the publication
- Export of summary tables and figure files into the /data directory
- Analysis of empty samples to assess the carryover on an EvoSep One
- Metanalysis of platform and vendor specific content found in PubMed publications
Raw data and search results are deposited separately on MassIVE (link will be provided upon publication).



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

