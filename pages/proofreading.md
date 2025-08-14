---
layout: page
title: Proofreading
permalink: /proofreading/
position: 3
---

## Registering To Proofread with CAVE

1. Apply for a CAVE account by submitting [this form](https://forms.gle/oCB8kjXzkWYQEbYL8). We will respond to your application within 24 h.
2. After you’ve been approved, open one of the links above and click the **Login** button at the bottom of the Neuroglancer page. You must use the same email address you provided through your application’s Google form.
3. Now, you are all set to start proofreading!

## Proofreading Overview

Proofreading is done in Neuroglancer, which you need to access through a special link:

1. [The full dataset](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5361288778612736) This allows users to proofread the entire Fish1.5 volume. Make edits only when confident—they’ll improve segmentation. 

2. [Tutorials](https://github.com) on programmatic interaction with CAVE.

3. Proofreading [Video Tutorials](https://www.youtube.com) from Flywire on YouTube. 

## Making Proofreading Edits

Here’s a detailed guide on editing within Neuroglancer:

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
   7. You can click Clear to cancel all your selections or cancel a selection one by one using the Trash icon.

2. **Cut a segment in two (Correcting Merge Errors)**  
   1. Go to the Graph Tab in the neuroglancer settings. In the above link, the merge feature is bound to the C key. Make sure you are in the Graph Tab and not (!) in the Seg. Tab.
   2. Click C to open the cutting menu.
   ![ ]({{ site.baseurl }}/assets/img/image3.png)
   3. In the 3D view, place points around the region you want to split on mesh 1. To place points hold Shift + Control while you click on a mesh.
   4. After you placed points on mesh 1, click Swap before you place points on mesh 2
   5. After you place points on both sides of the desired cut, it should look similar to this
   ![ ]({{ site.baseurl }}/assets/img/image4.png)
   6. Click Submit to perform the cut. After a few seconds, you should see both sides of the cut in separate colors. After reloading neuroglancer, the meshes will update.
-
- Click **Swap**, then place points on mesh 2.
- Usually, ~3 points per side suffice.
- Click **Submit** to perform the cut—after reloading, each side appears in a different color.

3. **Setting shortcuts for edit commands**  
If you want to change those shortcuts, you can bind new keys. In the Graph tab, Click & hold the mouse over the Merge or Multicut field. Next, hit the key you want to bind to the operation. The letter next to the field will update if the new shortcut was set successfully.

<div class="language-plaintext highlighter-rouge">
  <div class="highlight">
    <pre class="highlight"><code>Shift + A → Merge
Shift + C → Cut</code></pre>
  </div>
</div>


