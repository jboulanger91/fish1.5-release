---
layout: page
title: Tutorials
permalink: /tutorials/
position: 4
---

## Interacting with the dataset 

This page covers scripts for programmatic access to the Fish1.5 dataset using [CAVE](https://www.caveconnecto.me/CAVEclient/) (Connectome Annotation and Versioning Engine).  

## Setup CAVE
- To install CAVEclient use pip `pip install caveclient`.
- TO BE ADDED SOON : Once you have installed the CAVEclient, to use it you need to set up your user token in one of two ways

## Download cellular morphologies and connectivity 

- Morphology: This [page](https://tutorial.microns-explorer.org/quickstart_notebooks/06-cloudvolume-download-mesh.html) from the [MICrONs](https://tutorial.microns-explorer.org/) project explain how to retrieve meshes for segmented objects.  
- Connectivity: This [page](https://tutorial.microns-explorer.org/quickstart_notebooks/04-cave-query-synapses.html) from the same source explain how to retrieve input and output synapses for segmented objects
- TO BE ADDED SOON : A Notebook showcasing these different aspects 

## Retrieve neuronal activity 

- This part doesn't require to setup CAVE. 
- The dataset containing Fish1.5 activity has been deposited to Zenodo [here](https://doi.org/10.5281/zenodo.16893093). 
- Use this [notebook](https://github.com/jboulanger91/fish1.5-notebooks/blob/main/notebooks/functional_responses.ipynb) to display functional responses to random dots and sine gratings. 
