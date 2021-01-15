+++
title = "Deep Classification Network for Monocular Depth Estimation"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view = 4

# Optional featured image (relative to `static/img/` folder).
[header]
image = "kittitest.png"
caption = "Depth Predictions on KITTI. The Image on the left column, ground truth in the middle and our model prediction on the right."
+++
Monocular Depth Estimation is usually treated as a supervised and regression problem when it actually is very similar to semantic segmentation task since they both are fundamentally pixel-level classification tasks. We applied depth increments that increases with depth in discretizing depth values and then applied Deeplab v2 and the result was higher accuracy. We were able to achieve a state-of-the-art result on the KITTI dataset and outperformed existing architecture by an 8% margin.
[Poster](https://www.instadeep.com/wp-content/uploads/2019/09/Correct-Indaba-Poster-azeez-2.pdf) / [Presented at Deep Learning Indaba](http://www.deeplearningindaba.com/) / [Presented at MLSS London](https://sites.google.com/view/mlss-2019)