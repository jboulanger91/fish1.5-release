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
- Once you have installed the CAVEclient, to use it you need to set up your user token using the following [notebook](https://nbviewer.org/url/rawcdn.githack.com/jboulanger91/fish1.5-notebooks/main/notebooks/functional_responses.ipynb) 

## Download cellular morphologies and connectivity 
- Morphology and Connectivity: This [page](https://nbviewer.org/url/rawcdn.githack.com/jboulanger91/fish1.5-notebooks/main/notebooks/download_mesh_and_synapses.ipynb) explains how to retrieve morphology, input and output synapses for segmented objects

## Retrieve neuronal activity 

- This part doesn't require to setup CAVE. 
- The dataset containing Fish1.5 activity has been deposited to Zenodo [here](https://doi.org/10.5281/zenodo.16893093). 
- Use this [notebook](https://nbviewer.org/url/rawcdn.githack.com/jboulanger91/fish1.5-notebooks/main/notebooks/functional_responses.ipynb) to display functional responses to random dots and sine gratings. 
