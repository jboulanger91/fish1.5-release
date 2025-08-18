---
layout: page
title: A Functional Connectomics Ressource for the Larval Zebrafish Brain
nav_title: Home
permalink: /
---

<div style="overflow: hidden; margin-top: -2rem;">
  <img src="{{ '/assets/img/home_img.png' | relative_url }}"
       alt="Fish1.5 banner"
       style="width: 110%; max-width: 3000px; display: block; position: relative; left: -5%;">
</div>

<hr style="max-width: 1000px; margin: 1rem auto; border: none; border-top: 2px solid white;">
<hr style="max-width: 1000px; margin: 1rem auto; border: none; border-top: 2px solid white;">

The [Lichtman](http://lichtmanlab.fas.harvard.edu), [Engert](http://www.engertlab.org) laboratories at Harvard University, the [Del Bene](https://www.institut-vision.org/index.php/en/researchers/filippo-del-bene) laboratory at the Institut de la Vision (Sorbonne Université), Paris and the [Bahl](https://www.neurobiology-konstanz.com/bahl) laboratory at Konstanz University, Germany are releasing the Fish1.5 dataset and its companion [papers](https://jboulanger91.github.io/fish1.5-release/manuscripts/). 

**Fish1.5 is a 7-day post-fertilization larval zebrafish dataset**, combining electron microscopy (EM) and two-photon calcium imaging from the same specimen. Both modalities are registered at single cell resolution. The imaged region spans from the **medial optic tectum to rhombomere 3**. To generate this dataset, we used a transgenic larvae expressing a nuclear calcium indicator under the elavl3 pan-neuronal promoter, along with red fluorescent markers labeling the main inhibitory neuronal subtype and vascular endothelial cells: *Tg(elavl3:H2B-GCaMP7f, gad1b:DsRed, kdrl:mCherryCAAX)*

The resulting EM dataset, acquired at a resolution of **4 × 4 × 30 nm**, provides ultrastructural details such as synaptic connections and subcellular features. This volume includes **62745 cell bodies** out of which **15017** were functionally imaged using **4 stimuli : left- and rightward-moving dots of 100% coherence and sine gratings** in six optical planes spaced by 12 μm along the dorso-ventral axis. 

The dataset is editable through a collaborative proofreading tool, **CAVE** from [Dorkenwald et al., 2025](https://doi.org/10.1038/s41592-024-02426-z), allowing the community to reconstruct neurons of interest, analyze their connectivity, overlay neurotransmitter and functional information to test circuit models. To request **editing privileges** for the Fish1.5 dataset, please fill out this **[form](https://forms.gle/oCB8kjXzkWYQEbYL8)**. Browsing and editing the dataset requires a Google account and works best in Chrome and Firefox. 

We are grateful to [Zetta AI](https://zetta.ai/) for alignment, cell segmentation, synapse detection & assignment, and hosting CAVE. 

### Explore More:
- **[Manuscripts](https://jboulanger91.github.io/fish1.5-release/manuscripts/)** highlight recent publications that leverage or complement the Fish1.5 dataset. 
- **[Gallery](https://jboulanger91.github.io/fish1.5-release/gallery/)** showcases various neuronal and glial populations in the dataset. 
- **[Navigation and Proofreading](http://127.0.0.1:4000/fish1.5-release/navigation-proofreading/)** using CAVE. 
- **[Tutorials](https://jboulanger91.github.io/fish1.5-release/tutorials/)** For programmatic access to reconstructed cellular morphologies, synaptic connectivity, and functional activity data.

**Contact:** [boulangerweill@fas.harvard.edu](mailto:boulangerweill@fas.harvard.edu)

