# Augmentations: An Insight into their Effectiveness on Convolution Neural Networks

### This paper was presented at ICACDS, 2022 - 23 Apr 2022

### Authors - Sabeesh E, Bharath Kumar Bolla 

Original Paper : [Research_paper.pdf](https://github.com/sabeesh90/Augmentations-An-Insight-into-CNNs_ICACDS_2022/files/8976007/373_Submission_arxiv.pdf) <br>
PPT - A Glimpse : [ICACDS.pptx](https://github.com/sabeesh90/Augmentations-An-Insight-into-CNNs_ICACDS_2022/files/8976009/ICACDS.pptx) <br>

<img src = "https://user-images.githubusercontent.com/48343095/175537119-12165cc8-3d9e-45da-b6c3-2a2a887eada7.jpg" width = 500 height = 600>

<h2> Summary of the Paper </h2>
  - A need to identify augmentations that are consistent across datasets <br>
  - Evaluation of 3x3 vs Depthwise separable convolutions and their effect on augmentations  <br>
  - Bridging of gap between 3x3 and DW Convs by augmentations - Dimunishing differences / Higher number of params : DW better than 3x3 <br>
  - Cutouts / Mixup equivalent to Random horizontal flip - Consistent across architectures - Least STD +  Highest positive average change in accuracy <br>
  - Higher parameters - Augmentations cause little change in accuracy (Lower STD) <br>
  - Multiple augmentations  - synergestic at higher number of parameters / Antagonistic at lower number of parameters <br>
  
<h2> Aim of the Research </h2>
The aim of this paper is to design light weight and faster neural networks. <br>
  - To evaluate the relationship between model capacity and augmentation <br>
  - To evaluate the effect of model capacity on multiple augmentations <br>
  - To evaluate the effect of depth wise separable convolution on augmentation <br>
 
<h2> Augmentations  - Mosaic ML + Pytorch Augmentations </h2>
  - Random Rotation / Random Horizontal Flip <br>
  - Random Affine  / Random Perspective / Color jitters <br>
  - Cutouts / Mixup (Mosiac ML) <br>
   
<h2> Model Architecture </h2>   
<img src = "https://user-images.githubusercontent.com/48343095/179441525-d266cb76-ed28-476e-a408-bc2ebad2c4b7.jpg" width = 500 height = 600>

<h2> Results </h2>
1. Equivocal performances on architectural saturation   - Dimunision of accuracies <br>
2. 







