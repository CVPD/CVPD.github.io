---
title: Geometry-Based Differentiable Camera Placement for Optimal 3D Coverage.
authors:
- Ane Moraza
- Xiao Lin
- Daniel Mejia-Parra
- Nagore Barrena
date: '2026-01-01'
publishDate: '2026-07-08T06:12:17.844755Z'
publication_types:
- paper-conference
publication: '*VISAPP (3)*'
doi: 10.5220/0014335800004084
abstract: 'Optimal camera placement is fundamental for inspection and 3D reconstruction
  tasks. We address this traditionally discrete problem by reformulating it into a
  continuous optimization task using Differentiable Rendering (DR), a technique that
  enables gradient computation from 3D camera poses to a final loss value. Assuming
  a known scene, our pipeline treats camera poses as learnable parameters. We implement
  a novel differentiable visibility formulation that compares observed depths from
  the rendered scene, with the expected depth of the mesh vertices. Based on this,
  we define a geometry-based loss function using two specific coverage criteria: ”At-Least-Once”
  (ALO) and ”Exactly-Once” (EO), which find optimal placement configurations. Experiments
  conducted on diverse 3D objects and camera configurations demonstrate that our approach
  outperforms the SOTA baseline Neural Observation Field Guided Hybrid Optimization
  of Camera Placement (NeOF). Our methods yield superior quality, as demonstrated
  by our quantitative evaluation, and achieve lower computation times. Furthermore,
  the quality and efficiency of the generated poses show strong potential for future
  integration into trajectory planning systems.'
url_pdf: https://www.scitepress.org/Papers/2026/143358/143358.pdf
---
