---
layout: page
title: Navigation and Proofreading
permalink: /navigation-proofreading/
position: 2
---

Navigation and proofreading are done in Neuroglancer (most recent Spelunker branch). The dataset is accessible [here](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5397500134424576). 

## Registering To Navigate and Proofread with CAVE

1. Apply for a CAVE account by submitting [this form](https://forms.gle/oCB8kjXzkWYQEbYL8). We will respond to your application within 24 h.
2. After you’ve been approved, open one of the links above and click the **Login** button at the bottom of the Neuroglancer page. You must use the same email address you provided through your application’s Google form.
3. If you do not yet feel confident proofreading, we will initially grant view-only access to allow you time to explore the dataset and complete the necessary training.

## Navigation

1. Basic instructions can be found in the MICrONS Explorer website [here](https://www.microns-explorer.org/ngl-instructions), [here](https://tutorial.microns-explorer.org/neuroglancer-basic.html) and in this Eyewire [video](https://youtu.be/tnoIdea7Wmo?si=kd1xA3QVotrLYnTd)
2. The dataset contains multiple layers that can be toggled on and off by clicking on the tab or using the corresponding number key. 
![ ]({{ site.baseurl }}/assets/img/layers.jpg)
Rendering options for each layer can be modified by right clicking on the layer tab. This will open a panel to the right of the screen. 
- `1. img` corresponds to the EM images  
- `2. em_downsampled` corresponds to the EM images downsampled at 512 × 512 × 480 nm for faster browsing. This layer also helps when overlaying the two-photon imaging stacks (see below). 
- `3. seg` corresponds to the EM segmentation     
- `4. elavl3:H2B-GCaMP7f` is a registered two-photon imaging stack of the nuclear calcium indicator GCaMP7f under the elavl3 promoter.  
- `5. gad1b:DsRed, kdrl:mCherryCAAX` is a registered two-photon imaging stack of red fluorescent reporters that label the main inhibitory neuronal subtype (gad1b:DsRed) and vascular endothelial cells (kdrl:mCherryCAAX). 
- `6. functional masks` Functional masks are spatial masks registered from the two-photon functional imaging planes. Each mask corresponds to a unique neuronal ID, which can be used to retrieve activity data via custom Jupyter Notebooks (see the [Tutorials](https://jboulanger91.github.io/fish1.5-release/tutorials/) page). Mask IDs can be accessed by clicking on a mask and checking the Seg. tab in the right panel, or simply by hovering over a mask — the ID will appear directly in the functional masks layer tab. In the link above the neuron with ID 9978 is displayed. 
- `7. ot hb region outlines` are outlines of the main regions in this dataset: opti tectum (periventricular zone and neuropil) and hindbrain. 
- `8. synapses` describes how to render imagery. 
- `9. ann` is a manual annotation layer, allowing the user to add annotations to the data (`Ctrl + Click`, either in the 2D or 3D panel). You need to right click on the layers tab to add annotations. 

## Making Proofreading Edits

Proofreading in the Fish1.5 dataset is done in the same navigation link as above. Make edits only when confident—they’ll improve segmentation, you are contributing to a commuunity effort. To get started here’s a quick guide on editing within Neuroglancer:

1. **Merging two segments (Correct Split Errors)**  
The link above has shortcuts for merge and cut operations already defined.
You can merge multiple pairs of segments at once. A single bulk merge can merge up to 10 pairs of segments.
   
   1. Select the segments yo want to merge 
   2. Press `M` to open the merge menu. This should appear in the bottom left of the screen. 
   ![ ]({{ site.baseurl }}/assets/img/proofreading_merging_image1.png)
   3. `Ctrl + Click` on segment 1 (2D or 3D) to draw a red line; then `Ctrl + Click` on segment 2. You will see the red line connecting the two segments. If done successfully, both segments will appear in the merge menu.
   ![ ]({{ site.baseurl }}/assets/img/proofreading_merging_image2.png)
   4. This process can be repeated up to 10 times before submitting the merge request.
   ![ ]({{ site.baseurl }}/assets/img/proofreading_merging_image3.png)
   5. Click **Submit** to merge selected segments; merged ones render in the same color.
   ![ ]({{ site.baseurl }}/assets/img/proofreading_merging_image4.png)
   6. If you have enabled auto-submit, the request will be sent automatically after selecting each segment pair.
   7. You can click `Clear` to cancel all your selections or cancel a selection one by one using the Trash icon.

2. **Cut a segment in two (Correcting Merge Errors)**  
   1. Go to the Graph Tab in the neuroglancer settings. In the above link, the merge feature is bound to the C key. Make sure you are in the Graph Tab and not (!) in the Seg. Tab.
   2. Press `C` to open the cutting menu.
   ![ ]({{ site.baseurl }}/assets/img/image3.png)
   3. In the 3D view, place points around the region you want to split on mesh 1. To place points hold Shift + Control while you click on a mesh.
   4. After you placed points on mesh 1, click Swap before you place points on mesh 2
   5. After you place points on both sides of the desired cut, it should look similar to this: 
   ![ ]({{ site.baseurl }}/assets/img/image4.png)
   6. Click Submit to perform the cut. After a few seconds, you should see both sides of the cut in separate colors. After reloading neuroglancer, the meshes will update.

3. **Setting shortcuts for edit commands**  
If you want to change those shortcuts, you can bind new keys. In the Graph tab, Click & hold the mouse over the Merge or Multicut field. Next, hit the key you want to bind to the operation. The letter next to the field will update if the new shortcut was set successfully.

<div class="language-plaintext highlighter-rouge">
  <div class="highlight">
    <pre class="highlight"><code>Shift + A → Merge
Shift + C → Cut</code></pre>
  </div>
</div>




