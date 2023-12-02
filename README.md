# awesome-hd-map-construction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome HD map construction methods. Inspired by [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning).

## Contributing
Please help contribute this list by creating an issue or adding pull request.
Markdown format:
```markdown
- *[Model Name]* Paper Name. 
  [[pdf]](link) 
  [[code]](link)
  - Author 1, Author 2, and Author 3. *Conference Year*
```

## Table of Contents  
- [Survey](#survey)
- [Online HD map construction](#online-hd-map-construction)
- [HD map construction with human efforts](#hd-map-construction-with-human-efforts)
- [Lane detection](#lane-detection)  
- [Misc](#misc)
- [News](#news)
- [Talks](#talks)
- [Blog](#blog)

## Survey
-   High-definition map generation technologies for autonomous driving: a review.
    [[pdf]](https://arxiv.org/ftp/arxiv/papers/2206/2206.05400.pdf)
    -   Bao, Zhibin, Sabir Hossain, Haoxiang Lang, and Xianke Lin. *arXiv 2022*
 
-   High-definition maps: Comprehensive survey, challenges and future perspectives.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10184094)
    -   Elghazaly, Gamal, Raphaël Frank, Scott Harvey, and Stefan Safko. *IEEE Open Journal of Intelligent Transportation Systems 2023*

## Online HD map construction
-   [HDMapNet] Hdmapnet: An online hd map construction and evaluation framework.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/9812383)
    [[code]](https://github.com/Tsinghua-MARS-Lab/HDMapNet)
    -   Li, Qi, Yue Wang, Yilun Wang, and Hang Zhao. *ICRA 2022*

-   [VectorMapNet] VectorMapNet: End-to-end Vectorized HD Map Learning.
    [[pdf]](https://proceedings.mlr.press/v202/liu23ax/liu23ax.pdf)
    [[code]](https://github.com/Mrmoore98/VectorMapNet_code)
    -   Liu, Yicheng and Yuan, Tianyuan and Wang, Yue and Wang, Yilun and Zhao, Hang. *ICML 2023*

-   [MapTR] MapTR: Structured Modeling and Learning for Online Vectorized HD Map Construction.
    [[pdf]](https://openreview.net/pdf?id=k7p_YAO7yE)
    [[code]](https://github.com/hustvl/MapTR)
    -   Liao, Bencheng and Chen, Shaoyu and Wang, Xinggang and Cheng, Tianheng, and Zhang, Qian and Liu, Wenyu and Huang, Chang. *ICLR 2023*

-   [SuperFusion] SuperFusion: Multilevel LiDAR-Camera Fusion for Long-Range HD Map Generation.
    [[pdf]](https://arxiv.org/pdf/2211.15656.pdf)
    [[code]](https://github.com/haomo-ai/SuperFusion)
    -   Hao Dong and Xianjing Zhang and Jintao Xu and Rui Ai and Weihao Gu and Huimin Lu and Juho Kannala and Xieyuanli Chen. *arXiv 2022*

-   [InstaGraM] InstaGraM: Instance-level Graph Modeling for Vectorized HD Map Learning.
    [[pdf]](https://arxiv.org/pdf/2301.04470.pdf)
    -   Shin, Juyeb, Francois Rameau, Hyeonjun Jeong, and Dongsuk Kum. *arXiv 2023*

-   [NMP] Neural Map Prior for Autonomous Driving.
    [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Xiong_Neural_Map_Prior_for_Autonomous_Driving_CVPR_2023_paper.pdf)
    -   Xiong, Xuan and Liu, Yicheng and Yuan, Tianyuan and Wang, Yue and Wang, Yilun and Zhao, Hang. *CVPR 2023*

## HD map construction with human efforts
-   [THMA] THMA: tencent HD Map AI system for creating HD map annotations.
    [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/26848)
    -   Tang, K., Cao, X., Cao, Z., Zhou, T., Li, E., Liu, A., Zou, S., Liu, C., Mei, S., Sizikova, E., & Zheng, C. *AAAI 2023*

-   [VMA] VMA: Divide-and-Conquer Vectorized Map Annotation System for Large-Scale Driving Scene.
    [[pdf]](https://arxiv.org/pdf/2304.09807.pdf)
    [[code]](https://github.com/hustvl/VMA)
    -   Chen, Shaoyu, Yunchi Zhang, Bencheng Liao, Jiafeng Xie, Tianheng Cheng, Wei Sui, Qian Zhang, Chang Huang, Wenyu Liu, and Xinggang Wang. *arXiv 2023*

## Lane detection
-   [3D-LaneNet] 3D-LaneNet: End-to-End 3D Multiple Lane Detection.
    [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Garnett_3D-LaneNet_End-to-End_3D_Multiple_Lane_Detection_ICCV_2019_paper.pdf)
    -   Garnett, Noa and Cohen, Rafi and Pe'er, Tomer and Lahav, Roee and Levi, Dan. *ICCV 2019*

-   [Gen-LaneNet] Gen-lanenet: A generalized and scalable approach for 3d lane detection.
    [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660664.pdf)
    [[code]](https://github.com/yuliangguo/Pytorch_Generalized_3D_Lane_Detection)
    -   Yuliang Guo, Guang Chen, Peitao Zhao, Weide Zhang, Jinghao Miao, Jingao Wang, and Tae Eun Choe. *ECCV 2020*

-   [STSU] Structured Bird's-Eye-View Traffic Scene Understanding From Onboard Images.
    [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Can_Structured_Birds-Eye-View_Traffic_Scene_Understanding_From_Onboard_Images_ICCV_2021_paper.pdf)
    [[code]](https://github.com/ybarancan/STSU)
    -   Can, Yigit Baran and Liniger, Alexander and Paudel, Danda Pani and Van Gool, Luc. *ICCV 2021*

## Misc
-   [V2HDM-Mono] V2HDM-Mono: A Framework of Building a Marking-Level HD Map with One or More Monocular Cameras.
    [[pdf]](https://arxiv.org/pdf/2209.07737.pdf)
    -   Liu, Hongji, Linwei Zheng, Xiaoyang Yan, Zhenhua Xu, Bohuan Xue, Yang Yu, and Ming Liu. *arXiv 2022*

## News

## Talks

## Blog

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Honminden (Anqi Shi)](https://honminden.github.io/) has waived all copyright and related or neighboring rights to this work.
