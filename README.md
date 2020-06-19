[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg)
## Dance Revolution: Long Sequence Dance Generation with Music via Curriculum Learning
The code and data are going through the internal review and will be released later!

### Introduction
This repo is the PyTorch implementation of "Dance Revolution: Long Sequence Dance Generation with Music via Curriculum Learning". Our proposed approach significantly outperforms the existing methods in extensive experiments. It can generate long dance sequences, e.g. about <strong>1-minute length under 15 FPS</strong>, from the input music clips, which are smooth, natural-looking, diverse, style-consistent and beat-matching with the music.

### Paper 
Ruozi Huang*, [Huang Hu*](https://www.linkedin.com/in/tonyhu1993/), [Wei Wu](https://sites.google.com/view/wei-wu-homepage), [Kei Sawada](http://www.sp.nitech.ac.jp/~swdkei/index.html), [Mi Zhang](http://homepage.fudan.edu.cn/zhangmi/en) <br/>
Dance Revolution: Long Sequence Dance Generation with Music via Curriculum Learning <br/>
[[arXiv]](https://arxiv.org/pdf/2006.06119.pdf) [[YouTube]](https://www.youtube.com/watch?v=P6yhfv3vpDI) [Project]

### Generated Example Videos
- Ballet style
<p align='center'>
  <img src='imgs/ballet-1.gif' width='400'/>
  <img src='imgs/ballet-2.gif' width='400'/>
</p>

- Hiphop style
<p align='center'>
  <img src='imgs/hiphop-1.gif' width='400'/>
  <img src='imgs/hiphop-2.gif' width='400'/>
</p>

- Japanese Pop style
<p align='center'>
  <img src='imgs/pop-1.gif' width='400'/>
  <img src='imgs/pop-2.gif' width='400'/>
</p>

- Photo-Realisitc Videos by [vid2vid](https://github.com/NVIDIA/vid2vid)
<p align='center'>
  <img src='imgs/kazuna-crop-1.gif' width='400'/>
  <img src='imgs/skeleton-1.gif' width='400'/>
  <img src='imgs/kazuna-crop-2.gif' width='400'/>
  <img src='imgs/skeleton-2.gif' width='400'/>
</p>

- Driving 3D model by applying [3D human pose estimation](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ci_Optimizing_Network_Structure_for_3D_Human_Pose_Estimation_ICCV_2019_paper.pdf)  and Unity animation to generated skeleton dances.

### Requirements

### Citation
If you find this work useful for your research, please cite the following paper, thanks :-)
```
@article{huang2020dance,
  title={Dance Revolution: Long Sequence Dance Generation with Music via Curriculum Learning},
  author={Huang, Ruozi and Hu, Huang and Wu, Wei and Sawada, Kei and Zhang, Mi},
  journal={arXiv preprint arXiv:2006.06119},
  year={2020}
}
```
