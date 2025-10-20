---
layout: page
title: Tutorials
permalink: /tutorials/
position: 4
---

# Interacting with the Fish1.5 Dataset

This page covers scripts for programmatic access to the Fish1.5 dataset using [CAVE](https://www.caveconnecto.me/CAVEclient/) (Connectome Annotation and Versioning Engine).

---

## Setup CAVE

- To install CAVEclient use pip:

```bash
pip install caveclient
```

- Once you have installed the CAVEclient, you need to set up your user token using the following notebook:

[CAVE_setup.ipynb](https://nbviewer.org/url/rawcdn.githack.com/jboulanger91/fish1.5-notebooks/main/notebooks/CAVE_setup.ipynb)

---

## Download Cellular Morphologies and Connectivity

- This notebook explains how to retrieve morphology and input/output synapses for segmented objects:

[download_mesh_and_synapses.ipynb](https://nbviewer.org/url/rawcdn.githack.com/jboulanger91/fish1.5-notebooks/main/notebooks/download_mesh_and_synapses.ipynb)

---

## Retrieve Neuronal Activity

- This part does **not** require CAVE setup.
- The Fish1.5 calcium imaging dataset is available on Zenodo: [Zenodo DOI](https://doi.org/10.5281/zenodo.16893093)
- Use the following notebook to explore functional responses to random dots and sine gratings:

[functional_responses.ipynb](https://nbviewer.org/url/rawcdn.githack.com/jboulanger91/fish1.5-notebooks/main/notebooks/functional_responses.ipynb)

---

## Environment Setup

To ensure reproducibility and access to all dependencies, clone the GitHub repo and set up the environment using Conda:

```bash
git clone https://github.com/jboulanger91/fish1.5-notebooks.git
cd fish1.5-notebooks
conda env create -f environment.yml
conda activate fish-env
```

All necessary dependencies are included in the `environment.yml` file.

GitHub repository: [https://github.com/jboulanger91/fish1.5-notebooks]https://github.com/jboulanger91/fish1.5-notebooks

