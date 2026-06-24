---
title: "BetaExplainer: A Probabilistic Method to Explain Graph Neural Networks"
collection: publications
category: manuscripts
permalink: /publication/betaexplainer
excerpt: 'BetaExplainer is a probabilistic GNN explanation framework that provides uncertainty estimates for edge importance and improves interpretability on complex graph datasets.'
date: 2025-06-03
venue: 'Journal of Statistical Theory and Applications'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://wanghungjen.github.io/files/betaexplainer.pdf'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Sloneker, W., Patel, S., Wang, H.-J., Crawford, L., & Singh, R. (2025). "BetaExplainer: A Probabilistic Method to Explain Graph Neural Networks." Journal of Statistical Theory and Applications, 24, 469–488.'
---
"Graph neural networks (GNNs) are powerful tools for conducting inference on graph data but are often seen as “black boxes" due to difficulty in extracting meaningful subnetworks driving predictive performance. Many interpretable GNN methods exist, but they cannot quantify uncertainty in edge weights and suffer in predictive accuracy when applied to challenging graph structures. In this work, we proposed BetaExplainer which addresses these issues by using a sparsity-inducing prior to mask unimportant edges during model training. To evaluate our approach, we examine various simulated data sets with diverse real-world characteristics. Not only does this implementation provide a notion of edge importance uncertainty, it also improves upon evaluation metrics for challenging datasets compared to state-of-the art explainer methods."