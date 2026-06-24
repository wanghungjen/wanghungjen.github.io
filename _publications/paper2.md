---
title: "Time is of the Essence: Why Decision-Time Planning Costs Matter"
collection: publications
category: conferences
permalink: /publication/thinker
excerpt: 'This paper is about fixing template issue #693.'
date: 2024-06-04
venue: 'Finding the Frame: An RLC Workshop for Examining Conceptual Frameworks'
paperurl: 'https://wanghungjen.github.io/files/thinker.pdf'
citation: 'Wang, K. A., Xia, J., Chung, S., Wang, J., Piedrahita Velez, F., Wang, H.-J., & Greenwald, A. (2024). "Time is of the Essence: Why Decision-Time Planning Costs Matter." Finding the Frame: An RLC Workshop for Examining Conceptual Frameworks.'
---
"The goal of this work is to build agents that use resources efficiently during decision-
time planning. Such agents should learn to dynamically spend more compute at
difficult, critical decision points, and less otherwise. To this end, we propose timed
MDPs and timed policies, which augment MDPs and policies to explicitly factor in
the cost of time and compute usage. By extending MDPs in this way, agents can
learn to trade off the cost of planning against potentially higher rewards.

To make our point concretely, we modify an existing algorithm, Thinker, to use a
variable amount of compute to make each decision. We then train it to maximize a
reward that includes a penalty for using more compute that depends on the context.
Our modified algorithm, Dynamic Thinker, learns to use compute more efficiently
thanThinkerandAlphaZero. Morespecifically, itreachessimilarperformancelevels
using fewer planning steps in experiments on a simple knapsack problem."
