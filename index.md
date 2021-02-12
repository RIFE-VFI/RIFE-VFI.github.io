---
youtubeId: 3VWOblILqP4
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

### User Genereated demos

**2d Animation**
[御坂大哥想让我表白 - 魔女之旅](https://www.bilibili.com/video/BV1sr4y1P7Wg) | [ablyh - 超电磁炮](https://www.bilibili.com/video/BV1gK4y1Q7d9?from=search&seid=16584204362417247463) | [赫萝与罗伦斯的旅途 - 绫波丽](https://www.bilibili.com/video/BV1yz4y1m7iF) |  [没有鼠鼠的雏子Official - 千恋万花](https://www.bilibili.com/video/BV1AT4y1P7kY?from=search&seid=15458655842150253738) |

**3d Animation**
[没有鼠鼠的雏子Official - 原神魈](https://www.bilibili.com/video/BV1iU4y1s7Lk) | [今天我练出腹肌了吗 - 最终幻想14](https://www.bilibili.com/video/BV1R541177qr) | [娜不列颠 - 冰雪奇缘2](https://www.bilibili.com/video/BV1fy4y1J7Mu) |  [今天我练出腹肌了吗 - 仙剑奇侠传6](https://www.bilibili.com/video/BV1ut4y167az?from=search&seid=15458655842150253738) | 

**MV**
[Navetek - 邓丽君](https://www.bilibili.com/video/BV1ZK411u7CM) | [生米阿怪 - 周深](https://www.bilibili.com/video/BV1Wo4y1d73b?from=search&seid=16584204362417247463) |

**Film**
[Life in a Day 2020](https://www.youtube.com/watch?v=vcsSc2iksC0) |


### Want to generate your own videos?
**\[colab\]**: Try our [colab notebook](https://colab.research.google.com/github/hzwer/arXiv2020-RIFE/blob/main/Colab_demo.ipynb), upload your own videos or images, and run! Or your can visit our [github repo](https://github.com/hzwer/arXiv2020-RIFE)

**\[Apps\]**: You can refer to [Waifu2x-Extension-GUI](https://github.com/AaronFeng753/Waifu2x-Extension-GUI), [Flowframes](https://nmkd.itch.io/flowframes) and [RIFE-ncnn-vulkan](https://github.com/nihui/rife-ncnn-vulkan). A Chinese version: [Squirrel-RIFE](https://github.com/YiWeiHuang-stack/Squirrel-Video-Frame-Interpolation)


### Contact
You can reach us at: Zhewei Huang @ *huangzhewei@megvii.com*,  Tianyuan zhang @ *tianyuanzhang@pku.edu.cn*

### How to cite

```
@article{huang2020rife,
  title={RIFE: Real-Time Intermediate Flow Estimation for Video Frame Interpolation},
  author={Huang, Zhewei and Zhang, Tianyuan and Heng, Wen and Shi, Boxin and Zhou, Shuchang},
  journal={arXiv preprint arXiv:2011.06294},
  year={2020}
}
```

