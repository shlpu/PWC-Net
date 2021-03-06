[![License CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC4.0-blue.svg)](https://raw.githubusercontent.com/NVIDIA/FastPhotoStyle/master/LICENSE.md)
![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)

## PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume

### License
Copyright (C) 2018 NVIDIA Corporation. All rights reserved. Licensed under the CC BY-NC-SA 4.0 license (https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).


### Usage

For Caffe users, please refer to [Caffe/README.md](Caffe/README.md).

For PyTorch users, please refer to [PyTorch/README.md](PyTorch/README.md)

The PyTorch implementation almost matches the Caffe implementation (average EPE on the final pass of the Sintel training set: 2.31 by Pytorch and 2.29 by Caffe). 

### Network Architecture

PWC-Net fuses several classic optical flow estimation techniques, including image pyramid, warping, and cost volume, in an end-to-end trainable deep neural networks for achieving state-of-the-art results.

![](network.png)


### Paper & Citation
[Deqing Sun, Xiaodong Yang, Ming-Yu Liu, and Jan Kautz. "PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume." CVPR 2018 or arXiv:1709.02371](https://arxiv.org/abs/1709.02371)


[Project page link](http://research.nvidia.com/publication/2018-02_PWC-Net:-CNNs-for)

[Talk at robust vision challenge workshop](https://www.youtube.com/watch?v=vVU8XV0Ac_0)

[Talk at CVPR 2018 conference (starts ~7:00)](https://www.youtube.com/watch?v=LBJ20kxr1a0)
 

If you use PWC-Net, please cite the following paper: 
```
@InProceedings{Sun2018PWC-Net,
  author    = {Deqing Sun and Xiaodong Yang and Ming-Yu Liu and Jan Kautz},
  title     = {{PWC-Net}: {CNNs} for Optical Flow Using Pyramid, Warping, and Cost Volume},
  booktitle = CVPR,
  year      = {2018},
}
```
or the arXiv paper
```
@article{sun2017pwc,
  author={Sun, Deqing and Yang, Xiaodong and Liu, Ming-Yu and Kautz, Jan},
  title={{PWC-Net}: {CNNs} for Optical Flow Using Pyramid, Warping, and Cost Volume},
  journal={arXiv preprint arXiv:1709.02371},
  year={2017}
}
```
### Related Work from NVIDIA 
[flownet2-pytorch](https://github.com/NVIDIA/flownet2-pytorch)

### Contact
Deqing Sun (deqings@nvidia.com)

