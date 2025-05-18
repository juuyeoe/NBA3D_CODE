# NBA3D: Neighbor-Based Confdence Adjustment for 3D Rare Object Detection Using LiDAR (AAAI2025)
Jooyoung Lee, Jaeyoon Lee, Jongwon Choi*
## Abstract
> Recent research on LiDAR-based 3D object detectors has
shown strong performance; however, evaluations typically focus on dominant classes, overlooking rare classes, such as
strollers, which could be critical in real autonomous driving scenarios. This oversight is problematic because stateof-the-art 3D object detectors show signifcantly lower performance on rare classes compared to dominant ones when
trained on both. To address this issue and achieve accurate 3D
rare object detection using only LiDAR data, we propose the
Neighbor-Based confdence Adjustment for 3D rare class predictions (NBA3D). NBA3D utilizes a graph neural network
to analyze the surrounding environment of rare class prediction boxes, enabling a more effective distinction between true
positives and false positives based on their local context. Our
approach utilizes both 3D prediction box characteristics and
CLIP-based class semantic information to better contextualize neighboring objects. Various experiments demonstrate
that NBA3D effectively improves the detection performance
of rare class objects, regardless of the type of 3D object detectors used.

![#733_POSTER_1](https://github.com/user-attachments/assets/5fc8628e-b35d-4295-bb48-9375fe3367e7)


## Citation
```
@inproceedings{lee2025nba3d,
  title={NBA3D: Neighbor-Based Confidence Adjustment for 3D Rare Object Detection Using LiDAR},
  author={Lee, Jooyoung and Lee, Jaeyoon and Choi, Jongwon},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={39},
  number={4},
  pages={4508--4516},
  year={2025}
}
```
