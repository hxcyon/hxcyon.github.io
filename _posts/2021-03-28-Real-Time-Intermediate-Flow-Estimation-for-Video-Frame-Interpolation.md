# RIFE: Real-Time Intermediate Flow Estimation for Video Frame Interpolation [paper](https://arxiv.org/abs/2011.06294)

## Prerequisites to understand RIFE
* [Guide Video Frame Interpolation](https://hxcyon.github.io/Guide-to-Video-Frame-Interpolation-Research/) Here we cover traditional VFI methods and research to understand important concepts like optical flow. Along with Flow-based methods, Flow-free methods have also shown to achieve remarkable progress in recent years. 
* [Super-SloMo](https://hxcyon.github.io/Super-SloMo-High-Quality-Estimation-of-Multiple-Intermediate-Frames-For-Video-Interpolation/) is the first successful Flow-based VFI algorithm. 

### Traditional Video Frame interpolation (VFI) methods 
VFI is challenging due to the complex, large non-linear motions and illumination changes in the real world. Flow based VFI algorithms have recently offered a framework to address these challenges and have achieved impressive results.

Common approaches for these Flow-based methods involve two steps: 
1. warping the input frames according to approximated optical flows
2. fusing and refining the warped frames using a bunch of Convolutional Neural Networks. 

According to the way of warping frames, flow-based VFI algorithms can be classified into forward warping based methods and backward warping based methods. 

---

