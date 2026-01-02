# Machine-Learning-Enhanced-SERS-on-Silicon-Gold-Sensors-for-Ultra-High-Throughput-Pathogen-Detection
This repository contains the supplementary materials supporting an automated SERS-based biosensing platform integrating reproducible nanostructured substrates with machine learning and deep learning for pathogen classification.


The purpose of this repository is to document, explain, and support all experimental, analytical, and computational components that could not be fully detailed in the main manuscript due to space limitations. The materials are intended to ensure methodological transparency, reproducibility, and reuse of the proposed platform.



# Scope of the Supplementary Materials
The supplements expand on four main aspects of the study:
1.	SERS substrate fabrication and characterization
2.	Automated Raman spectral acquisition system
3.	Spectral preprocessing and dataset construction
4.	Machine learning and deep learning analysis
Each supplementary item is described below.


# Description of Supplementary Contents
# Supplementary Figures
These figures provide additional visualization of:
•	Gold nanoparticle self-assembly on silicon substrates
•	Spatial uniformity and reproducibility of SERS enhancement
•	Automated Raman mapping strategy and measurement grid
•	Model performance metrics and training behavior
They support and complement the figures presented in the main manuscript.



# Supplementary Tables
 Supplementary tables report:
•	Dataset composition before and after preprocessing
•	Number of spectra per class and sensor
•	Classification performance metrics for all models
•	Hyperparameters used in machine learning and deep learning models
These tables allow quantitative comparison and reproducibility of results.

 
# Automated Acquisition Workflow
This section documents the custom-developed automation framework used to:
•	Control the XY translation stage
•	Perform high-throughput Raman mapping
•	Synchronize spectral acquisition and data storage
The workflow ensures consistent measurement conditions and minimizes operator-dependent variability.


 
# Data Preprocessing and Outlier Detection
Detailed descriptions are provided for:
•	Spectral normalization and standardization
•	Mahalanobis distance-based outlier detection
•	Dataset cleaning and class balancing
This section explains how raw spectral data were transformed into a statistically robust dataset suitable for machine learning analysis.
 

# Machine Learning Analysis
The supplementary materials describe the implementation of:
•	Principal Component Analysis (PCA)
•	Linear Discriminant Analysis (LDA)
•	Support Vector Machines (SVM)
•	Random Forest classifiers
Model training, testing strategies, and evaluation metrics are documented in detail.


# Deep Learning Architecture
This section details the one-dimensional Convolutional Neural Network (CNN) used for direct spectral classification, including:
•	Network architecture
•	Activation functions and optimization strategy
•	Training parameters and early stopping criteria
The rationale for using deep learning over classical methods is also discussed.
 


# Data Availability
Due to file size constraints and institutional data policies, raw SERS spectral data are not publicly distributed. However, the structure of the dataset, preprocessing logic, and analysis pipeline are fully described to enable reproduction of results using independent datasets.


# Intended Audience
This repository is intended for researchers and practitioners working in:
•	Surface-enhanced Raman spectroscopy (SERS)
•	Biosensing and diagnostic technologies
•	Machine learning applied to spectroscopy
•	Automated analytical platforms


