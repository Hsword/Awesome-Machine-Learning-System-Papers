# Awesome-Machine-Learning-System-Papers

**Awesome-Machine-Learning-System-Papers** is a curated list of *machine learning system* papers in recent years (since 2017). **Star** this repository, and then you can keep abreast of the latest developments of this booming research field. 

Thanks to all the people who made contributions to this project. We strongly encourage the researchers to make **pull request** and help the others in this community!

<!-- omit in toc -->
## Conference

Currently, the listed papers are collected from the following conferences:


| Conferences | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2022 | 2023 | 2024 | 2025 |
|-------------|------|------|------|------|------|------|------|------|------|------|
| [OSDI](#osdi)      |   3   |   -   |   4   |   -   |   11   |   8   |      |      |      |      |
| [SOSP](#sosp)      |   -   |   1   |   -   |   10   |      |      |      |      |      |      |
| [SIGMOD](#sigmod)  |   2   |   4   |   3   |   4   |   8   |   16   |      |      |      |      |
| [ASPLOS](#asplos)  |   -   |   3   |   3   |   9   |   4   |      |      |      |      |      |
| [ATC](#atc)        |   -   |   2   |   3   |   5   |      |      |      |      |      |      |
| [PPoPP](#ppopp)    |   -   |   3   |   5   |   2   |      |      |      |      |      |      |
| [HPCA](#hpca)    |   -   |   3   |   4   |   4   |   1   |      |      |      |      |      |
| [MICRO](#micro)    |   -   |   4   |   6   |   9   |      |      |      |      |      |      |
| [SC](#sc)   |    5  |   -   |   9   |   6   |      |      |      |      |      |      |
| [NSDI](#nsdi)    |   -   |    3  |   -   |   3   |      |      |      |      |      |      |
| [ISCA](#isca)    |   -   |   6   |   11   |   7   |      |      |      |      |      |      |

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

## Papers

### OSDI 

#### 2016

1. **TensorFlow: A System for Large-Scale Machine Learning** OSDI 2016

   *Martín Abadi, Paul Barham, Jianmin Chen, Zhifeng Chen, Andy Davis, Jeffrey Dean, Matthieu Devin, Sanjay Ghemawat, Geoffrey Irving, Michael Isard, Manjunath Kudlur, Josh Levenberg, Rajat Monga, Sherry Moore, Derek Gordon Murray, Benoit Steiner, Paul A. Tucker, Vijay Vasudevan, Pete Warden, Martin Wicke, Yuan Yu, Xiaoqiang Zheng*
   
   Code: [https://github.com/tensorflow/tensorflow](https://github.com/tensorflow/tensorflow)

2. **Exploring the Hidden Dimension in Graph Processing** OSDI 2016

	*Mingxing Zhang, Yongwei Wu, Kang Chen, Xuehai Qian, Xue Li, Weimin Zheng*

3. **Gemini: A Computation-Centric Distributed Graph Processing System** OSDI 2016

	*Xiaowei Zhu, Wenguang Chen, Weimin Zheng, Xiaosong Ma*
	
	Code: [https://github.com/thu-pacman/GeminiGraph](https://github.com/thu-pacman/GeminiGraph)


#### 2018

1. **Ray: A Distributed Framework for Emerging AI Applications** OSDI 2018

	*Philipp Moritz, Robert Nishihara, Stephanie Wang, Alexey Tumanov, Richard Liaw, Eric Liang, Melih Elibol, Zongheng Yang, William Paul, Michael I. Jordan, Ion Stoica*
	
	Code: [https://github.com/ray-project/ray](https://github.com/ray-project/ray)
	
2. **TVM: An Automated End-to-End Optimizing Compiler for Deep Learning** OSDI 2018

	*Tianqi Chen, Thierry Moreau, Ziheng Jiang, Lianmin Zheng, Eddie Q. Yan, Haichen Shen, Meghan Cowan, Leyuan Wang, Yuwei Hu, Luis Ceze, Carlos Guestrin, Arvind Krishnamurthy*
	
	Code: [https://github.com/apache/tvm](https://github.com/apache/tvm)
	
3. **Gandiva: Introspective Cluster Scheduling for Deep Learning** OSDI 2018

	*Wencong Xiao, Romil Bhardwaj, Ramachandran Ramjee, Muthian Sivathanu, Nipun Kwatra, Zhenhua Han, Pratyush Patel, Xuan Peng, Hanyu Zhao, Quanlu Zhang, Fan Yang, Lidong Zhou*
	
4. **PRETZEL: Opening the Black Box of Machine Learning Prediction Serving Systems** OSDI 2018

	*Yunseong Lee, Alberto Scolari, Byung-Gon Chun, Marco Domenico Santambrogio, Markus Weimer, Matteo Interlandi*

#### 2020

1. **Serving DNNs like Clockwork: Performance Predictability from the Bottom Up** OSDI 2020

   *Arpan Gujarati, Reza Karimi, Safya Alzayat, Wei Hao, Antoine Kaufmann, Ymir Vigfusson, Jonathan Mace*

2. **A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters** OSDI 2020

   *Yimin Jiang, Yibo Zhu, Chang Lan, Bairen Yi, Yong Cui, Chuanxiong Guo*

3. **Heterogeneity-Aware Cluster Scheduling Policies for Deep Learning Workloads** OSDI 2020

   *Deepak Narayanan, Keshav Santhanam, Fiodar Kazhamiaka, Amar Phanishayee, Matei Zaharia*

4. **PipeSwitch: Fast Pipelined Context Switching for Deep Learning Applications** OSDI 2020

   *Zhihao Bai, Zhen Zhang, Yibo Zhu, Xin Jin*

5. **HiveD: Sharing a GPU Cluster for Deep Learning with Guarantees** OSDI 2020

   *Hanyu Zhao, Zhenhua Han, Zhi Yang, Quanlu Zhang, Fan Yang, Lidong Zhou, Mao Yang, Francis C. M. Lau, Yuqi Wang, Yifan Xiong, Bin Wang*

6. **AntMan: Dynamic Scaling on GPU Clusters for Deep Learning** OSDI 2020

   *Wencong Xiao, Shiru Ren, Yong Li, Yang Zhang, Pengyang Hou, Zhi Li, Yihui Feng, Wei Lin, Yangqing Jia*
	
7. **Ansor: Generating High-Performance Tensor Programs for Deep Learning** OSDI 2020

	*Lianmin Zheng, Chengfan Jia, Minmin Sun, Zhao Wu, Cody Hao Yu, Ameer Haj-Ali, Yida Wang, Jun Yang, Danyang Zhuo, Koushik Sen, Joseph E. Gonzalez, Ion Stoica*


8. **Rammer: Enabling Holistic Deep Learning Compiler Optimizations with rTasks** OSDI 2020

	*Lingxiao Ma, Zhiqiang Xie, Zhi Yang, Jilong Xue, Youshan Miao, Wei Cui, Wenxiang Hu, Fan Yang, Lintao Zhang, Lidong Zhou*

9. **A Tensor Compiler for Unified Machine Learning Prediction Serving** OSDI 2020

	*Supun Nakandala, Karla Saur, Gyeong-In Yu, Konstantinos Karanasos, Carlo Curino, Markus Weimer, Matteo Interlandi*

10. **Retiarii: A Deep Learning Exploratory-Training Framework** OSDI 2020

	*Quanlu Zhang, Zhenhua Han, Fan Yang, Yuge Zhang, Zhe Liu, Mao Yang, Lidong Zhou*

11. **KungFu: Making Training in Distributed Machine Learning Adaptive**
	
	*Luo Mai, Guo Li, Marcel Wagenländer, Konstantinos Fertakis, Andrei-Octavian Brabete, Peter R. Pietzuch*

#### 2021

1. **Pollux: Co-adaptive Cluster Scheduling for Goodput-Optimized Deep Learning** OSDI 2021
	
	*Aurick Qiao, Sang Keun Choe, Suhas Jayaram Subramanya, Willie Neiswanger, Qirong Ho, Hao Zhang, Gregory R. Ganger, Eric P. Xing*


2. **Oort: Efficient Federated Learning via Guided Participant Selection** OSDI 2021

	*Fan Lai, Xiangfeng Zhu, Harsha V. Madhyastha, Mosharaf Chowdhury*

3. **PET: Optimizing Tensor Programs with Partially Equivalent Transformations and Automated Corrections** OSDI 2021

	*Haojie Wang, Jidong Zhai, Mingyu Gao, Zixuan Ma, Shizhi Tang, Liyan Zheng, Yuanzhi Li, Kaiyuan Rong, Yuanyong Chen, Zhihao Jia*
	
4. **Privacy Budget Scheduling** OSDI 2021

	*Tao Luo, Mingen Pan, Pierre Tholoniat, Asaf Cidon, Roxana Geambasu, Mathias Lécuyer*

5. **Dorylus: Affordable, Scalable, and Accurate GNN Training with Distributed CPU Servers and Serverless Threads** OSDI 2021

	*John Thorpe, Yifan Qiao, Jonathan Eyolfson, Shen Teng, Guanzhou Hu, Zhihao Jia, Jinliang Wei, Keval Vora, Ravi Netravali, Miryung Kim, Guoqing Harry Xu*
	
6. **GNNAdvisor: An Adaptive and Efficient Runtime System for GNN Acceleration on GPUs** OSDI 2021

	*Yuke Wang, Boyuan Feng, Gushu Li, Shuangchen Li, Lei Deng, Yuan Xie, Yufei Ding*

7. **Marius: Learning Massive Graph Embeddings on a Single Machine** OSDI 2021

	*Jason Mohoney, Roger Waleffe, Henry Xu, Theodoros Rekatsinas, Shivaram Venkataraman*

8. **P3: Distributed Deep Graph Learning at Scale** OSDI 2021

	*Swapnil Gandhi, Anand Padmanabha Iyer*

### SOSP

#### 2017

1. **DeepXplore: Automated Whitebox Testing of Deep Learning Systems** SOSP 2017

#### 2019

1. **PipeDream: Generalized Pipeline Parallelism for DNN Training** SOSP 2019
2. **A Generic Communication Scheduler for Distributed DNN Training Acceleration** SOSP 2019
3. **Parity Models: Erasure-Coded Resilience for Prediction Serving Systems** SOSP 2019
4. **TASO: Optimizing Deep Learning Computation with Automated Generation of Graph Substitutions** SOSP 2019
5. **Optimizing Data-Intensive Computations in Existing Libraries with Split Annotations** SOSP 2019
6. **Niijima: Sound and Automated Computation Consolidation for Efficient Multilingual Data-Parallel Pipelines** SOSP 2019
7. **Nexus: A GPU Cluster Engine for Accelerating DNN-Based Video Analysis** SOSP 2019
8. **AutoMine: Harmonizing High-Level Abstraction and High Performance for Graph Mining** SOSP 2019
9. **KnightKing: A Fast Distributed Graph Random Walk Engine** SOSP 2019
10. **Gerenuk: Thin Computation over Big Native Data Using Speculative Program Transformation** SOSP 2019

### SIGMOD

#### 2016

1. **Building Machine Learning Systems that Understand** SIGMOD 2016
2. **M3: Scaling Up Machine Learning via Memory Mapping** SIGMOD 2016

#### 2017

1. **Heterogeneity-aware Distributed Parameter Servers** SIGMOD 2017
2. **Bolt-on Differential Privacy for Scalable Stochastic Gradient Descent-based Analytics** SIGMOD 2017
3. **Data Management in Machine Learning: Challenges, Techniques, and Systems** SIGMOD 2017
4. **Data Management Challenges in Production Machine Learning** SIGMOD 2017

#### 2018

1.	**DimBoost: Boosting Gradient Boosting Decision Tree to Higher Dimensions** SIGMOD 2018
2.	**SketchML: Accelerating Distributed Machine Learning with Data Sketches** SIGMOD 2018
3.	**Accelerating Machine Learning Inference with Probabilistic Predicates** SIGMOD 2018

#### 2019

1. **PS2: Parameter Server on Spark** SIGMOD 2019
2.	**Large Scale Graph Mining with G-Miner** SIGMOD 2019
3.	**BlinkML: Efficient Maximum Likelihood Estimation with Probabilistic Guarantees** SIGMOD 2019
4.	**Democratizing Data Science through Interactive Curation of ML Pipelines** SIGMOD 2019

#### 2020

1.	**Memory-Aware Framework for Efficient Second-Order Random Walk on Large Graphs** SIGMOD 2020
2.	**TensorFlow Data Validation: Data Analysis and Validation in Continuous ML Pipelines** SIGMOD 2020
3.	**Optimizing Machine Learning Workloads in Collaborative Environments** SIGMOD 2020
4.	**Vertica-ML: Distributed Machine Learning in Vertica Database** SIGMOD 2020
5.	**DB4ML - An In-Memory Database Kernel with Machine Learning Support** SIGMOD 2020
6.	**Active Learning for ML Enhanced Database Systems** SIGMOD 2020
7.	**MemFlow: Memory-Aware Distributed Deep Learning** SIGMOD 2020
8.	**Systems and ML: When the Sum is Greater than Its Parts** SIGMOD 2020

#### 2021

1.	**Heterogeneity-Aware Distributed Machine Learning Training via Partial Reduce** SIGMOD 2021
2.	**VF^2Boost: Very Fast Vertical Federated Gradient Boosting for Cross-Enterprise Learning** SIGMOD 2021
3.	**ALG: Fast and Accurate Active Learning Framework for Graph Convolutional Networks** SIGMOD 2021
4.	**Agile and Accurate CTR Prediction Model Training for Massive-Scale Online Advertising Systems** SIGMOD 2021
5.	**Production Machine Learning Pipelines: Empirical Analysis and Optimization Opportunities** SIGMOD 2021
6.	**Vertex-Centric Visual Programming for Graph Neural Networks** SIGMOD 2021
7.	**Deep Learning: Systems and Responsibility** SIGMOD 2021
8.	**Expand your Training Limits! Generating Training Data for ML-based Data Management** SIGMOD 2021
9.	**Towards Benchmarking Feature Type Inference for AutoML Platforms** SIGMOD 2021
10. **LightNE: A Lightweight Graph Processing System for Network Embedding** SIGMOD 2021
11.	**Scalable and Usable Relational Learning With Automatic Language Bias** SIGMOD 2021
12.	**Model-Parallel Model Selection for Deep Learning Systems** SIGMOD 2021
13.	**Automatic Optimization of Matrix Implementations for Distributed Machine Learning and Linear Algebra** SIGMOD 2021
14.	**Automation of Data Prep, ML, and Data Science: New Cure or Snake Oil?** SIGMOD 2021
15.	**Towards Demystifying Serverless Machine Learning Training** SIGMOD 2021
16.	**AI Meets Database: AI4DB and DB4AI** SIGMOD 2021

### ASPLOS

#### 2017

1.	**SaberLDA: Sparsity-Aware Learning of Topic Models on GPUs** ASPLOS 2017
2.	**SC-DCNN: Highly-Scalable Deep Convolutional Neural Network using Stochastic Computing** ASPLOS 2017
3.	**Optimizing CNNs on Multicores for Scalability, Performance and Goodput** ASPLOS 2017

#### 2018

1.	**Bridging the Gap Between Neural Networks and Neuromorphic Hardware with A Neural Network Compiler** ASPLOS 2018
2.	**MAERI: Enabling Flexible Dataflow Mapping over DNN Accelerators via Reconfigurable Interconnects** ASPLOS 2018
3.	**VIBNN: Hardware Acceleration of Bayesian Neural Networks** ASPLOS 2018

### 2019

1.	**PUMA: A Programmable Ultra-efficient Memristor-based Accelerator for Machine Learning Inference** ASPLOS 2019
2.	**FPSA: A Full System Stack Solution for Reconfigurable ReRAM-based NN Accelerator Architecture** ASPLOS 2019
3.	**Bit-Tactical: A Software/Hardware Approach to Exploiting Value and Bit Sparsity in Neural Networks** ASPLOS 20189
4.	**TANGRAM: Optimized Coarse-Grained Dataflow for Scalable NN Accelerators** ASPLOS 2019
5.	**Packing Sparse Convolutional Neural Networks for Efficient Systolic Array Implementations: Column Combining Under Joint Optimization** ASPLOS 2019
6.	**Split-CNN: Splitting Window-based Operations in Convolutional Neural Networks for Memory System Optimization** ASPLOS 2019
7.	**HOP: Heterogeneity-Aware Decentralized Training** ASPLOS 2019
8.	**Astra: Exploiting Predictability to Optimize Deep Learning** ASPLOS 2019
9.	**ADMM-NN: An Algorithm-Hardware Co-Design Framework of DNNs Using Alternating Direction Methods of Multipliers** ASPLOS 2019

### 2020

1.	**Prague: High-Performance Heterogeneity-Aware Asynchronouos Decentralized Training** ASPLOS 2020
2.	**Capuchin: Tensor-based GPU Memory Management for Deep Learning** ASPLOS 2020
3.	**DNN-Guard: An Elastic Heterogeneous Architecture for DNN Accelerator against Adversarial Attacks** ASPLOS 2020
4.	**PatDNN: Achieving Real-Time DNN Execution on Mobile Devices with Pattern-based Weight Pruning** ASPLOS 2020


### ATC

#### 2017

1.	**Poseidon: An Efficient Communication Architecture for Distributed Deep Learning on GPU Clusters** ATC 2017
2.	**Garaph: Efficient GPU-accelerated Graph Processing on a Single Machine with Balanced Replication** ATC 2017

### 2018

1.	**Litz: Elastic Framework for High-Performance Distributed Machine Learning** ATC 2018
2.	**Cavs: An Efficient Runtime System for Dynamic Neural Networks** ATC 2018
3.	**DeepCPU: Serving RNN-based Deep Learning Models 10x Faster** ATC 2018

### 2019

1.	**STRADS-AP: Simplifying Distributed Machine Learning Programming without Introducing a New Programming Model** ATC 2019
2.	**NeuGraph: Parallel Deep Neural Network Computation on Large Graphs** ATC 2019
3.	**Analysis of Large-Scale Multi-Tenant GPU Clusters for DNN Training Workloads** ATC 2019
4.	**Optimizing CNN Model Inference on CPUs** ATC 2019
5.	**MArk: Exploiting Cloud Services for Cost-Effective, SLO-Aware Machine Learning Inference Serving** ATC 2019

### PPoPP

#### 2017

1.	**Groute: An Asynchronous Multi-GPU Programming Model for Irregular Computations** PPoPP 2017
2.	**Exploiting Vector and Multicore Parallelism for Recursive Data- and Task-Parallel Programs** PPoPP 2017
3.	**S-Caffe: Co-designing MPI Runtimes and Caffe for Scalable Deep Learning on Modern GPU Clusters** PPoPP 2017

#### 2018

1.	**An Effective Fusion and Tile Size Model for Optimizing Image Processing Pipelines** PPoPP 2018
2.	**Bridging the Gap between Deep Learning and Sparse Matrix Format Selection** PPoPP 2018
3.	**LazyGraph: Lazy Data Coherency for Replicas in Distributed Graph-Parallel Computation** PPoPP 2018
4.	**Making Pull-Based Graph Processing Performant** PPoPP 2018
5.	**SuperNeurons: Dynamic GPU Memory Management for Training Deep Neural Networks** PPoPP 2018

#### 2019

1.	**Beyond Human-Level Accuracy: Computational Challenges in Deep Learning** PPoPP 2019
2.	**A Pattern Based Algorithmic Autotuner for Graph Processing on GPUs** PPoPP 2019

### HPCA

#### 2017

1.	**Towards Pervasive and User Satisfactory CNN across GPU Microarchitectures** HPCA 2017
2.	**PipeLayer: A Pipelined ReRAM-Based Accelerator for Deep Learning** HPCA 2017
3.	**FlexFlow: A Flexible Dataflow Accelerator Architecture for Convolutional Neural Networks** HPCA 2017

#### 2018

1.	**Towards Efficient Microarchitectural Design for Accelerating Unsupervised GAN-based Deep Learning** HPCA 2018
2.	**Making Memristive Neural Network Accelerators Reliable** HPCA 2018
3.	**Compressing DMA Engine: Leveraging Activation Sparsity for Training Deep Neural Networks** HPCA 2018
4.	**In-situ AI: Towards Autonomous and Incremental Deep Learning for IoT Systems** HPCA 2018

#### 2019

1.	**HyPar: Towards Hybrid Parallelism for Deep Learning Accelerator Array** HPCA 2019
2.	**E-RNN: Design Optimization for Efficient Recurrent Neural Networks in FPGAs** HPCA 2019
3.	**Bit Prudent In-Cache Acceleration of Deep Convolutional Neural Networks** HPCA 2019
4.	**Shortcut Mining: Exploiting Cross-Layer Shortcut Reuse in DCNN Accelerators** HPCA 2019

#### 2020

1.	**AccPar: Tensor Partitioning for Heterogeneous Deep Learning Accelerator Arrays** HPCA 2020

### MICRO

#### 2017

1.	**Scale-Out Acceleration for Machine Learning** MICRO 2017
2.	**Bit-Pragmatic Deep Neural Network Computing** MICRO 2017
3.	**CirCNN: Accelerating and Compressing Deep Neural Networks Using Block-Circulant Weight Matrices** MICRO 2017
4.	**DeftNN: Addressing Bottlenecks for DNN Execution on GPUs via Synapse Vector Elimination and Near-compute Data Fission** MICRO 2017

#### 2018

1.	**Addressing Irregularity in Sparse Neural Networks:A Cooperative Software/Hardware Approach** MICRO 2018
2.	**Diffy: a Deja vu-Free Differential Deep Neural Network Accelerator** MICRO 2018
3.	**Towards Memory Friendly Long-Short Term Memory Networks (LSTMs) on Mobile GPUs** MICRO 2018
4.	**A Network-Centric Hardware/Algorithm Co-Design to Accelerate Distributed Training of Deep Neural Networks** MICRO 2018 
5.	**PermDNN: Efficient Compressed Deep Neural Network Architecture with Permuted Diagonal Matrices** MICRO 2018 
6.	**Processing-in-Memory for Energy-efficient Neural Network Training: A Heterogeneous Approach** MICRO 2018

#### 2019

1.	**Wire-Aware Architecture and Dataflow for CNN Accelerators** MICRO 2019
2.	**Simba: Scaling Deep-Learning Inference with Multi-Chip-Module-Based Architecture** MICRO 2019
3.	**ShapeShifter: Enabling Fine-Grain Data Width Adaptation in Deep Learning** MICRO 2019
4.	**ZCOMP: Reducing DNN Cross-Layer Memory Footprint Using Vector Extensions** MICRO 2019
5.	**Boosting the Performance of CNN Accelerators with Dynamic Fine-Grained Channel Gating** MICRO 2019
6.	**SparTen: A Sparse Tensor Accelerator for Convolutional Neural Networks** MICRO 2019
7.	**EDEN: Enabling Energy-Efficient, High-Performance Deep Neural Network Inference Using Approximate DRAM** MICRO 2019
8.	**eCNN: A Block-Based and Highly-Parallel CNN Accelerator for Edge Inference** MICRO 2019
9.	**Efficient SpMV Operation for Large and Highly Sparse Matrices using Scalable Multi-way Merge Parallelization** MICRO 2019

### SC

#### 2016

1.	**SERF: Efficient Scheduling for Fast Deep Neural Network Serving via Judicious Parallelism** SC 2016
2.	**Optimizing Memory Efficiency for Deep Convolutional Neural Networks on GPUs** SC 2016
3.	**dCUDA: Hardware Supported Overlap of Computation and Communication** SC 2016
4.	**GreenLA: Green Linear Algebra Software for GPU-Accelerated Heterogeneous Computing** SC 2016
5.	**Merge-Based Parallel Sparse Matrix-Vector Multiplication (SpMV)** SC 2016

#### 2018

1.	**Large-Scale Hierarchical K-Means for Heterogeneous Many-Core Supercomputers** SC 2018
2.	**TriCore: Parallel Triangle Counting on GPUs** SC 2018
3.	**Distributed-Memory Hierarchical Compression of Dense SPD Matrices** SC 2018
4.	**HiCOO: Hierarchical Storage of Sparse Tensors** SC 2018
5.	**Distributed Memory Sparse Inverse Covariance Matrix Estimation on High-Performance Computing Architectures** SC 2018
6.	**PruneJuice: Pruning Trillion-Edge Graphs to a Precise Pattern-Matching Solution** SC 2018
7.	**Exploring Flexible Communications for Streamlining DNN Ensemble Training Pipelines** SC 2018
8.	**Anatomy of High-Performance Deep Learning Convolutions on SIMD Architectures** SC 2018
9.	**Fault Tolerant One-Sided Matrix Decompositions on Heterogeneous Systems with GPUs** SC 2018

#### 2019

1.	**Large-Batch Training for LSTM and Beyond** SC 2019
2.	**Channel and Filter Parallelism for Large-Scale CNN Training** SC 2019
3.	**SparCML: High-Performance Sparse Communication for Machine Learning** SC 2019
4.	**PruneTrain: Fast Neural Network Training by Dynamic Sparse Model Reconfiguration** SC 2019
5.	**Scalable Reinforcement-Learning-Based Neural Architecture Search for Cancer Deep Learning Research** SC 2019
6.	**BSTC: A Novel Binarized-Soft-Tensor-Core Design for Accelerating Bit-Based Approximated Neural Nets** SC 2019

### NSDI

#### 2017

1.	**Clipper: A Low-Latency Online Prediction Serving System** NSDI 2017
2.	**Gaia: Geo-Distributed Machine Learning Approaching LAN Speeds** NSDI 2017
3.	**TUX2: Distributed Graph Computation for Machine Learning** NSDI 2017

#### 2019

1.	**Janus: Fast and Flexible Deep Learning via Symbolic Graph Execution of Imperative Programs** NSDI 2019
2.	**BLAS-on-flash: An Efficient Alternative for Large Scale ML Training and Inference?** NSDI 2019
3.	**Tiresias: A GPU Cluster Manager for Distributed Deep Learning** NSDI 2019

### ISCA

#### 2017

1.	**In-Datacenter Performance Analysis of a Tensor Processing Unit** ISCA 2017
2.	**SCALEDEEP: A Scalable Compute Architecture for Learning and Evaluating Deep Networks** ISCA 2017
3.	**SCNN: An Accelerator for Compressed-sparse Convolutional Neural Networks** ISCA 2017
4. **Maximizing CNN Accelerator Efficiency Through Resource Partitioning** ISCA 2017
5.	**Scalpel: Customizing DNN Pruning to the Underlying Hardware Parallelism** ISCA 2017
6.	**Understanding and Optimizing Asynchronous Low-Precision Stochastic Gradient Descent** ISCA 2017

#### 2018

1.	**PROMISE: An End-to-End Design of a Programmable Mixed-Signal Accelerator for Machine-Learning Algorithms** ISCA 2018
2.	**Computation Reuse in DNNs by Exploiting Input Similarity** ISCA 2018
3.	**GenAx: A Genome Sequencing Accelerator** ISCA 2018
4.	**GANAX: A Unified MIMD-SIMD Acceleration for Generative Adversarial Networks** ISCA 2018
5.	**SnaPEA: Predictive Early Activation for Reducing Computation in Deep Convolutional Neural Networks** ISCA 2018
6.	**UCNN: Exploiting Computational Reuse in Deep Neural Networks via Weight Repetition** ISCA 2018
7.	**Energy-Efficient Neural Network Accelerator Based on Outlier-Aware Low-Precision Computation** ISCA 2018
8.	**Prediction based Execution on Deep Neural Networks** ISCA 2018
9.	**Bit Fusion: Bit-Level Dynamically Composable Architecture for Accelerating Deep Neural Network** ISCA 2018
10. **Gist: Efficient Data Encoding for Deep Neural Network Training** ISCA 2018
11. **The Dark Side of DNN Pruning** ISCA 2018

#### 2019

1.	**Sparse ReRAM Engine: Joint exploration of activation and weight sparsity on compressed neural network** ISCA 2019
2.	**MnnFast: A Fast and Scalable System Architecture for Memory-Augmented Neural Networks** ISCA 2019
3.	**TIE: Energy-efficient tensor train-based inference engine for deep neural network** ISCA 2019
4.	**Accelerating Distributed Reinforcement Learning with In-Switch Computing** ISCA 2019
5.	**Eager Pruning: Algorithm and Architecture Support for Fast Training of Deep Neural Networks** ISCA 2019
6.	**Laconic Deep Learning Inference Acceleration** ISCA 2019
7.	**DeepAttest: An End-to-End Attestation Framework for Deep Neural Networks** ISCA 2019

## Contributors

Contributed by [Xupeng Miao](https://github.com/Hsword).