+++
title = "Unsupervised Domain Adaptation by Optical Flow Augmentation in Semantic
  Segmentation (A proposal)"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view = 3

# Optional featured image (relative to `static/img/` folder).
<!-- [header]
image = "kittitest.png"
caption = "Unsupervised Domain Adaptation by Optical Flow Augmentation in Semantic Segmentation" -->
+++

It is expensive to generate real-life image labels and there is a domain gap
between real-life and simulated images, hence a model trained on the latter
cannot adapt to the former. Solving this can totally eliminate the need for
labeling real-life datasets completely. Class balanced self-training is one of
the existing techniques that attempt to reduce the domain gap. Moreover,
augmenting RGB with flow maps has improved performance in simple semantic
segmentation and geometry is preserved across domains. Hence, by augmenting
images with dense optical flow map, domain adaptation in semantic segmentation
can be improved.