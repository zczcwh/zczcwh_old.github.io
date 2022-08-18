---
title: "A Lightweight Graph Transformer Network for Human Mesh Reconstruction from 2D Human Pose"
collection: publications
permalink: /publication/gtrs
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2021-07-17
venue: "arxiv 2022"
paperurl: https://arxiv.org/pdf/2111.12696.pdf"

citation: '<b>Ce Zheng</b>, Matias Mendieta, Pu Wang, Aidong Lu, Chen Chen. "A Lightweight Graph Transformer Network for Human Mesh Reconstruction from 2D Human Pose". <i>(ACM Multimedia 2022)</i>. '
---
# A Lightweight Graph Transformer Network for Human Mesh Reconstruction from 2D Human Pose

[<a href="https://arxiv.org/pdf/2111.12696.pdf">Paper</a>]



## Abstract
Existing deep learning-based human mesh reconstruction approaches have a tendency to build larger networks in order to achieve higher accuracy. Computational complexity and model size are often neglected, despite being key characteristics for practical use of human mesh reconstruction models (e.g. virtual try-on systems). In this paper, we present GTRS, a lightweight pose-based method that can reconstruct human mesh from 2D human pose. We propose a pose analysis module that uses graph transformers to exploit structured and implicit joint correlations, and a mesh regression module that combines the extracted pose feature with the mesh template to reconstruct the final human mesh. We demonstrate the efficiency and generalization of GTRS by extensive evaluations on the Human3.6M and 3DPW datasets. In particular, GTRS achieves better accuracy than the SOTA pose-based method Pose2Mesh while only using 10.2% of the parameters (Params) and 2.5% of the FLOPs on the challenging in-the-wild 3DPW dataset. Code will be publicly available.

## Citation
    @article{zheng2022gtrs,
      title={A Lightweight Graph Transformer Network for Human Mesh Reconstruction from 2D Human Pose},
      author={Zheng, Ce and and Mendieta, Matias and Wang, Pu and Lu,Aidong and Chen, Chen},
      journal={ACM Multimedia},
      year={2022}
    }
