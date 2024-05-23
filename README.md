![Maturity level-0](https://img.shields.io/badge/Maturity%20Level-ML--0-red)

![Logo](https://github.com/alxndgb/ComPPlete/blob/main/images/Alexion_AZ_Logo.png)

# ComPPlete

## Project Description

ComPPlete (Completing the Protein-Protein Interaction Network) is a novel ML pipeline utilizing PPI network topology for strategic sampling of protein-protein non-interactions (PPNIs) by leveraging higher-order network characteristics that capture the inherent complementarity-driven mechanisms of PPIs.
Integrating unsupervised pre-training in protein representation learning with topological PPNI samples, ComPPlete improves PPI prediction generalizability and interpretability, particularly in identifying potential binding sites locations on amino acid sequences.
ComPPlete strengthens the prioritization of screening assays, facilitates the transferability of ML predictions across protein families and homodimers.
ComPPlete establishes the foundation for a fundamental negative sampling methodology in graph machine learning by integrating insights from network topology.

## Software Requirements

ComPPlete is developed in Python 3. Required packages to run ComPPlete is available in: compplete_env.yml.

## How to use/Run the code

ComPPlete is developed with NVIDIA A100 GPUs with CUDA 12.0. Use the compplete_env.yml to set-up the Python 3 environment. Then use ComPPlete_Frontend.ipynb to run predictions. You require the amino acid sequences of both proteins.

# Data

## data/ComPPlete_PPNI_PPI_Interactome

ComPPlete interactome is available here. It contains predicted PPIs (protein-prtoein interactions) and PPNIs (protein-prtoein none interactions). 

## Topological_Negatives

The negatives used in training ComPPlete.

# Models

## models/ 

Trained models.

# Code

## frontend/ 

Use this notebook to run ComPPlete models.

## interpretability

This notebook offers the code to obtain binding profiles

