# awesome-hd-map-construction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome HD map construction methods. Inspired by [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning).

## Contributing
Please help contribute this list by creating an issue or adding pull request.
Markdown format:
```markdown
- [Model Name] Paper Name. 
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
    -   Bao, Zhibin and Hossain, Sabir and Lang, Haoxiang and Lin, Xianke. *arXiv 2022*
 
-   High-definition maps: Comprehensive survey, challenges and future perspectives.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10184094)
    -   Elghazaly, Gamal and Frank, Raphaël and Harvey, Scott and Safko, Stefan. *IEEE Open Journal of Intelligent Transportation Systems 2023*
 
-   High-Definition Maps Construction Based on Visual Sensor: A Comprehensive Survey
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10336514)
    -   Tang, Xuewei and Jiang, Kun and Yang, Mengmeng and Liu, Zhaoyang and Jia, Peijin and Wijaya, Benny and Wen, Tuopu and Cui, Le and Yang, Diange. *IEEE Transactions on Intelligent Vehicles 2023*

## Online HD map construction
### 2021
-   [HDMapNet] Hdmapnet: An online hd map construction and evaluation framework.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/9812383)
    [[code]](https://github.com/Tsinghua-MARS-Lab/HDMapNet)
    -   Li, Qi and Wang, Yue and Wang, Yilun and Zhao, Hang. *ICRA 2022*

### 2022
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
    -   Dong, Hao and Zhang, Xianjing and Xu, Jintao and Ai, Rui and Gu, Weihao and Lu, Huimin and Kannala, Juho and Chen, Xieyuanli. *arXiv 2022*

### 2023
-   [InstaGraM] InstaGraM: Instance-level Graph Modeling for Vectorized HD Map Learning.
    [[pdf]](https://arxiv.org/pdf/2301.04470.pdf)
    -   Shin, Juyeb and Rameau, Francois and Jeong, Hyeonjun and Kum, Dongsuk. *arXiv 2023*

-   [NMP] Neural Map Prior for Autonomous Driving.
    [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Xiong_Neural_Map_Prior_for_Autonomous_Driving_CVPR_2023_paper.pdf)
    -   Xiong, Xuan and Liu, Yicheng and Yuan, Tianyuan and Wang, Yue and Wang, Yilun and Zhao, Hang. *CVPR 2023*

-   [MV-Map] MV-Map: Offboard HD-Map Generation with Multi-view Consistency.
    [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Xie_MV-Map_Offboard_HD-Map_Generation_with_Multi-view_Consistency_ICCV_2023_paper.pdf)
    [[code]](https://github.com/ZiYang-xie/MV-Map)
    -   Xie, Ziyang and Pang, Ziqi and Wang, Yu-Xiong. *ICCV 2023*

-   [MapSeg] MapSeg: Segmentation guided structured model for online HD map construction.
    [[pdf]](https://arxiv.org/pdf/2311.02503.pdf)
    -   Jiang, Mingchao and Cheng, Yin and Liu, Linghai. *arXiv 2023*

-   [BeMapNet] End-to-End Vectorized HD-Map Construction With Piecewise Bezier Curve.
    [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Qiao_End-to-End_Vectorized_HD-Map_Construction_With_Piecewise_Bezier_Curve_CVPR_2023_paper.pdf)
    [[code]](https://github.com/er-muyue/BeMapNet)
    -   Qiao, Limeng and Ding, Wenjie and Qiu, Xi and Zhang, Chi. *CVPR 2023*

-   [PolyDiffuse] PolyDiffuse: Polygonal Shape Reconstruction via Guided Set Diffusion Models.
    [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/05f0e2fa003602db2d98ca72b79dec51-Paper-Conference.pdf)
    [[code]](https://github.com/woodfrog/poly-diffuse)
    -   Chen, Jiacheng and Deng, Ruizhi and Furukawa, Yasutaka. *NeurIPS 2023*

-   [NeMO] NeMO: Neural Map Growing System for Spatiotemporal Fusion in Bird's-Eye-View and BDD-Map Benchmark.
    [[pdf]](https://arxiv.org/pdf/2306.04540)
    -   Zhu, Xi and Cao, Xiya and Dong, Zhiwei and Zhou, Caifa and Liu, Qiangbo and Li, Wei and Wang, Yongliang. *arXiv 2023*

-   [MachMap] MachMap: End-to-End Vectorized Solution for Compact HD-Map Construction.
    [[pdf]](https://arxiv.org/pdf/2306.10301.pdf)
    -   Qiao, Limeng and Zheng, Yongchao and Zhang, Peng and Ding, Wenjie and Qiu, Xi and Wei, Xing and Zhang, Chi. *arXiv 2023*

-   [MapVR] Online Map Vectorization for Autonomous Driving: A Rasterization Perspective.
    [[pdf]](https://arxiv.org/pdf/2306.10502.pdf)
    [[code]](https://github.com/ZhangGongjie/MapVR)
    -   Zhang, Gongjie and Lin, Jiahao and Wu, Shuang and Song, Yilin and Luo, Zhipeng and Xue, Yang and Lu, Shijian and Wang, Zuoguan. *NeurIPS 2023*

-   [MapTRv2] MapTRv2: An End-to-End Framework for Online Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2308.05736.pdf)
    [[code]](https://github.com/hustvl/MapTR)
    -   Liao, Bencheng and Chen, Shaoyu and Zhang, Yunchi and Jiang, Bo and Zhang, Qian and Liu, Wenyu and Huang, Chang and Wang, Xinggang. *arXiv 2023*

-   [InsightMapper] InsightMapper: A Closer Look at Inner-instance Information for Vectorized High-Definition Mapping.
    [[pdf]](https://arxiv.org/pdf/2308.08543.pdf)
    -   Xu, Zhenhua and Wong, Kenneth KY and Zhao, Hengshuang. *arXiv 2023*

-   [StreamMapNet] Streammapnet: Streaming mapping network for vectorized online hd map construction.
    [[pdf]](https://arxiv.org/pdf/2308.12570.pdf)
    [[code]](https://github.com/yuantianyuan01/StreamMapNet)
    -   Yuan, Tianyuan and Liu, Yicheng and Wang, Yue and Wang, Yilun and Zhao, Hang. *WACV 2024*

-   [SatforHDMap] Complementing Onboard Sensors with Satellite Map: A New Perspective for HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2308.15427.pdf)
    [[code]](https://github.com/xjtu-cs-gao/SatforHDMap)
    -   Gao, Wenjie and Fu, Jiawei and Jing, Haodong and Zheng, Nanning. *arXiv 2023*

-   [PivotNet] PivotNet: Vectorized Pivot Learning for End-to-end HD Map Construction.
    [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ding_PivotNet_Vectorized_Pivot_Learning_for_End-to-end_HD_Map_Construction_ICCV_2023_paper.pdf)
    -   Ding, Wenjie and Qiao, Limeng and Qiu, Xi and Zhang, Chi. *ICCV 2023*

-   [ScalableMap] ScalableMap: Scalable Map Learning for Online Long-Range Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2310.13378.pdf)
    [[code]](https://github.com/jingy1yu/ScalableMap)
    -   Yu, Jingyi and Zhang, Zizhao and Xia, Shengfu and Sang, Jizhang. *CoRL 2023*

-   [MapEX] Mind the map! Accounting for existing map information when estimating online HDMaps from sensor data.
    [[pdf]](https://arxiv.org/pdf/2311.10517.pdf)
    -   Sun, Rémy and Yang, Li and Lingrand, Diane and Precioso, Frédéric. *arXiv 2023*

-   [GeMap] Online Vectorized HD Map Construction using Geometry.
    [[pdf]](https://arxiv.org/pdf/2312.03341.pdf)
    [[code]](https://github.com/cnzzx/GeMap)
    -   Zhixin Zhang and Yiyuan Zhang and Xiaohan Ding and Fusheng Jin and Xiangyu Yue. *arXiv 2023*

### 2024
-   [MapNeXt] MapNeXt: Revisiting Training and Scaling Practices for Online Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2401.07323.pdf)
    -   Li, Toyota. *arXiv 2024*
  
-   [SQD-MapNet] Stream Query Denoising for Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2401.09112.pdf)
    -   Wang, Shuo and Jia, Fan and Liu, Yingfei and Zhao, Yucheng and Chen, Zehui and Wang, Tiancai and Zhang, Chi and Zhang, Xiangyu and Zhao, Feng. *arXiv 2024*

-   [ADMap] ADMap: Anti-disturbance framework for reconstructing online vectorized HD map.
    [[pdf]](https://arxiv.org/pdf/2401.13172.pdf)
    [[code]](https://github.com/hht1996ok/ADMap)
    -   Hu, Haotian and Wang, Fanyi and Wang, Yaonong and Hu, Laifeng and Xu, Jingwei and Zhang, Zhiwang. *arXiv 2024*

-   [MapQR] Leveraging Enhanced Queries of Point Sets for Vectorized Map Construction.
    [[pdf]](https://arxiv.org/pdf/2402.17430.pdf)
    -   Liu, Zihao and Zhang, Xiaoyu and Liu, Guangwei and Zhao, Ji and Xu, Ningyi. *arXiv 2024*

-   [EAN-MapNet] EAN-MapNet: Efficient Vectorized HD Map Construction with Anchor Neighborhoods.
    [[pdf]](https://arxiv.org/pdf/2402.18278.pdf)
    -   Xiong, Huiyuan and Shen, Jun and Zhu, Taohong and Pan, Yuelong. *arXiv 2024*

-   [HIMap] HIMap: HybrId Representation Learning for End-to-end Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2403.08639.pdf)
    -   Zhou, Yi and Zhang, Hui and Yu, Jiaqian and Yang, Yifan and Jung, Sangil and Park, Seung-In and Yoo, ByungIn. *CVPR 2024*

-   [PreSight] PreSight: Enhancing Autonomous Vehicle Perception with City-Scale NeRF Priors.
    [[pdf]](https://arxiv.org/pdf/2403.09079.pdf)
    -   Yuan, Tianyuan and Mao, Yucheng and Yang, Jiawei and Liu, Yicheng and Wang, Yue and Zhao, Hang. *arXiv 2024*

-   [P-MapNet] P-MapNet: Far-seeing Map Generator Enhanced by both SDMap and HDMap Priors.
    [[pdf]](https://arxiv.org/pdf/2403.10521.pdf)
    [[code]](https://github.com/jike5/P-MapNet)
    -   Jiang, Zhou and Zhu, Zhenxin and Li, Pengfei and Gao, Huan-ang and Yuan, Tianyuan and Shi, Yongliang and Zhao, Hang and Zhao, Hao. *arXiv 2024*

-   [Buffered Gaussian Modeling] Buffered Gaussian Modeling for Vectorized HD Map Construction.
    [[pdf]](https://ieeexplore.ieee.org/document/10445925)
    -   Shi, Anqi and Chen, Huaqiu and Lu, Hong and Zhang, Rui. *ICASSP 2024*

-   [MapTracker] MapTracker: Tracking with Strided Memory Fusion for Consistent Vector HD Mapping.
    [[pdf]](https://arxiv.org/pdf/2403.15951.pdf)
    [[code]](https://github.com/woodfrog/maptracker)
    -   Chen, Jiacheng and Wu, Yuefan and Tan, Jiaqi and Ma, Hang and Furukawa, Yasutaka. *arXiv 2024*

-   [MGMap] MGMap: Mask-Guided Learning for Online Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2404.00876.pdf)
    -   Liu, Xiaolu and Wang, Song and Li, Wentong and Yang, Ruizi and Chen, Junbo and Zhu, Jianke. *arXiv 2024*

-   [SparseAD] SparseAD: Sparse Query-Centric Paradigm for Efficient End-to-End Autonomous Driving.
    [[pdf]](https://arxiv.org/pdf/2404.06892.pdf)
    -   Zhang, Diankun and Wang, Guoan and Zhu, Runwen and Zhao, Jianbo and Chen, Xiwu and Zhang, Siyu and Gong, Jiahao and Zhou, Qibin and Zhang, Wenyuan and Wang, Ningzi and others. *arXiv 2024*

-   [HybriMap] HybriMap: Hybrid Clues Utilization for Effective Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2404.11155.pdf)
    -   Zhang, Chi and Song, Qi and Li, Feifei and Chen, Yongquan and Huang, Rui. *arXiv 2024*

-   [GNMap] Neural HD Map Generation from Multiple Vectorized Tiles Locally Produced by Autonomous Vehicles.
    [[pdf]](https://link.springer.com/chapter/10.1007/978-981-97-2966-1_22)
    -   Fan, Miao and Yao, Yi and Zhang, Jianping and Song, Xiangbo and Wu, Daihui. *SpatialDI 2024*

-   [DTCLMapper] DTCLMapper: Dual Temporal Consistent Learning for Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2405.05518)
    -   Li, Siyu and Lin, Jiacheng and Shi, Hao and Zhang, Jiaming and Wang, Song and Yao, You and Li, Zhiyong and Yang, Kailun. *arXiv 2024*

-   [POP-Net] Camera-based Online Vectorized HD Map Construction with Incomplete Observation.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10542214)
    -   Liu, Hui and Chang, Faliang and Liu, Chunsheng and Lu, Yansha and Liu, Minhang. * IEEE Robotics and Automation Letters 2024*

## HD map construction with human efforts
-   [THMA] THMA: tencent HD Map AI system for creating HD map annotations.
    [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/26848)
    -  Tang, Kun and Cao, Xu and Cao, Zhipeng and Zhou, Tong and Li, Erlong and Liu, Ao and Zou, Shengtao and Liu, Chang and Mei, Shuqi and Sizikova, Elena and others. *AAAI 2023*

-   [VMA] VMA: Divide-and-Conquer Vectorized Map Annotation System for Large-Scale Driving Scene.
    [[pdf]](https://arxiv.org/pdf/2304.09807.pdf)
    [[code]](https://github.com/hustvl/VMA)
    -   Chen, Shaoyu and Zhang, Yunchi and Liao, Bencheng and Xie, Jiafeng and Cheng, Tianheng and Sui, Wei and Zhang, Qian and Huang, Chang and Liu, Wenyu and Wang, Xinggang. *arXiv 2023*

-   Open HD map service model: an interoperable high-Definition map data model for autonomous driving.
    [[pdf]](https://www.tandfonline.com/doi/full/10.1080/17538947.2023.2220615)
    -  Zhang, Fengyuan and Shi, Wenzhong and Chen, Min and Huang, Wei and Liu, Xintao. *International Journal of Digital Earth 2023*

-   Multi-LiDAR Localization and Mapping Pipeline for Urban Autonomous Driving.
    [[pdf]](https://arxiv.org/pdf/2311.01823.pdf)
    -   Sauerbeck, Florian and Kulmer, Dominik and Pielmeier, Markus and Leitenstern, Maximilian and Wei{\ss}, Christoph and Betz, Johannes. 2023 IEEE SENSORS*

-   [FlexMap Fusion] FlexMap Fusion: Georeferencing and Automated Conflation of HD Maps with OpenStreetMap.
    [[pdf]](https://arxiv.org/pdf/2404.11155.pdf)
    [[code]](https://github.com/TUMFTM/FlexMap_Fusion)
    -   Leitenstern, Maximilian and Sauerbeck, Florian and Kulmer, Dominik and Betz, Johannes. *arXiv 2024*

## Lane detection
-   [3D-LaneNet] 3D-LaneNet: End-to-End 3D Multiple Lane Detection.
    [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Garnett_3D-LaneNet_End-to-End_3D_Multiple_Lane_Detection_ICCV_2019_paper.pdf)
    -   Garnett, Noa and Cohen, Rafi and Pe'er, Tomer and Lahav, Roee and Levi, Dan. *ICCV 2019*

-   [Gen-LaneNet] Gen-lanenet: A generalized and scalable approach for 3d lane detection.
    [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660664.pdf)
    [[code]](https://github.com/yuliangguo/Pytorch_Generalized_3D_Lane_Detection)
    -   Guo, Yuliang and Chen, Guang and Zhao, Peitao and Zhang, Weide and Miao, Jinghao and Wang, Jingao and Choe, Tae Eun. *ECCV 2020*

-   [STSU] Structured Bird's-Eye-View Traffic Scene Understanding From Onboard Images.
    [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Can_Structured_Birds-Eye-View_Traffic_Scene_Understanding_From_Onboard_Images_ICCV_2021_paper.pdf)
    [[code]](https://github.com/ybarancan/STSU)
    -   Can, Yigit Baran and Liniger, Alexander and Paudel, Danda Pani and Van Gool, Luc. *ICCV 2021*

## Misc
-   [MapLite 2.0] MapLite 2.0: Online HD Map Inference Using a Prior SD Map.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/9807400)
    -   Ort, Teddy and Walls, Jeffrey M. and Parkison, Steven A. and Gilitschenski, Igor and Rus, Daniela. *IEEE Robotics and Automation Letters 2022*

-   [V2HDM-Mono] V2HDM-Mono: A Framework of Building a Marking-Level HD Map with One or More Monocular Cameras.
    [[pdf]](https://arxiv.org/pdf/2209.07737.pdf)
    -   Liu, Hongji and Zheng, Linwei and Yan, Xiaoyang and Xu, Zhenhua and Xue, Bohuan and Yu, Yang and Liu, Ming. *arXiv 2022*

-   Clothoid-Based Reference Path Reconstruction for HD Map Generation.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10229966)
    -   Zhang, Songyi and Wang, Runsheng and Jian, Zhiqiang and Zhan, Wei and Zheng, Nanning and Tomizuka, Masayoshi. *IEEE Transactions on Intelligent Transportation Systems 2023*

-   [MIM4D] MIM4D: Masked Modeling with Multi-View Video for Autonomous Driving Representation Learning
    [[pdf]](https://arxiv.org/pdf/2403.08760.pdf)
    [[code]](https://github.com/hustvl/MIM4D)
    -   Zou, Jialv and Liao, Bencheng and Zhang, Qian and Liu, Wenyu and Wang, Xinggang. *arXiv 2024*

## News

## Talks

## Blog

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Honminden (Anqi Shi)](https://honminden.github.io/) has waived all copyright and related or neighboring rights to this work.
