# GhostNet及其相关网络的实验
including GhostNet, TNT (Transformer in Transformer), AugViT, WaveMLP and ViG developed by Huawei Noah's Ark Lab.
- [GhostNet Code](#ghostnet-code)


**News**

2022/12/01 The code of NeurIPS 2022 (Spotlight) [GhostNetV2](https://arxiv.org/abs/2211.12905) is released at [./ghostnetv2_pytorch](https://github.com/huawei-noah/Efficient-AI-Backbones/tree/master/ghostnetv2_pytorch).

2022/11/13 The code of IJCV 2022 [G-Ghost RegNet](https://arxiv.org/abs/2201.03297) is released at [./vig_pytorch](https://github.com/huawei-noah/Efficient-AI-Backbones/tree/master/g_ghost_pytorch). 

2022/06/17 The code of NeurIPS 2022 [Vision GNN (ViG)](https://arxiv.org/abs/2206.00272) is released at [./vig_pytorch](https://github.com/huawei-noah/Efficient-AI-Backbones/tree/master/vig_pytorch). 

2022/02/06 Transformer in Transformer (TNT) is selected as the **[Most Influential NeurIPS 2021 Papers](https://www.paperdigest.org/2022/02/most-influential-nips-papers-2022-02/)**.

2021/09/28 The paper of TNT (Transformer in Transformer) is accepted by [NeurIPS 2021](https://arxiv.org/abs/2103.00112).

2021/09/18 The extended version of [Versatile Filters](https://github.com/huawei-noah/Efficient-AI-Backbones/tree/master/versatile_filters) is accepted by T-PAMI.

2021/08/30 GhostNet paper is selected as the **[Most Influential CVPR 2020 Papers](https://www.paperdigest.org/2021/08/most-influential-cvpr-papers-2021-08/)**.

2020/10/31 GhostNet+TinyNet achieves better performance. See details in our NeurIPS 2020 paper: [arXiv](https://arxiv.org/abs/2010.14819).

---

## GhostNet Code

This repo provides GhostNet **pretrained models** and **inference code** for TensorFlow and PyTorch:
- Tensorflow: [./ghostnet_tensorflow](https://github.com/huawei-noah/CV-backbones/tree/master/ghostnet_tensorflow) with pretrained model.
- PyTorch: [./ghostnet_pytorch](https://github.com/huawei-noah/CV-backbones/tree/master/ghostnet_pytorch) with pretrained model.
- We also opensource code on [MindSpore Hub](https://www.mindspore.cn/resources/hub) and [MindSpore Model Zoo](https://gitee.com/mindspore/models/tree/master/research/cv).

For **training**, please refer to [tinynet](https://gitee.com/mindspore/models/tree/master/research/cv/tinynet) or [timm](https://rwightman.github.io/pytorch-image-models/training_hparam_examples/#mobilenetv3-large-100-75766-top-1-92542-top-5).


## GhostNetV2 Code

This repo provides the implementation of paper [GhostNetV2: Enhance Cheap Operation with Long-Range Attention (NeurIPS 2022 Spotlight)](https://arxiv.org/abs/2211.12905)
- PyTorch: [./ghostnetv2_pytorch](https://github.com/huawei-noah/Efficient-AI-Backbones/tree/master/ghostnetv2_pytorch).
- We also release the code on [MindSpore Model Zoo](https://gitee.com/mindspore/models/tree/master/research/cv/ghostnetv2).
