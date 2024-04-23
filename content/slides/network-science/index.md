---
title: "Diffusion "
date: 2022-07-24T11:03:08.395Z
draft: false
featured: false
tags:
  - networks
categories:
  - networks
image:
  filename: 1-00nm5nz_7baahep25vpf3a.jpeg
  focal_point: Smart
  preview_only: false
---
Diffusion is a common method for examining the structure and modelling physical processes on graphs. In particular, I have been interested in the transient responses of nodes to diffusion at some source. Using the transient responses of other nodes we can extract lots of interesting information about the graph and also perform node classification.

Probably the most interesting output from our exploration into diffusion, geometry and graph structures was the definition of Relative Dimension. Dimension is a fundamental concept within physics and mathematics that characterizes objects and the spaces in which they are embedded, and has many important physical consequences. Yet in many real-world, complex physical systems, the ideal notion of dimension does not extend easily to many real-world, complex physical systems, in which the spaces under consideration can be finite with boundaries; may be bounded, inhomogeneous; or can be intrinsically discrete (as in networks), thus any processes within the space are constrained. Here we introduced a dynamics-based notion of dimension that applies naturally to such non-ideal physical systems.

Our work exploits the classic link between diffusive processes and the geometry of the space in which they evolve. Classically, Indeed, diffusion has been used to examine the geometry of such spaces, and through observation of the the observation of diffusion behaviour one can be used to reveal the dimension of the space in which it occurs. For example, by considering, e.g., the speed of decay of the decay of a delta function at a point. at a some source then one can extract an estimate of the dimension (S. Reuveni, R. Granek, and J. Klafter, Proceedings of the National Academy of Sciences, 107, 13696, 2010). However, such approaches to measuring dimension, such as that cited, only consider the dynamics at one point - the source of the delta function. In contrast, we introduce a notion of dimension that exploits the propagation of the diffusion, i.e., we compute the dimension from the observation of ing the transient response at a some different point yi different fromto the source y0. Accordingly, the dimension is relative between the source and observer, and forms the basis of our conceptualisation of relative dimension. This Importantly, our approach enriches the notion of dimension, a statement which we illustrate through a simple constructed example in which we consider a 2-d filled circle attached to a 1-d line. We can initialise a delta function at the joint between the circle and line and then measure the dimension at y1 in the centre of the circle and y2 at the end of the 1-d line. The relative dimension of the source to y1 would be closer to \~2, whilst closer to \~1 when measuring relative to y2. Had we only considered the source, and not the propagation of diffusion, we would have ignored these crucial differences stemming from the relative geometry between each pair of points.