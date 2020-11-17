---
youtubeId: kUQ7KK6MhHw
layout: default
---

We propose RIFE, a Real-time Intermediate Flow Estimation algorithm, with applications to Video Frame Interpolation (VFI). Most existing flow estimation methods first estimate the bi-directional optical flows, and then linearly combine them to approximate intermediate flows, leading to artifacts on motion boundaries. We design a neural network named IFNet, that can directly estimate the intermediate flows from images. When interpolating videos, we can warp the frames according to the estimated intermediate flows and employ a fusion process to compute final results. Based on our proposed leakage distillation loss, RIFE can be trained in an end-to-end fashion. Experiments demonstrate that our method is significantly faster than existing VFI methods and can achieve state-of-the-art performance on public benchmarks. 

## 16x interpolation results using only two images

![Demo](./demo/I0_slomo_clipped.gif)
![Demo](./demo/I2_slomo_clipped.gif)


## Video demos

{% include youtubePlayer.html id=page.youtubeId %}

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

