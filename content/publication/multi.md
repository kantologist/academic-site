+++
date = 2020-08-11
title = "EFFICIENT INTEGRATION OF MULTI-CHANNEL INFORMATION FOR DNN-BASED SPEECH SEPARATION USING ATTENTION MECHANISM AND TRANSFER LEARNING"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view = 4

# Optional featured image (relative to `static/img/` folder).
[header]
image = "multi.png"
+++

  Although deep-learning-based methods have significantly improved
the performance of speech separation over the past few years, efficient integration of multi-channel signals still remains an open question. The main problem is that the performance tends to degrade
when the angle difference between speakers is small. In addition,
the computational complexity of several existing algorithms scales
with the number of input channels. We propose an attention-based
architecture to adaptively process signals with any angle difference.
Its computational complexity hardly increases even when the number of input channels increases. Moreover, we propose a transfer
learning framework that converts a network that works on singlechannel input to one that works on multi-channel input. This framework helps our proposed architecture obtain better attention weights
and contributes to improving the separation performance. Experiments showed that our proposed method achieved the state-of-the-art
performance while remaining computationally efficient.
[Paper](https://arxiv.org/pdf/2005.11612.pdf)/ [Under Review at ICASSP 2021](https://2021.ieeeicassp.org/)