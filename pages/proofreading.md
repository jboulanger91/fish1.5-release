---
layout: page
title: Proofreading
permalink: /proofreading/
feature-img: "assets/img/pexels/travel.jpeg"
position: 3
---

## Registering To Proofread with CAVE

1. Apply for a CAVE account by submitting [this form](https://forms.gle/oCB8kjXzkWYQEbYL8). We will respond to your application within 24 h.
2. After you’ve been approved, open one of the links above and click the **Login** button at the bottom of the Neuroglancer page. You must use the same email address you provided through your application’s Google form.
3. Now, you are all set to start proofreading!

## Proofreading Overview

Proofreading is done in Neuroglancer, which you need to access through a special link:

Currently, we support proofreading for two datasets:

1. [Test dataset](https://ngl.brain-wire.org)  
   The test dataset is a previous version of agglomeration for the Fish1 and serves as a sandbox to test proofreading. You can play around without worrying about correctness.

2. [The full dataset](https://ngl.brain-wire.org)  
   This allows users to proofread the entire Fish1 volume. Make edits only when confident—they’ll improve segmentation.

3. [Tutorials](https://github.com) on programmatic interaction with CAVE.

4. Proofreading [Video Tutorials](https://www.youtube.com) on YouTube.

## Making Proofreading Edits

Here’s a detailed guide on editing within Neuroglancer:

1. **Setting shortcuts for edit commands**  
   Default shortcuts:

To rebind, go to the Graph tab, click and hold over the Merge or Multicut field, then press your desired key—if successful, the letter updates.

2. **Merging two segments (Correct Split Errors)**  
- Select the segments to merge.
- Press `M` to open the merge menu.
- `Ctrl + Click` on segment 1 (2D or 3D) to draw a red line; then `Ctrl + Click` on segment 2. Both appear in the merge menu.
- Repeat up to 10 times before submitting.
- Click **Submit** to merge selected segments; merged ones render in the same color.
- If **auto-submit** is enabled, submissions happen as you connect segments.
- Use **Clear** to reset selections, or remove them individually with the **Trash** icon.

3. **Cut a segment in two (Correcting Merge Errors)**  
- In the Graph Tab (ensure you're not in the Seg. tab), press `C` to open the cutting menu.
- In 3D view, place points around the split region on mesh 1 using `Shift + Ctrl + Click`.
- Click **Swap**, then place points on mesh 2.
- Usually, ~3 points per side suffice.
- Click **Submit** to perform the cut—after reloading, each side appears in a different color.


