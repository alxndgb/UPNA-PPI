![Maturity level-0](https://img.shields.io/badge/Maturity%20Level-ML--0-red)

![Logo](https://github.com/alxndgb/UPNA-PPI/blob/main/images/Alexion_AZ_Logo.png)

# UPNA-PPI

## Project Description

UPNA-PPI is a novel ML pipeline utilizing PPI network topology for strategic sampling of protein-protein non-interactions (PPNIs) by leveraging higher-order network characteristics that capture the inherent complementarity-driven mechanisms of PPIs.
Integrating unsupervised pre-training in protein representation learning with topological PPNI samples, UPNA-PPI improves PPI prediction generalizability and interpretability, particularly in identifying potential binding site locations on amino acid sequences.
UPNA-PPI strengthens the prioritization of screening assays and facilitates the transferability of ML predictions across protein families and homodimers.
UPNA-PPI establishes the foundation for a fundamental negative sampling methodology in graph machine learning by integrating insights from network topology.

## Software Requirements

UPNA-PPI is developed in Python 3. Required packages to run UPNA-PPI is available in: UPNA-PPI_env.yml.

## How to use/Run the code

UPNA-PPI is developed with NVIDIA A100 GPUs with CUDA 12.0. Use the UPNA-PPI_env.yml to set-up the Python 3 environment. Then use UPNA-PPI_Frontend.ipynb to run predictions. You require the amino acid sequences of both proteins.

# Data

## data/UPNA-PPI_PPNI_PPI_Interactome/

Two UPNA-PPI interactomes are available here: 

(1) UPNA-PPI PPI (Protein-Protein Interactions) interactome that has 4,582,765 PPI predictions

(2) UPNA-PPI PPNI (Protein-Prtoein None-Interactions) interactome that has 1,287,060 PPNI predictions. 

## Topological_Negatives/

The topological negatives were obtained from the contrastive-L3 approach. A total of 3,063,604 negatives between 5,037 proteins.

# Models

## models/ 

Trained models.

# Code

## frontend/ 

Use this notebook to run UPNA-PPI models.

## interpretability/

This notebook offers the code to obtain binding profiles

# Cite UPNA-PPI

If you find UPNA-PPI useful in your research, please add the following citation:

```
@article{UPNA-PPI,
  title={Topology-Driven Negative Sampling Enhances Generalizability in Protein-Protein Interaction Prediction},
  author={Chatterjee, Ayan and Ravandi, Babak and Philip, Naomi H and Abdelmessih, Mario and Mowrey, William R and Ricchiuto, Piero and Liang, Yupu and Ding, Wei and Mobarec, Juan C and Eliassi-Rad, Tina},
  url = {https://www.biorxiv.org/content/10.1101/2024.04.27.591478},
  journal={bioRxiv},
  pages={2024--04},
  year={2024},
}

```

