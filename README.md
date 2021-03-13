# Awesome-Temporal-Sentence-Grounding-in-Videos[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of grounding natural language in video and related area. :-)

## Introduce

本方向主要分为两类任务：

- **Temporal Activity Localization by Language**：给定一个query（包含对activity的描述），找到对应动作（事件）的起止时间；

  <div align="center"><img height="200px" src="https://res.cloudinary.com/dzu6x6nqi/image/upload/v1554267644/Awesome%20Language%20Moment%20Retrieval/TALL_-_2.png"></div>

- **Spatio-temporal object referring by language**： 给定一个query（包含对object/person的描述），在时空中找到连续的bounding box (也就是一个tube)。

  <div align="center"><img width="500px" src="https://res.cloudinary.com/dzu6x6nqi/image/upload/v1554267650/Awesome%20Language%20Moment%20Retrieval/SPRL_-_4.png"></div>

## Format

Markdown format:

```markdown
- [Paper Name](link) - Author 1 et al, `Conference Year`. [[code]](link)
```

## Change Log

* 2019/12/16: Add CBP (AAAI 2020)

## Table of Contents

- [Papers](#papers)
  - [Survey](#survey)
  - [Before](#before) - [2017](#2017) - [2018](#2018) - [2019](#2019) - [2020](#2020)
- [Dataset](#dataset)
- [Benchmark Results](#benchmark-results)
- [Popular Implementations](#popular-implementations)
  - [PyTorch](#pytorch)
  - [TensorFlow](#tensorflow)
  - [Other](#other)

## Papers

### Survey

- None.

### Before

- [Grounded Language Learning from Video Described with Sentences](https://www.aclweb.org/anthology/P13-1006/) - H. Yu et al, `ACL 2013`. 
- [Visual Semantic Search: Retrieving Videos via Complex Textual Queries](<https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Lin_Visual_Semantic_Search_2014_CVPR_paper.pdf>) - Dahua Lin et al, `CVPR 2014`.
- [Jointly Modeling Deep Video and Compositional Text to Bridge Vision and Language in a Unified Framework](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9734) - R. Xu et al, `AAAI 2015`.
- [Unsupervised Alignment of Actions in Video with Text Descriptions](https://pdfs.semanticscholar.org/5893/7d427ff36e1470b18120245148355047e4ea.pdf) - Y. C. Song et al, `IJCAI 2016`.

### 2017

- [Localizing Moments in Video with Natural Language](https://arxiv.org/abs/1708.01641) - Lisa Anne Hendricks et al, `ICCV 2017`. [[code]](<https://people.eecs.berkeley.edu/~lisa_anne/didemo.html>)

- [TALL: Temporal Activity Localization via Language Query](https://arxiv.org/abs/1705.02101) - Jiyang Gao et al, `ICCV 2017`. [[code]](<https://github.com/jiyanggao/TALL>). 

- [Spatio-temporal Person Retrieval via Natural Language Queries](https://arxiv.org/abs/1704.07945) - M. Yamaguchi et al, `ICCV 2017`.  [[code]](<https://www.mi.t.u-tokyo.ac.jp/>)

* [Attention-based Natural Language Person Retrieval](<https://arxiv.org/abs/1705.08923>) - Tao Zhou et al, `CVPR 2017`.
* [Where to Play: Retrieval of Video Segments using Natural-Language Queries](<https://arxiv.org/abs/1707.00251>) - S. Lee et al, `arxiv 2017`.

### 2018

- [Find and Focus: Retrieve and Localize Video Events with Natural Language Queries](<http://openaccess.thecvf.com/content_ECCV_2018/papers/Dian_SHAO_Find_and_Focus_ECCV_2018_paper.pdf>) - Dian Shao  et al, `ECCV 2018`.
- [Temporal Modular Networks for Retrieving Complex Compositional Activities in Videos](<http://svl.stanford.edu/assets/papers/liu2018eccv.pdf>) - B. Liu et al, `ECCV 2018`.
- [Temporally Grounding Natural Sentence in Video](<https://aclweb.org/anthology/papers/D/D18/D18-1015/>) - J. Chen et al, `EMNLP 2018`.
- [Localizing Moments in Video with Temporal Language](<https://arxiv.org/abs/1809.01337>) - Lisa Anne Hendricks et al, `EMNLP 2018`.
- [Object Referring in Videos with Language and Human Gaze](https://arxiv.org/abs/1801.01582) - A. B. Vasudevan et al, `CVPR 2018`. [[code]](<http://people.ee.ethz.ch/~arunv/ORGaze.html>). 
- [Weakly Supervised Dense Event Captioning in Videos](https://arxiv.org/abs/1812.03849) - X. Duan et al, `NIPS 2018`. 
- [Actor and Action Video Segmentation from a Sentence](<https://arxiv.org/abs/1803.07485>) - Kirill Gavrilyuk et al, `CVPR 2018`.
- [Attentive Moment Retrieval in Videos](http://staff.ustc.edu.cn/~hexn/papers/sigir18-video-retrieval.pdf) - M. Liu et al, `SIGIR 2018`.

### 2019

- [Multilevel Language and Vision Integration for Text-to-Clip Retrieval](<https://arxiv.org/abs/1804.05113>) - H. Xu et al, `AAAI 2019`. [[code]](<https://github.com/VisionLearningGroup/Text-to-Clip_Retrieval>)
- [Read, Watch, and Move: Reinforcement Learning for Temporally Grounding Natural Language Descriptions in Videos](https://arxiv.org/abs/1901.06829) - He, Dongliang et al, `AAAI 2019`.
- [To Find Where You Talk: Temporal Sentence Localization in Video with Attention Based Location Regression](http://arxiv.org/abs/1804.07014) - Y. Yuan et al, `AAAI 2019`. [[code]](https://github.com/yytzsy/ABLR_code)
- [Semantic Proposal for Activity Localization in Videos via Sentence Query](http://yugangjiang.info/publication/19AAAI-actionlocalization.pdf) - S. Chen et al, `AAAI 2019`.
- [MAN: Moment Alignment Network for Natural Language Moment Retrieval via Iterative Graph Adjustment](https://arxiv.org/abs/1812.00087) - Da Zhang et al, `CVPR 2019`. 

* [Weakly Supervised Video Moment Retrieval From Text Queries](<https://arxiv.org/abs/1904.03282>) - N. C. Mithun et al, `CVPR 2019`. 
* [Language-Driven Temporal Activity Localization_ A Semantic Matching Reinforcement Learning Model](<http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Language-Driven_Temporal_Activity_Localization_A_Semantic_Matching_Reinforcement_Learning_Model_CVPR_2019_paper.pdf>) - W. Wang et al, `CVPR 2019`. 
* [Semantic Conditioned Dynamic Modulation for Temporal Sentence Grounding in Videos](https://arxiv.org/pdf/1910.14303.pdf) - Yitian Yuan et al, `NIPS 2019`. [[code]](https://github.com/yytzsy/SCDM)
* [WSLLN: Weakly Supervised Natural Language Localization Networks](https://arxiv.org/abs/1909.00239) - M. Gao et al, `EMNLP 2019`. 
* [ExCL: Extractive Clip Localization Using Natural Language Descriptions](https://arxiv.org/abs/1904.02755) - S. Ghosh et al, `NAACL 2019`.
* [Cross-Modal Interaction Networks for Query-Based Moment Retrieval in Videos](https://arxiv.org/abs/1906.02497) - Zhu Zhang et al, `SIGIR 2019`. [[code]](https://github.com/ikuinen/CMIN_moment_retrieval)
* [Cross-Modal Video Moment Retrieval with Spatial and Language-Temporal Attention](https://dl.acm.org/citation.cfm?id=3325019) - B. Jiang et al, `ICMR 2019`. [[code]](https://github.com/BonnieHuangxin/SLTA)
* [MAC: Mining Activity Concepts for Language-based Temporal Localization](https://arxiv.org/abs/1811.08925) - Runzhou Ge Ge et al, `WACV 2019`. [[code]](https://github.com/runzhouge/MAC)
* [Temporal Localization of Moments in Video Collections with Natural Language](https://arxiv.org/abs/1907.12763v1) - V. Escorcia et al, `arxiv 2019`. 
* [Proposal-free Temporal Moment Localization of a Natural-Language Query in Video using Guided Attention](https://arxiv.org/abs/1908.07236) - C. R. Opazo et al, `arxiv 2019`.
* [Tripping through time: Efficient Localization of Activities in Videos](https://arxiv.org/abs/1904.09936) - Meera Hahn et al, `arxiv 2019`. 
* [Related] [Localizing Unseen Activities in Video via Image Query](https://arxiv.org/abs/1906.12165) - Zhu Zhang et al, `IJCAI 2019`. 
* [WSLLN:Weakly Supervised Natural Language Localization Networks](https://arxiv.org/abs/1909.00239) - Mingfei Gao et al, `EMNLP2019`.

### 2020

* [Temporally Grounding Language Queries in Videos by Contextual Boundary-aware Prediction](https://arxiv.org/abs/1909.05010) - Jingwen Wang et al, `AAAI 2020`. [[code]](https://github.com/JaywongWang/CBP)

  **Motivation**: The inaccurate temporal boundaries.

  **Methodology**: Propose a novel model that jointly predicts temporal anchors and boundaries at each time step. Boundary Submodule is implemented with a simple binary classifier with cross-entropy loss. The final score is achieved via  Boundary Score Fusion.

* [Learning 2D Temporal Localization Networks for Moment Localization with Natural Language](https://arxiv.org/abs/1912.03590) - Songyang Zhang et al, `AAAI 2020`. [[code1]](https://github.com/microsoft/2D-TAN)[[code2]](https://github.com/ChenJoya/2dtan)

* [Multi-Scale 2D Temporal Adjacent Networks for Moment Localization with Natural Language](https://arxiv.org/pdf/2012.02646.pdf) - Songyang Zhang et al, `TPAMI submission`.

* [Jointly Cross- and Self-Modal Graph Attention Network for Query-Based Moment Localization](https://dl.acm.org/doi/pdf/10.1145/3394171.3414026) - Daizong Liu et al, `ACM MM`. [[code]](https://github.com/liudaizong/CSMGAN)

* [Weakly-Supervised Video Moment Retrieval via Semantic Completion Network](https://ojs.aaai.org/index.php/AAAI/article/view/6820) - Zhijie Lin et al, `AAAI 2020`.

  **Motivation**：The latent attention weights without extra supervision usually focus on the most discriminative but small regions (Singh and Lee 2017) instead of covering complete regions. 

  **Methodology**: (a) Proposal Generation Module: Transformer-based score assignment and decay rate Top-K selection. (b) Semantic Completion Module. (Masked language tokens and the video sequences input.) (c) Reconstruction Loss and Rank Loss.

* [Look Closer to Ground Better: Weakly-Supervised Temporal Grounding of Sentence in Video](https://arxiv.org/pdf/2001.09308.pdf) - Zhenfang Chen et al, `arXiv`.

  **Motivation**: Ground in a coarse-to-fine manner.

  **Methodology**: (a) Feature Encoder by Bi-LSTM for both video and language. (b) Coarse stage: proposal generation and compute the similarity to the sentence feature with classification stream and selection stream. (c) Fine stage: frame level feature similarity compution. (d) Training with MIL (cross entropy loss and ranking loss).

* [VLANet: Video-Language Alignment Network for Weakly-Supervised Video Moment Retrieval](https://arxiv.org/pdf/2008.10238.pdf) - Minuk Ma et al, `ECCV 2020`.

* [Counterfactual Contrastive Learning for Weakly-Supervised Vision-Language Grounding](https://proceedings.neurips.cc/paper/2020/file/d27b95cac4c27feb850aaa4070cc4675-Paper.pdf) - Zhu Zhang et al, `NIPS 2020`.



## Dataset

- [ActivityNet Captions](http://cs.stanford.edu/people/ranjaykrishna/densevid/)
- [Charades-STA](<https://allenai.org/plato/charades/>)
- [DiDeMo](<https://github.com/LisaAnne/LocalizingMoments>)
- [TACoS](http://www.coli.uni-saarland.de/projects/smile/page.php?id=software)

## Dataset C3D Features
- [Overall](https://drive.google.com/drive/folders/1D3nav3TKZmYNHvSLBgDt1vpBUXoV2MRv), shared by [2D-TAN](https://github.com/microsoft/2D-TAN)
- [ActivityNet Captions](http://activity-net.org/challenges/2016/download.html)
- [TACos](https://drive.google.com/file/d/1Y53pJebaZdwenbHOpj-yIURSk_cit1OI/view?usp=sharing), shared by [ChenJoya_2dtan](https://github.com/ChenJoya/2dtan/blob/master/DATASET.md)


## Benchmark Results

#### ActivityNet Captions

|                 | R@1 IoU@0.1 | R@1 IoU@0.3 | R@1 IoU@0.5 | R@1 IoU@0.7 | R@5 IoU@0.1 | R@5 IoU@0.3 | R@5 IoU@0.5 | R@5 IoU@0.7 | Method |
| :-------------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :----: |
|       MCN       |    42.80    |    21.37    |    9.58     |      -      |      -      |      -      |      -      |      -      |   PB   |
|      CTRL       |    49.09    |    28.70    |    14.0     |      -      |      -      |      -      |      -      |      -      |   PB   |
|      ACRN       |    50.37    |    31.29    |    16.17    |      -      |      -      |      -      |      -      |      -      |   PB   |
|      QSPN       |      -      |    45.3     |    27.7     |    13.6     |      -      |    75.7     |    59.2     |    38.3     |   PB   |
|       TGN       |    70.06    |    45.51    |    28.47    |      -      |    79.10    |    57.32    |    44.20    |      -      |   PB   |
|      SCDM       |      -      |    54.80    |    36.75    |    19.86    |      -      |    77.29    |    64.99    |    41.53    |   PB   |
|       CBP       |      -      |    54.30    |    35.76    |    17.80    |      -      |    77.63    |    65.89    |    46.20    |   PB   |
|     TripNet     |      -      |    48.42    |    32.19    |    13.93    |      -      |      -      |      -      |      -      |   RL   |
|      ABLR       |    73.30    |    55.67    |    36.79    |      -      |      -      |      -      |      -      |      -      |   RL   |
|      ExCL       |      -      |    63.30    |    43.6     |    24.1     |      -      |      -      |      -      |      -      |   PF   |
|      PFGA       |    75.25    |    51.28    |    33.04    |    19.26    |      -      |      -      |      -      |      -      |   PF   |
| WSDEC-X(Weakly) |    62.7     |    42.0     |    23.3     |      -      |      -      |      -      |      -      |      -      |        |
| WSLLN (Weakly)  |    75.4     |    42.8     |    22.7     |      -      |      -      |      -      |      -      |      -      |        |




#### Charades-STA

|         | R@1 IoU@0.1 | R@1 IoU@0.3 | R@1 IoU@0.5 | R@1 IoU@0.7 | R@5 IoU@0.1 | R@5 IoU@0.3 | R@5 IoU@0.5 | R@5 IoU@0.7 | Method |
| :-----: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :----: |
|  CTRL   |      -      |      -      |    23.63    |    8.89     |      -      |      -      |    58.92    |    29.52    |   PB   |
|  ABLR   |      -      |      -      |    24.36    |    9.01     |      -      |      -      |      -      |      -      |   PB   |
|  SMRL   |      -      |      -      |    24.36    |    11.17    |      -      |      -      |    61.25    |    32.08    |   PB   |
|  ACL-K  |      -      |      -      |    30.48    |    12.20    |      -      |      -      |    64.84    |    35.13    |   PB   |
|   SAP   |      -      |      -      |    27.42    |    13.36    |      -      |      -      |    66.37    |    38.15    |   PB   |
|  QSPN   |      -      |    54.7     |    35.6     |    15.8     |      -      |    95.8     |    79.4     |    45.4     |   PB   |
|   MAN   |      -      |      -      |    46.53    |    22.72    |      -      |      -      |    86.23    |    53.72    |   PB   |
|  SCDM   |      -      |      -      |    54.44    |    33.43    |      -      |      -      |    74.43    |    58.08    |   PB   |
|   CBP   |      -      |      -      |    36.80    |    18.87    |      -      |      -      |    70.94    |    50.19    |   PB   |
| TripNet |      -      |    51.33    |    36.61    |    14.50    |      -      |      -      |      -      |      -      |   RL   |
|  ExCL   |      -      |    65.1     |    44.1     |    23.3     |      -      |      -      |      -      |      -      |   RL   |
|  PFGA   |      -      |    67.53    |    52.02    |    33.74    |      -      |      -      |      -      |      -      |   PF   |



#### DiDeMo

|                | R@1 IoU@0.1 | R@1 IoU@0.3 | R@1 IoU@0.5 | R@1 IoU@0.7 | R@5 IoU@0.1 | R@5 IoU@0.3 | R@5 IoU@0.5 | R@5 IoU@0.7 |
| :------------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
|      TMN       |    22.92    |      -      |      -      |      -      |    76.08    |      -      |      -      |      -      |
|      MCN       |    28.10    |      -      |      -      |      -      |    78.21    |      -      |      -      |      -      |
|      TGN       |    28.23    |      -      |      -      |      -      |    79.26    |      -      |      -      |      -      |
|      MAN       |    27.02    |      -      |      -      |      -      |    81.70    |      -      |      -      |      -      |
| WSLLN (Weakly) |    19.4     |      -      |      -      |      -      |    54.4     |      -      |      -      |      -      |

#### TACoS

|         | R@1 IoU@0.1 | R@1 IoU@0.3 | R@1 IoU@0.5 | R@1 IoU@0.7 | R@5 IoU@0.1 | R@5 IoU@0.3 | R@5 IoU@0.5 | R@5 IoU@0.7 | Method |
| :-----: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :---------: | :----: |
|   MCN   |    2.62     |    1.64     |    1.25     |      -      |    2.88     |    1.82     |    1.01     |      -      |   PB   |
|  CTRL   |    24.32    |    18.32    |    13.30    |      -      |    48.73    |    36.69    |    25.42    |      -      |   PB   |
|   TGN   |    41.87    |    21.77    |    18.90    |      -      |    53.40    |    39.06    |    31.02    |      -      |   PB   |
|  ACRN   |    24.22    |    19.52    |    14.62    |      -      |    47.42    |    34.97    |    24.88    |      -      |   PB   |
|  ACL-K  |    31.64    |    24.17    |    20.01    |      -      |    57.85    |    42.15    |    30.66    |      -      |   PB   |
|  SCDM   |      -      |    26.11    |    21.17    |      -      |      -      |    40.16    |    32.18    |      -      |   PB   |
|   CBP   |      -      |    27.31    |    24.79    |    19.10    |      -      |    43.64    |    37.40    |    25.59    |   PB   |
| TripNet |      -      |    23.95    |    19.17    |    9.52     |      -      |      -      |      -      |      -      |   RL   |
|  SMRL   |    26.51    |    20.25    |    15.95    |      -      |    50.01    |    38.47    |    27.84    |      -      |   RL   |
|  ABLR   |    34.7     |    19.5     |     9.4     |      -      |      -      |      -      |      -      |      -      |   RL   |
|  ExCL   |      -      |    45.5     |    28.0     |    14.6     |      -      |      -      |      -      |      -      |   PF   |

## Popular Implementations

### PyTorch

- [ikuinen/CMIN_moment_retrieval](https://github.com/ikuinen/CMIN_moment_retrieval)

### TensorFlow

- [jiyanggao/TALL](<https://github.com/jiyanggao/TALL>)
- [runzhouge/MAC](https://github.com/runzhouge/MAC)
- [BonnieHuangxin/SLTA](https://github.com/BonnieHuangxin/SLTA)
- [yytzsy/ABLR_code](https://github.com/yytzsy/ABLR_code)
- [yytzsy/SCDM](https://github.com/yytzsy/SCDM)
- [JaywongWang/TGN](https://github.com/JaywongWang/TGN)
- [JaywongWang/CBP](https://github.com/JaywongWang/CBP)

### Others

- None.

## Licenses

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [muketong](https://github.com/iworldtong) all copyright and related or neighboring rights to this work.

