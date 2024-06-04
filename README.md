# DiffAvatar Simulation-Ready Garment Optimization with Differentiable Simulation

Copyright (c) Meta Platforms, Inc. and affiliates.

This source code is licensed under the MIT license found in the
LICENSE file in the root directory of this source tree.

**Abstract**
The realism of digital avatars is crucial in enabling telepresence applications with self-expression and customization. A key aspect of this realism originates from the physical accuracy of both a true-to-life body shape and clothing. While physical simulations can produce high-quality, realistic motions for clothed humans, they require precise estimation of body shape and high-quality garment assets with associated physical parameters for cloth simulations. However, manually creating these assets and calibrating their parameters is labor-intensive and requires specialized expertise. To address this gap, we propose DiffAvatar, a novel approach that performs body and garment co-optimization using differentiable simulation. By integrating physical simulation into the optimization loop and accounting for the complex nonlinear behavior of cloth and its intricate interaction with the body, our framework recovers body and garment geometry and extracts important material parameters in a physically plausible way. Our experiments demonstrate that our approach generates realistic clothing and body shape that can be easily used in downstream applications.

**Citation**
> @inproceedings{li2023diffavatar,
  title={{DiffAvatar}: Simulation-Ready Garment Optimization with Differentiable Simulation}, 
  author={Li, Yifei  and Chen, Hsiao-yu and Larionov, Egor and Sarafianos, Nikolaos and Matusik, Wojciech and Stuyck, Tuur},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  month = {June},
  eprint={2311.12194},
  year = {2024}
}