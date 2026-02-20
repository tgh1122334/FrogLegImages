
# Deep Neural Network Identification of Limnonectes Species and New Class Detection Using Image Data

This repository contains the data and code for the paper: [Deep Neural Network Identification of Limnonectes Species and New Class Detection Using Image Data](https://link.springer.com/article/10.1007/s13253-023-00592-9).

## Table of Contents
- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Citation](#citation)

## Overview
This project provides code and data for training and evaluating deep neural networks to identify Limnonectes frog species and detect new (out-of-distribution) classes using image data. The repository includes scripts for model training, evaluation, and statistical analysis, as well as the datasets used in the study.

## Repository Structure
- `Frogs_4clade_CV.ipynb` — Cross-validation experiments for 4 Limnonectes clades
- `Frogs_4cladesID_othersOOD.ipynb` — Identification and out-of-distribution detection
- `Frogs_QDALDA_fitting.ipynb` — QDA/LDA fitting and analysis
- `lib_RMD_v2.py` — Supporting Python library for Mahalanobis distance and LDA/QDA calculations
- `Frogs_Fewer_CV_res.csv` — Example results from cross-validation
- `iter_res.txt` — Iterative results and confusion matrices for QDA/LDA fitting
- `filled_images/` — Image data for each frog clade (subfolders per clade)

## Installation
1. Clone this repository:
	```bash
	git clone <repo-url>
	cd AIUQ
	```
2. Install required Python packages (see below for a typical set):
	```bash
	pip install numpy pandas scikit-learn matplotlib torch torchvision
	```
	Additional dependencies may be required depending on your environment.

## Usage
Open the Jupyter notebooks (`.ipynb` files) in your preferred environment (e.g., JupyterLab, VS Code) and follow the instructions in each notebook to reproduce the experiments and analyses from the paper.

## Data
The `filled_images/` directory contains subfolders for each Limnonectes clade, with images used for training and evaluation. CSV and TXT files provide results and labels for experiments.

## Results
Results from cross-validation and OOD detection experiments are provided in the CSV and TXT files. For detailed results and discussion, refer to the paper.


## Citation
If you use this code or data, please cite the following paper:
```bibtex
@article{limnonectes2024,
	title={Deep Neural Network Identification of Limnonectes Species and New Class Detection Using Image Data},
	journal={Statistical Analysis and Data Mining},
	year={2024},
	doi={10.1007/s13253-023-00592-9},
	url={https://link.springer.com/article/10.1007/s13253-023-00592-9}
}
```

## Acknowledgement
This README was generated with the assistance of AI tools. However, the associated paper was written entirely by human authors without AI-generated content.

