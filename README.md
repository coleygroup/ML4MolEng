# Machine Learning for Molecular Engineering (3.C01/3.C51, 7.C01/7.C51 10.C01/10.C51, 20.C01/20.C51)

Materials and problem sets for the course Machine Learning for Molecular Engineering taught at MIT.

**Instructors**: Prof. Connor Coley and Prof. Rafael Gomez-Bombarelli 

**Course Numbers**: 3.C01/3.C51, 7.C01/7.C51, 10.C01/10.C51, 20.C01/20.C51

## Warning

These assignments are a work in progress and will change. Do not start working on an assignment until it has been released on Canvas.

## Problem Sets

[**PS0**](https://github.com/coleygroup/ML4MolEng/blob/main/psets/ps0/)

Ungraded problem set (no submission) to practice using Google Colab and numpy.

[**PS1**](https://github.com/coleygroup/ML4MolEng/blob/main/psets/ps1/)

Data size: ~10^2

Basic linear classification problem to get you started for the course. You will use logistic regression to diagnose cancer. You will apply linear methods with L1 and L2 regularization and understand what effects they have on your regression results. You also will experiment with hyperparameter optimization to tune your model with cross-validation.

[**PS2 (Perovskites)**](github.com/coleygroup/ML4MolEng/blob/main/psets/ps2-perov/) 

Data size: ~10^3

You will apply a MLP regressor to predict properties of perovskites. You will compare differences between different representations of the chemical composition of a perovskite crystal. You will also use [hyperopt](https://github.com/hyperopt/hyperopt) to perform hyperparameter search for your MLP architecture.

[**PS2 (MHC)**](https://github.com/coleygroup/ML4MolEng/blob/main/psets/ps2-MHC/)

Data size: ~10^3

You will apply an MLP regressor to predict MHC binding to peptides. You will compare differences between different representations of the amino acid composition of a peptide. You will also use [hyperopt](https://github.com/hyperopt/hyperopt) to perform hyperparameter search for your MLP architecture.

[**PS3**](https://github.com/coleygroup/ML4MolEng/blob/main/psets/ps3/)

Data size: ~10^4

This problem set has two parts: 1) In the first part, you will use PyTorch to train a LSTM-based classifier to classify DNA binding sites. 2) In the second part, you will try to reduce a high-dimensional dataset into lower dimensions with PCA and t-SNE. You will try to find out if the obtained low-dimensional embedding is meaningful. 

This problem set is an application of computer vision to molecular engineering. You will use a deep learning model to classify steel surface defects and perform image segmentation to identify cell nuclei.

[**PS4**](https://github.com/coleygroup/ML4MolEng/blob/main/psets/ps4/)

Data size: ~10^6

This problem set will be more meaty than the previous ones. You will implement your own Graph Neural Nets to predict molecular properties and train a Variational Auto-Encoder to generate new molecules from a learned hidden continuous representation.

[**PS5**](https://github.com/coleygroup/ML4MolEng/blob/main/psets/ps5/)

Data size: ~10^3

This problem set is an application of ML to predicting Solvation Free Energies and participating in a private kaggle dataset challenge.

[**PS6 (SFE)**](https://github.com/coleygroup/ML4MolEng/blob/main/psets/ps6-sfe/)

Data size: ~10^3

You will complete a short clustering exercise and participate in a ML competition to predict drug screen.

[**PS6 (Drug Screen)**](https://github.com/coleygroup/ML4MolEng/blob/master/psets/ps6-drug-screen/)

Data size: ~10^3

You will participate in a ML competition to predict solvation free energies of solute/solvent pairs.
