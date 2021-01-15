+++
title = "ChexNet Model Compression for Pneumonia Detection Using Low Powered Edge Devices"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view = 4

# Optional featured image (relative to `static/img/` folder).

+++
Globally, there are approximately 7% of the population suffering from Pneumonia (Ruuskanen et al. [2011]). Diagnosing pneumonia requires a review of chest radiography by specialized trained radiologists. Improving the efficiency and reach of diagnostic services is of great importance in developing countries.

Deep Neural Networks (DNN) have been experiencing a rapid, tremendous progress due to the availability of large datasets. DNNs such as ChexNet (Rajpurkar et al. [2017]), TieNet (Wang et al. [2018]) have been proposed by researchers to aid in early diagnosis and detection of pneumonia and there has been great success. These networks, however, have deep architectures resulting into large memory storage and computation requirements. And as such, poses a great challenge for portable medical devices and embedded systems.

Model compression is a technique for reducing such large computations and memory requirements. Various methods to do such have been proposed. Some of which include filter pruning (Li et al. [2016]), channel pruning (He et al. [2017]). Majority of these pruning techniques have been experimented on large DNN models for different task. To our knowledge, not much has been done for models trained for medical image detection.

Hence, the goal of this work is to build a model compression algorithm for ChexNet. The ChexNet network is chosen as the base model because it is the current state of the art technique in detecting Pneumonia on chest x-ray and as such, a reasonable choice.
[Website ](https://www.k4all.org/project/chexnet-model-pneumonia/)