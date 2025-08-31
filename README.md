# awesome-hd-map-construction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome HD map construction methods. Inspired by [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning).

## Contributing
Please help contribute this list by creating an issue or adding pull request.
Markdown format:
```markdown
-   [Model Name] Paper Title. 
    [[pdf]](link)
    [[code]](link)
    -   Author1 first name, Author1 last name and Author 2 first name, Author 2 last name and ... *Conference Year*
```
Please follow these rules:
1. If the paper does not propose a model name, `[Model Name]` should be omitted
2. `[[pdf]](link)` could be the arxiv version if the published version is not available
3. If the paper does not give the code link, or the corresponding link does not contain any real source code, `[[code]](link)` should be omitted

Example:
```markdown
-   [MapTR] MapTR: Structured Modeling and Learning for Online Vectorized HD Map Construction.
    [[pdf]](https://openreview.net/pdf?id=k7p_YAO7yE)
    [[code]](https://github.com/hustvl/MapTR)
    -   Liao, Bencheng and Chen, Shaoyu and Wang, Xinggang and Cheng, Tianheng, and Zhang, Qian and Liu, Wenyu and Huang, Chang. *ICLR 2023*
```

## Table of Contents  
- [awesome-hd-map-construction ](#awesome-hd-map-construction-)
  - [Contributing](#contributing)
  - [Table of Contents](#table-of-contents)
  - [Survey](#survey)
    - [2018](#2018)
    - [2020](#2020)
    - [2021](#2021)
    - [2022](#2022)
    - [2023](#2023)
    - [2024](#2024)
  - [Online HD map construction](#online-hd-map-construction)
    - [2021](#2021-1)
    - [2022](#2022-1)
    - [2023](#2023-1)
    - [2024](#2024-1)
    - [2025](#2025)
  - [HD map crowdsourcing](#hd-map-crowdsourcing)
    - [2017](#2017)
    - [2020](#2020-1)
    - [2023](#2023-2)
    - [2024](#2024-2)
    - [2025](#2025-1)
  - [HD map construction with human efforts](#hd-map-construction-with-human-efforts)
  - [Lane detection](#lane-detection)
  - [Misc](#misc)
  - [News](#news)
  - [Talks](#talks)
  - [Blog](#blog)
  - [License](#license)

## Survey
### 2018
-   Machine learning assisted high-definition map creation.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/8377682)
    -   Jiao, Jialin. *COMPSAC 2018*

-   High definition maps in urban context.
    [[pdf]](https://dl.acm.org/doi/abs/10.1145/3231541.3231546)
    -   Zang, Andi and Chen, Xin and Trajcevski, Goce. *Sigspatial Special 2018*

### 2020
-   Creation of high definition map for autonomous driving.
    [[pdf]](https://isprs-archives.copernicus.org/articles/XLIII-B4-2020/415/2020/isprs-archives-XLIII-B4-2020-415-2020.pdf)
    -   Tsushima, F and Kishimoto, N and Okada, Y and Che, W. *The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences 2020*

-   High definition map for automated driving: Overview and analysis.
    [[pdf]](https://www.cambridge.org/core/journals/journal-of-navigation/article/high-definition-map-for-automated-driving-overview-and-analysis/7FFB4F68B9C27F4312AF8DCD553205FE)
    -   Liu, Rong and Wang, Jinling and Zhang, Bingqi. *The Journal of Navigation 2020*

### 2021
-   High-definition map update framework for intelligent autonomous transfer vehicles.
    [[pdf]](https://www.tandfonline.com/doi/full/10.1080/0952813X.2020.1789754)
    -   Tas, Muhammed Oguz and Yavuz, Hasan Serhan and Yazici, Ahmet. *Journal of Experimental & Theoretical Artificial Intelligence 2021*

-   On Construction and Applications of High-Definition (HD) Maps.
    [[pdf]](https://izenderi.github.io/pdfs/On_High_Definition__HD__Maps.pdf)
    -   Zhu, Yuanjie and Alrashid, Hussah and Bai, Song and Zhang, Chunhan and Zhang, Ziliang and Qu, Zhengyi and Magdy, Amr. *personal website 2021*

-   High-definition map creation and update for autonomous driving.
    [[pdf]](https://www.diva-portal.org/smash/get/diva2:1578797/FULLTEXT01.pdf)
    -   Xia, Wanru. *master thesis 2021*

### 2022
-   High definition map update for autonomous and connected vehicles: A survey.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/9825276)
    -   Boubakri, Anis and Gammar, Sonia METTALI and Brahim, Mohamed BEN and Filali, Fethi. *IWCMC 2022*

-   High-definition map generation technologies for autonomous driving: a review.
    [[pdf]](https://arxiv.org/ftp/arxiv/papers/2206/2206.05400.pdf)
    -   Bao, Zhibin and Hossain, Sabir and Lang, Haoxiang and Lin, Xianke. *arXiv 2022*

### 2023
-   A review of high-definition map creation methods for autonomous driving.
    [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0952197623003093)
    -   Bao, Zhibin and Hossain, Sabir and Lang, Haoxiang and Lin, Xianke. *Engineering Applications of Artificial Intelligence 2023*

-   High-definition maps: Comprehensive survey, challenges and future perspectives.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10184094)
    -   Elghazaly, Gamal and Frank, Raphaël and Harvey, Scott and Safko, Stefan. *IEEE Open Journal of Intelligent Transportation Systems 2023*

-   High-Definition Maps Construction Based on Visual Sensor: A Comprehensive Survey.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10336514)
    -   Tang, Xuewei and Jiang, Kun and Yang, Mengmeng and Liu, Zhaoyang and Jia, Peijin and Wijaya, Benny and Wen, Tuopu and Cui, Le and Yang, Diange. *IEEE Transactions on Intelligent Vehicles 2023*

### 2024
-   High precision map crowdsource update technology and SLAM technology-Application in autonomous driving.
    [[pdf]](https://www.mdpi.com/2220-9964/13/3/104)
    -   Liu, Dapeng. *Journal of Physics: Conference Series 2024*

-   A Review of Crowdsourcing Update Methods for High-Definition Maps.
    [[pdf]](https://www.mdpi.com/2220-9964/13/3/104)
    -   Guo, Yuan and Zhou, Jian and Li, Xicheng and Tang, Youchen and Lv, Zhicheng. * ISPRS International Journal of Geo-Information 2024*

-   On the Ecosystem of High-Definition (HD) Maps.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10555117)
    -   Zhuy, Yuanjie and Alrashid, Hussah and Bai, Song and Zhang, Chunhan and Zhang, Ziliang and Qu, Zhengyi and Ali, Reem Y and Magdy, Amr. *ICDEW 2024*

-   High Definition Map Mapping and Update: A General Overview and Future Directions.
    [[pdf]](https://arxiv.org/pdf/2409.09726)
    -   Wijaya, Benny and Jiang, Kun and Yang, Mengmeng and Wen, Tuopu and Wang, Yunlong and Tang, Xuewei and Fu, Zheng and Zhou, Taohua and Yang, Diange. *arXiv 2024*

-   Online High-Definition Map Construction for Autonomous Vehicles: A Comprehensive Survey.
    [[pdf]](https://www.preprints.org/manuscript/202411.1810/v1)
    -   Lyu, Hongyu and Perez, Julie Stephany Berrio and Huang, Yaoqi and Li, Kunming and Shan, Mao and Worrall, Stewart. *Journal of Sensor and Actuator Networks 2025*

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
    -   Dong, Hao and Zhang, Xianjing and Xu, Jintao and Ai, Rui and Gu, Weihao and Lu, Huimin and Kannala, Juho and Chen, Xieyuanli. *ICRA 2024*

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
    -   Liao, Bencheng and Chen, Shaoyu and Zhang, Yunchi and Jiang, Bo and Zhang, Qian and Liu, Wenyu and Huang, Chang and Wang, Xinggang. *IJCV 2024*

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
    -   Gao, Wenjie and Fu, Jiawei and Jing, Haodong and Zheng, Nanning. *ICRA 2024*

-   [PivotNet] PivotNet: Vectorized Pivot Learning for End-to-end HD Map Construction.
    [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ding_PivotNet_Vectorized_Pivot_Learning_for_End-to-end_HD_Map_Construction_ICCV_2023_paper.pdf)
    -   Ding, Wenjie and Qiao, Limeng and Qiu, Xi and Zhang, Chi. *ICCV 2023*

-   [ScalableMap] ScalableMap: Scalable Map Learning for Online Long-Range Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2310.13378.pdf)
    [[code]](https://github.com/jingy1yu/ScalableMap)
    -   Yu, Jingyi and Zhang, Zizhao and Xia, Shengfu and Sang, Jizhang. *CoRL 2023*

-   [MapEX] Mind the map! Accounting for existing map information when estimating online HDMaps from sensor data.
    [[pdf]](https://arxiv.org/pdf/2311.10517.pdf)
    -   Sun, Rémy and Yang, Li and Lingrand, Diane and Precioso, Frédéric. *WACV 2025*

-   [GeMap] Online Vectorized HD Map Construction using Geometry.
    [[pdf]](https://arxiv.org/pdf/2312.03341.pdf)
    [[code]](https://github.com/cnzzx/GeMap)
    -   Zhixin Zhang and Yiyuan Zhang and Xiaohan Ding and Fusheng Jin and Xiangyu Yue. *ECCV 2024*

-   [LaneSegNet] LaneSegNet: Map Learning with Lane Segment Perception for Autonomous Driving.
    [[pdf]](https://arxiv.org/pdf/2312.16108)
    [[code]](https://github.com/OpenDriveLab/LaneSegNet)
    -   Li, Tianyu and Jia, Peijin and Wang, Bangjun and Chen, Li and JIANG, KUN and Yan, Junchi and Li, Hongyang. *ICLR 2024*

### 2024
-   [MapNeXt] MapNeXt: Revisiting Training and Scaling Practices for Online Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2401.07323.pdf)
    -   Li, Toyota. *arXiv 2024*

-   [SQD-MapNet] Stream Query Denoising for Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2401.09112.pdf)
    [[code]](https://github.com/shuowang666/SQD-MapNet)
    -   Wang, Shuo and Jia, Fan and Liu, Yingfei and Zhao, Yucheng and Chen, Zehui and Wang, Tiancai and Zhang, Chi and Zhang, Xiangyu and Zhao, Feng. *ECCV 2024*

-   [ADMap] ADMap: Anti-disturbance framework for reconstructing online vectorized HD map.
    [[pdf]](https://arxiv.org/pdf/2401.13172.pdf)
    [[code]](https://github.com/hht1996ok/ADMap)
    -   Hu, Haotian and Wang, Fanyi and Wang, Yaonong and Hu, Laifeng and Xu, Jingwei and Zhang, Zhiwang. *arXiv 2024*

-   [MapQR] Leveraging Enhanced Queries of Point Sets for Vectorized Map Construction.
    [[pdf]](https://arxiv.org/pdf/2402.17430.pdf)
    -   Liu, Zihao and Zhang, Xiaoyu and Liu, Guangwei and Zhao, Ji and Xu, Ningyi. *ECCV 2024*

-   [EAN-MapNet] EAN-MapNet: Efficient Vectorized HD Map Construction with Anchor Neighborhoods.
    [[pdf]](https://arxiv.org/pdf/2402.18278.pdf)
    -   Xiong, Huiyuan and Shen, Jun and Zhu, Taohong and Pan, Yuelong. *arXiv 2024*

-   [HIMap] HIMap: HybrId Representation Learning for End-to-end Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2403.08639.pdf)
    -   Zhou, Yi and Zhang, Hui and Yu, Jiaqian and Yang, Yifan and Jung, Sangil and Park, Seung-In and Yoo, ByungIn. *CVPR 2024*

-   [PreSight] PreSight: Enhancing Autonomous Vehicle Perception with City-Scale NeRF Priors.
    [[pdf]](https://arxiv.org/pdf/2403.09079.pdf)
    -   Yuan, Tianyuan and Mao, Yucheng and Yang, Jiawei and Liu, Yicheng and Wang, Yue and Zhao, Hang. *ECCV 2024*

-   [P-MapNet] P-MapNet: Far-seeing Map Generator Enhanced by both SDMap and HDMap Priors.
    [[pdf]](https://arxiv.org/pdf/2403.10521.pdf)
    [[code]](https://github.com/jike5/P-MapNet)
    -   Jiang, Zhou and Zhu, Zhenxin and Li, Pengfei and Gao, Huan-ang and Yuan, Tianyuan and Shi, Yongliang and Zhao, Hang and Zhao, Hao. *IEEE Robotics and Automation Letters 2024*

-   [Buffered Gaussian Modeling] Buffered Gaussian Modeling for Vectorized HD Map Construction.
    [[pdf]](https://ieeexplore.ieee.org/document/10445925)
    -   Shi, Anqi and Chen, Huaqiu and Lu, Hong and Zhang, Rui. *ICASSP 2024*

-   [MapTracker] MapTracker: Tracking with Strided Memory Fusion for Consistent Vector HD Mapping.
    [[pdf]](https://arxiv.org/pdf/2403.15951.pdf)
    [[code]](https://github.com/woodfrog/maptracker)
    -   Chen, Jiacheng and Wu, Yuefan and Tan, Jiaqi and Ma, Hang and Furukawa, Yasutaka. *ECCV 2024*

-   [MGMap] MGMap: Mask-Guided Learning for Online Vectorized HD Map Construction.
    [[pdf]](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_MGMap_Mask-Guided_Learning_for_Online_Vectorized_HD_Map_Construction_CVPR_2024_paper.pdf)
    [[code]](https://github.com/xiaolul2/MGMap)
    -   Liu, Xiaolu and Wang, Song and Li, Wentong and Yang, Ruizi and Chen, Junbo and Zhu, Jianke. *CVPR 2024*

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
    [[code]](https://github.com/lynn-yu/DTCLMapper)
    -   Li, Siyu and Lin, Jiacheng and Shi, Hao and Zhang, Jiaming and Wang, Song and Yao, You and Li, Zhiyong and Yang, Kailun. *IEEE Transactions on Intelligent Transportation Systems 2024*

-   [SparseDrive] SparseDrive: End-to-End Autonomous Driving via Sparse Scene Representation.
    [[pdf]](https://arxiv.org/pdf/2405.19620)
    [[code]](https://github.com/swc-17/SparseDrive)
    -   Sun, Wenchao and Lin, Xuewu and Shi, Yining and Zhang, Chuang and Wu, Haoran and Zheng, Sifa. *arXiv 2024*

-   [POP-Net] Camera-based Online Vectorized HD Map Construction with Incomplete Observation.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10542214)
    -   Liu, Hui and Chang, Faliang and Liu, Chunsheng and Lu, Yansha and Liu, Minhang. *IEEE Robotics and Automation Letters 2024*

-   Exploring Real World Map Change Generalization of Prior-Informed HD Map Prediction Models.
    [[pdf]](https://openaccess.thecvf.com/content/CVPR2024W/WAD/papers/Bateman_Exploring_Real_World_Map_Change_Generalization_of_Prior-Informed_HD_Map_CVPRW_2024_paper.pdf)
    -   Bateman, Samuel M and Xu, Ning and Zhao, H Charles and Ben Shalom, Yael and Gong, Vince and Long, Greg and Maddern, Will. *CVPR 2024 Workshops*

-   [MapVision] MapVision: CVPR 2024 Autonomous Grand Challenge Mapless Driving Tech Report.
    [[pdf]](https://arxiv.org/pdf/2406.10125)
    -   Yang, Zhongyu and Liu, Mai and Xie, Jinluo and Zhang, Yueming and Shen, Chen and Shao, Wei and Jiao, Jichao and Xing, Tengfei and Hu, Runbo and Xu, Pengfei. *arXiv 2024*

-   [MapBench] Is Your HD Map Constructor Reliable under Sensor Corruptions?.
    [[pdf]](https://mapbench.github.io/paper.pdf)
    [[code]](https://github.com/mapbench/toolkit)
    -   Hao, Xiaoshuai and Wei, Mengchuan and Yang, Yifan and Zhao, Haimei and Zhang, Hui and Zhou, Yi and Wang, Qiang and Li, Weiming and Kong, Lingdong and Zhang, Jing. *arXiv 2024*

-   [LGmap] LGmap: Local-to-Global Mapping Network for Online Long-Range Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2406.13988)
    -   Wu, Kuang and Nian, Sulei and Shen, Can and Yang, Chuan and Li, Zhanbin. *arXiv 2024*

-   [MapBEVPrediction] Accelerating Online Mapping and Behavior Prediction via Direct BEV Feature Attention.
    [[pdf]](https://arxiv.org/pdf/2407.06683)
    [[code]](https://github.com/alfredgu001324/MapBEVPrediction)
    -   Gu, Xunjiang and Song, Guanyu and Gilitschenski, Igor and Pavone, Marco and Ivanovic, Boris. *arXiv 2024*

-   [Mask2Map] Vectorized HD Map Construction Using Bird's Eye View Segmentation Masks.
    [[pdf]](https://arxiv.org/pdf/2407.13517)
    -   Choi, Sehwan and Kim, Jungho and Shin, Hongjae and Choi, Jun Won. *ECCV 2024*

-   [LaneDAG] LaneDAG: Automatic HD Map Topology Generator Based on Geometry and Attention Fusion Mechanism.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10588515)
    -   Jia, Peijin and Wen, Tuopu and Luo, Ziang and Fu, Zheng and Liao, Jiaqi and Chen, Huixian and Jiang, Kun and Yang, Mengmeng and Yang, Diange. *IEEE Intelligent Vehicles Symposium 2024*

-   [E-MLP] E-MLP: Effortless Online HD Map Construction with Linear Priors.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10588612)
    -   Li, Ruikai and Shan, Hao and Jiang, Han and Xiao, Jianru and Chang, Yizhuo and He, Yifan and Yu, Haiyang and Ren, Yilong. *IEEE Intelligent Vehicles Symposium 2024*

-   [LaneMapNet] LaneMapNet: Lane Network Recognization and HD Map Construction Using Curve Region Aware Temporal Bird’s-Eye-View Perception.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10588419)
    -   Zhu, Tianyi and Leng, Jianghao and Zhong, Jiaru and Zhang, Zhang and Sun, Chao. *IEEE Intelligent Vehicles Symposium 2024*

-   [UniHDMap] UniHDMap: Unified Lane Elements Detection for Topology HD Map Construction.
    [[pdf]](https://opendrivelab.github.io/Challenge%202024/mapless_CrazyFriday.pdf)
    -   ZKou, Genghua and Jia, Fan and Wu, Dongming and Liu, Yingfei and Li, Ying and Wang, Tiancai. *personal website 2024*

-   [MapDistill] MapDistill: Boosting Efficient Camera-based HD Map Construction via Camera-LiDAR Fusion Model Distillation.
    [[pdf]](https://arxiv.org/pdf/2407.11682)
    -   Hao, Xiaoshuai and Li, Ruikai and Zhang, Hui and Li, Dingzhe and Yin, Rong and Jung, Sangil and Park, Seung-In and Yoo, ByungIn and Zhao, Haimei and Zhang, Jing. *arXiv 2024*

-   [PrevPredMap] PrevPredMap: Exploring Temporal Modeling with Previous Predictions for Online Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2407.17378)
    [[code]](https://github.com/pnnnnnnn/PrevPredMap)
    -   Peng, Nan and Zhou, Xun and Wang, Mingming and Yang, Xiaojun and Chen, Songming and Chen, Guisong. *WACV 2025*

-   Enhancing Online Road Network Perception and Reasoning with Standard Definition Maps.
    [[pdf]](https://arxiv.org/pdf/2408.01471)
    -   Zhang, Hengyuan and Paz, David and Guo, Yuliang and Das, Arun and Huang, Xinyu and Haug, Karsten and Christensen, Henrik I and Ren, Liu. *IROS 2024*

-   [HRMapNet] Enhancing Vectorized Map Perception with Historical Rasterized Maps.
    [[pdf]](https://arxiv.org/pdf/2409.00620)
    [[code]](https://github.com/HXMap/HRMapNet)
    -   Zhang, Xiaoyu and Liu, Guangwei and Liu, Zihao and Xu, Ningyi and Liu, Yunhui and Zhao, Ji. *ECCV 2024*

-   [PriorMapNet] PriorMapNet: Enhancing Online Vectorized HD Map Construction with Priors.
    [[pdf]](https://arxiv.org/pdf/2408.08802)
    -   Wang, Rongxuan and Lu, Xin and Liu, Xiaoyang and Zou, Xiaoyi and Cao, Tongyi and Li, Ying. *arXiv 2024*

-   [HoMap] HoMap: End-to-End Vectorized HD Map Construction with High-order Modeling.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10638726)
    -   Cai, Yingfeng and Dong, Wei and Liu, Ze and Wang, Hai and Chen, Long. *IEEE Transactions on Intelligent Vehicles 2024*

-   [PriorDrive] Driving with Prior Maps: Unified Vector Prior Encoding for Autonomous Vehicle Mapping.
    [[pdf]](https://arxiv.org/pdf/2409.05352)
    -   Zeng, Shuang and Chang, Xinyuan and Liu, Xinran and Pan, Zheng and Wei, Xing. *arXiv 2024*

-   [GenMapping] GenMapping: Unleashing the Potential of Inverse Perspective Mapping for Robust Online HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2409.08688)
    -   Li, Siyu and Yang, Kailun and Shi, Hao and Wang, Song and Yao, You and Li, Zhiyong. *arXiv 2024*

-   [GlobalMapNet] GlobalMapNet: An Online Framework for Vectorized Global HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2409.10063)
    [[code]](https://github.com/Honminden/GlobalMapNet)
    -   Shi, Anqi and Cai, Yuze and Chen, Xiangyu and Pu, Jian and Fu, Zeyu and Lu, Hong. *arXiv 2024*

-   [ExelMap] ExelMap: Explainable Element-based HD-Map Change Detection and Update.
    [[pdf]](https://arxiv.org/pdf/2409.10178)
    -   Wild, Lena and Ericson, Ludvig and Valencia, Rafael and Jensfelt, Patric. *arXiv 2024*

-   [MemFusionMap] MemFusionMap: Working Memory Fusion for Online Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2409.18737)
    -   Song, Jingyu and Chen, Xudong and Lu, Liupei and Li, Jie and Skinner, Katherine A. *arXiv 2024*

-   [SeqHDMapCDNet] Investigation on Change Detection of High Definition Map Based on Sequential Model.
    [[pdf]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4980104)
    -   Li, Lijun and Qiao, Zhenghao and Hu, Xing and Zhang, Wei. *SSRN 2024*

-   [MGMapNet] MGMapNet: Multi-Granularity Representation Learning for End-to-End Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2410.07733)
    -   Yang, Jing and Jiang, Minyue and Yang, Sen and Tan, Xiao and Li, Yingying and Ding, Errui and Wang, Hanli and Wang, Jingdong. *arXiv 2024*

-   [TICMapNet] TICMapNet: A Tightly Coupled Temporal Fusion Pipeline for Vectorized HD Map Learning.
    [[pdf]](https://ieeexplore.ieee.org/document/10740793)
    [[code]](https://github.com/adasfag/TICMapNet)
    -   Qiu, Wenzhao and Pang, Shanmin and Zhang, Hao and Fang, Jianwu and Xue, Jianru. *IEEE Robotics and Automation Letters 2024*

-   [HeightMapNet] HeightMapNet: Explicit Height Modeling for End-to-End HD Map Learning.
    [[pdf]](https://arxiv.org/pdf/2411.01408)
    -   Qiu, Wenzhao and Pang, Shanmin and Zhang, Hao and Fang, Jianwu and Xue, Jianru. *arXiv 2024*

-   [M3TR] M3TR: Generalist HD Map Construction with Variable Map Priors.
    [[pdf]](https://arxiv.org/pdf/2411.10316)
    -   Immel, Fabian and Fehler, Richard and Bieder, Frank and Pauls, Jan-Hendrik and Stiller, Christoph. *arXiv 2024*

-   [MapUnveiler] Unveiling the Hidden: Online Vectorized HD Map Construction with Clip-Level Token Interaction and Propagation.
    [[pdf]](https://arxiv.org/pdf/2411.11002)
    -   Kim, Nayeon and Seong, Hongje and Ji, Daehyun and Jang, Sujin. *NeurIPS 2024*

-   [GaussianPretrain] GaussianPretrain: A Simple Unified 3D Gaussian Representation for Visual Pre-training in Autonomous Driving.
    [[pdf]](https://arxiv.org/pdf/2411.12452)
    [[code]](https://github.com/Public-BOTs/GaussianPretrain)
    -   Xu, Shaoqing and Li, Fang and Jiang, Shengyin and Song, Ziying and Liu, Li and Yang, Zhi-xin. *arXiv 2024*

-   [MapExpert] MapExpert: Online HD Map Construction with Simple and Efficient Sparse Map Element Expert.
    [[pdf]](https://arxiv.org/pdf/2412.12704)
    -   Zhang, Dapeng and Chen, Dayu and Zhi, Peng and Chen, Yinda and Yuan, Zhenlong and Li, Chenyang and Sunjing and Zhou, Rui and Zhou, Qingguo. *arXiv 2024*

-   [ImagineMap] ImagineMap: Enhanced HD Map Construction with SD Maps.
    [[pdf]](https://arxiv.org/pdf/2412.16938)
    -   Ji, Yishen and Li, Zhiqi and Lu, Tong. *arXiv 2024*

### 2025
-   [MSC-Bench] MSC-Bench: Benchmarking and Analyzing Multi-Sensor Corruption for Driving Perception.
    [[pdf]](https://arxiv.org/pdf/2501.01037)
    -   Hao, Xiaoshuai and Liu, Guanqun and Zhao, Yuting and Ji, Yuheng and Wei, Mengchuan and Zhao, Haimei and Kong, Lingdong and Yin, Rong and Liu, Yu. *arXiv 2025*

-   [MapGS] MapGS: Generalizable Pretraining and Data Augmentation for Online Mapping via Novel View Synthesis.
    [[pdf]](https://arxiv.org/pdf/2501.06660)
    -   Zhang, Hengyuan and Paz, David and Guo, Yuliang and Huang, Xinyu and Christensen, Henrik I and Ren, Liu. *arXiv 2025*

-   [SMART] SMART: Advancing Scalable Map Priors for Driving Topology Reasoning.
    [[pdf]](https://arxiv.org/pdf/2502.04329)
    -   Ye, Junjie and Paz, David and Zhang, Hengyuan and Guo, Yuliang and Huang, Xinyu and Christensen, Henrik I and Wang, Yue and Ren, Liu. *arXiv 2025*

-   [MapFusion] MapFusion: A Novel BEV Feature Fusion Network for Multi-modal Map Construction.
    [[pdf]](https://arxiv.org/pdf/2502.04377)
    -   Hao, Xiaoshuai and Diao, Yunfeng and Wei, Mengchuan and Yang, Yifan and Hao, Peng and Yin, Rong and Zhang, Hui and Li, Weiming and Zhao, Shu and Liu, Yu. *arXiv 2025*

-   [AerialHDMappper] AerialHDMappper: High-Definition Map Construction from Aerial Imagery.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10879386)
    -   Xie, Haofeng and Hu, Xiangyun and Jiang, Huiwei and Dai, Hengming and Dong, Pengwei and Wang, Pengfei. *IEEE Transactions on Geoscience and Remote Sensing 2025*

-   [HDMapLaneNet] Leveraging V2X for Collaborative HD Maps Construction Using Scene Graph Generation.
    [[pdf]](https://arxiv.org/pdf/2502.10127)
    -   Elghazaly, Gamal and Frank, Raphael. *arXiv 2025*

-   [InVDriver] InVDriver: Intra-Instance Aware Vectorized Query-Based Autonomous Driving Transformer.
    [[pdf]](https://arxiv.org/pdf/2502.17949)
    -   Zhang, Bo and Huang, Heye and Liu, Chunyang and Zhang, Yaqin and Xu, Zhenhua. *arXiv 2025*

-   [TS-CGNet] TS-CGNet: Temporal-Spatial Fusion Meets Centerline-Guided Diffusion for BEV Mapping.
    [[pdf]](https://arxiv.org/pdf/2503.02578)
    -   Hong, Xinying and Li, Siyu and Zeng, Kang and Shi, Hao and Peng, Bomin and Yang, Kailun and Li, Zhiyong. *arXiv 2025*

-   [FastMap] FastMap: Fast Queries Initialization Based Vectorized HD Map Reconstruction Framework.
    [[pdf]](https://arxiv.org/pdf/2503.05492)
    -   Hu, Haotian and Xu, Jingwei and Wang, Fanyi and Li, Toyota and Wang, Yaonong and Hu, Laifeng and Zhang, Zhiwang. *arXiv 2025*

-   [HisTrackMap] HisTrackMap: Global Vectorized High-Definition Map Construction via History Map Tracking.
    [[pdf]](https://arxiv.org/pdf/2503.07168)
    -   Yang, Jing and Yang, Sen and Tan, Xiao and Wang, Hanli. *arXiv 2025*

-   Enhancing Online HD Map Construction with Trajectory Guidance in Challenging.
    [[pdf]](https://link.springer.com/chapter/10.1007/978-981-96-3973-1_27)
    -   Yao, Ziying and Xiong, Zhongxia and Wu, Xinkai. *International Conference on Artificial Intelligence and Autonomous Transportation 2024*

-   [AugMapNet] AugMapNet: Improving Spatial Latent Structure via BEV Grid Augmentation for Enhanced Vectorized Online HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2503.13430)
    -   Monninger, Thomas and Anwar, Md Zafar and Antol, Stanislaw and Staab, Steffen and Ding, Sihao. *arXiv 2025*

-   [KPMapNet] KPMapNet: Keypoint Representation Learning for Online Vectorized High-Definition Map Construction.
    [[pdf]](https://www.mdpi.com/1424-8220/25/6/1897)
    -   Jin, Bicheng and Hao, Wenyu and Qiu, Wenzhao and Pang, Shanmin. *Sensors 2025*

-   [InteractionMap] InteractionMap: Improving Online Vectorized HDMap Construction with Interaction.
    [[pdf]](https://arxiv.org/pdf/2503.21659)
    -   Wu, Kuang and Yang, Chuan and Li, Zhanbin. *arXiv 2025*

-   [UIGenMap] Uncertainty-Instructed Structure Injection for Generalizable HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2503.23109)
    -   Liu, Xiaolu and Yang, Ruizi and Wang, Song and Li, Wentong and Chen, Junbo and Zhu, Jianke. *arXiv 2025*

-   [V2I-HD] A Benchmark for Vision-Centric HD Mapping by V2I Systems.
    [[pdf]](https://arxiv.org/pdf/2503.23963)
    [[code]](https://1drv.ms/f/c/76645c25a8914a0b/EgWy5XCUk6pKgvE9vB-HbVEBCdCQjJvgx1KKjeKF7hPdZw)
    -   Fan, Miao and Yu, Shanshan and Xu, Shengtong and Jiang, Kun and Xiong, Haoyi and Liu, Xiangzeng. *arXiv 2025*

-   Control Map Distribution using Map Query Bank for Online Map Generation.
    [[pdf]](https://arxiv.org/pdf/2504.03868)
    -   Liu, Ziming and Wang, Leichen and Yang, Ge and Li, Xinrun and Hu, Xingtao and Sun, Hao and Gao, Guangyu. *arXiv 2025*

-   [Uni-PrevPredMap] Uni-PrevPredMap: Extending PrevPredMap to a Unified Framework of Prior-Informed Modeling for Online Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2504.06647)
    [[code]](https://github.com/pnnnnnnn/uni-prevpredmap)
    -   Peng, Nan and Zhou, Xun and Wang, Mingming and Chen, Guisong and Xu, Wenqi. *arXiv 2025*

-   [SIO-Mapper] SIO-Mapper: A Framework for Lane-Level HD Map Construction Using Satellite Images and OpenStreetMap with No On-Site Visits.
    [[pdf]](https://arxiv.org/pdf/2504.09882)
    -   Cho, Younghun and Ryu, Jee-Hwan. *arXiv 2025*

-   [SparseMeXt] SparseMeXt: Unlocking the Potential of Sparse Representations for HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2504.09882)
    -   Jiang, Anqing and Chai, Jinhao and Gao, Yu and Wang, Yiru and Heng, Yuwen and Sun, Zhigang and Sun, Hao and Zhao, Zezhong and Sun, Li and Zhou, Jian and Zhu, Lijuan and Xu, Shugong and Zhao, Hao. *arXiv 2025*

-   [SuperMapNet] SuperMapNet for Long-Range and High-Accuracy Vectorized HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2505.13856)
    -   Zhou, Ruqin and Jiang, San and Jiang, Wanshou and Zhang, Yongsheng and Dai, Chenguang. *arXiv 2025*

-   [SDTagNet] SDTagNet: Leveraging Text-Annotated Navigation Maps for Online HD Map Construction.
    [[pdf]](https://arxiv.org/pdf/2506.08997)
      - Immel, Fabian and Pauls, Jan-Hendrik and Fehler, Richard and Bieder, Frank and Merkert, Jonas and Stiller, Christoph. *arXiv 2025*

-   [HDP-Map] HDP-Map: Hierarchical Dual-Path Learning Framework with Geometric-Semaware Attention.
    [[pdf]](https://ssrn.com/abstract=5281666)
    -   Tian, Keke and Zhang, Jingtao and Zhang, Jing and Qin, Ke. *SSRN 2025*

  - [CrowdMap] Scalable Crowd-Sourced Global HD Map Construction via Collaborative Map Perception and Sparse Graph Fusion.
    [[pdf]](https://ry4nzhu.github.io/publication/scalable_crowded_hd_map_construction/scalable_crowded_HD_map_construction.pdf)
      - Zhu, Ruiyang and Cho, Minkyoung and Zeng, Shuqing and Bai, Fan and Gao, Xiang and Mao, Z. Morley. *2024*

-   [MapFM] MapFM: Foundation Model-Driven HD Mapping with Multi-Task Contextual Learning.
    [[pdf]](https://arxiv.org/pdf/2506.15313)
    -   Ivanov, Leonid and Yuryev, Vasily and Yudin, Dmitry. *arXiv 2025*

-   [SafeMap] SafeMap: Robust HD Map Construction from Incomplete Observations.
    [[pdf]](https://arxiv.org/pdf/2507.00861)
    -   Hao, Xiaoshuai and Kong, Lingdong and Yin, Rong and Wang, Pengwei and Zhang, Jing and Diao, Yunfeng and Zhao, Shu. *ICML 2025*

-   [RTMap] RTMap: Real-Time Recursive Mapping with Change Detection and Localization.
    [[pdf]](https://arxiv.org/pdf/2507.00980)
    -   Du, Yuheng and Yang, Sheng and Wang, Lingxuan and Hou, Zhenghua and Cai, Chengying and Tan, Zhitao and Chen, Mingxia and Huang, Shi-Sheng and Li, Qiang. *ICCV 2025*

-   [Score] Coherent Online Road Topology Estimation and Reasoning with Standard-Definition Maps.
    [[pdf]](https://arxiv.org/pdf/2507.01397v2)
    -   Pham, Khanh Son and Witte, Christian and Behley, Jens and Betz, Johannes and Stachniss, Cyrill. *arXiv 2025*

-   [RoboMap] What Really Matters for Robust Multi-Sensor HD Map Construction?.
    [[pdf]](https://arxiv.org/pdf/2507.01484v1)
    -   Hao, Xiaoshuai and Zhao, Yuting and Ji, Yuheng and Dai, Luanyuan and Hao, Peng and Li, Dingzhe and Cheng, Shuai and Yin, Rong. *arXiv 2025*

-   [MAT] Driving by Hybrid Navigation: An Online HD-SD Map Association Framework and Benchmark for Autonomous Vehicles.
    [[pdf]](https://arxiv.org/pdf/2507.07487v2)
    [[code]](https://github.com/WallelWan/OMA-MAT)
    -   Wan, Jiaxu and Wang, Xu and Chang, Xinyuan and Pan, Zheng and Xu, Mu and Xie, Mengwei and Liu, Xinran and Yuan, Ding. *arXiv 2025*

-   Multimodal HD Mapping for Intersections by Intelligent Roadside Units.
    [[pdf]](https://arxiv.org/pdf/2507.08903v1)
    -   Chen, Zhongzhang and Fan, Miao and Xu, Shengtong and Yang, Mengmeng and Jiang, Kun and Liu, Xiangzeng and Xiong, Haoyi. *arXiv 2025*

-   Delving into Mapping Uncertainty for Mapless Trajectory Prediction.
    [[pdf]](https://arxiv.org/pdf/2507.18498v1)
    [[code]](https://github.com/Ethan-Zheng136/Map-Uncertainty-for-Trajectory-Prediction)
    -   Zhang, Zongzheng and Qiu, Xuchong and Zhang, Boran and Zheng, Guantian and Gu, Xunjiang and Chi, Guoxuan and Gao, Huan-ang and Wang, Leichen and Liu, Ziming and Li, Xinrun and Gilitschenski, Igor and Li, Hongyang and Zhao, Hang and Zhao, Hao. *arXiv 2025*

-   [MambaMap] MambaMap: Online Vectorized HD Map Construction using State Space Model.
    [[pdf]](https://arxiv.org/pdf/2507.20224v1)
    -   Yang, Ruizi and Liu, Xiaolu and Chen, Junbo and Zhu, Jianke. *arXiv 2025*

-   [MapDiffusion] MapDiffusion: Generative Diffusion for Vectorized Online HD Map Construction and Uncertainty Estimation in Autonomous Driving.
    [[pdf]](https://arxiv.org/pdf/2507.21423v1)
    -   Monninger, Thomas and Zhang, Zihan and Mo, Zhipeng and Anwar, Md Zafar and Staab, Steffen and Ding, Sihao. *arXiv 2025*

-   [RelMap] RelMap: Enhancing Online Map Construction with Class-Aware Spatial Relation and Semantic Priors.
    [[pdf]](https://arxiv.org/abs/2507.21567)
    -   Cai, Tianhui and Zhang, Yun and Zhou, Zewei and Huang, Zhiyu and Ma, Jiaqi. *arXiv 2025*

-   [PriorFusion] PriorFusion: Unified Integration of Priors for Robust Road Perception in Autonomous Driving.
    [[pdf]](https://arxiv.org/abs/2507.23309)
    -   Tang, Xuewei and Yang, Mengmeng and Wen, Tuopu and Jia, Peijin and Cui, Le and Luo, Mingshan and Sheng, Kehua and Zhang, Bo and Jiang, Kun and Yang, Diange. *arXiv 2025*

-   [MapKD] MapKD: Unlocking Prior Knowledge with Cross - Modal Distillation for Efficient Online HD Map Construction.
    [[pdf]](https://arxiv.org/abs/2508.15653)
    [[code]](https://github.com/2004yan/MapKD2026)
    -   Yan, Ziyang and Li, Ruikai and Cui, Zhiyong and Li, Bohan and Jiang, Han and Ren, Yilong and Li, Aoyong and Li, Zhenning and Wen, Sijia and Yu, Haiyang. *arXiv 2025*

-   [PseudoMapTrainer] PseudoMapTrainer: Learning Online Mapping without HD Maps.
    [[pdf]](https://arxiv.org/abs/2508.18788)
    [[code]](https://github.com/boschresearch/PseudoMapTrainer)
    -   Löwens, Christian and Funke, Thorben and Xie, Jingchao and Condurache, Alexandru Paul. *arXiv 2025*

## HD map crowdsourcing
### 2017
-   An end-to-end system for crowdsourced 3D maps for autonomous vehicles: The mapping component.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/8202218)
    -   Dabeer, Onkar and Ding, Wei and Gowaiker, Radhika and Grzechnik, Slawomir K and Lakshman, Mythreya J and Lee, Sean and Reitmayr, Gerhard and Sharma, Arunandan and Somasundaram, Kiran and Sukhavasi, Ravi Teja and others. *IROS 2017*

### 2020
-   Crowdsourced 3D mapping: a combined multi-view geometry and self-supervised learning approach.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/9341243)
    -   Chawla, Hemang and Jukola, Matti and Brouns, Terence and Arani, Elahe and Zonooz, Bahram. *IROS 2020*

### 2023
-   Recruiting Heterogeneous Crowdsource Vehicles for Updating a High-Definition Map.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10349885)
    -   Ye, Wentao and Luo, Yuan and Liu, Bo and Huang, Jianwei. *WiOpt 2023*

-   Traffic Flow-Based Crowdsourced Mapping in Complex Urban Scenario.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10171417)
    -   Qin, Tong and Huang, Haihui and Wang, Ziqiang and Chen, Tongqing and Ding, Wenchao. *IEEE Robotics and Automation Letters 2023*

### 2024
-   [MapCVV] MapCVV: On-cloud Map Construction Using Crowdsourcing Visual Vectorized Elements towards Autonomous Driving.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/10517387)
    -   Chen, Pengxin and Jiang, Xiaoqi and Zhang, Yingjun and Tan, Jiahao and Jiang, Rong. *IEEE Robotics and Automation Letters 2024*

### 2025
-   [CleanMAP] CleanMAP: Distilling Multimodal LLMs for Confidence-Driven Crowdsourced HDMapUpdates.
    [[pdf]](https://arxiv.org/pdf/2504.10738)
    -   Shaw, Ankit Kumar and Jiang, Kun and Wen, Tuopu and Sah, Chandan Kumar and Shi, Yining and Yang, Mengmeng and Yang, Diange and Lian, Xiaoli. *arxiv 2025*

-   [TrailTR] Inferring Driving Maps by Deep Learning-based Trail Map Extraction.
    [[pdf]](https://arxiv.org/pdf/2505.10258)
    -   Hubbertz, Michael and Colling, Pascal and Han, Qi and Meisen, Tobias. *arxiv 2025*

-   [AutoTS] Traffic Sign Localization and Orientation Classification for Automated Map Updating.
    [[pdf]](https://ieeexplore.ieee.org/abstract/document/11005561)
    -   Han, Xianjing and Hu, Wenmiao and Song, Xuemeng and Kruppa, Hannes and Ng, See-Kiong and Zimmermann, Roger. *IEEE Transactions on Circuits and Systems for Video Technology 2025*

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
    -   Sauerbeck, Florian and Kulmer, Dominik and Pielmeier, Markus and Leitenstern, Maximilian and Wei{\ss}, Christoph and Betz, Johannes. *2023 IEEE SENSORS*

-   [FlexMap Fusion] FlexMap Fusion: Georeferencing and Automated Conflation of HD Maps with OpenStreetMap.
    [[pdf]](https://arxiv.org/pdf/2404.11155.pdf)
    [[code]](https://github.com/TUMFTM/FlexMap_Fusion)
    -   Leitenstern, Maximilian and Sauerbeck, Florian and Kulmer, Dominik and Betz, Johannes. *arXiv 2024*

-   An Indoor-Outdoor Layered HD Map Construction for Unmanned Ground Vehicles.
    [[pdf]](https://isprs-annals.copernicus.org/articles/X-4-2024/117/2024/isprs-annals-X-4-2024-117-2024.pdf)
    -   Gao, Huimin and Zhong, Ruofei and Qi, Xingyu and Xie, Donghai and Sun, Zhenxing and Sun, Haili. *2024 ISPRS Annals*

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

-   [HDMapGen] HDMapGen: AHierarchical Graph Generative Model of High Definition Maps.
    [[pdf]](https://arxiv.org/pdf/2106.14880v1)
    -   Mi, Lu and Zhao, Hang and Nash, Charlie and Jin, Xiaohan and Gao, Jiyang and Sun, Chen and Schmid, Cordelia and Shavit, Nir and Chai, Yuning and Anguelov, Dragomir. *CVPR 2021*

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
