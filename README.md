# Single-Object Visual Tracking: A Paper List

*A complete paper list of Single-Object Visual Tracking Algorithms, Surveys and Benchmarks of recent years. Different from existing paper list, this project doesn't simply category the papers by publishment, but from a tracking process perspective. Main Contributions and Novelties of each tracker paper is carefully studied, forming our taxonomy criteria. The investigation covers top conferences as AAAI, CVPR, ECCV, ICCV, ICML, IJCAI, NIPS and top journals as IJCV, IP, PAMI. Note that the list is not bijective, namely a single paper may appear in diverse contents.* 

## 1 Popular Benchmarks

- **A Refined Note for 7 Benchmarks**, Yuzhe Shi. [[project](https://github.com/YuzheSHI/Benchmarks-for-Single-Object-Visual-Tracking)]
- **OTB2015** Yi Wu, Jongwoo Lim, and Ming-Hsuan Yang, "Object Tracking Benchmark", PAMI, 2015. [[paper](https://ieeexplore.ieee.org/document/7001050)] [[bib](https://dblp.uni-trier.de/rec/bibtex/journals/pami/WuLY15)] [[project](http://cvlab.hanyang.ac.kr/tracker_benchmark/datasets.html)]
- **UAV123** Matthias Mueller, Neil Smith, and Bernard Ghanem, "A Benchmark and Simulator for UAV Tracking", ECCV, 2016. [[paper](https://link.springer.com/chapter/10.1007%2F978-3-319-46448-0_27)] [[bib](https://dblp.uni-trier.de/rec/bibtex/conf/eccv/MuellerSG16)] [[project](https://uav123.org/)]
- **NFS** Hamed Kiani Galoogahi, Ashton Fagg, Chen Huang, Deva Ramanan and Simon Lucey, "Need for Speed: A Benchmark for Higher Frame Rate Object Tracking", ICCV, 2017.
- **TrackingNet** Matthias Müller, Adel Bibi, Silvio Giancola, Salman Al-Subaihi, Bernard Ghanem, "TrackingNet: A Large-Scale Dataset and Benchmark for Object Tracking in the Wild", ECCV, 2018.
- **LaSOT** Heng Fan, Liting Lin, Fan Yang, Peng Chu, Ge Deng, Sijia Yu, Yong Xu, Chunyuan Liao, Haibin Ling, "LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking", CVPR, 2019.
- **GOT-10k** Lianghua Huang, Xin Zhao and Kaiqi Huang, "GOT-10k: A Large High-Diversity Benchmark for
  Generic Object Tracking in the Wild", PAMI, 2019.
- **VOT** Matej Kristan, Jiri Matas, Aleš Leonardis, Tomáš Vojı́ř, Roman Pflugfelder, Gustavo Fernández, Georg Nebehay, Fatih Porikli and Luka Čehovin, "A Novel Performance Evaluation Methodology
  for Single-Target Trackers", PAMI, 2016. [[paper](https://ieeexplore.ieee.org/document/7379002)] [[bib](https://dblp.uni-trier.de/rec/bibtex/journals/pami/KristanMLVPFNPC16)] [[challenge](http://votchallenge.net/)] [[project](https://github.com/votchallenge/vot-toolkit)] [[publications](https://prints.vicos.si/publications/groups/vot/)]

## 2 Reviews and Survey Papers

- Alper Yilmaz, Omar Javed, Mubarak Shah, "Object Tracking: A Survey", CSUR, 2006.
- Xi Li, Weiming Hu, Chunhua Shen, Zhongfei Zhang, Anthony Dick, Anton van den Hengel, "A Survey of Appearance Models in Visual Object Tracking", ACM IST, 2013.
- Seyed Mojtaba Marvasti-Zadeh, Li Cheng, Hossein Ghanei-Yakhdan, and Shohreh Kasaei, "Deep Learning for Visual Tracking: A Comprehensive Survey", IEEE Access, 2019.
- MUSTANSAR FIAZ, ARIF MAHMOOD, SAJID JAVED, SOON KI JUNG, "Handcrafted and Deep Trackers: Recent Visual Object Tracking Approaches and Trends", CSUR, 2019.
- Shaoze You, Hua Zhu, Menggang Li, Yutan Li, "A Review of Visual Trackers and Analysis of its
  Application to Mobile Robot", CoRR/abs, 2019.
- RUI YAO, GUOSHENG LIN, SHIXIONG XIA, JIAQI ZHAO and YONG ZHOU, "Video Object Segmentation and Tracking: A Survey", CoRR/abs, 2019.

## 3 Recent Trackers

### 3.1 Data Augmentation 

#### 3.1.1 Data Generation

- **SINT++** Xiao Wang, Chenglong Li, Bin Luo, Jin Tang, "SINT++: Robust Visual Tracking via Adversarial Positive Instance Generation", CVPR, 2018. [[paper](http://openaccess.thecvf.com/content_cvpr_2018/html/Wang_SINT_Robust_Visual_CVPR_2018_paper.html)] [[bib](https://dblp.uni-trier.de/rec/bibtex/conf/cvpr/WangL0T18)] 
- **VITAL** Yibing Song, Chao Ma, Xiaohe Wu, Lijun Gong, Linchao Bao, Wangmeng Zuo, Chunhua Shen, Rynson W.H. Lau and Ming-Hsuan Yang, "VITAL: VIsual Tracking via Adversarial Learning", CVPR, 2018. [[paper](http://openaccess.thecvf.com/content_cvpr_2018/html/Song_VITAL_VIsual_Tracking_CVPR_2018_paper.html)] [[bib](https://dblp.uni-trier.de/rec/bibtex/conf/cvpr/Song0WGBZSL018)] [[code](https://github.com/ybsong00/Vital_release)]
- **PAT** Rey Reza Wiyatno, Anqi Xu, "Physical Adversarial Textures That Fool Visual Object Tracking", ICCV, 2019.

#### 3.1.2 Offline Training

- **SINT** Ran Tao, Efstratios Gavves, Arnold W.M. Smeulders, "Siamese Instance Search for Tracking", CVPR, 2016.
- **STCT** Lijun Wang, Wanli Ouyang, Xiaogang Wang and Huchuan Lu, "STCT: Sequentially Training Convolutional Networks for Visual Tracking", CVPR, 2016.
- **GOTURN** David Held, Sebastian Thrun, Silvio Savarese, "Learning to Track at 100 FPS with Deep
  Regression Networks", ECCV, 2016.
- **SiameseFC** Luca Bertinetto, Jack Valmadre, João F. Henriques, Andrea Vedaldi, Philip H. S. Torr, "Fully-Convolutional Siamese Networks for Object Tracking", ECCV, 2016.
- **CFNet** Luca Bertinetto, Jack Valmadre, João F. Henriques, Andrea Vedaldi, Philip H. S. Torr, "End-to-end representation learning for Correlation Filter based tracking", CVPR, 2017.
- **UCT** Zheng Zhu, Guan Huang, Wei Zou, Dalong Du, Chang Huang, "UCT: Learning Unified Convolutional Networks for Real-time Visual Tracking", ICCV, 2017.
- **DSLT** Xiankai Lu, Chao Ma, Bingbing Ni, Xiaokang Yang, Ian Reid and Ming-Hsuan Yang, "Deep Regression Tracking with Shrinkage Loss", ECCV, 2018.
- **Meta-Tracker** Eunbyung Park, Alexander C. Berg, "Meta-Tracker: Fast and Robust Online
  Adaptation for Visual Object Trackers", ECCV, 2018.
- **RTINet** Yingjie Yao, Xiaohe Wu, Lei Zhang, Shiguang Shan and Wangmeng Zuo, "Joint Representation and Truncated Inference Learning for Correlation Filter based Tracking", ECCV, 2018.
- **DATRL** Shi Pu, Yibing Song, Chao Ma, Honggang Zhang, Ming-Hsuan Yang, "Deep Attentive Tracking via Reciprocative Learning", NIPS, 2018.
- **UDT** Ning Wang, Yibing Song, Chao Ma, Wengang Zhou, Wei Liu, Houqiang Li, "Unsupervised Deep Tracking", CVPR, 2019.
- **GradNet** Peixia Li, Boyu Chen, Wanli Ouyang, Dong Wang, Xiaoyun Yang, Huchuan Lu, "GradNet: Gradient-Guided Network for Visual Object Tracking", ICCV, 2019.
- **SILOT** Eric Crawford, Joelle Pineau, "Exploiting Spatial Invariance for Scalable Unsupervised Object Tracking", AAAI, 2020.

###### Reinforcement Learning Based Method:

- **ADNet** Sangdoo Yun, Jongwon Choi, Youngjoon Yoo, Kimin Yun and Jin Young Choi, "Action-Decision Networks for Visual Tracking with Deep Reinforcement Learning", CVPR, 2017.
- **EAST** Chen Huang, Simon Lucey, Deva Ramanan, "Learning Policies for Adaptive Tracking with Deep Feature Cascades", ICCV, 2017.
- **p-tracker** James Supančič III, Deva Ramanan, "Tracking as Online Decision-Making: Learning a Policy from Streaming Videos with Reinforcement Learning", ICCV, 2017.
- **HP** Xingping Dong, Jianbing Shen, Wenguan Wang, Yu Liu, Ling Shao, and Fatih Porikli, "Hyperparameter Optimization for Tracking with Continuous Deep Q-Learning", CVPR, 2018.
- **ACT** Boyu Chen, Dong Wang, Peixia Li, Shuang Wang and Huchuan Lu, "Real-time ‘Actor-Critic’ Tracking", ECCV, 2018.
- **DRL-IS** Liangliang Ren, Xin Yuan, Jiwen Lu, Ming Yang, Jie Zhou, "Deep Reinforcement Learning with Iterative Shift for Visual Tracking", ECCV, 2018.
- **ConvNet-LSTM** Wenhan Luo, Peng Sun, Fangwei Zhong, Wei Liu, Tong Zhang, Yizhou Wang, "End-to-end Active Object Tracking via Reinforcement Learning", ICML, 2018.
- **EDCF-EDSiam** Qiang Wang, Mengdan Zhang, Junliang Xing, Jin Gao, Weiming Hu, Steve Maybank, "Do not Lose the Details: Reinforced Representation Learning for High Performance Visual Tracking", IJCAI, 2018.
- **UJDPT** Xiaobai Liu, Donovan Lo, Chau Thuan, "Unsupervised Learning based Jump-Diffusion Process for Object Tracking in Video Surveillance", IJCAI, 2018.
- **JDPT** Xiaobai Liu, Qian Xu, Thuan Chau, Yadong Mu, Lei Zhu, Shuicheng Yan, "Revisiting Jump-Diffusion Process for Visual Tracking: A Reinforcement Learning Approach", CSVT, 2018.

### 3.2 Online Tracking

#### 3.2.1 Model Learning

- **RCF** Yao Sui, Ziming Zhang, Guanghui Wang, Yafei Tang, Li Zhang, "Real-Time Visual Tracking: Promoting the Robustness of Correlation Filter Learning", ECCV, 2016.
- **LearNet** Luca Bertinetto, Jack Valmadre, João F. Henriques, Andrea Vedaldi, Philip H. S. Torr, "Learning feed-forward one-shot learners", NIPS, 2016.
- **CFNN** Yang Li, Zhan Xu and Jianke Zhu, "CFNN: Correlation Filter Neural Network for Visual Object Tracking", IJCAI, 2017.
- **MKCFup** Ming Tang, Bin Yu, Fan Zhang and Jinqiao Wang, "High-speed Tracking with Multi-kernel Correlation Filters", CVPR, 2018.
- **DiMP** Goutam Bhat, Martin Danelljan, Luc Van Gool, Radu Timofte, "Learning Discriminative Model Prediction for Tracking", ICCV, 2019.
- **RT-MLT** Ilchae Jung, Kihyun You, Hyeonwoo Noh, Minsu Cho, Bohyung Han, "Real-Time Object Tracking via Meta-Learning: Efficient Model Adaptation and One-Shot Channel Pruning", AAAI, 2020.

#### 3.2.2 Input: Target Representation

- **HDT** Yuankai Qi, Shengping Zhang, Lei Qin, Hongxun Yao, Qingming Huang, Jongwoo Lim, Ming-Hsuan Yang, "Hedged Deep Tracking", CVPR, 2016.
- **SCT** Jongwon Choi, Hyung Jin Chang, Jiyeoup Jeong, Yiannis Demiris, Jin Young Choi, "Visual Tracking Using Attention-Modulated Disintegration and Integration", CVPR, 2016.
- **Staple** Luca Bertinetto, Jack Valmadre, Stuart Golodetz, Ondrej Miksik, Philip H.S. Torr, "Staple: Complementary Learners for Real-Time Tracking", CVPR, 2016.
- **BranchOut** Bohyung Han, Jack Sim, Hartwig Adam, "BranchOut: Regularization for Online Ensemble Tracking with Convolutional Neural Networks", CVPR, 2017.
- **SANet** Heng Fan, Haibin Ling, "SANet: Structure-Aware Network for Visual Tracking", CVPR, 2017.
- **CFWCR** Zhiqun He, Yingruo Fan, Junfei Zhuang, Yuan Dong, HongLiang Bai, "Correlation Filters with Weighted Convolution Responses", ICCV, 2017.
- **RFL** Tianyu Yang, Antoni B. Chan, "Recurrent Filter Learning for Visual Tracking", ICCV, 2017.
- **DNT** Zhizhen Chi, Hongyang Li, Huchuan Lu and Ming-Hsuan Yang, "Dual Deep Network for Visual Tracking", IP, 2017.
- **MCCT** Ning Wang, Wengang Zhou, Qi Tian, Richang Hong, Meng Wang, Houqiang Li, "Multi-Cue Correlation Filters for Robust Visual Tracking", CVPR, 2018.
- **SA-Siam** Anfeng He, Chong Luo, Xinmei Tian, and Wenjun Zeng, "A Twofold Siamese Network for Real-Time Object Tracking", CVPR, 2018.
- **TRACA** Jongwon Choi, Hyung Jin Chang, Tobias Fischer, Sangdoo Yun, "Context-aware Deep Feature Compression for High-speed Visual Tracking", CVPR, 2018.
- **Siam-tri** Xingping Dong and Jianbing Shen, "Triplet Loss in Siamese Network for Object Tracking", ECCV, 2018.
- **UPDT** Goutam Bhat, Joakim Johnander, Martin Danelljan, Fahad Shahbaz Khan and Michael Felsberg, "Unveiling the Power of Deep Tracking", ECCV, 2018.
- **CFWFI** Aishi Li, Ming Yang, Wanqi Yang, "Feature Integration with Adaptive Importance Maps for Visual Tracking", IJCAI, 2018.
- **EDCF-EDSiam** Qiang Wang, Mengdan Zhang, Junliang Xing, Jin Gao, Weiming Hu, Steve Maybank, "Do not Lose the Details: Reinforced Representation Learning for High Performance Visual Tracking", IJCAI, 2018.
- **LASRT** Yuankai Qi, Shengping Zhang, Weigang Zhang, Li Su, Qingming Huang, Ming-Hsuan Yang, "Learning Attribute-Specific Representations for Visual Tracking", AAAI, 2019.
- **CIR (SiamDW)** Zhipeng Zhang, Houwen Peng, Qiang Wang, Bing Li, "Deeper and Wider Siamese Networks for Real-Time Visual Tracking", CVPR, 2019.
- **C-RPN** Heng Fan, Haibin Ling, "Siamese Cascaded Region Proposal Networks for Real-Time Visual Tracking", CVPR, 2019.
-  **OTR** Uğur Kart, Alan Lukežič, Matej Kristan, Joni-Kristian Kämäräinen and Jiřı́ Matas, "Object Tracking by Reconstruction with View-Specific Discriminative Correlation Filters", CVPR, 2019.
- **SiamRPN++** Bo Li, Wei Wu, Qiang Wang, Fangyi Zhang, Junliang Xing, Junjie Yan, "SiamRPN++: Evolution of Siamese Visual Tracking with Very Deep Networks", CVPR, 2019.
- **GFS-DCF** Tianyang Xu, Zhen-Hua Feng, Xiao-Jun Wu, Josef Kittler, "Joint Group Feature Selection and Discriminative Filter Learning for Robust Visual Object Tracking", ICCV, 2019.
- **MLT** Janghoon Choi, Junseok Kwon, Kyoung Mu Lee, "Deep Meta Learning for Real-Time Target-Aware Visual Tracking", ICCV, 2019.

#### 3.2.3 Input: Spatial Information

- **EBT** Gao Zhu, Fatih Porikli, and Hongdong Li, "Beyond Local Search: Tracking Objects Everywhere with Instance-Specific Proposals", CVPR, 2016.
- **C-COT** Martin Danelljan, Andreas Robinson, Fahad Shahbaz Khan, Michael Felsberg, "Beyond Correlation Filters: Learning Continuous Convolution Operators for Visual Tracking", ECCV, 2016.
- **CFAT** Adel Bibi, Matthias Mueller, Bernard Ghanem, "Target Reponse Adaption for Correlation Filter Tracking", ECCV, 2016.
- **LGCF** Heng Fan, Jinhai Xiang, "Robust Visual Tracking via Local-Global Correlation Filter", AAAI, 2017.
- **CACF** Matthias Mueller, Neil Smith, Bernard Ghanem, "Context-Aware Correlation Filter Tracking", CVPR, 2017.
- **CSR-DCF** Alan Lukežič, Tomáš Vojı́ř, Luka Čehovin Zajc, Jiřı́ Matas and Matej Kristan, "Discriminative Correlation Filter with Channel and Spatial Reliability", CVPR, 2017.

- **BACF** Hamed Kiani Galoogahi, Ashton Fagg and Simon Lucey, "Learning Background-Aware Correlation Filters for Visual Tracking", ICCV, 2017.
- **DRT** Junyu Gao, Tianzhu Zhang, Xiaoshan Yang and Changsheng Xu, "Deep Relative Tracking", IP, 2017.
- **HART** Adam R. Kosiorek, Alex Bewley, Ingmar Posner, "Hierarchical Attentive Recurrent Tracking", NIPS, 2017.
- **DRT** Chong Sun, Dong Wang, Huchuan Lu, Ming-Hsuan Yang, "Correlation Tracking via Joint Discrimination and Reliability Learning", CVPR, 2018.
- **LSART** Chong Sun, Dong Wang, Huchuan Lu, Ming-Hsuan Yang, "Learning Spatial-Aware Regressions for Visual Tracking", CVPR, 2018.
- **RASNet** Qiang Wang, Zhu Teng, Junliang Xing, Jin Gao, Weiming Hu, Stephen Maybank, "Learning Attentions: Residual Attentional Siamese Network for High Performance Online Visual Tracking", CVPR, 2018.
- **STRCF** Feng Li, Cheng Tian, Wangmeng Zuo, Lei Zhang, and Ming-Hsuan Yang, "Learning Spatial-Temporal Regularized Correlation Filters for Visual Tracking", CVPR, 2018.
- **DaSiamRPN** Zheng Zhu, Qiang Wang, Bo Li, Wei Wu, Junjie Yan and Weiming Hu, "Distractor-aware Siamese Networks for Visual Object Tracking", ECCV, 2018.
- **SACF** Mengdan Zhang, Qiang Wang, Junliang Xing, Jin Gao, Peixi Peng, "Visual Tracking via Spatially Aligned Correlation Filters Network", ECCV, 2018.
- **StructSiam** Yunhua Zhang, Lijun Wang, Jinqing Qi, Dong Wang, Mengyang Feng and Huchuan Lu, "Structured Siamese Network for Real-Time Visual Tracking", ECCV, 2018.
- **DATRL** Shi Pu, Yibing Song, Chao Ma, Honggang Zhang, Ming-Hsuan Yang, "Deep Attentive Tracking via Reciprocative Learning", NIPS, 2018.
- **RSST** Tianzhu Zhang, Changsheng Xu, and Ming-Hsuan Yang, "Robust Structural Sparse Tracking", PAMI, 2018.
- **ASRCF** Kenan Dai, Dong Wang, Huchuan Lu, Chong Sun, Jianhua Li, "Visual Tracking via Adaptive Spatially-Regularized Correlation Filters", CVPR, 2019.
- **GCT** Junyu Gao, Tianzhu Zhang and Changsheng Xu, "Graph Convolutional Tracking", CVPR, 2019.
- **RPCF** Yuxuan Sun, Chong Sun, Dong Wang, You He, Huchuan Lu, "ROI Pooled Correlation Filters for Visual Tracking", CVPR, 2019.
- **TADT** Xin Li, Chao Ma, Baoyuan Wu, Zhenyu He, Ming-Hsuan Yang, "Target-Aware Deep Tracking", CVPR, 2019.
- **ARCF** Ziyuan Huang, Changhong Fu, Yiming Li, Fuling Lin and Peng Lu, "Learning Aberrance Repressed Correlation Filters for Real-Time UAV Tracking", ICCV, 2019.
- **GFS-DCF** Tianyang Xu, Zhen-Hua Feng, Xiao-Jun Wu, Josef Kittler, "Joint Group Feature Selection and Discriminative Filter Learning for Robust Visual Object Tracking", ICCV, 2019.
- **SPST** Qintao Hu, Lijun Zhou, Xiaoxiao Wang, Yao Mao, Jianlin Zhang, Qixiang Ye, "SPSTracker: Sub-Peak Suppression of Response Map for Robust Object Tracking", AAAI, 2020.

#### 3.2.4 Input: Temporal Information

- **AMCT** Donghun Yeo, Jeany Son, Bohyung Han, Joon Hee Han, "Superpixel-based Tracking-by-Segmentation using Markov Chains", CVPR, 2017.
- **DSiam** Qing Guo, Wei Feng, Ce Zhou, Rui Huang, Liang Wan, Song Wang, "Learning Dynamic Siamese Network for Visual Object Tracking", ICCV, 2017.
- **TSN** Zhu Teng, Junliang Xing, Qiang Wang, Congyan Lang, Songhe Feng, Yi Jin, "Robust Object Tracking based on Temporal and Spatial Deep Networks", ICCV, 2017.
- **FlowTrack** Zheng Zhu, Wei Wu, Wei Zou, Junjie Yan, "End-to-end Flow Correlation Tracking with Spatial-temporal Attention", CVPR, 2018.
- **RASNet** Qiang Wang, Zhu Teng, Junliang Xing, Jin Gao, Weiming Hu, Stephen Maybank, "Learning Attentions: Residual Attentional Siamese Network for High Performance Online Visual Tracking", CVPR, 2018. 
- **STRCF** Feng Li, Cheng Tian, Wangmeng Zuo, Lei Zhang, and Ming-Hsuan Yang, "Learning Spatial-Temporal Regularized Correlation Filters for Visual Tracking", CVPR, 2018.
- **MemTrack** Tianyu Yang and Antoni B. Chan, "Learning Dynamic Memory Networks for Object
  Tracking", ECCV, 2018.
- **LCT+** Chao Ma, Jia-Bin Huang, Xiaokang Yang, Ming-Hsuan Yang, "Adaptive Correlation Filters with Long-Term and Short-Term Memory for Object Tracking", IJCV, 2018.
- **GCT** Junyu Gao, Tianzhu Zhang and Changsheng Xu, "Graph Convolutional Tracking", CVPR, 2019.
- **GFS-DCF** Tianyang Xu, Zhen-Hua Feng, Xiao-Jun Wu, Josef Kittler, "Joint Group Feature Selection and Discriminative Filter Learning for Robust Visual Object Tracking", ICCV, 2019.
- **GradNet** Peixia Li, Boyu Chen, Wanli Ouyang, Dong Wang, Xiaoyun Yang, Huchuan Lu, "GradNet: Gradient-Guided Network for Visual Object Tracking", ICCV, 2019.
- **DSTN** Zhu Teng, Junliang Xing, Qiang Wang, Baopeng Zhang and Jianping Fan, "Deep Spatial and Temporal Network for Robust Visual Object Tracking", IP, 2020.

#### 3.2.5 Output: Localization

- **MDNet** Hyeonseob Nam, Bohyung Han, "Learning Multi-Domain Convolutional Neural Networks for Visual Tracking", CVPR, 2016.
- **TrackingCompletion** Yao Sui, Guanghui Wang, Yafei Tang, Li Zhang, "Tracking Completion", ECCV, 2016.
- **AFCN** Jongwon Choi, Hyung Jin Chang,Sangdoo Yun, Tobias Fischer, Yiannis Demiris, Jin Young Choi, "Attentional Correlation Filter Network for Adaptive Visual Tracking", CVPR, 2017.
- **LMCF** Mengmeng Wang, Yong Liu, Zeyi Huang, "Large Margin Object Tracking with Circulant Feature Maps", CVPR, 2017.
- **MCPF** Tianzhu Zhang, Changsheng Xu, Ming-Hsuan Yang, "Multi-task Correlation Particle Filter for Robust Object Tracking", CVPR, 2017.
- **RaF** Le Zhang, Jagannadan Varadarajan, Ponnuthurai Nagaratnam Suganthan, Narendra Ahuja and Pierre Moulin, "Robust Visual Tracking Using Oblique Random Forests", CVPR, 2017.
- **CREST** Yibing Song, Chao Ma, Lijun Gong, Jiawei Zhang, Rynson W.H. Lau and Ming-Hsuan Yang, "CREST: Convolutional Residual Learning for Visual Tracking", ICCV, 2017.
- **DSiam** Qing Guo, Wei Feng, Ce Zhou, Rui Huang, Liang Wan, Song Wang, "Learning Dynamic Siamese Network for Visual Object Tracking", ICCV, 2017.
- **PTAV** Heng Fan, Haibin Ling, "Parallel Tracking and Verifying: A Framework for Real-Time and High
  Accuracy Visual Tracking", ICCV, 2017.
- **SP-KCF** Xin Sun, Ngai-Man Cheung, Hongxun Yao, Yiluan Guo, "Non-Rigid Object Tracking via Deformable Patches using Shape-Preserved KCF and Level Sets", ICCV, 2017.
- **MDSLT** Kunpeng, Yu Kong and Yun Fu, "Multi-Stream Deep Similarity Learning Networks for Visual Tracking", IJCAI, 2017.
- **AOGT** Tianfu Wu, Yang Lu and Song-Chun Zhu, "Online Object Tracking, Learning and Parsing
  with And-Or Graphs", PAMI, 2017.
- **DEDT** Kourosh Meshgi, Shigeyuki Oba, Shin Ishii, "Efficient Diverse Ensemble for Discriminative Co-Tracking", CVPR, 2018.
- **SiamRPN** Bo Li, Junjie Yan, Wei Wu, Zheng Zhu, Xiaolin Hu, "High Performance Visual Tracking with Siamese Region Proposal Network", CVPR, 2018.
- **RT-MDNet** Ilchae Jung, Jeany Son, Mooyeol Baek and Bohyung Han, "Real-Time MDNet", ECCV, 2018.
- **GPRT** Linyu Zheng, Ming Tang and Jinqiao Wang, "Learning Robust Gaussian Process Regression for Visual Tracking", IJCAI, 2018.
- **LDES** Yang Li, Jianke Zhu, Steven C.H. Hoi, Wenjie Song, Zhefeng Wang, Hantang Liu, "Robust Estimation of Similarity Transformation for Visual Object Tracking", AAAI, 2019.
- **SPM** Guangting Wang, Chong Luo, Zhiwei Xiong, Wenjun Zeng, "SPM-Tracker: Series-Parallel Matching for Real-Time Visual Object Tracking", CVPR, 2019.
- **Bridge** Lianghua Huang, Xin Zhao, Kaiqi Huang, "Bridging the Gap Between Detection and Tracking: A Unified Approach", ICCV, 2019.
- **SPLT** Bin Yan, Haojie Zhao, Dong Wang, Huchuan Lu and Xiaoyun Yang, "‘Skimming-Perusal’ Tracking: A Framework for Real-Time and Robust Long-term Tracking", ICCV, 2019.
- **SiamFC++** Yinda Xu, Zeyu Wang, Zuoxin Li, Ye Yuan, Gang Yu, "SiamFC++: Towards Robust and Accurate Visual Tracking with Target Estimation Guidelines", AAAI, 2019.

#### 3.2.6 Output: Appearance

- **IBCCF** Feng Li, Yingjie Yao, Peihua Li, David Zhang, Wangmeng Zuo, and Ming-Hsuan Yang, "Integrating Boundary and Center Correlation Filters for Visual Tracking with Aspect Ratio Variation", ICCV Workshops, 2017.
- **PWSeg** Tobias Böttger, Patrick Follmann, "The Benefits of Evaluating Tracker Performance using Pixel-wise Segmentations", ICCV Workshops, 2017.
- **SiamRPN** Bo Li, Junjie Yan, Wei Wu, Zheng Zhu, Xiaolin Hu, "High Performance Visual Tracking with Siamese Region Proposal Network", CVPR, 2018.
- **LDES** Yang Li, Jianke Zhu, Steven C.H. Hoi, Wenjie Song, Zhefeng Wang, Hantang Liu, "Robust Estimation of Similarity Transformation for Visual Object Tracking", AAAI, 2019.
- **ATOM** Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg, "ATOM: Accurate Tracking by Overlap Maximization", CVPR, 2019.
- **SiamMask** Qiang Wang, Li Zhang, Luca Bertinetto, Weiming Hu, Philip H.S. Torr, "Fast Online Object Tracking and Segmentation: A Unifying Approach", CVPR, 2019.

#### 3.2.7 Updating: Sample

- **SRDCFdecon** Martin Danelljan, Gustav Häger, Fahad Shahbaz Khan, Michael Felsberg, "Adaptive Decontamination of the Training Set: A Unified Formulation for Discriminative Visual Tracking", CVPR, 2016.

#### 3.2.8 Updating: Model

- **DLSSVM** Jifeng Ning, Jimei Yang, Shaojie Jiang, Lei Zhang and Ming-Hsuan Yang, "Object Tracking via Dual Linear Structured SVM and Explicit Feature Map", CVPR, 2016.
- **ECO** Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg, "ECO: Efficient Convolution Operators for Tracking", CVPR, 2017.
- **UCT** Zheng Zhu, Guan Huang, Wei Zou, Dalong Du, Chang Huang, "UCT: Learning Unified Convolutional Networks for Real-time Visual Tracking", ICCV, 2017.
- **Re^2EMA** Jianglei Huang, Wengang Zhou, "Re^2EMA: Regularized and Reinitialized Exponential
  Moving Average for Target Model Update in Object Tracking", AAAI, 2019.
- **Bridge** Lianghua Huang, Xin Zhao, Kaiqi Huang, "Bridging the Gap Between Detection and Tracking: A Unified Approach", ICCV, 2019.
- **UpdateNet** Lichao Zhang, Abel Gonzalez-Garcia, Joost van de Weijer, Martin Danelljan, Fahad Shahbaz Khan, "Learning the Model Update for Siamese Trackers", ICCV, 2019.

