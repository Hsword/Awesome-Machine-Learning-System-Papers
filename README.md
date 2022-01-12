# Awesome-Machine-Learning-System-Papers

**Awesome-Machine-Learning-System-Papers** is a curated list of *machine learning system* papers in recent years (since 2017). **Star** this repository, and then you can keep abreast of the latest developments of this booming research field. 

Thanks to all the people who made contributions to this project. We strongly encourage the researchers to make **pull request** and help the others in this community!

<!-- omit in toc -->
## Conference

Currently, the listed papers are collected from the following conferences:


| Conferences | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2022 | 2023 | 2024 | 2025 |
|-------------|------|------|------|------|------|------|------|------|------|------|
| [OSDI](#osdi)      |   3   |   -   |   4   |   -   |   11   |   8   |      |      |      |      |
| [SOSP](#sosp)      |   -   |   1   |   -   |   10   | - |   3   |      |      |      |      |
| [SIGMOD](#sigmod)  |   2   |   4   |   3   |   4   |   8   |   16   |      |      |      |      |
| [ASPLOS](#asplos)  |   -   |   3   |   3   |   9   |   4   |    5   |      |      |      |      |
| [ATC](#atc)        |   -   |   2   |   3   |   5   |   8   |   10   |      |      |      |      |
| [PPoPP](#ppopp)    |   -   |   3   |   5   |   2   |   1   |   17   |      |      |      |      |
| [HPCA](#hpca)    |   -   |   3   |   4   |   4   |   1   | 12 |      |      |      |      |
| [MICRO](#micro)    |   -   |   4   |   6   |   9   | 13 | 4 |      |      |      |      |
| [SC](#sc)   |    5  |   -   |   9   |   6   | 14 | 15 |      |      |      |      |
| [NSDI](#nsdi)    |   -   |    3  |   -   |   3   | - | 4 |      |      |      |      |
| [ISCA](#isca)    |   -   |   6   |   11   |   7   | 13 | 18 |      |      |      |      |

Some conferences to be added in the future:

- [SysML](#sysml)
- [NeurIPS](#neurips)
- [ICML](#icml)
- [VLDB](#vldb)
- [SIGCOMM](#sigcomm)
- [ICDE](#icde)
- [SIGKDD](#sigkdd)
- [WWW](#www)
- [EuroSys](#eurosys)
- [SoCC](#socc)
- [INFOCOM](#infocom)
- [SIGIR](#sigir)

## Category Keywords

- ![](https://img.shields.io/badge/Training-red) Model training
- ![](https://img.shields.io/badge/Inference-blue) Model inference and serving
- ![](https://img.shields.io/badge/Hardware-green) Hardware-efficient ML methods
- ![](https://img.shields.io/badge/Security-85144b) Privacy and security for ML applications
- ![](https://img.shields.io/badge/Debugging-orange) Testing, debugging, and monitoring of ML applications
- ![](https://img.shields.io/badge/Data-ff69b4) Data preparation, feature selection, and feature extraction
- ![](https://img.shields.io/badge/Parallel-blueviolet) Distributed and parallel learning algorithms
- ![](https://img.shields.io/badge/Compiler-206777) ML compilers and runtime
- ![](https://img.shields.io/badge/Resource-cc9e08) Resource scheduling for ML applications
- ![](https://img.shields.io/badge/Graph-cc231e) Graph learning systems
- ![](https://img.shields.io/badge/Others-gray) ...

<!--
- Fairness, interpretability and explainability for ML applications
- ML programming models and abstractions
- Programming languages for machine learning
- Visualization of data, models, and predictions
-->


## Papers

### OSDI 

#### 2016

1. **TensorFlow: A System for Large-Scale Machine Learning** OSDI 2016 ![](https://img.shields.io/badge/Training-red)

   *Martín Abadi, Paul Barham, Jianmin Chen, Zhifeng Chen, Andy Davis, Jeffrey Dean, Matthieu Devin, Sanjay Ghemawat, Geoffrey Irving, Michael Isard, Manjunath Kudlur, Josh Levenberg, Rajat Monga, Sherry Moore, Derek Gordon Murray, Benoit Steiner, Paul A. Tucker, Vijay Vasudevan, Pete Warden, Martin Wicke, Yuan Yu, Xiaoqiang Zheng*
   
   Code: [https://github.com/tensorflow/tensorflow](https://github.com/tensorflow/tensorflow)

2. **Exploring the Hidden Dimension in Graph Processing** OSDI 2016 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Graph-cc231e)

	*Mingxing Zhang, Yongwei Wu, Kang Chen, Xuehai Qian, Xue Li, Weimin Zheng*

3. **Gemini: A Computation-Centric Distributed Graph Processing System** OSDI 2016 ![](https://img.shields.io/badge/Graph-cc231e)

	*Xiaowei Zhu, Wenguang Chen, Weimin Zheng, Xiaosong Ma*
	
	Code: [https://github.com/thu-pacman/GeminiGraph](https://github.com/thu-pacman/GeminiGraph)


#### 2018

1. **Ray: A Distributed Framework for Emerging AI Applications** OSDI 2018 ![](https://img.shields.io/badge/Training-red)

	*Philipp Moritz, Robert Nishihara, Stephanie Wang, Alexey Tumanov, Richard Liaw, Eric Liang, Melih Elibol, Zongheng Yang, William Paul, Michael I. Jordan, Ion Stoica*
	
	Code: [https://github.com/ray-project/ray](https://github.com/ray-project/ray)
	
2. **TVM: An Automated End-to-End Optimizing Compiler for Deep Learning** OSDI 2018 ![](https://img.shields.io/badge/Compiler-206777)

	*Tianqi Chen, Thierry Moreau, Ziheng Jiang, Lianmin Zheng, Eddie Q. Yan, Haichen Shen, Meghan Cowan, Leyuan Wang, Yuwei Hu, Luis Ceze, Carlos Guestrin, Arvind Krishnamurthy*
	
	Code: [https://github.com/apache/tvm](https://github.com/apache/tvm)
	
3. **Gandiva: Introspective Cluster Scheduling for Deep Learning** OSDI 2018 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Wencong Xiao, Romil Bhardwaj, Ramachandran Ramjee, Muthian Sivathanu, Nipun Kwatra, Zhenhua Han, Pratyush Patel, Xuan Peng, Hanyu Zhao, Quanlu Zhang, Fan Yang, Lidong Zhou*
	
4. **PRETZEL: Opening the Black Box of Machine Learning Prediction Serving Systems** OSDI 2018 ![](https://img.shields.io/badge/Inference-blue)

	*Yunseong Lee, Alberto Scolari, Byung-Gon Chun, Marco Domenico Santambrogio, Markus Weimer, Matteo Interlandi*

#### 2020

1. **Serving DNNs like Clockwork: Performance Predictability from the Bottom Up** OSDI 2020 ![](https://img.shields.io/badge/Inference-blue)

   *Arpan Gujarati, Reza Karimi, Safya Alzayat, Wei Hao, Antoine Kaufmann, Ymir Vigfusson, Jonathan Mace*

2. **A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters** OSDI 2020 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Hardware-green)

   *Yimin Jiang, Yibo Zhu, Chang Lan, Bairen Yi, Yong Cui, Chuanxiong Guo*

3. **Heterogeneity-Aware Cluster Scheduling Policies for Deep Learning Workloads** OSDI 2020 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Deepak Narayanan, Keshav Santhanam, Fiodar Kazhamiaka, Amar Phanishayee, Matei Zaharia*

4. **PipeSwitch: Fast Pipelined Context Switching for Deep Learning Applications** OSDI 2020 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Zhihao Bai, Zhen Zhang, Yibo Zhu, Xin Jin*

   Code: [https://github.com/netx-repo/PipeSwitch](https://github.com/netx-repo/PipeSwitch)

5. **HiveD: Sharing a GPU Cluster for Deep Learning with Guarantees** OSDI 2020 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Hanyu Zhao, Zhenhua Han, Zhi Yang, Quanlu Zhang, Fan Yang, Lidong Zhou, Mao Yang, Francis C. M. Lau, Yuqi Wang, Yifan Xiong, Bin Wang*

   Code: [https://github.com/microsoft/hivedscheduler](https://github.com/microsoft/hivedscheduler)

6. **AntMan: Dynamic Scaling on GPU Clusters for Deep Learning** OSDI 2020 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Wencong Xiao, Shiru Ren, Yong Li, Yang Zhang, Pengyang Hou, Zhi Li, Yihui Feng, Wei Lin, Yangqing Jia*

   Code: [https://github.com/alibaba/GPU-scheduler-for-deep-learning](https://github.com/alibaba/GPU-scheduler-for-deep-learning)
	
7. **Ansor: Generating High-Performance Tensor Programs for Deep Learning** OSDI 2020 ![](https://img.shields.io/badge/Compiler-206777)

	*Lianmin Zheng, Chengfan Jia, Minmin Sun, Zhao Wu, Cody Hao Yu, Ameer Haj-Ali, Yida Wang, Jun Yang, Danyang Zhuo, Koushik Sen, Joseph E. Gonzalez, Ion Stoica*


8. **Rammer: Enabling Holistic Deep Learning Compiler Optimizations with rTasks** OSDI 2020 ![](https://img.shields.io/badge/Compiler-206777)

	*Lingxiao Ma, Zhiqiang Xie, Zhi Yang, Jilong Xue, Youshan Miao, Wei Cui, Wenxiang Hu, Fan Yang, Lintao Zhang, Lidong Zhou*

	Code: [https://github.com/microsoft/nnfusion](https://github.com/microsoft/nnfusion)

9. **A Tensor Compiler for Unified Machine Learning Prediction Serving** OSDI 2020 ![](https://img.shields.io/badge/Inference-blue) ![](https://img.shields.io/badge/Compiler-206777)

	*Supun Nakandala, Karla Saur, Gyeong-In Yu, Konstantinos Karanasos, Carlo Curino, Markus Weimer, Matteo Interlandi*

10. **Retiarii: A Deep Learning Exploratory-Training Framework** OSDI 2020 ![](https://img.shields.io/badge/Training-red)

	*Quanlu Zhang, Zhenhua Han, Fan Yang, Yuge Zhang, Zhe Liu, Mao Yang, Lidong Zhou*

11. **KungFu: Making Training in Distributed Machine Learning Adaptive** ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)
	
	*Luo Mai, Guo Li, Marcel Wagenländer, Konstantinos Fertakis, Andrei-Octavian Brabete, Peter R. Pietzuch*

#### 2021

1. **Pollux: Co-adaptive Cluster Scheduling for Goodput-Optimized Deep Learning** OSDI 2021 ![](https://img.shields.io/badge/Resource-cc9e08)
	
	*Aurick Qiao, Sang Keun Choe, Suhas Jayaram Subramanya, Willie Neiswanger, Qirong Ho, Hao Zhang, Gregory R. Ganger, Eric P. Xing*

	Code: [https://github.com/petuum/adaptdl](https://github.com/petuum/adaptdl)

2. **Oort: Efficient Federated Learning via Guided Participant Selection** OSDI 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Fan Lai, Xiangfeng Zhu, Harsha V. Madhyastha, Mosharaf Chowdhury*

	Code: [https://github.com/SymbioticLab/Oort](https://github.com/SymbioticLab/Oort)

3. **PET: Optimizing Tensor Programs with Partially Equivalent Transformations and Automated Corrections** OSDI 2021 ![](https://img.shields.io/badge/Data-ff69b4)

	*Haojie Wang, Jidong Zhai, Mingyu Gao, Zixuan Ma, Shizhi Tang, Liyan Zheng, Yuanzhi Li, Kaiyuan Rong, Yuanyong Chen, Zhihao Jia*

	Code: [https://github.com/thu-pacman/PET](https://github.com/thu-pacman/PET)
	
4. **Privacy Budget Scheduling** OSDI 2021 ![](https://img.shields.io/badge/Security-85144b)

	*Tao Luo, Mingen Pan, Pierre Tholoniat, Asaf Cidon, Roxana Geambasu, Mathias Lécuyer*

5. **Dorylus: Affordable, Scalable, and Accurate GNN Training with Distributed CPU Servers and Serverless Threads** OSDI 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*John Thorpe, Yifan Qiao, Jonathan Eyolfson, Shen Teng, Guanzhou Hu, Zhihao Jia, Jinliang Wei, Keval Vora, Ravi Netravali, Miryung Kim, Guoqing Harry Xu*
	
	Code: [https://github.com/uclasystem/dorylus](https://github.com/uclasystem/dorylus)
	
6. **GNNAdvisor: An Adaptive and Efficient Runtime System for GNN Acceleration on GPUs** OSDI 2021 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Graph-cc231e)

	*Yuke Wang, Boyuan Feng, Gushu Li, Shuangchen Li, Lei Deng, Yuan Xie, Yufei Ding*

	Code: [https://github.com/YukeWang96/OSDI21_AE](https://github.com/YukeWang96/OSDI21_AE)

7. **Marius: Learning Massive Graph Embeddings on a Single Machine** OSDI 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*Jason Mohoney, Roger Waleffe, Henry Xu, Theodoros Rekatsinas, Shivaram Venkataraman*

	Code: [https://github.com/marius-team/marius](https://github.com/marius-team/marius)

8. **P3: Distributed Deep Graph Learning at Scale** OSDI 2021 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Swapnil Gandhi, Anand Padmanabha Iyer*

### SOSP

#### 2017

1. **DeepXplore: Automated Whitebox Testing of Deep Learning Systems** SOSP 2017 ![](https://img.shields.io/badge/Debugging-orange)

	*Kexin Pei, Yinzhi Cao, Junfeng Yang, Suman Jana*

  Code: [https://github.com/peikexin9/deepxplore](https://github.com/peikexin9/deepxplore)

#### 2019

1. **PipeDream: Generalized Pipeline Parallelism for DNN Training** SOSP 2019 ![](https://img.shields.io/badge/Training-red)

	*Deepak Narayanan, Aaron Harlap, Amar Phanishayee, Vivek Seshadri, Nikhil R. Devanur, Gregory R. Ganger, Phillip B. Gibbons, Matei Zaharia*

2. **A Generic Communication Scheduler for Distributed DNN Training Acceleration** SOSP 2019![](https://img.shields.io/badge/Training-red)![](https://img.shields.io/badge/Parallel-blueviolet)

	*Yanghua Peng, Yibo Zhu, Yangrui Chen, Yixin Bao, Bairen Yi, Chang Lan, Chuan Wu, Chuanxiong Guo*

3. **Parity Models: Erasure-Coded Resilience for Prediction Serving Systems** SOSP 2019 ![](https://img.shields.io/badge/Inference-blue)

	*Jack Kosaian, K. V. Rashmi, Shivaram Venkataraman*

4. **TASO: Optimizing Deep Learning Computation with Automated Generation of Graph Substitutions** SOSP 2019 ![](https://img.shields.io/badge/Graph-cc231e)

	*Zhihao Jia, Oded Padon, James Thomas, Todd Warszawski, Matei Zaharia, Alex Aiken*

5. **Optimizing Data-Intensive Computations in Existing Libraries with Split Annotations** SOSP 2019 ![](https://img.shields.io/badge/Compiler-206777)

	*Shoumik Palkar, Matei Zaharia*

6. **Niijima: Sound and Automated Computation Consolidation for Efficient Multilingual Data-Parallel Pipelines** SOSP 2019 ![](https://img.shields.io/badge/Compiler-206777)

	*Guoqing Harry Xu, Margus Veanes, Michael Barnett, Madan Musuvathi, Todd Mytkowicz, Ben Zorn, Huan He, Haibo Lin*

7. **Nexus: A GPU Cluster Engine for Accelerating DNN-Based Video Analysis** SOSP 2019 ![](https://img.shields.io/badge/Hardware-green)

	*Haichen Shen, Lequn Chen, Yuchen Jin, Liangyu Zhao, Bingyu Kong, Matthai Philipose, Arvind Krishnamurthy, Ravi Sundaram*

8. **AutoMine: Harmonizing High-Level Abstraction and High Performance for Graph Mining** SOSP 2019 ![](https://img.shields.io/badge/Graph-cc231e)

	*Daniel Mawhirter, Bo Wu*

9. **KnightKing: A Fast Distributed Graph Random Walk Engine** SOSP 2019 ![](https://img.shields.io/badge/Graph-cc231e)

	*Ke Yang, MingXing Zhang, Kang Chen, Xiaosong Ma, Yang Bai, Yong Jiang*

	Code: [https://github.com/KnightKingWalk/KnightKing](https://github.com/KnightKingWalk/KnightKing)

10. **Gerenuk: Thin Computation over Big Native Data Using Speculative Program Transformation** SOSP 2019 ![](https://img.shields.io/badge/Compiler-206777)

	*Christian Navasca, Cheng Cai, Khanh Nguyen, Brian Demsky, Shan Lu, Miryung Kim, Guoqing Harry Xu*

#### 2021

1. **Gradient Compression Supercharged High-Performance Data Parallel DNN Training** SOSP 2021 ![](https://img.shields.io/badge/Training-red)![](https://img.shields.io/badge/Parallel-blueviolet)

	*Youhui Bai, Cheng Li, Quan Zhou, Jun Yi, Ping Gong, Feng Yan, Ruichuan Chen, Yinlong Xu*

2. **Generating Complex, Realistic Cloud Workloads using Recurrent Neural Networks** SOSP 2021 ![](https://img.shields.io/badge/Resource-cc9e08)
	*Shane Bergsma, Timothy Zeyl, Arik Senderovich, J. Christopher Beck*

3. **Random Walks on Huge Graphs at Cache Efficiency** SOSP 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Ke Yang, Xiaosong Ma, Saravanan Thirumuruganathan, Kang Chen, Yongwei Wu*



### SIGMOD

#### 2016

1. **Building Machine Learning Systems that Understand** SIGMOD 2016 ![](https://img.shields.io/badge/Others-gray)

	*Jeff Dean*

2. **M3: Scaling Up Machine Learning via Memory Mapping** SIGMOD 2016 ![](https://img.shields.io/badge/Hardware-green)

	*Dezhi Fang, Duen Horng Chau*

#### 2017

1. **Heterogeneity-aware Distributed Parameter Servers** SIGMOD 2017 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Jiawei Jiang, Bin Cui, Ce Zhang, Lele Yu*

2. **Bolt-on Differential Privacy for Scalable Stochastic Gradient Descent-based Analytics** SIGMOD 2017 ![](https://img.shields.io/badge/Security-85144b)

	*Xi Wu, Fengan Li, Arun Kumar, Kamalika Chaudhuri, Somesh Jha, Jeffrey F. Naughton*

3. **Data Management in Machine Learning: Challenges, Techniques, and Systems** SIGMOD 2017 ![](https://img.shields.io/badge/Data-ff69b4)

	*Arun Kumar, Matthias Boehm, Jun Yang*

4. **Data Management Challenges in Production Machine Learning** SIGMOD 2017 ![](https://img.shields.io/badge/Data-ff69b4)

	*Neoklis Polyzotis, Sudip Roy, Steven Euijong Whang, Martin Zinkevich*

#### 2018

1.	**DimBoost: Boosting Gradient Boosting Decision Tree to Higher Dimensions** SIGMOD 2018 ![](https://img.shields.io/badge/Data-ff69b4)

	*Jiawei Jiang, Bin Cui, Ce Zhang, Fangcheng Fu*

2.	**SketchML: Accelerating Distributed Machine Learning with Data Sketches** SIGMOD 2018  ![](https://img.shields.io/badge/Data-ff69b4)

	*Jiawei Jiang, Fangcheng Fu, Tong Yang, Bin Cui*

3.	**Accelerating Machine Learning Inference with Probabilistic Predicates** SIGMOD 2018 ![](https://img.shields.io/badge/Data-ff69b4) ![](https://img.shields.io/badge/Inference-blue)

	*Yao Lu, Aakanksha Chowdhery, Srikanth Kandula, Surajit Chaudhuri*

#### 2019

1. **PS2: Parameter Server on Spark** SIGMOD 2019 ![](https://img.shields.io/badge/Data-ff69b4)

	*Zhipeng Zhang, Bin Cui, Yingxia Shao, Lele Yu, Jiawei Jiang, Xupeng Miao*

2.	**Large Scale Graph Mining with G-Miner** SIGMOD 2019 ![](https://img.shields.io/badge/Graph-cc231e)

	*Hongzhi Chen, Xiaoxi Wang, Chenghuan Huang, Juncheng Fang, Yifan Hou, Changji Li, James Cheng*

	Code: [https://github.com/yaobaiwei/GMiner](https://github.com/yaobaiwei/GMiner)

3.	**BlinkML: Efficient Maximum Likelihood Estimation with Probabilistic Guarantees** SIGMOD 2019 ![](https://img.shields.io/badge/Data-ff69b4) ![](https://img.shields.io/badge/Training-red)

	*Yongjoo Park, Jingyi Qing, Xiaoyang Shen, Barzan Mozafari*

4.	**Democratizing Data Science through Interactive Curation of ML Pipelines** SIGMOD 2019 ![](https://img.shields.io/badge/Data-ff69b4)

	*Zeyuan Shang, Emanuel Zgraggen, Benedetto Buratti, Ferdinand Kossmann, Philipp Eichmann, Yeounoh Chung, Carsten Binnig, Eli Upfal, Tim Kraska*

#### 2020

1.	**Memory-Aware Framework for Efficient Second-Order Random Walk on Large Graphs** SIGMOD 2020 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Data-ff69b4)

	*Yingxia Shao, Shiyue Huang, Xupeng Miao, Bin Cui, Lei Chen*

2.	**TensorFlow Data Validation: Data Analysis and Validation in Continuous ML Pipelines** SIGMOD 2020 ![](https://img.shields.io/badge/Data-ff69b4)

	*Emily Caveness, Paul Suganthan G. C., Zhuo Peng, Neoklis Polyzotis, Sudip Roy, Martin Zinkevich*

3.	**Optimizing Machine Learning Workloads in Collaborative Environments** SIGMOD 2020 ![](https://img.shields.io/badge/Data-ff69b4) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Behrouz Derakhshan, Alireza Rezaei Mahdiraji, Ziawasch Abedjan, Tilmann Rabl, Volker Markl*

4.	**Vertica-ML: Distributed Machine Learning in Vertica Database** SIGMOD 2020 ![](https://img.shields.io/badge/Data-ff69b4) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Arash Fard, Anh Le, George Larionov, Waqas Dhillon, Chuck Bear*

5.	**DB4ML - An In-Memory Database Kernel with Machine Learning Support** SIGMOD 2020 ![](https://img.shields.io/badge/Data-ff69b4)

	*Matthias Jasny, Tobias Ziegler, Tim Kraska, Uwe Röhm, Carsten Binnig*

6.	**Active Learning for ML Enhanced Database Systems** SIGMOD 2020 ![](https://img.shields.io/badge/Data-ff69b4)

	*Lin Ma, Bailu Ding, Sudipto Das, Adith Swaminathan*

7.	**MemFlow: Memory-Aware Distributed Deep Learning** SIGMOD 2020 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Neil Band*

8.	**Systems and ML: When the Sum is Greater than Its Parts** SIGMOD 2020

	*Ion Stoica*

#### 2021

1.	**Heterogeneity-Aware Distributed Machine Learning Training via Partial Reduce** SIGMOD 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Xupeng Miao, Xiaonan Nie, Yingxia Shao, Zhi Yang, Jiawei Jiang, Lingxiao Ma, Bin Cui*

2.	**VF^2Boost: Very Fast Vertical Federated Gradient Boosting for Cross-Enterprise Learning** SIGMOD 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Fangcheng Fu, Yingxia Shao, Lele Yu, Jiawei Jiang, Huanran Xue, Yangyu Tao, Bin Cui*

3.	**ALG: Fast and Accurate Active Learning Framework for Graph Convolutional Networks** SIGMOD 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*Wentao Zhang, Yu Shen, Yang Li, Lei Chen, Zhi Yang, Bin Cui*

4.	**Agile and Accurate CTR Prediction Model Training for Massive-Scale Online Advertising Systems** SIGMOD 2021 ![](https://img.shields.io/badge/Inference-blue)

	*Zhiqiang Xu, Dong Li, Weijie Zhao, Xing Shen, Tianbo Huang, Xiaoyun Li, Ping Li*

5.	**Production Machine Learning Pipelines: Empirical Analysis and Optimization Opportunities** SIGMOD 2021 ![](https://img.shields.io/badge/Data-ff69b4)

	*Doris Xin, Hui Miao, Aditya G. Parameswaran, Neoklis Polyzotis*

6.	**Vertex-Centric Visual Programming for Graph Neural Networks** SIGMOD 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*Yidi Wu, Yuntao Gui, Tatiana Jin, James Cheng, Xiao Yan, Peiqi Yin, Yufei Cai, Bo Tang, Fan Yu*

7.	**Deep Learning: Systems and Responsibility** SIGMOD 2021 ![](https://img.shields.io/badge/Others-gray)

	*Abdul Wasay, Subarna Chatterjee, Stratos Idreos*

8.	**Expand your Training Limits! Generating Training Data for ML-based Data Management** SIGMOD 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Data-ff69b4)

	*Francesco Ventura, Zoi Kaoudi, Jorge-Arnulfo Quiané-Ruiz, Volker Markl*

	Code: [https://github.com/agora-ecosystem/data-farm](https://github.com/agora-ecosystem/data-farm)

9.	**Towards Benchmarking Feature Type Inference for AutoML Platforms** SIGMOD 2021 ![](https://img.shields.io/badge/Data-ff69b4)

	*Vraj Shah, Jonathan Lacanlale, Premanand Kumar, Kevin Yang, Arun Kumar*

	Code: [https://github.com/pvn25/ML-Data-Prep-Zoo/tree/master/MLFeatureTypeInference](https://github.com/pvn25/ML-Data-Prep-Zoo/tree/master/MLFeatureTypeInference)

10. **LightNE: A Lightweight Graph Processing System for Network Embedding** SIGMOD 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*Jiezhong Qiu, Laxman Dhulipala, Jie Tang, Richard Peng, Chi Wang*

	Code: [https://github.com/xptree/LightNE](https://github.com/xptree/LightNE)

11.	**Scalable and Usable Relational Learning With Automatic Language Bias** SIGMOD 2021 ![](https://img.shields.io/badge/Data-ff69b4)

	*Jose Picado, Arash Termehchy, Alan Fern, Sudhanshu Pathak, Praveen Ilango, John Davis*

	Code: [https://github.com/OSU-IDEA-Lab/AutoBias](https://github.com/OSU-IDEA-Lab/AutoBias)

12.	**Model-Parallel Model Selection for Deep Learning Systems** SIGMOD 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Kabir Nagrecha*

13.	**Automatic Optimization of Matrix Implementations for Distributed Machine Learning and Linear Algebra** SIGMOD 2021 ![](https://img.shields.io/badge/Data-ff69b4) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Shangyu Luo, Dimitrije Jankov, Binhang Yuan, Chris Jermaine*

14.	**Automation of Data Prep, ML, and Data Science: New Cure or Snake Oil?** SIGMOD 2021 ![](https://img.shields.io/badge/Data-ff69b4)

	*Arun Kumar*

15.	**Towards Demystifying Serverless Machine Learning Training** SIGMOD 2021 ![](https://img.shields.io/badge/Training-red)

	*Jiawei Jiang, Shaoduo Gan, Yue Liu, Fanlin Wang, Gustavo Alonso, Ana Klimovic, Ankit Singla, Wentao Wu, Ce Zhang*

	Code: [https://github.com/DS3Lab/LambdaML](https://github.com/DS3Lab/LambdaML)

16.	**AI Meets Database: AI4DB and DB4AI** SIGMOD 2021 ![](https://img.shields.io/badge/Data-ff69b4)

	*Guoliang Li, Xuanhe Zhou, Lei Cao*

### ASPLOS

#### 2017

1.	**SaberLDA: Sparsity-Aware Learning of Topic Models on GPUs** ASPLOS 2017 ![](https://img.shields.io/badge/Hardware-green)

	*Kaiwei Li, Jianfei Chen, Wenguang Chen, Jun Zhu*

2.	**SC-DCNN: Highly-Scalable Deep Convolutional Neural Network using Stochastic Computing** ASPLOS 2017 ![](https://img.shields.io/badge/Data-ff69b4)

	*Ao Ren, Zhe Li, Caiwen Ding, Qinru Qiu, Yanzhi Wang, Ji Li, Xuehai Qian, Bo Yuan*

3.	**Optimizing CNNs on Multicores for Scalability, Performance and Goodput** ASPLOS 2017 ![](https://img.shields.io/badge/Hardware-green)

	*Samyam Rajbhandari, Yuxiong He, Olatunji Ruwase, Michael Carbin, Trishul M. Chilimbi*

#### 2018

1.	**Bridge the Gap Between Neural Networks and Neuromorphic Hardware with A Neural Network Compiler** ASPLOS 2018 ![](https://img.shields.io/badge/Compiler-206777)

	*Yu Ji, Youhui Zhang, Wenguang Chen, Yuan Xie*

2.	**MAERI: Enabling Flexible Dataflow Mapping over DNN Accelerators via Reconfigurable Interconnects** ASPLOS 2018 ![](https://img.shields.io/badge/Hardware-green)

	*Hyoukjun Kwon, Ananda Samajdar, Tushar Krishna*

3.	**VIBNN: Hardware Acceleration of Bayesian Neural Networks** ASPLOS 2018 ![](https://img.shields.io/badge/Hardware-green)

	*Ruizhe Cai, Ao Ren, Ning Liu, Caiwen Ding, Luhao Wang, Xuehai Qian, Massoud Pedram, Yanzhi Wang*


### 2019

1.	**PUMA: A Programmable Ultra-efficient Memristor-based Accelerator for Machine Learning Inference** ASPLOS 2019 ![](https://img.shields.io/badge/Inference-blue) ![](https://img.shields.io/badge/Hardware-green)

	*Aayush Ankit, Izzat El Hajj, Sai Rahul Chalamalasetti, Geoffrey Ndu, Martin Foltin, R. Stanley Williams, Paolo Faraboschi, Wen-mei W. Hwu, John Paul Strachan, Kaushik Roy, Dejan S. Milojicic*

2.	**FPSA: A Full System Stack Solution for Reconfigurable ReRAM-based NN Accelerator Architecture** ASPLOS 2019 ![](https://img.shields.io/badge/Compiler-206777)

	*Yu Ji, Youyang Zhang, Xinfeng Xie, Shuangchen Li, Peiqi Wang, Xing Hu, Youhui Zhang, Yuan Xie*

3.	**Bit-Tactical: A Software/Hardware Approach to Exploiting Value and Bit Sparsity in Neural Networks** ASPLOS 20189 ![](https://img.shields.io/badge/Hardware-green)

	*Alberto Delmas Lascorz, Patrick Judd, Dylan Malone Stuart, Zissis Poulos, Mostafa Mahmoud, Sayeh Sharify, Milos Nikolic, Kevin Siu, Andreas Moshovos*

4.	**TANGRAM: Optimized Coarse-Grained Dataflow for Scalable NN Accelerators** ASPLOS 2019 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Mingyu Gao, Xuan Yang, Jing Pu, Mark Horowitz, Christos Kozyrakis*

5.	**Packing Sparse Convolutional Neural Networks for Efficient Systolic Array Implementations: Column Combining Under Joint Optimization** ASPLOS 2019 ![](https://img.shields.io/badge/Hardware-green)

	*H. T. Kung, Bradley McDanel, Sai Qian Zhang*

6.	**Split-CNN: Splitting Window-based Operations in Convolutional Neural Networks for Memory System Optimization** ASPLOS 2019 ![](https://img.shields.io/badge/Hardware-green)

	*Tian Jin, Seokin Hong*

7.	**HOP: Heterogeneity-Aware Decentralized Training** ASPLOS 2019 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Qinyi Luo, Jinkun Lin, Youwei Zhuo, Xuehai Qian*

8.	**Astra: Exploiting Predictability to Optimize Deep Learning** ASPLOS 2019 ![](https://img.shields.io/badge/Compiler-206777)

	*Muthian Sivathanu, Tapan Chugh, Sanjay S. Singapuram, Lidong Zhou*

9.	**ADMM-NN: An Algorithm-Hardware Co-Design Framework of DNNs Using Alternating Direction Methods of Multipliers** ASPLOS 2019 ![](https://img.shields.io/badge/Hardware-green)

	*Ao Ren, Tianyun Zhang, Shaokai Ye, Jiayu Li, Wenyao Xu, Xuehai Qian, Xue Lin, Yanzhi Wang*

	Code: [https://github.com/bowenl0218/bpgan-signal-compression](https://github.com/bowenl0218/bpgan-signal-compression)

### 2020

1.	**Prague: High-Performance Heterogeneity-Aware Asynchronouos Decentralized Training** ASPLOS 2020 ![](https://img.shields.io/badge/Training-red)

	*Qinyi Luo, Jiaao He, Youwei Zhuo, Xuehai Qian*

2.	**Capuchin: Tensor-based GPU Memory Management for Deep Learning** ASPLOS 2020 ![](https://img.shields.io/badge/Hardware-green)

	*Xuan Peng, Xuanhua Shi, Hulin Dai, Hai Jin, Weiliang Ma, Qian Xiong, Fan Yang, Xuehai Qian*

3.	**DNNGuard: An Elastic Heterogeneous DNN Accelerator Architecture against Adversarial Attacks** ASPLOS 2020 ![](https://img.shields.io/badge/Hardware-green)

	*Xingbin Wang, Rui Hou, Boyan Zhao, Fengkai Yuan, Jun Zhang, Dan Meng, Xuehai Qian*

4.	**PatDNN: Achieving Real-Time DNN Execution on Mobile Devices with Pattern-based Weight Pruning** ASPLOS 2020 ![](https://img.shields.io/badge/Compiler-206777)

	*Wei Niu, Xiaolong Ma, Sheng Lin, Shihao Wang, Xuehai Qian, Xue Lin, Yanzhi Wang, Bin Ren*

### 2021

1. **Neural architecture search as program transformation exploration** ASPLOS 2021 ![](https://img.shields.io/badge/Compiler-206777)

	*Jack Turner, Elliot J. Crowley, Michael F. P. O'Boyle*

	Code: [https://github.com/jack-willturner/nas-as-program-transformation-exploration](https://github.com/jack-willturner/nas-as-program-transformation-exploration)

2. **Analytical characterization and design space exploration for optimization of CNNs** ASPLOS 2021 ![](https://img.shields.io/badge/Compiler-206777)

	*Rui Li, Yufan Xu, Aravind Sukumaran-Rajam, Atanas Rountev, P. Sadayappan*

	Code: [https://github.com/HPCRL/ASPLOS_artifact](https://github.com/HPCRL/ASPLOS_artifact)

3. **Mind mappings: enabling efficient algorithm-accelerator mapping space search** ASPLOS 2021 ![](https://img.shields.io/badge/Hardware-green)

	*Kartik Hegde, Po-An Tsai, Sitao Huang, Vikas Chandra, Angshuman Parashar, Christopher W. Fletcher*

	Code: [https://github.com/kartik-hegde/mindMappings](https://github.com/kartik-hegde/mindMappings)

4. **NeuroEngine: a hardware-based event-driven simulation system for advanced brain-inspired computing** ASPLOS 2021 ![](https://img.shields.io/badge/Hardware-green)

	*Hunjun Lee, Chanmyeong Kim, Yujin Chung, Jangwoo Kim*

5. **Defensive approximation: securing CNNs using approximate computing** ASPLOS 2021 ![](https://img.shields.io/badge/Security-85144b)

	*Amira Guesmi, Ihsen Alouani, Khaled N. Khasawneh, Mouna Baklouti, Tarek Frikha, Mohamed Abid, Nael B. Abu-Ghazaleh*

	Code: [https://github.com/AG-X09/Defensive-Approximation](https://github.com/AG-X09/Defensive-Approximation)

### ATC

#### 2017

1.	**Poseidon: An Efficient Communication Architecture for Distributed Deep Learning on GPU Clusters** ATC 2017 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Hao Zhang, Zeyu Zheng, Shizhen Xu, Wei Dai, Qirong Ho, Xiaodan Liang, Zhiting Hu, Jinliang Wei, Pengtao Xie, Eric P. Xing*

2.	**Garaph: Efficient GPU-accelerated Graph Processing on a Single Machine with Balanced Replication** ATC 2017 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Lingxiao Ma, Zhi Yang, Han Chen, Jilong Xue, Yafei Dai*

#### 2018

1.	**Litz: Elastic Framework for High-Performance Distributed Machine Learning** ATC 2018 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Aurick Qiao, Abutalib Aghayev, Weiren Yu, Haoyang Chen, Qirong Ho, Garth A. Gibson, Eric P. Xing*

2.	**Cavs: An Efficient Runtime System for Dynamic Neural Networks** ATC 2018 ![](https://img.shields.io/badge/Compiler-206777) 

	*Shizhen Xu, Hao Zhang, Graham Neubig, Wei Dai, Jin Kyu Kim, Zhijie Deng, Qirong Ho, Guangwen Yang, Eric P. Xing*

3.	**DeepCPU: Serving RNN-based Deep Learning Models 10x Faster** ATC 2018 ![](https://img.shields.io/badge/Inference-blue)

	*Minjia Zhang, Samyam Rajbhandari, Wenhan Wang, Yuxiong He*

#### 2019

1.	**STRADS-AP: Simplifying Distributed Machine Learning Programming without Introducing a New Programming Model** ATC 2019 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Jin Kyu Kim, Abutalib Aghayev, Garth A. Gibson, Eric P. Xing*

2.	**NeuGraph: Parallel Deep Neural Network Computation on Large Graphs** ATC 2019 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Graph-cc231e)

	*Lingxiao Ma, Zhi Yang, Youshan Miao, Jilong Xue, Ming Wu, Lidong Zhou, Yafei Dai*

3.	**Analysis of Large-Scale Multi-Tenant GPU Clusters for DNN Training Workloads** ATC 2019 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Myeongjae Jeon, Shivaram Venkataraman, Amar Phanishayee, Junjie Qian, Wencong Xiao, Fan Yang*

4.	**Optimizing CNN Model Inference on CPUs** ATC 2019 ![](https://img.shields.io/badge/Inference-blue)

	*Yizhi Liu, Yao Wang, Ruofei Yu, Mu Li, Vin Sharma, Yida Wang*

5.	**MArk: Exploiting Cloud Services for Cost-Effective, SLO-Aware Machine Learning Inference Serving** ATC 2019 ![](https://img.shields.io/badge/Inference-blue)

	*Chengliang Zhang, Minchen Yu, Wei Wang, Feng Yan*

#### 2020

1.	**HetPipe: Enabling Large DNN Training on (Whimpy) Heterogeneous GPU Clusters through Integration of Pipelined Model Parallelism and Data Parallelism** ATC 2020 ![](https://img.shields.io/badge/Training-red)

	*Jay H. Park, Gyeongchan Yun, Chang M. Yi, Nguyen T. Nguyen, Seungmin Lee, Jaesik Choi, Sam H. Noh, Young-ri Choi*

2.	**AutoSys: The Design and Operation of Learning-Augmented Systems** ATC 2020 ![](https://img.shields.io/badge/Others-gray)

	*Chieh-Jan Mike Liang, Hui Xue, Mao Yang, Lidong Zhou, Lifei Zhu, Zhao Lucis Li, Zibo Wang, Qi Chen, Quanlu Zhang, Chuanjie Liu, Wenjun Dai*

3.	**Daydream: Accurately Estimating the Efficacy of Optimizations for DNN Training** ATC 2020 ![](https://img.shields.io/badge/Training-red)

	*Hongyu Zhu, Amar Phanishayee, Gennady Pekhimenko*

4. 	**ALERT: Accurate Learning for Energy and Timeliness** ![](https://img.shields.io/badge/Resource-cc9e08)

	*Chengcheng Wan, Muhammad Husni Santriaji, Eri Rogers, Henry Hoffmann, Michael Maire, Shan Lu*

5.	**NeuOS: A Latency-Predictable Multi-Dimensional Optimization Framework for DNN-driven Autonomous Systems** ATC 2020 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Soroush Bateni, Cong Liu*

	Code: [https://github.com/Soroosh129/NeuOS](https://github.com/Soroosh129/NeuOS)

6.	**PERCIVAL: Making In-Browser Perceptual Ad Blocking Practical with Deep Learning** ATC 2020 ![](https://img.shields.io/badge/Inference-blue)

	*Zain ul Abi Din, Panagiotis Tigas, Samuel T. King, Benjamin Livshits*

	Code: [https://github.com/dxaen/percival](https://github.com/dxaen/percival)

7.	**GraphWalker: An I/O-Efficient and Resource-Friendly Graph Analytic System for Fast and Scalable Random Walks** ATC 2020 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Rui Wang, Yongkun Li, Hong Xie, Yinlong Xu, John C. S. Lui*

8.	**Scaph: Scalable GPU-Accelerated Graph Processing with Value-Driven Differential Scheduling** ATC 2020 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Long Zheng, Xianliang Li, Yaohui Zheng, Yu Huang, Xiaofei Liao, Hai Jin, Jingling Xue, Zhiyuan Shao, Qiang-Sheng Hua*

#### 2021

1.	**Zico: Efficient GPU Memory Sharing for Concurrent DNN Training** ATC 2021 ![](https://img.shields.io/badge/Training-red)

	*Gangmuk Lim, Jeongseob Ahn, Wencong Xiao, Youngjin Kwon, Myeongjae Jeon*

2.	**Octo: INT8 Training with Loss-aware Compensation and Backward Quantization for Tiny On-device Learning** ATC 2021 ![](https://img.shields.io/badge/Training-red)

	*Qihua Zhou, Song Guo, Zhihao Qu, Jingcai Guo, Zhenda Xu, Jiewei Zhang, Tao Guo, Boyuan Luo, Jingren Zhou*

	Code: [https://github.com/kimihe/Octo](https://github.com/kimihe/Octo)

3.	**GLIST: Towards In-Storage Graph Learning** ATC 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*Cangyuan Li, Ying Wang, Cheng Liu, Shengwen Liang, Huawei Li, Xiaowei Li*

4.	**Fine-tuning giant neural networks on commodity hardware with automatic pipeline model parallelism** ATC 2021 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Saar Eliad, Ido Hakimi, Alon De Jagger, Mark Silberstein, Assaf Schuster*

	Code: [https://github.com/saareliad/FTPipe](https://github.com/saareliad/FTPipe)

5.	**INFaaS: Automated Model-less Inference Serving** ATC 2021 ![](https://img.shields.io/badge/Inference-blue) 

	*Francisco Romero, Qian Li, Neeraja J. Yadwadkar, Christos Kozyrakis*

	Code: [https://github.com/stanford-mast/INFaaS](https://github.com/stanford-mast/INFaaS)

6.	**Jump-Starting Multivariate Time Series Anomaly Detection for Online Service Systems** ATC 2021 ![](https://img.shields.io/badge/Debugging-orange)

	*Minghua Ma, Shenglin Zhang, Junjie Chen, Jim Xu, Haozhe Li, Yongliang Lin, Xiaohui Nie, Bo Zhou, Yong Wang, Dan Pei*

	Code: [https://github.com/NetManAIOps/JumpStarter](https://github.com/NetManAIOps/JumpStarter)

7.	**Palleon: A Runtime System for Efficient Video Processing toward Dynamic Class Skew** ATC 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Boyuan Feng, Yuke Wang, Gushu Li, Yuan Xie, Yufei Ding*

8.	**Habitat: A Runtime-Based Computational Performance Predictor for Deep Neural Network Training** ATC 2021 ![](https://img.shields.io/badge/Training-red)

	*Geoffrey X. Yu, Yubo Gao, Pavel Golikov, Gennady Pekhimenko*

	Code: [https://github.com/geoffxy/habitat](https://github.com/geoffxy/habitat)

9.	**Refurbish Your Training Data: Reusing Partially Augmented Samples for Faster Deep Neural Network Training** ATC 2021 ![](https://img.shields.io/badge/Training-red)

	*Gyewon Lee, Irene Lee, Hyeonmin Ha, Kyung-Geun Lee, Hwarim Hyun, Ahnjae Shin, Byung-Gon Chun*

10.	**ZeRO-Offload: Democratizing Billion-Scale Model Training** ATC 2021 ![](https://img.shields.io/badge/Training-red)
	
	*Jie Ren, Samyam Rajbhandari, Reza Yazdani Aminabadi, Olatunji Ruwase, Shuangyan Yang, Minjia Zhang, Dong Li, Yuxiong He*
	
	Code: [https://github.com/microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed)

### PPoPP

#### 2017

1.	**Groute: An Asynchronous Multi-GPU Programming Model for Irregular Computations** PPoPP 2017 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Tal Ben-Nun, Michael Sutton, Sreepathi Pai, Keshav Pingali:*

	Code: [https://github.com/groute/ppopp17-artifact](https://github.com/groute/ppopp17-artifact)

2.	**Exploiting Vector and Multicore Parallelism for Recursive Data- and Task-Parallel Programs** PPoPP 2017 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Bin Ren, Sriram Krishnamoorthy, Kunal Agrawal, Milind Kulkarn*

3.	**S-Caffe: Co-designing MPI Runtimes and Caffe for Scalable Deep Learning on Modern GPU Clusters** PPoPP 2017 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Ammar Ahmad Awan, Khaled Hamidouche, Jahanzeb Maqbool Hashmi, Dhabaleswar K. Panda*

#### 2018

1.	**An Effective Fusion and Tile Size Model for Optimizing Image Processing Pipelines** PPoPP 2018 ![](https://img.shields.io/badge/Compiler-206777)

	*Abhinav Jangda, Uday Bondhugula*

2.	**Bridging the Gap between Deep Learning and Sparse Matrix Format Selection** PPoPP 2018 ![](https://img.shields.io/badge/Data-ff69b4)

	*Yue Zhao, Jiajia Li, Chunhua Liao, Xipeng Shen*

3.	**LazyGraph: Lazy Data Coherency for Replicas in Distributed Graph-Parallel Computation** PPoPP 2018 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Data-ff69b4)

	*Lei Wang, Liangji Zhuang, Junhang Chen, Huimin Cui, Fang Lv, Ying Liu, Xiaobing Feng*

4.	**Making Pull-Based Graph Processing Performant** PPoPP 2018 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Samuel Grossman, Heiner Litz, Christos Kozyrakis*

	Code: [https://github.com/stanford-mast/Grazelle-PPoPP18](https://github.com/stanford-mast/Grazelle-PPoPP18)

5.	**SuperNeurons: Dynamic GPU Memory Management for Training Deep Neural Networks** PPoPP 2018 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Linnan Wang, Jinmian Ye, Yiyang Zhao, Wei Wu, Ang Li, Shuaiwen Leon Song, Zenglin Xu, Tim Kraska*


#### 2019

1.	**Beyond Human-Level Accuracy: Computational Challenges in Deep Learning** PPoPP 2019 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Joel Hestness, Newsha Ardalani, Gregory F. Diamos*

	Code: [https://github.com/baidu-research/catamount](https://github.com/baidu-research/catamount)

2.	**A Pattern Based Algorithmic Autotuner for Graph Processing on GPUs** PPoPP 2019 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Ke Meng, Jiajia Li, Guangming Tan, Ninghui Sun*

	Code: [https://github.com/PAA-NCIC/gswitch](https://github.com/PAA-NCIC/gswitch)

#### 2020

1.	**Taming unbalanced training workloads in deep learning with partial collective operations** PPoPP 2020 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Shigang Li, Tal Ben-Nun, Salvatore Di Girolamo, Dan Alistarh, Torsten Hoefler*

#### 2021

1.	**Understanding and bridging the gaps in current GNN performance optimizations** PPoPP 2021 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Kezhao Huang, Jidong Zhai, Zhen Zheng, Youngmin Yi, Xipeng Shen*

2.	**Scaling implicit parallelism via dynamic control replication** PPoPP 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Michael Bauer, Wonchan Lee, Elliott Slaughter, Zhihao Jia, Mario Di Renzo, Manolis Papadakis, Galen M. Shipman, Patrick S. McCormick, Michael Garland, Alex Aiken*

3.	**Compiler support for near data computing** PPoPP 2021 ![](https://img.shields.io/badge/Compiler-206777)

	*Mahmut Taylan Kandemir, Jihyun Ryoo, Xulong Tang, Mustafa Karaköy*

4.	**BiPart: a parallel and deterministic hypergraph partitioner** PPoPP 2021 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Sepideh Maleki, Udit Agarwal, Martin Burtscher, Keshav Pingali*

	Code: [https://github.com/IntelligentSoftwareSystems/Galois](https://github.com/IntelligentSoftwareSystems/Galois)
	
5.	**GPTune: multitask learning for autotuning exascale applications** PPoPP 2021 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Yang Liu, Wissam M. Sid-Lakhdar, Osni Marques, Xinran Zhu, Chang Meng, James Weldon Demmel, Xiaoye S. Li*

	Code: [https://github.com/gptune/GPTune](https://github.com/gptune/GPTune)

6.	**I/O lower bounds for auto-tuning of convolutions in CNNs** PPoPP 2021 ![](https://img.shields.io/badge/Data-ff69b4) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Xiaoyang Zhang, Junmin Xiao, Guangming Tan*

7.	**ApproxTuner: a compiler and runtime system for adaptive approximations** PPoPP 2021 ![](https://img.shields.io/badge/Compiler-206777)

	*Hashim Sharif, Yifan Zhao, Maria Kotsifakou, Akash Kothari, Ben Schreiber, Elizabeth Wang, Yasmin Sarita, Nathan Zhao, Keyur Joshi, Vikram S. Adve, Sasa Misailovic, Sarita V. Adve*

8.	**TurboTransformers: an efficient GPU serving system for transformer models** PPoPP 2021 ![](https://img.shields.io/badge/Inference-blue) ![](https://img.shields.io/badge/Hardware-green)

	*Jiarui Fang, Yang Yu, Chengduo Zhao, Jie Zhou*

	Code: [https://github.com/Tencent/TurboTransformers](https://github.com/Tencent/TurboTransformers)

9.	**Extracting clean performance models from tainted programs** PPoPP 2021 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Resource-cc9e08)

	*Marcin Copik, Alexandru Calotoiu, Tobias Grosser, Nicolas Wicki, Felix Wolf, Torsten Hoefler*

	Code: [https://github.com/spcl/perf-taint](https://github.com/spcl/perf-taint)

10.	**DAPPLE: a pipelined data parallel approach for training large models** PPoPP 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

	*Shiqing Fan, Yi Rong, Chen Meng, Zongyan Cao, Siyu Wang, Zhen Zheng, Chuan Wu, Guoping Long, Jun Yang, Lixue Xia, Lansong Diao, Xiaoyong Liu, Wei Lin*

	Code: [https://github.com/AlibabaPAI/DAPPLE](https://github.com/AlibabaPAI/DAPPLE)

11.	**In-situ workflow auto-tuning through combining component models** PPoPP 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Tong Shu, Yanfei Guo, Justin M. Wozniak, Xiaoning Ding, Ian T. Foster, Tahsin M. Kurç*

12.	**Corder: cache-aware reordering for optimizing graph analytics** PPoPP 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*YuAng Chen, Yeh-Ching Chung*

13.	**DFOGraph: an I/O- and communication-efficient system for distributed fully-out-of-core graph processing** PPoPP 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*Jiping Yu, Wei Qin, Xiaowei Zhu, Zhenbo Sun, Jianqiang Huang, Xiaohan Li, Wenguang Chen*

14.	**An efficient uncertain graph processing framework for heterogeneous architectures** PPoPP 2021 ![](https://img.shields.io/badge/Graph-cc231e)

	*Heng Zhang, Lingda Li, Donglin Zhuang, Rui Liu, Shuang Song, Dingwen Tao, Yanjun Wu, Shuaiwen Leon Song*

15.	**Dynamic scaling for low-precision learning** PPoPP 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

	*Ruobing Han, Min Si, James Demmel, Yang You*

	Code: [https://github.com/drcut/CPD](https://github.com/drcut/CPD)

16.	**Exploring deep reuse in winograd CNN inference** PPoPP 2021 ![](https://img.shields.io/badge/Inference-blue)

	*Ruofan Wu, Feng Zhang, Zhen Zheng, Xiaoyong Du, Xipeng Shen*

17.	**A novel memory-efficient deep learning training framework via error-bounded lossy compression** PPoPP 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Hardware-green)

	*Sian Jin, Guanpeng Li, Shuaiwen Leon Song, Dingwen Tao*

### HPCA

#### 2017

1. **Towards Pervasive and User Satisfactory CNN across GPU Microarchitectures** HPCA 2017 ![](https://img.shields.io/badge/Compiler-206777) ![](https://img.shields.io/badge/Resource-cc9e08) 

   *Mingcong Song, Yang Hu, Huixiang Chen, Tao Li*

2. **PipeLayer: A Pipelined ReRAM-Based Accelerator for Deep Learning** HPCA 2017 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Linghao Song, Xuehai Qian, Hai Li, Yiran Chen*

3. **FlexFlow: A Flexible Dataflow Accelerator Architecture for Convolutional Neural Networks** HPCA 2017  ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Wenyan Lu, Guihai Yan, Jiajun Li, Shijun Gong, Yinhe Han, Xiaowei Li*

#### 2018

1. **Towards Efficient Microarchitectural Design for Accelerating Unsupervised GAN-based Deep Learning** HPCA 2018 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Mingcong Song, Jiaqi Zhang, Huixiang Chen, Tao Li*

1.	**Making Memristive Neural Network Accelerators Reliable** HPCA 2018 ![](https://img.shields.io/badge/Hardware-green)
	
	*Ben Feinberg, Shibo Wang, Engin Ipek*
	
3. **Compressing DMA Engine: Leveraging Activation Sparsity for Training Deep Neural Networks** HPCA 2018 ![](https://img.shields.io/badge/Hardware-green)![](https://img.shields.io/badge/Training-red)

   *Minsoo Rhu, Mike O'Connor, Niladrish Chatterjee, Jeff Pool, Youngeun Kwon, Stephen W. Keckler*

4. **In-situ AI: Towards Autonomous and Incremental Deep Learning for IoT Systems** HPCA 2018![](https://img.shields.io/badge/Training-red)

   *Mingcong Song, Kan Zhong, Jiaqi Zhang, Yang Hu, Duo Liu, Weigong Zhang, Jing Wang, Tao Li*

#### 2019

1. **HyPar: Towards Hybrid Parallelism for Deep Learning Accelerator Array** HPCA 2019 ![](https://img.shields.io/badge/Resource-cc9e08) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Linghao Song, Jiachen Mao, Youwei Zhuo, Xuehai Qian, Hai Li, Yiran Chen*

2. **E-RNN: Design Optimization for Efficient Recurrent Neural Networks in FPGAs** HPCA 2019 ![](https://img.shields.io/badge/Compiler-206777) ![](https://img.shields.io/badge/Training-red)

   *Zhe Li, Caiwen Ding, Siyue Wang, Wujie Wen, Youwei Zhuo, Chang Liu, Qinru Qiu, Wenyao Xu, Xue Lin, Xuehai Qian, Yanzhi Wang*

   Code: https://github.com/lz1313/BlockCIrculantRNN

3. **Bit Prudent In-Cache Acceleration of Deep Convolutional Neural Networks** HPCA 2019 ![](https://img.shields.io/badge/Hardware-green)

   *Xiaowei Wang, Jiecao Yu, Charles Augustine†, Ravi Iyer†, Reetuparna Das*

4. **Shortcut Mining: Exploiting Cross-Layer Shortcut Reuse in DCNN Accelerators** HPCA 2019 ![](https://img.shields.io/badge/Resource-cc9e08)![](https://img.shields.io/badge/Data-ff69b4)

   *Arash Azizimazreah, Lizhong Chen*

#### 2020

1. **AccPar: Tensor Partitioning for Heterogeneous Deep Learning Accelerator Arrays** HPCA 2020 ![](https://img.shields.io/badge/Parallel-blueviolet)![](https://img.shields.io/badge/Data-ff69b4)

   *Linghao Song, Fan Chen, Youwei Zhuo, Xuehai Qian, Hai Li, Yiran Chen*

#### 2021

1. **A Computational Stack for Cross-Domain Acceleration** HPCA 2021 ![](https://img.shields.io/badge/Platform-034d0f)

   *Sean Kinzer, Joon Kyung Kim, Soroush Ghodrati, Brahmendra Yatham, Alric Althoff, Divya Mahajan, Sorin Lerner, Hadi Esmaeilzadeh*

   Code: https://github.com/he-actlab/polymath

2. **Heterogeneous Dataflow Accelerators for Multi-DNN Workloads** HPCA 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Hyoukjun Kwon, Liangzhen Lai, Michael Pellauer, Tushar Krishna, Yu-Hsin Chen, Vikas Chandra*

3. **SPAGHETTI: Streaming Accelerators for Highly Sparse GEMM on FPGAs** HPCA 2021 ![](https://img.shields.io/badge/Compiler-206777)

   *Reza Hojabr, Ali Sedaghati, Amirali Sharifian, Ahmad Khonsari, Arrvindh Shriraman*

   Code: https://github.com/sfu-arch/SPAGHETTI

4. **SpAtten: Efficient Sparse Attention Architecture with Cascade Token and Head Pruning** HPCA 2021  ![](https://img.shields.io/badge/Hardware-green)

   *Jiajun Li, Ahmed Louri, Avinash Karanth, Razvan Bunescu*

5. **Mix and Match: A Novel FPGA-Centric Deep Neural Network Quantization Framework** HPCA 2021 ![](https://img.shields.io/badge/Others-gray)

   *Sung-En Chang, Yanyu Li, Mengshu Sun, Runbin Shi, Hayden K.-H. So, Xuehai Qian, Yanzhi Wang, Xue Lin*

6. **Revisiting HyperDimensional Learning for FPGA and Low-Power Architectures** HPCA 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Inference-blue)

   *Mohsen Imani, Zhuowen Zou, Samuel Bosch, Sanjay Anantha Rao, Sahand Salamat, Venkatesh Kumar, Yeseong Kim, Tajana Rosing*

7. **Tensor Casting: Co-Designing Algorithm-Architecture for Personalized Recommendation Training** HPCA 2021 ![](https://img.shields.io/badge/Training-red)

   *Youngeun Kwon, Yunjae Lee, Minsoo Rhu*

8. **GradPIM: A Practical Processing-in-DRAM Architecture for Gradient Descent** HPCA 2021 ![](https://img.shields.io/badge/Training-red)

   *Heesu Kim, Hanmin Park, Taehyun Kim, Kwanheum Cho, Eojin Lee, Soojung Ryu, Hyuk-Jae Lee, Kiyoung Choi, Jinho Lee*

9. **SpaceA: Sparse Matrix Vector Multiplication on Processing-in-Memory Accelerator** HPCA 2021 ![](https://img.shields.io/badge/Hardware-green)

   *Xinfeng Xie, Zheng Liang, Peng Gu, Abanti Basak, Lei Deng, Ling Liang, Xing Hu, Yuan Xie*

10. **Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling** HPCA 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

    *Young H. Oh, Seonghak Kim, Yunho Jin, Sam Son, Jonghyun Bae, Jongsung Lee, Yeonhong Park, Dong Uk Kim, Tae Jun Ham, Jae W. Lee*

11. **Sentinel: Efficient Tensor Migration and Allocation on Heterogeneous Memory Systems for Deep Learning** HPCA 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

    *Jie Ren, Jiaolin Luo, Kai Wu, Minjia Zhang, Hyeran Jeon, Dong Li*

12. **CSCNN: Algorithm-hardware Co-design for CNN Accelerators using Centrosymmetric Filters** HPCA 2021 ![](https://img.shields.io/badge/Hardware-green)

    *Jiajun Li, Ahmed Louri, Avinash Karanth, Razvan Bunescu*

### MICRO

#### 2017

1. **Scale-Out Acceleration for Machine Learning** MICRO 2017 ![](https://img.shields.io/badge/Others-gray)

   *Jongse Park, Hardik Sharma, Divya Mahajan, Joon Kyung Kim, Preston Olds, Hadi Esmaeilzadeh*

2. **Bit-Pragmatic Deep Neural Network Computing** MICRO 2017 ![](https://img.shields.io/badge/Hardware-green)

   *Jorge Albericio, Alberto Delmás, Patrick Judd, Sayeh Sharify, Gerard O'Leary, Roman Genov, Andreas Moshovos*

3. **CirCNN: Accelerating and Compressing Deep Neural Networks Using Block-Circulant Weight Matrices** MICRO 2017 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Caiwen Ding, Siyu Liao, Yanzhi Wang, Zhe Li, Ning Liu, Youwei Zhuo, Chao Wang, Xuehai Qian, Yu Bai, Geng Yuan, Xiaolong Ma, Yipeng Zhang, Jian Tang, Qinru Qiu, Xue Lin, Bo Yuan*

4. **DeftNN: Addressing Bottlenecks for DNN Execution on GPUs via Synapse Vector Elimination and Near-compute Data Fission** MICRO 2017 ![](https://img.shields.io/badge/Hardware-green)

   *Parker Hill, Animesh Jain, Mason Hill, Babak Zamirai, Chang-Hong Hsu, Michael A. Laurenzano, Scott Mahlke, Lingjia Tang, Jason Mars*

#### 2018

1. **Addressing Irregularity in Sparse Neural Networks:A Cooperative Software/Hardware Approach** MICRO 2018 ![](https://img.shields.io/badge/Hardware-green)

   *Xi Zeng, Tian Zhi, Xuda Zhou, Zidong Du, Qi Guo, Shaoli Liu, Bingrui Wang, Yuanbo Wen, Chao Wang, Xuehai Zhou, Ling Li, Tianshi Chen, Ninghui Sun, Yunji Chen*

2. **Diffy: a Deja vu-Free Differential Deep Neural Network Accelerator** MICRO 2018 ![](https://img.shields.io/badge/Hardware-green)

   *Mostafa Mahmoud, Kevin Siu, Andreas Moshovos*

3. **Towards Memory Friendly Long-Short Term Memory Networks (LSTMs) on Mobile GPUs** MICRO 2018 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Resource-cc9e08)

   *Xingyao Zhang, Chenhao Xie, Jing Wang, Weidong Zhang, Xin Fu*

4. **A Network-Centric Hardware/Algorithm Co-Design to Accelerate Distributed Training of Deep Neural Networks** MICRO 2018  ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Hardware-green)![](https://img.shields.io/badge/Parallel-blueviolet)

   *Youjie Li, Jongse Park, Mohammad Alian, Yifan Yuan, Zheng Qu, Peitian Pan, Ren Wang, Alexander Gerhard Schwing, Hadi Esmaeilzadeh, Nam Sung Kim*

5. **PermDNN: Efficient Compressed Deep Neural Network Architecture with Permuted Diagonal Matrices** MICRO 2018 ![](https://img.shields.io/badge/Hardware-green)

   *Chunhua Deng, Siyu Liao, Yi Xie, Keshab K. Parhi, Xuehai Qian, Bo Yuan*

6. **Processing-in-Memory for Energy-efficient Neural Network Training: A Heterogeneous Approach** MICRO 2018 ![](https://img.shields.io/badge/Training-red)

   *Jiawen Liu, Hengyu Zhao, Matheus Almeida Ogleari, Dong Li, Jishen Zhao*

#### 2019

1. **Wire-Aware Architecture and Dataflow for CNN Accelerators** MICRO 2019 ![](https://img.shields.io/badge/Hardware-green)

   *Sumanth Gudaparthi, Surya Narayanan, Rajeev Balasubramonian, Edouard Giacomin, Hari Kambalasubramanyam, Pierre-Emmanuel Gaillardon*

2. **Simba: Scaling Deep-Learning Inference with Multi-Chip-Module-Based Architecture** MICRO 2019 ![](https://img.shields.io/badge/Inference-blue)![](https://img.shields.io/badge/Hardware-green)

   *Yakun Sophia Shao, Jason Clemons, Rangharajan Venkatesan, Brian Zimmer, Matthew Fojtik, Nan Jiang, Ben Keller, Alicia Klinefelter, Nathaniel Pinckney, Priyanka Raina, Stephen G. Tell, Yanqing Zhang, William J. Dally, Joel Emer, C. Thomas Gray, Brucek Khailany, Stephen W. Keckler*

3. **ShapeShifter: Enabling Fine-Grain Data Width Adaptation in Deep Learning** MICRO 2019 ![](https://img.shields.io/badge/Data-ff69b4)

   *Alberto DelmásLascorz, Sayeh Sharify, Isak Edo, Dylan Malone Stuart, Omar Mohamed Awad, Patrick Judd, Mostafa Mahmoud, Milos Nikolic, Kevin Siu, Zissis Poulos, Andreas Moshovos*

4. **ZCOMP: Reducing DNN Cross-Layer Memory Footprint Using Vector Extensions** MICRO 2019 ![](https://img.shields.io/badge/Resource-cc9e08) ![](https://img.shields.io/badge/Hardware-green)

   *Berkin Akin  , Zeshan A. Chishti, Alaa R. Alameldeen*

5. **Boosting the Performance of CNN Accelerators with Dynamic Fine-Grained Channel Gating** MICRO 2019 ![](https://img.shields.io/badge/Others-gray)

   *Weizhe Hua, Yuan Zhou, Christopher De Sa, Zhiru Zhang, G. Edward Suh*

6. **SparTen: A Sparse Tensor Accelerator for Convolutional Neural Networks** MICRO 2019 ![](https://img.shields.io/badge/Training-red)![](https://img.shields.io/badge/Hardware-green) 

   *Ashish Gondimalla, Noah Chesnut, Mithuna Thottethodi, T. N. Vijaykumar*

7. **EDEN: Enabling Energy-Efficient, High-Performance Deep Neural Network Inference Using Approximate DRAM** MICRO 2019 ![](https://img.shields.io/badge/Hardware-green)

   *Skanda Koppula, Lois Orosa, A. Giray Yağlıkçı, Roknoddin Azizi, Taha Shahroodi, Konstantinos Kanellopoulos, Onur Mutlu*

8. **eCNN: A Block-Based and Highly-Parallel CNN Accelerator for Edge Inference** MICRO 2019 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Chao-Tsung Huang, Yu-Chun Ding, Huan-Ching Wang, Chi-Wen Weng, Kai-Ping Lin, Li-Wei Wang, Li-De Chen*

9. **Efficient SpMV Operation for Large and Highly Sparse Matrices using Scalable Multi-way Merge Parallelization** MICRO 2019 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Fazle Sadi, Joe Sweeney, Tze Meng Low, James C. Hoe, Larry Pileggi, Franz Franchetti*

#### 2020

1. **SuperNPU: An Extremely Fast Neural Processing Unit Using Superconducting Logic Devices** MICRO 2020 ![](https://img.shields.io/badge/Hardware-green)

   *Koki Ishida, Ilkwon Byun, Ikki Nagaoka, Kosuke Fukumitsu, Masamitsu Tanaka, Satoshi Kawakami, Teruo Tanimoto, Takatsugu Ono, Jangwoo Kim, and Koji Inoue*

2. **Printed Machine Learning Classifiers** MICRO 2020![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Inference-blue)

   *Muhammad Husnain Mubarik ,Dennis D. Weller, Nathaniel Bleier, Matthew Tomei Jasmin Aghassi-Hagmann, Mehdi B. Tahoori and Rakesh Kumar*

   Code: https://github.com/PrintedComputing

3. **Look-Up Table based Energy Efficient Processing in Cache Support for Neural Network Acceleration** MICRO 2020 ![](https://img.shields.io/badge/Hardware-green)

   *Akshay Krishna Ramanathan, Gurpreet S Kalsi, Srivatsa Srinivasa, Tarun Makesh Chandran, Kamlesh R Pillai, Om J Omer, Vijaykrishnan Narayanan, Sreenivas Subramoney*

4. **ConfuciuX: Autonomous Hardware Resource Assignment for DNN Accelerators using Reinforcement Learning** MICRO 2020 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Sheng-Chun Kao, Geonhwa Jeong, Tushar Krishna*

5. **VR-DANN: Real-Time Video Recognition via Decoder-Assisted Neural Network Acceleration** MICRO 2020 ![](https://img.shields.io/badge/Inference-blue)

   *Zhuoran Song, Feiyang Wu, Xueyuan Liu, Jing Ke, Naifeng Jing, Xiaoyao Liang*

6. **Procrustes: A Dataflow and Accelerator for Sparse Deep Neural Network Training** MICRO 2020 ![](https://img.shields.io/badge/Training-red)

   *Dingqing Yang, Amin Ghasemazar, Xiaowei Ren, Maximilian Golub, Guy Lemieux, Mieszko Lis*

7. **Duplo: Lifting Redundant Memory Accesses of Deep Neural Networks for GPU Tensor Cores** MICRO 2020 ![](https://img.shields.io/badge/Resource-cc9e08) ![](https://img.shields.io/badge/Hardware-green)

   *Hyeonjin Kim , Sungwoo Ahn , Yunho Oh† , Bogil Kim , Won Woo Ro , William J. Song*

8. **DUET: Boosting Deep Neural Network Efficiency on Dual-Module Architecture** MICRO 2020 ![](https://img.shields.io/badge/Others-gray)

   *Liu Liu, Zheng Qu, Lei Deng, Fengbin Tu, Shuangchen Li, Xing Hu, Zhenyu Gu, Yufei Ding, Yuan Xie*

9. **TFE: Energy-Efficient Transferred Filter-Based Engine to Compress and Accelerate Convolutional Neural Networks** MICRO 2020 ![](https://img.shields.io/badge/Hardware-green)

   *Huiyu Mo, Leibo Liu, Wenjing Hu, Wenping Zhu, Qiang Li, Ang Li, Shouyi Yin, Jian Chen, Xiaowei Jiang, Shaojun Wei*

10. **MatRaptor: A Sparse-Sparse Matrix Multiplication Accelerator Based on Row-Wise Product** MICRO 2020![](https://img.shields.io/badge/Training-red)

    *Nitish Srivastava, Hanchen Jin, Jie Liu, David Albonesi, Zhiru Zhang*

11. **TensorDash: Exploiting Sparsity to Accelerate Deep Neural Network Training** MICRO 2020 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Training-red)

    *Mostafa Mahmoud, Isak Edo, Ali Hadi Zadeh, Omar Mohamed Awad, Gennady Pekhimenko, Jorge Albericio, Andreas Moshovos*

12. **SAVE: Sparsity-Aware Vector Engine for Accelerating DNN Training and Inference on CPUs** MICRO 2020 ![](https://img.shields.io/badge/Training-red)![](https://img.shields.io/badge/Inference-blue)

    *Zhangxiaowen Gong, Houxiang Ji, Christopher W. Fletcher, Christopher J. Hughes, Sara Baghsorkhi, Josep Torrellas*

13. **GOBO: Quantizing Attention-Based NLP Models for Low Latency and Energy Efficient Inference** MICRO 2020 ![](https://img.shields.io/badge/Hardware-green)![](https://img.shields.io/badge/Inference-blue)

    *Ali Hadi Zadeh, Isak Edo, Omar Mohamed Awad, Andreas Moshovos*

#### 2021

1. **EdgeBERT: Sentence-Level Energy Optimizations for Latency-Aware Multi-Task NLP Inference** MICRO 2021 ![](https://img.shields.io/badge/Hardware-green)![](https://img.shields.io/badge/Inference-blue)

   *Thierry Tambe, Coleman Hooper, Lillian Pentecost, Tianyu Jia, En-Yu Yang, Marco Donato, Victor Sanh, Paul Whatmough, Alexander M. Rush, David Brooks, Gu-Yeon Wei*

   Code: https://github.com/harvard-acc/EdgeBERT

2. **FPRaker: A Processing Element for Accelerating Neural Network Training** MICRO 2021 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Training-red)

   *Omar Mohamed Awad, Mostafa Mahmoud, Isak Edo, Ali Hadi Zadeh, Ciaran Bannon, Anand Jayarajan, Gennady Pekhimenko, Andreas Moshovos*

3. **RecPipe: Co-designing Models and Hardware to Jointly Optimize Recommendation Quality and Performance** MICRO 2021 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Inference-blue)

   *Udit Gupta, Samuel Hsia, Jeff Zhang, Mark Wilkening, Javin Pombra, Hsien-Hsin Sean Lee, Gu-Yeon Wei, Carole-Jean Wu, David Brooks*

   Code: https://github.com/harvard-acc/RecPipe

4. **Shift-BNN: Highly-Efficient Probabilistic Bayesian Neural Network Training via Memory-Friendly Pattern Retrieving** MICRO 2021 ![](https://img.shields.io/badge/Training-red)

   *Qiyu Wan, Haojun Xia, Xingyao Zhang, Lening Wang, Shuaiwen Leon Song, Xin Fu*

### SC

#### 2016

1. **SERF: Efficient Scheduling for Fast Deep Neural Network Serving via Judicious Parallelism** SC 2016 ![](https://img.shields.io/badge/Inference-blue) ![](https://img.shields.io/badge/Resource-cc9e08)![](https://img.shields.io/badge/Parallel-blueviolet)

   *Feng Yan, Olatunji Ruwase, Yuxiong He, Evgenia Smirni*

2. **Optimizing Memory Efficiency for Deep Convolutional Neural Networks on GPUs** SC 2016 ![](https://img.shields.io/badge/Others-gray) 

   *Chao Li, Yi Yang, Min Feng, Srimat Chakradhar, Huiyang Zhou*

3. **dCUDA: Hardware Supported Overlap of Computation and Communication** SC 2016 ![](https://img.shields.io/badge/Hardware-green)

   *Tobias Gysi, Jeremia Bär, Torsten Hoefler*

4. **GreenLA: Green Linear Algebra Software for GPU-Accelerated Heterogeneous Computing** SC 2016 ![](https://img.shields.io/badge/Platform-034d0f)

   *Jieyang Chen, Li Tan, Panruo Wu, Dingwen Tao, Hongbo Li, Xin Liang, Sihuan Li, Rong Ge, Laxmi Bhuyan, Zizhong Chen*

5. **Merge-Based Parallel Sparse Matrix-Vector Multiplication (SpMV)** SC 2016 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Duane Merrill, Michael Garland*
   
   Code: https://github.com/dumerrill/mergespmv

#### 2018

1. **Large-Scale Hierarchical K-Means for Heterogeneous Many-Core Supercomputers** SC 2018 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Liandeng Li, Teng Yu, Wenlai Zhao, Haohuan Fu, Chenyu Wang, Li Tan, Guangwen Yang, John Thomson*

2. **TriCore: Parallel Triangle Counting on GPUs** SC 2018 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Graph-cc231e)

   *Yang Hu, Hang Liu, H. Howie Huang*

3. **Distributed-Memory Hierarchical Compression of Dense SPD Matrices** SC 2018 ![](https://img.shields.io/badge/Hardware-green)![](https://img.shields.io/badge/Parallel-blueviolet)

   *Chenhan D. Yu, Severin Reiz, George Biros*

4. **HiCOO: Hierarchical Storage of Sparse Tensors** SC 2018 ![](https://img.shields.io/badge/Hardware-green)

   *Jiajia Li, Jimeng Sun, Richard Vuduc*

   Code: https://github.com/hpcgarage/ParTI.

5. **Distributed Memory Sparse Inverse Covariance Matrix Estimation on High-Performance Computing Architectures** SC 2018 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Aryan Eftekhari, Matthias BollhöFer, Olaf Schenk*

6. **PruneJuice: Pruning Trillion-Edge Graphs to a Precise Pattern-Matching Solution** SC 2018 ![](https://img.shields.io/badge/Graph-cc231e)

   *Tahsin Reza, Matei Ripeanu, Nicolas Tripoul, Geoffrey Sanders, Roger Pearce*

   Code: https://github.com/LLNL/havoqgt

7. **Exploring Flexible Communications for Streamlining DNN Ensemble Training Pipelines** SC 2018 ![](https://img.shields.io/badge/Training-red)

   *Randall Pittman, Hui Guan, Xipeng Shen, Seung-Hwan Lim, Robert M. Patton*

8. **Anatomy of High-Performance Deep Learning Convolutions on SIMD Architectures** SC 2018 ![](https://img.shields.io/badge/Others-gray)

   *Evangelos Georganas, Sasikanth Avancha, Kunal Banerjee, Dhiraj Kalamkar, Greg Henry, Hans Pabst, Alexander Heinecke*

9. **Fault Tolerant One-Sided Matrix Decompositions on Heterogeneous Systems with GPUs** SC 2018 ![](https://img.shields.io/badge/Hardware-green)

   *Jieyang Chen, Hongbo Li, Sihuan Li, Xin Liang, Panruo Wu, Dingwen Tao, Kaiming Ouyang, Yuanlai Liu, Kai Zhao, Qiang Guan, Zizhong Chen*

#### 2019

1. **Large-Batch Training for LSTM and Beyond** SC 2019 ![](https://img.shields.io/badge/Training-red)

   *Yang You, Jonathan Hseu, Chris Ying, James Demmel, Kurt Keutzer, Cho-Jui Hsieh*

2. **Channel and Filter Parallelism for Large-Scale CNN Training** SC 2019 ![](https://img.shields.io/badge/Parallel-blueviolet)![](https://img.shields.io/badge/Training-red)

   *Nikoli Dryden, Naoya Maruyama, Tim Moon, Tom Benson, Marc Snir, Brian Van Essen*

3. **SparCML: High-Performance Sparse Communication for Machine Learning** SC 2019 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Cedric Renggli, Saleh Ashkboos, Mehdi Aghagolzadeh, Dan Alistarh, and Torsten Hoefler*

4. **PruneTrain: Fast Neural Network Training by Dynamic Sparse Model Reconfiguration** SC 2019 ![](https://img.shields.io/badge/Training-red)

   *Sangkug Lym, Esha Choukse, Siavash Zangeneh, Wei Wen, Sujay Sanghavi, Mattan Erez*

5. **Scalable Reinforcement-Learning-Based Neural Architecture Search for Cancer Deep Learning Research** SC 2019 ![](https://img.shields.io/badge/Inference-blue)

   *Prasanna Balaprakash, Romain Egele, Misha Salim, Stefan Wild, Venkatram Vishwanath, Fangfang Xia, Tom Brettin, Rick Stevens*

6. **BSTC: A Novel Binarized-Soft-Tensor-Core Design for Accelerating Bit-Based Approximated Neural Nets** SC 2019 ![](https://img.shields.io/badge/Hardware-green)

   *Ang Li, Tong Geng, Tianqi Wang, Martin Herbordt, Shuaiwen Leon Song, Kevin Barker*
   
   Code: https://github.com/uuudown/SBNN

#### 2020

1. **A Parallel Framework for Constraint-Based Bayesian Network Learning via Markov Blanket Discovery** SC 2020 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Ankit Srivastava, Sriram Chockalingam, Srinivas Aluru*

   Code: https://github.com/asrivast28/ramBLe

2. **Recurrent Neural Network Architecture Search for Geophysical Emulation** SC 2020 ![](https://img.shields.io/badge/Inference-blue)

   *Romit Maulik, Romain Egele, Bethany Lusch, Prasanna Balaprakash*

   Code: https://github.com/rmjcs2020/Geophysical_NAS

3. **Accelerating Sparse DNN Models without Hardware-Support via Tile-Wise Sparsity** SC 2020 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Cong Guo, Bo Yang Hsueh, Jingwen Leng, Yuxian Qiu, Yue Guan, Zehuan Wang, Xiaoying Jia, Xipeng Li, Minyi Guo, Yuhao Zhu*

   Code: https://github.com/clevercool/TileSparsity

4. **Sparse GPU Kernels for Deep Learning** SC 2020 ![](https://img.shields.io/badge/Hardware-green)

   *Trevor Gale, Matei Zaharia,Cliff Young, Erich Elsen*

   Code: https://github.com/google-research/sputnik

5. **Scaling Distributed Deep Learning Workloads beyond the Memory Capacity with KARMA** SC 2020 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Mohamed Wahib, Haoyu Zhang, Truong Thao Nguyen, Aleksandr Drozd, Jens Domke, Lingqi Zhang, Ryousei Takano, Satoshi Matsuoka*

   Code: https://github.com/wahibium/SC20-KARMA-AD-Appendix-Description-

6. **ZeRO: Memory optimizations Toward Training Trillion Parameter Models** SC 2020 ![](https://img.shields.io/badge/Training-red)![](https://img.shields.io/badge/Parallel-blueviolet)

   *Samyam Rajbhandari, Jeff Rasley, Olatunji Ruwase, Yuxiong He*

7. **Kraken: Memory-Efficient Continual Learning for Large-Scale Real-Time Recommendations** SC 2020 ![](https://img.shields.io/badge/Inference-blue)

   *Minhui Xie, Kai Ren, Youyou Lu, Guangxu Yang,Qingxing Xu, Bihai Wu, Jiazhen Lin, Hongbo Ao, Wanhong Xu, Jiwu Shu*

   Code: https://github.com/adamadagradsgd/Kraken

8. **Optimizing Deep Learning Recommender Systems Training on CPU Cluster Architectures** SC 2020 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Dhiraj Kalamkar, Evangelos Georganas, Sudarshan Srinivasan, Jianping Chen, Mikhail Shiryaev, Alexander Heinecke*

9. **Herring: Rethinking the Parameter Server at Scale for the Cloud** SC 2020 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Indu Thangakrishnan, Derya Cavdar, Can Karakus, Piyush Ghai, Yauheni Selivonchyk, Cory Pruce*

10. **GEMS: GPU-Enabled Memory-Aware Model-Parallelism System for Distributed DNN Training** SC 2020 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

    *Arpan Jain, Ammar Ahmad Awan, Asmaa M. Aljuhani, Jahanzeb Maqbool Hashmi, Quentin G. Anthony, Hari Subramoni, Dhabaleswar K. Panda, Raghu Machiraju, Anil Parwani*

11. **Newton-ADMM: A Distributed GPU-Accelerated Optimizer for Multiclass Classification Problems** SC 2020 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Parallel-blueviolet)

    *Chih-Hao Fang, Sudhir B. Kylasa, Fred Roosta, Michael W. Mahoney, Ananth Grama*

    Code: https://github.com/fang150/Newton_ADMM

12. **Reducing Communication in Graph Neural Network Training** SC 2020 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Training-red)

    *Alok Tripathy, Katherine Yelick, Aydın Buluç*

    Code: https://github.com/PASSIONLab/CAGNET

13. **FeatGraph: A Flexible and Efficient Backend for Graph Neural Network Systems** SC 2020 ![](https://img.shields.io/badge/Graph-cc231e)

    *Yuwei Hu, Zihao Ye, Minjie Wang, Jiali Yu, Da Zheng, Mu Li, Zheng Zhang, Zhiru Zhang, Yida Wang*

    Code: https://github.com/dglai/FeatGraph

14. **GE-SpMM: General-Purpose Sparse Matrix-Matrix Multiplication on GPUs for Graph Neural Networks** ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Graph-cc231e)

    *Guyue Huang, Guohao Dai, Yu Wang, Huazhong Yang*

    Code: https://github.com/hgyhungry/ge-spmm

#### 2021

1. **KAISA: An Adaptive Second-Order Optimizer Framework for Deep Neural Networks** SC 2021 ![](https://img.shields.io/badge/Training-red)

   *J. Gregory Pauloski, Qi Huang, Lei Huang, Shivaram Venkataraman, Kyle Chard, Ian Foster, Zhao Zhang*

   Code: https://github.com/gpauloski/kfac_pytorch

2. **Tensor Processing Primitives: A Programming Abstraction for Efficiency And Portability in Deep Learning Workloads** SC 2021 ![](https://img.shields.io/badge/Compiler-206777)

   *Evangelos Georganas, Dhiraj Kalamkar, Sasikanth Avancha, Menachem Adelman, Cristina Anderson, Alexander Breuer, Jeremy Bruestle, Narendra Chaudhary, Abhisek Kundu, Denise Kutnick, Frank Laub, Vasimuddin Md, Sanchit Misra, Ramanarayan Mohanty, Hans Pabst, Barukh Ziv, Alexander Heinecke*

3. **ET: Re-Thinking Self-Attention for Transformer Models on GPUs** SC 2021  ![](https://img.shields.io/badge/Training-red)

   *Weihao Cui, Han Zhao, Quan Chen, Ningxin Zheng, Jingwen Leng, Jieru Zhao, Zhuo Song, Tao Ma, Yong Yang, Chao Li, Minyi Guo*

   Code: https://github.com/cctry/SCpaper-2021/tree/aedab163f44bff8dfad3745d4f57972cb7640cda

4. **Parallel Construction of Module Networks** SC 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Ankit Srivastava, Sriram P. Chockalingam, Maneesha Aluru, Srinivas Aluru*

   Code: https://github.com/asrivast28/ParsiMoNe

5. **Chimera: Efficiently Training Large-Scale Neural Networks with Bidirectional Pipelines** SC 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Shigang Li, Torsten Hoefler*

   Code: https://github.com/Shigangli/Chimera

6. **APNN-TC: Accelerating Arbitrary Precision Neural Networks on Ampere GPU Tensor Cores**  SC 2021 ![](https://img.shields.io/badge/Hardware-green)

   *Boyuan Feng, Yuke Wang, Tong Geng, Ang Li, Yufei Ding*

   Code: https://github.com/BoyuanFeng/APNN-TC

7. **Scalable Edge-based Hyperdimensional Learning System with Brain-like Neural Adaptation**  SC 2021 ![](https://img.shields.io/badge/Training-red)

   *Zhuowen Zou, Yeseong Kim, Farhad Imani, Haleh Alimohamadi, Rosario Cammarota, Mohsen Imani*

8. **Dr. Top-k: Delegate-Centric Top-k Computation on GPUs** SC 2021 ![](https://img.shields.io/badge/Inference-blue)

   *Anil Gaihre, Da Zheng, Scott Weitze, Lingda Li, Shuaiwen Leon Song, Caiwen Ding, Xiaoye S. Li, Hang Liu*

9. **Distributed Multigrid Neural Solver on Megavoxel Domains** SC 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Aditya Balu, Sergio Botelho, Biswajit Khara, Vinay Rao, Soumik Sarkar, Chinmay Hegde, Adarsh Krishnamurthy, Santi Adavani, Baskar Ganapathysubramanian*

10. **Efficient Large-Scale Language Model Training on GPU Clusters Using Megatron-LM** SC 2021 ![](https://img.shields.io/badge/Training-red)

    *Deepak Narayanan, Mohammad Shoeybi, Jared Casper, Patrick LeGresley, Mostofa Patwary, Vijay Korthikanti, Dmitri Vainbrand, Prethvi Kashinkunti, Julie Bernauer, Bryan Catanzaro, Amar Phanishayee, Matei Zaharia*

11. **ZeRO-Infinity: Breaking the GPU Memory Wall for Extreme Scale Deep Learning** SC 2021 ![](https://img.shields.io/badge/Hardware-green)

    *Samyam Rajbhandari, Olatunji Ruwase, Jeff Rasley, Shaden Smith, Yuxiong He*

12. **FedAT: A High-Performance and Communication-Efficient Federated Learning System with Asynchronous Tiers** SC 2021 ![](https://img.shields.io/badge/Training-red)

    *Zheng Chai, Yujing Chen, Ali Anwar, Liang Zhao, Yue Cheng, Huzefa Rangwala*

13. **DistGNN: Scalable Distributed Training for Large-Scale Graph Neural Networks** SC 2021 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Training-red)

    *Vasimuddin Md, Sanchit Misra, Guixiang Ma, Ramanarayan Mohanty, Evangelos Georganas, Alexander Heinecke, Dhiraj Kalamkar, Nesreen K. Ahmed, Sasikanth Avancha*

    Code: https://github.com/dmlc/dgl/pull/2914 (commit: cfb73e2)

14. **Efficient Scaling of Dynamic Graph Neural Networks** SC 2021 ![](https://img.shields.io/badge/Graph-cc231e)

    *Venkatesan T. Chakaravarthy, Shivmaran S. Pandian, Saurabh Raje, Yogish Sabharwal, Toyotaro Suzumura, Shashanka Ubaru*

15. **Efficient Tensor Core-Based GPU Kernels for Structured Sparsity Under Reduced Precision** SC 2021![](https://img.shields.io/badge/Hardware-green)

    *Zhaodong Chen, Zheng Qu, Liu Liu, Yufei Ding, Yuan Xie*

    Code: https://github.com/apuaaChen/vectorSparse

### NSDI

#### 2017

1. **Clipper: A Low-Latency Online Prediction Serving System** NSDI 2017 ![](https://img.shields.io/badge/Inference-blue)

   *Daniel Crankshaw, Xin Wang, Guilio Zhou, Michael J. Franklin, Joseph E. Gonzalez, Ion Stoica*

2. **Gaia: Geo-Distributed Machine Learning Approaching LAN Speeds** NSDI 2017 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Kevin Hsieh, Aaron Harlap, Nandita Vijaykumar, Dimitris Konomis, Gregory R. Ganger, and Phillip B. Gibbons, Onur Mutlu*

3. **TUX2: Distributed Graph Computation for Machine Learning** NSDI 2017 ![](https://img.shields.io/badge/Graph-cc231e) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Wencong Xiao, Jilong Xue, Youshan Miao, Zhen Li, Cheng Chen, Ming Wu, Wei Li, Lidong Zhou*

#### 2019

1. **Janus: Fast and Flexible Deep Learning via Symbolic Graph Execution of Imperative Programs** NSDI 2019 ![](https://img.shields.io/badge/Training-red)

   *Eunji Jeong, Sungwoo Cho, Gyeong-In Yu, Joo Seong Jeong, Dong-Jin Shin, and Byung-Gon Chun*

2. **BLAS-on-flash: An Efficient Alternative for Large Scale ML Training and Inference?** NSDI 2019 ![](https://img.shields.io/badge/Training-red)

   *Suhas Jayaram Subramanya and Harsha Vardhan Simhadri, Srajan Garg, Anil Kag and Venkatesh Balasubramanian*

   Code: https://github.com/Microsoft/BLAS-on-flash

3. **Tiresias: A GPU Cluster Manager for Distributed Deep Learning** NSDI 2019 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Juncheng Gu, Mosharaf Chowdhury, and Kang G. Shin, Yibo Zhu, Myeongjae Jeon, Junjie Qian, Hongqiang Liu, Chuanxiong Guo*

   Code: https://github.com/SymbioticLab/Tiresias

#### 2021

1. **Elastic Resource Sharing for Distributed Deep Learning** NSDI 2021 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Changho Hwang and Taehyun Kim, Sunghyun Kim, Jinwoo Shin and KyoungSoo Park*

2. **ATP: In-network Aggregation for Multi-tenant Learning** NSDI 2021 ![](https://img.shields.io/badge/Resource-cc9e08) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *ChonLam Lao, Yanfang Le and Kshiteej Mahajan, Yixi Chen and Wenfei Wu, Aditya Akella, Michael Swift*

3. **On the Use of ML for Blackbox System Performance Prediction** NSDI 2021 ![](https://img.shields.io/badge/Inference-blue)

   *Silvery Fu, Saurabh Gupta and Radhika Mittal, Sylvia Ratnasamy*

4. **Scaling Distributed Machine Learning with In-Network Aggregation** NSDI 2021 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Amedeo Sapio, Marco Canini, Chen-Yu Ho, Jacob Nelson, Panos Kalnis, Changhoon Kim, Arvind Krishnamurthy, Masoud Moshref,  Dan Ports, Peter Richtarik*

### ISCA

#### 2017

1. **In-Datacenter Performance Analysis of a Tensor Processing Unit** ISCA 2017 ![](https://img.shields.io/badge/Hardware-green)

   *Norman P. Jouppi, Cliff Young, Nishant Patil, David Patterson, Gaurav Agrawal, Raminder Bajwa, Sarah Bates, Suresh Bhatia, Nan Boden, Al Borchers, Rick Boyle, Pierre-luc Cantin, Clifford Chao, Chris Clark, Jeremy Coriell, Mike Daley, Matt Dau, Jeffrey Dean, Ben Gelb, Tara Vazir Ghaemmaghami, Rajendra Gottipati, William Gulland, Robert Hagmann, C. Richard Ho, Doug Hogberg, John Hu, Robert Hundt, Dan Hurt, Julian Ibarz, Aaron Jaffey, Alek Jaworski, Alexander Kaplan, Harshit Khaitan, Daniel Killebrew, Andy Koch, Naveen Kumar, Steve Lacy, James Laudon, James Law, Diemthu Le, Chris Leary, Zhuyuan Liu, Kyle Lucke, Alan Lundin, Gordon MacKean, Adriana Maggiore, Maire Mahony, Kieran Miller, Rahul Nagarajan, Ravi Narayanaswami, Ray Ni, Kathy Nix, Thomas Norrie, Mark Omernick, Narayana Penukonda, Andy Phelps, Jonathan Ross, Matt Ross, Amir Salek, Emad Samadiani, Chris Severn, Gregory Sizikov, Matthew Snelham, Jed Souter, Dan Steinberg, Andy Swing, Mercedes Tan, Gregory Thorson, Bo Tian, Horia Toma, Erick Tuttle, Vijay Vasudevan, Richard Walter, Walter Wang, Eric Wilcox, Doe Hyun Yoon*

2. **SCALEDEEP: A Scalable Compute Architecture for Learning and Evaluating Deep Networks** ISCA 2017 ![](https://img.shields.io/badge/Training-red)

   *Swagath Venkataramani, Ashish Ranjan, Subarno Banerjee, Dipankar Das, Sasikanth Avancha, Ashok Jagannathan, Ajaya Durg, Dheemanth Nagaraj, Bharat Kaul, Pradeep Dubey, Anand Raghunathan*

3. **SCNN: An Accelerator for Compressed-sparse Convolutional Neural Networks** ISCA 2017 ![](https://img.shields.io/badge/Training-red)

   *Angshuman Parashar, Minsoo Rhu, Anurag Mukkara, Antonio Puglielli, Rangharajan Venkatesan, Brucek Khailany, Joel Emer, Stephen W. Keckler, William J. Dally*

4. **Maximizing CNN Accelerator Efficiency Through Resource Partitioning** ISCA 2017 ![](https://img.shields.io/badge/Resource-cc9e08)

   *Yongming Shen, Michael Ferdman, Peter Milder*

5. **Scalpel: Customizing DNN Pruning to the Underlying Hardware Parallelism** ISCA 2017 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Jiecao Yu, Andrew Lukefahr, David Palframan, Ganesh Dasika, Reetuparna Das, Scott Mahlke*

6. **Understanding and Optimizing Asynchronous Low-Precision Stochastic Gradient Descent** ISCA 2017 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Christopher De Sa, Matthew Feldman, Christopher Ré, Kunle Olukotun*

#### 2018

1. **PROMISE: An End-to-End Design of a Programmable Mixed-Signal Accelerator for Machine-Learning Algorithms** ISCA 2018 ![](https://img.shields.io/badge/Compiler-206777)

   *Prakalp Srivastava, Mingu Kang, Sujan K. Gonugondla, Sungmin Lim, Jungwook Choi, Vikram Adve, Nam Sung Kim, Naresh   Shanbhag*

2. **Computation Reuse in DNNs by Exploiting Input Similarity** ISCA 2018 ![](https://img.shields.io/badge/Inference-blue)

   *Marc Riera, Jose-Maria Arnau, Antonio González*

3. **GenAx: A Genome Sequencing Accelerator** ISCA 2018 ![](https://img.shields.io/badge/Inference-blue)

   *Daichi Fujiki, Aran Subramaniyan, Tianjun Zhang, Yu Zeng, Reetuparna Das, David Blaauw, Satish Narayanasamy*

4. **GANAX: A Unified MIMD-SIMD Acceleration for Generative Adversarial Networks** ISCA 2018 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Training-red)

   *Amir Yazdanbakhsh, Kambiz Samadi, Nam Sung Kim, Hadi Esmaeilzadeh*

5. **SnaPEA: Predictive Early Activation for Reducing Computation in Deep Convolutional Neural Networks** ISCA 2018 ![](https://img.shields.io/badge/Training-red)

   *Vahideh Akhlaghi, Amir Yazdanbakhsh, Kambiz Samadi, Rajesh K. Gupta, Hadi Esmaeilzadeh*

6. **UCNN: Exploiting Computational Reuse in Deep Neural Networks via Weight Repetition** ISCA 2018 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Hardware-green)

   *Kartik Hegde, Jiyong Yu, Rohit Agrawal, Mengjia Yan, Michael Pellauer, Christopher W. Fletcher*

7. **Energy-Efficient Neural Network Accelerator Based on Outlier-Aware Low-Precision Computation** ISCA 2018 ![](https://img.shields.io/badge/Hardware-green)

   *Eunhyeok Park, Dongyoung Kim, Sungjoo Yoo*

8. **Prediction based Execution on Deep Neural Networks** ISCA 2018 ![](https://img.shields.io/badge/Inference-blue)

   *Mingcong Song, Jiechen Zhao, Yang Hu, Jiaqi Zhang, Tao Li*

9. **Bit Fusion: Bit-Level Dynamically Composable Architecture for Accelerating Deep Neural Network** ISCA 2018 ![](https://img.shields.io/badge/Hardware-green)

   *Hardik Sharma, Jongse Park, Naveen Suda, Liangzhen Lai, Benson Chau, Vikas Chandra, Hadi Esmaeilzadeh*

10. **Gist: Efficient Data Encoding for Deep Neural Network Training** ISCA 2018 ![](https://img.shields.io/badge/Training-red)

    *Animesh Jain, Amar Phanishayee, Jason Mars, Lingjia Tang, Gennady Pekhimenko*

11. **The Dark Side of DNN Pruning** ISCA 2018 ![](https://img.shields.io/badge/Inference-blue)

    *Reza Yazdani, Marc Riera, Jose-Maria Arnau, Antonio González*

#### 2019

1. **Sparse ReRAM Engine: Joint exploration of activation and weight sparsity on compressed neural network** ISCA 2019 ![](https://img.shields.io/badge/Inference-blue)

   *Tzu-Hsien Yang, Hsiang-Yun Cheng, Chia-Lin Yang, I-Ching Tseng, Han-Wen Hu, Hung-Sheng Chang, Hsiang-Pang Li*

2. **MnnFast: A Fast and Scalable System Architecture for Memory-Augmented Neural Networks** ISCA 2019 ![](https://img.shields.io/badge/Hardware-green)

   *Hanhwi Jang, Joonsung Kim, Jae-Eon Jo, Jaewon Lee, Jangwoo Kim*

3. **TIE: Energy-efficient tensor train-based inference engine for deep neural network** ISCA 2019 ![](https://img.shields.io/badge/Inference-blue)

   *Chunhua Deng, Fangxuan Sun, Xuehai Qian, Jun Lin, Zhongfeng Wang, Bo Yuan*

4. **Accelerating Distributed Reinforcement Learning with In-Switch Computing** ISCA 2019 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Youjie Li, Iou-Jen Liu, Yifan Yuan, Deming Chen, Alexander Schwing, Jian Huang*

5. **Eager Pruning: Algorithm and Architecture Support for Fast Training of Deep Neural Networks** ISCA 2019 ![](https://img.shields.io/badge/Training-red)

   *Jiaqi Zhang, Xiangru Chen, Mingcong Song, Tao Li*

6. **Laconic Deep Learning Inference Acceleration** ISCA 2019 ![](https://img.shields.io/badge/Inference-blue)

   *Sayeh Sharify, Alberto Delmas Lascorz, Mostafa Mahmoud, Milos Nikolic, Kevin Siu, Dylan Malone Stuart, Zissis Poulos, Andreas Moshovos*

7. **DeepAttest: An End-to-End Attestation Framework for Deep Neural Networks** ISCA 2019 ![](https://img.shields.io/badge/Security-85144b)![](https://img.shields.io/badge/Training-red)

   *Huili Chen, Cheng Fu, Bita Darvish Rouhani, Jishen Zhao, Farinaz Koushanfar*

#### 2020

1. **High-Performance Deep-Learning Coprocessor Integrated into x86 SoC with Server-Class CPUs** ISCA 2020 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Glenn Henry, Parviz Palangpour, Michael Thomson, J Scott Gardner, Bryce Arden, Kimble Houck, Jonathan Johnson, Kyle O'Brien, Scott Petersen, Benjamin Seroussi, Tyler Walker*

2. **Think Fast: A Tensor Streaming Processor (TSP) for Accelerating Deep Learning Workloads**  ISCA 2020 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Dennis Abts, Jonathan Ross, Jon Sparling, Mark Wong-VanHaren, Max Baker, Tom Hawkins, Andrew Bell, John Thompson, Teme Kahsai, Garrin Kimmell, Jennifer Hwang, Rebekah Leslie-Hurd, Michael Bye, Rogan Creswick, Matthew Boyd, Mahitha Venigalla, Evan Laforge, Jon Purdy, Utham Kamath, Dinesh Maheshwari, Michael Beidler, Geert Rosseel, Omar Ahmad, Gleb Gagarin, Rick Czekalski, Ashay Rane, Sahil Parmar*

3. **Gorgon: Accelerating Machine Learning from Relational Data**  ISCA 2020 ![](https://img.shields.io/badge/Data-ff69b4)

   *Matthew Vilim, Alexander Rucker, Yaqi Zhang, Sophia Liu, Kunle Olukotun*

4. **SpinalFlow: An Architecture and Dataflow Tailored for Spiking Neural Networks** ISCA 2020 ![](https://img.shields.io/badge/Data-ff69b4)

   *Surya Narayanan, Karl Taht, Rajeev Balasubramonian, Edouard Giacomin, Pierre-Emmanuel Gaillardon*

5. **NEBULA: A Neuromorphic Spin-Based Ultra-Low Power Architecture for SNNs and ANNs** ISCA 2020 ![](https://img.shields.io/badge/Hardware-green)

   *Sonali Singh, Anup Sarma, Nicholas Jao, Ashutosh Pattnaik, Sen Lu, Kezhou Yang, Abhronil Sengupta, Vijaykrishnan Narayanan, Chita R. Das*

6. **uGEMM: Unary Computing Architecture for GEMM Applications** ISCA 2020 ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Di Wu, Jingjie Li, Ruokai Yin, Hsuan Hsiao, Younghyun Kim, Joshua San Miguel*

7. **Buddy Compression: Enabling Larger Memory for Deep Learning and HPC Workloads on GPUs** ISCA 2020 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Hardware-green)

   *Esha Choukse, Michael B. Sullivan, Mike O’Connor, Mattan Erez, Jeff Pool, David Nellans, Stephen W. Keckler*

8. **A Multi-Neural Network Acceleration Architecture** ISCA 2020 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Resource-cc9e08)

   *Eunjin Baek, Dongup Kwon, Jangwoo Kim*

9. **SmartExchange: Trading Higher-Cost Memory Storage/Access for Lower-Cost Computation** ISCA 2020 ![](https://img.shields.io/badge/Inference-blue) 

   *Yang Zhao, Xiaohan Chen, Yue Wang, Chaojian Li, Haoran You, Yonggan Fu, Yuan Xie, Zhangyang Wang, Yingyan Lin*

10. **Centaur: A Chiplet-based, Hybrid Sparse-Dense Accelerator for Personalized Recommendations** ISCA 2020 ![](https://img.shields.io/badge/Hardware-green)

    *Ranggi Hwang, Taehun Kim, Youngeun Kwon, Minsoo Rhu*

11. **DeepRecSys: A System for Optimizing End-to-End At-Scale Neural Recommendation Inference** ISCA 2020 ![](https://img.shields.io/badge/Inference-blue)

    *Udit Gupta, Samuel Hsia, Vikram Saraph, Xiaodong Wang, Brandon Reagen, Gu-Yeon Wei, Hsien-Hsin S. Lee, David Brooks, Carole-Jean Wu*

12. **An In-Network Architecture for Accelerating Shared-Memory Multiprocessor Collectives** ISCA 2020 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/Hardware-green)

    *Benjamin Klenk, Nan Jiang, Greg Thorson, Larry Dennison*

13. **DRQ: Dynamic Region-Based Quantization for Deep Neural Network Acceleration** ISCA 2020 ![](https://img.shields.io/badge/Inference-blue)

    *Zhuoran Song, Bangqi Fu, Feiyang Wu, Zhaoming Jiang, Li Jiang, Naifeng Jing, Xiaoyao Liang*

#### 2021

1. **RaPiD: AI Accelerator for Ultra-Low Precision Training and Inference** ISCA 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Inference-blue)

   *Swagath Venkataramani, Vijayalakshmi Srinivasan, Wei Wang, Sanchari Sen, Jintao Zhang, Ankur Agrawal, Monodeep Kar, Shubham Jain, Alberto Mannari, Hoang Tran, Yulong Li, Eri Ogawa, Kazuaki Ishizaki, Hiroshi Inoue, Marcel Schaal, Mauricio Serrano, Jungwook Choi, Xiao Sun, Naigang Wang, Chia-Yu Chen, Allison Allain, James Bonano, Nianzheng Cao, Robert Casatuta, Matthew Cohen, Bruce Fleischer, Michael Guillorn, Howard Haynie, Jinwook Jung, Mingu Kang, Kyu-hyoun Kim, Siyu Koswatta, Saekyu Lee, Martin Lutz, Silvia Mueller, Jinwook Oh, Ashish Ranjan, Zhibin Ren, Scot Rider, Kerstin Schelm, Michael Scheuermann, Joel Silberman, Jie Yang, Vidhi Zalani, Xin Zhang, Ching Zhou, Matt Ziegler, Vinay Shah, Moriyoshi Ohara, Pong-Fei Lu, Brian Curran, Sunil Shukla, Leland Chang, Kailash Gopalakrishnan*

2. **REDUCT: Keep It Close, Keep It Cool! - Scaling DNN Inference on Multi-Core CPUs with Near-Cache Compute** ISCA 2021 ![](https://img.shields.io/badge/Inference-blue) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Anant V. Nori, Rahul Bera, Shankar Balachandran, Joydeep Rakshit, Om J. Omer, Avishaii Abuhatzera, Belliappa Kuttanna, Sreenivas Subramoney*

3. **Communication Algorithm-Architecture Co-Design for Distributed Deep Learning** ISCA 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Parallel-blueviolet)

   *Jiayi Huang, Pritam Majumder, Sungkeun Kim, Abdullah Muzahid, Ki Hwan Yum, Eun Jung Kim*

4. **Hetero-ViTAL: A Virtualization Stack for Heterogeneous FPGA Clusters** ISCA 2021 ![](https://img.shields.io/badge/Compiler-206777)

   *Yue Zha, Jing LiYue Zha, Jing Li*

5. **Enabling Compute-Communication Overlap in Distributed Deep Learning Training Platforms** ISCA 2021 ![](https://img.shields.io/badge/Training-red)

   *Saeed Rashidi, Matthew Denton, Srinivas Sridharan, Sudarshan Srinivasan, Amoghavarsha Suresh, Jade Nie, Tushar Krishna*

6. **CoSA: Scheduling by Constrained Optimization for Spatial Accelerators** ISCA 2021 ![](https://img.shields.io/badge/Resource-cc9e08) ![](https://img.shields.io/badge/Compiler-206777)

   *Qijing Huang, Aravind Kalaiah, Minwoo Kang, James Demmel, Grace Dinh, John Wawrzynek, Thomas Norell, Yakun Sophia Shao*

7. **η-LSTM: Co-Designing Highly-Efficient Large LSTM Training via Exploiting Memory-Saving and Architectural Design Opportunities** ISCA 2021 ![](https://img.shields.io/badge/Training-red)

   *Xingyao Zhang, Haojun Xia, Donglin Zhuang, Hao Sun, Xin Fu, Michael B. Taylor, Shuaiwen Leon Song*

8. **SPACE: Locality-Aware Processing in Heterogeneous Memory for Personalized Recommendations** ISCA 2021 ![](https://img.shields.io/badge/Hardware-green)

   *Hongju Kal, Seokmin Lee, Gun Ko, Won Woo Ro*

9. **ELSA: Hardware-Software Co-Design for Efficient, Lightweight Self-Attention Mechanism in Neural Networks** ISCA 2021 ![](https://img.shields.io/badge/Hardware-green)

   *Tae Jun Ham, Yejin Lee, Seong Hoon Seo, Soosung Kim, Hyunji Choi, Sung Jun Jung, Jae W. Lee*

10. **Cambricon-Q: A Hybrid Architecture for Efficient Training** ISCA 2021 ![](https://img.shields.io/badge/Training-red)

    *Yongwei Zhao, Chang Liu, Zidong Du, Qi Guo, Xing Hu, Yimin Zhuang, Zhenxing Zhang, Xinkai Song, Wei Li, Xishan Zhang, Ling Li, Zhiwei Xu, Tianshi Chen*

11. **TENET: A Framework for Modeling Tensor Dataflow Based on Relation-Centric Notation** ISCA 2021 ![](https://img.shields.io/badge/Compiler-206777)

    *Liqiang Lu, Naiqing Guan, Yuyue Wang, Liancheng Jia, Zizhang Luo, Jieming Yin, Jason Cong, Yun Liang*

    Code: https://github.com/pku-liang/TENET

12. **NASGuard: A Novel Accelerator Architecture for Robust Neural Architecture Search (NAS) Networks** ISCA 2021 ![](https://img.shields.io/badge/Parallel-blueviolet) ![](https://img.shields.io/badge/AutoML-06046e)

    *Xingbin Wang, Boyan Zhao, Rui Hou, Amro Awad, Zhihong Tian, Dan Meng*

13. **NASA: Accelerating Neural Network Design with a NAS Processor** ISCA 2021 ![](https://img.shields.io/badge/Training-red) ![](https://img.shields.io/badge/Resource-cc9e08)![](https://img.shields.io/badge/AutoML-06046e) 

    *Xiaohan Ma, Chang Si, Ying Wang, Cheng Liu, Lei Zhang*

14. **NN-Baton: DNN Workload Orchestration and Chiplet Granularity Exploration for Multichip Accelerators** ISCA 2021 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Resource-cc9e08)

    *Zhanhong Tan, Hongyu Cai, Runpei Dong, Kaisheng Ma*

15. **HASCO: Towards Agile Hardware and Software CO-design for Tensor Computation** ISCA 2021 ![](https://img.shields.io/badge/Hardware-green) ![](https://img.shields.io/badge/Platform-034d0f)

    *Qingcheng Xiao, Size Zheng, Bingzhe Wu, Pengcheng Xu, Xuehai Qian, Yun Liang*

    Code: https://github.com/pku-liang/HASCO

16. **Dual-Side Sparse Tensor Core** ISCA 2021 ![](https://img.shields.io/badge/Platform-034d0f)

    *Yang Wang, Chen Zhang, Zhiqiang Xie, Cong Guo, Yunxin Liu, Jingwen Leng*

17. **RingCNN: Exploiting Algebraically-Sparse Ring Tensors for Energy-Efficient CNN-Based Computational Imaging** ISCA 2021   ![](https://img.shields.io/badge/Hardware-green)

    *Chao-Tsung Huang*

18. **GoSPA: An Energy-Efficient High-Performance Globally Optimized SParse Convolutional Neural Network Accelerator** ISCA 2021 ![](https://img.shields.io/badge/Hardware-green)

    *Chunhua Deng, Yang Sui, Siyu Liao, Xuehai Qian, Bo Yuan*

## Contributors

Contributed by [Xupeng Miao](https://github.com/Hsword), [Zihao Yu](https://github.com/Hankpipi), [Chunan Shi](https://github.com/SpiritedAwayCN).