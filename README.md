# Using-ML-to-Analyse-Telescope-Data
This is the repository for a project named Bright Dots in the Sky: Using Machine Learning Algorithms to Analyse Telescope Data, which was created as part of the SJF competition 2025.

The data used is the stellar classification dataset from kaggle at https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17 which is taken from the Sloan Digital Sky Survey DR17.

All coding files were created in jupyter notebook and can be used independently.

Section 3.1 describes the relevant features of the data.
Section 3.2 makes photometric predicitons for redshifts of galaxies and quasars (individually; the original labels were created using a spectroscopic redshift).
Section 3.3 compares different ML classifiers and the effect that data preprocessing has on them.
Section 3.4 makes photometric redshift predictions on the unclassified datset and subsequently classifies the objects with a high confidence.
