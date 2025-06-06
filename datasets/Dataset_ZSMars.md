---
permalink: /datacode/ZSMars/
title: "ZSMars"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

To facilitate the zero-shot classification task focusing on Mars scenes, we reclassified the image categories within the collected public datasets. By reviewing the two versions of the Mars surface image datasets, MSL (v1) and MSL (v2), we identified overlapping categories and inconsistencies in size and color across images. To resolve these issues, we standardized the size and color of the images across the datasets and redefined the image categories specific to the MSC. We then formed an annotation team to conduct visual image annotation on the revised ZSMSC dataset, now named ZSMars.

In this dataset, we define the Martian surface scene into the following categories:

| Class name | Class definition | legend |
|------------|------------------|--------|
|Martian Regolith|Unconsolidated or poorly consolidated weathered material on Mars, reddish in color, does not form ridges due to terrain influence, and has relatively low mobility.| <img src="/images/ZMars/image01.png" alt="example" style="zoom:50%;" /> |
|Sand|Fine-grained material on Mars composed of small rock particles, typically formed by weathering and erosion, often forms ridges with windward and leeward slopes, and has relatively high mobility.| <img src="/images/ZMars/image02.png" alt="example2" style="zoom:50%;" /> |
|Gravel|Coarser than sand but finer than rocks, formed by weathering and erosion; generally moderate in mobility.| <img src="/images/ZMars/image03.png" alt="example3" style="zoom:50%;" /> |
|Veined Gravel Rock|Terrain on Mars consisting of patches of gravel and rocks, with distinct vein-like or extended strip patterns, usually rock-dominant with gravel coverage.| <img src="/images/ZMars/image04.png" alt="example4" style="zoom:50%;" /> |
|Pebbles|Small rocks fallen from larger rocks on the Martian surface, blocky or oval in shape, solid and brittle, larger than gravel particles, and generally free of gravel.| <img src="/images/ZMars/image05.png" alt="example5" style="zoom:50%;" /> |
|Igneous Rock|Rock formed from cooled and solidified magma on or beneath the Martian surface, featuring visible mineral crystals or vesicles, dark in color, irregular in shape, and lacking mobility.| <img src="/images/ZMars/image06.png" alt="example6" style="zoom:50%;" /> |
|Sedimentary Rock|Rock formed from the consolidation of layered loose sediment, often with visible stratification; contains little or no sand; larger in volume and immobile; sediments include gravel, sand, clay, or silt.| <img src="/images/ZMars/image07.png" alt="example7" style="zoom:50%;" /> |
|Rover Tracks|Imprints left by the wheels of Mars rovers on soft regolith or sand; close-up images show clear tread patterns, while distant shots display dragged strip marks caused by heavy movement.| <img src="/images/ZMars/image08.png" alt="example8" style="zoom:50%;" /> |
|Rover Components|Visible parts of a Mars rover or structures attached to it.| <img src="/images/ZMars/image09.png" alt="example9" style="zoom:50%;" /> |
|Unknown|Long-distance images of the Martian surface dominated by soft soil, possibly including sky or hills, but with indistinguishable surface compositions and clear light-dark layering between regions.| <img src="/images/ZMars/image10.png" alt="example9" style="zoom:50%;" /> |

### Citation of papers

If it is helpful for your work, please cite this paper:

@ARTICLE{10699382,  
  author={Tan, Xiaomeng and Xi, Bobo and Xu, Haitao and Li, Jiaojiao and Li, Yunsong and Xue, Changbin and Chanussot, Jocelyn},  
  journal={IEEE Transactions on Geoscience and Remote Sensing},  
  title={A Lightweight Framework with Knowledge Distillation for Zero-Shot Mars Scene Classification},  
  year={2024},  
  volume={},  
  number={},  
  pages={1-1},  
  keywords={Mars;Visualization;Semantics;Feature extraction;Scene classification;Image recognition;Microwave integrated circuits;Accuracy;Transformers;Data models;Mars scene classification;zero-shot learning;knowledge distillation;lightweight model},  
  doi={10.1109/TGRS.2024.3470526}
}

### [Google Drive Download Link](https://drive.google.com/drive/folders/1H0rA5CFzubRzLufm9y0YpSDPYMv63r5k)

<!-- 你也可以在此处添加参与构建数据集的人员列表 -->
