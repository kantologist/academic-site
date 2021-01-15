+++
date = 2019-09-14
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
caption = "Depth Predictions on KITTI. The Image on the left column, ground truth in the middle and our modelprediction on the right."
+++

Monocular Depth Estimation is usually treated as a supervised and regression problem when it actually is very similar to semantic segmentation task since they both are fundamentally pixel-level classification tasks. We applied depth increments that increases with depth in discretizing depth values and then applied Deeplab v2 and the result was higher accuracy. We were able to achieve a state-of-the-art result on the KITTI dataset and outperformed existing architecture by an 8% margin.
[Paper](https://arxiv.org/abs/1910.10369) / [Accepted in BAI Workshop 2019](https://blackinai.github.io/)