+++
title = "Agent Probing Interaction Policies"

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view = 3

# Optional featured image (relative to `static/img/` folder).
+++

  Reinforcement learning in a multi agent system is difficult because these
systems are inherently non-stationary in nature. In such a case, identifying
the type of the opposite agent is crucial and can help us address this
non-stationary environment. We have investigated if we can employ some probing
policies which help us better identify the type of the other agent in the
environment. We've made a simplifying assumption that the other agent has a
stationary policy that our probing policy is trying to approximate. Our work
extends Environmental Probing Interaction Policy framework to handle multi
agent environments.
[Paper](https://arxiv.org/abs/1910.10369)