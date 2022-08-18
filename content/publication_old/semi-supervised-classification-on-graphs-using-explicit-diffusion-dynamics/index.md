---
title: Semi-supervised classification on graphs using explicit diffusion dynamics
publication_types:
  - "2"
authors:
  - Robert Peach
  - Alexis Arnaudon
  - Mauricio Barahona
doi: http://dx.doi.org/10.3934/fods.2020002
publication: Foundations of Data Science 2 (1), 19-33
abstract: Classification tasks based on feature vectors can be significantly
  improved by including within deep learning a graph that summarises pairwise
  relationships between the samples. Intuitively, the graph acts as a conduit to
  channel and bias the inference of class labels. Here, we study classification
  methods that consider the graph as the originator of an explicit graph
  diffusion. We show that appending graph diffusion to feature-based learning as
  an a posteriori refinement achieves state-of-the-art classification accuracy.
  This method, which we call Graph Diffusion Reclassification (GDR), uses
  overshooting events of a diffusive graph dynamics to reclassify individual
  nodes. The method uses intrinsic measures of node influence, which are
  distinct for each node, and allows the evaluation of the relationship and
  importance of features and graph for classification. We also present diff-GCN,
  a simple extension of Graph Convolutional Neural Network (GCN) architectures
  that leverages explicit diffusion dynamics, and allows the natural use of
  directed graphs. To showcase our methods, we use benchmark datasets of
  documents with associated citation data.
draft: false
featured: false
tags:
  - networks
categories:
  - networks
projects:
  - networks
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-08-04T10:58:00.000Z
---
