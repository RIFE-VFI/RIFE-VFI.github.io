---
youtubeId: 4we9UWsQtxQ
layout: default
---

**Abstract:** We propose RIFE, a Real-time Intermediate Flow Estimation algorithm, with applications to Video Frame Interpolation (VFI). Most existing flow estimation methods first estimate the bi-directional optical flows, and then linearly combine them to approximate intermediate flows, leading to artifacts on motion boundaries. We design a neural network named IFNet, that can directly estimate the intermediate flows from images. When interpolating videos, we can warp the frames according to the estimated intermediate flows and employ a fusion process to compute final results. Based on our proposed leakage distillation loss, RIFE can be trained in an end-to-end fashion. Experiments demonstrate that our method is significantly faster than existing VFI methods and can achieve state-of-the-art performance on public benchmarks. 

### Image demos
16x interpolation results using only two images

![Demo](./demo/I0_slomo_clipped.gif)
![Demo](./demo/I2_slomo_clipped.gif)


### Video demos
We are consistenly working on improving the models generalization to videos with various appearance.

24 FPS -> 96 FPS
{% include youtubePlayer.html id=page.youtubeId %}

### How to cite

```
@article{huang2020rife,
  title={RIFE: Real-Time Intermediate Flow Estimation for Video Frame Interpolation},
  author={Huang, Zhewei and Zhang, Tianyuan and Heng, Wen and Shi, Boxin and Zhou, Shuchang},
  journal={arXiv preprint arXiv:2011.06294},
  year={2020}
}
```

### Want to generate your own videos?
**\[colab\]**: Try our [colab notebook](https://colab.research.google.com/github/hzwer/arXiv2020-RIFE/blob/main/Colab_demo.ipynb), upload your own videos or images, and run! Or your can visit our [github repo](https://github.com/hzwer/arXiv2020-RIFE)

**\[Apps\]**: There is a new **windows app** which intergrated our algorithm, you can download it for free: [FlowFrames](https://nmkd.itch.io/flowframes)

If you have any interesting samples you'd like to share, please email Tianyuan Zhang @ *tianyuanzhang@pku.edu.cn*
### Contact
You can reach us at: Zhewei Huang @ *huangzhewei@megvii.com*,  Tianyuan zhang @ *tianyuanzhang@pku.edu.cn*
