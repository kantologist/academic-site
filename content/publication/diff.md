+++
date = 2020-11-20
title = "Differentiable Histogram with Hard-Binning"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view = 4

# Optional featured image (relative to `static/img/` folder).
+++

  The simplicity and expressiveness of a histogram render it a useful feature in different contexts including deep learning. Although the process of computing a histogram is non-differentiable, researchers have proposed differentiable approximations, which have some limitations. A differentiable histogram that directly approximates the hard-binning operation in conventional histograms is proposed. It combines the strength of existing differentiable histograms and overcomes their individual challenges. In comparison to a histogram computed using Numpy, the proposed histogram has an absolute approximation error of 0.000158.
[Paper](https://arxiv.org/pdf/2012.06311.pdf)/ [Accepted in BAI Workshop 2020](https://blackinai2020.vercel.app/cpfbai2020)