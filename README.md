# **Papers Reading List.**
- This is a collection of papers aiming at reducing model sizes or the ASIC/FPGA accelerator for Machine Learning, especially deep neural network related applications. (Inspiled by [Neural-Networks-on-Silicon](https://github.com/fengbintu/Neural-Networks-on-Silicon/blob/master/README.md))
- Tutorials:
   - **Hardware Accelerator**: Efficient Processing of Deep Neural Networks. ([link](https://arxiv.org/abs/1703.09039))
   - **Model Compression**: Model Compression and Acceleration for Deep Neural Networks. ([link](https://arxiv.org/abs/1710.09282))
## **Table of Contents**
- [Our Contributions](#our-contributions)
- [Network Compression](#network-compression)
   - Parameter Sharing
   - Teacher-Student Mechanism (Distilling)
   - Fixed-precision training and storage
   - Sparsity regularizers & Pruning
   - Tensor Decomposition
   - Conditional (Adaptive) Computing
- [Hardware Accelerator](#hardware-accelerator)
   - Benchmark and Platform Analysis
   - Recurrent Neural Networks
- [Conference Papers](#conference-papers)
   - 2016: [NIPS](#nips-2016)
   - 2017: [ICASSP](#icassp-2017)、[CVPR](#cvpr-2017)、[ICML](#icml-2017)、[ICCV](#iccv-2017)、[NIPS](#nips-2017)
   - 2018：[ICLR](#iclr-2018)、[CVPR](#cvpr-2018)、[ECCV](#eccv-2018)、[ICML](#icml-2018)
   - 2019：[ICLR](#iclr-2019)
##  **Our Contributions**
- **TODO**
##  **Network Compression**
> **This field is changing rapidly, belowing entries may be somewhat antiquated.**
### **Parameter Sharing**
- **structured matrices**
   - Structured Convolution Matrices for Energy-efficient Deep learning. (IBM Research–Almaden)
   - Structured Transforms for Small-Footprint Deep Learning. (Google Inc)
   - An Exploration of Parameter Redundancy in Deep Networks with Circulant Projections.
   - Theoretical Properties for Neural Networks with Weight Matrices of Low Displacement Rank.
- **Hashing**
   - Functional Hashing for Compressing Neural Networks. (Baidu Inc)
   - Compressing Neural Networks with the Hashing Trick. (Washington University + NVIDIA)
- Learning compact recurrent neural networks. (University of Southern California + Google)

### **Teacher-Student Mechanism (Distilling)**
- Distilling the Knowledge in a Neural Network. (Google Inc)
- Sequence-Level Knowledge Distillation. (Harvard University)
- Like What You Like: Knowledge Distill via Neuron Selectivity Transfer. (TuSimple)

### **Fixed-precision training and storage**
- Binary/Ternary Neural Networks
   - XNOR-Net, Ternary Weight Networks (TWNs), Binary-net and their variants.
- Deep neural networks are robust to weight binarization and other non-linear distortions. (IBM Research–Almaden)
- Recurrent Neural Networks With Limited Numerical Precision. (ETH Zurich + Montréal@Yoshua Bengio)
- Neural Networks with Few Multiplications. (Montréal@Yoshua Bengio)
- 1-Bit Stochastic Gradient Descent and its Application to Data-Parallel Distributed Training of Speech DNNs. (Tsinghua University + Microsoft)
- Towards the Limit of Network Quantization. (Samsung US R&D Center)
- Incremental Network Quantization_Towards Lossless CNNs with Low-precision Weights. (Intel Labs China)
- Loss-aware Binarization of Deep Networks. (Hong Kong University of Science and Technology)
- Trained Ternary Quantization. (Tsinghua University + Stanford University + NVIDIA)

### **Sparsity regularizers & Pruning**
- Learning both Weights and Connections for Efficient Neural Networks. (SongHan, Stanford University)
- Deep Compression, EIE. (SongHan, Stanford University)
- Dynamic Network Surgery for Efficient DNNs. (Intel)
- Compression of Neural Machine Translation Models via Pruning. (Stanford University)
- Accelerating Deep Convolutional Networks using low-precision and sparsity. (Intel)
- Faster CNNs with Direct Sparse Convolutions and Guided Pruning. (Intel)
- Exploring Sparsity in Recurrent Neural Networks. (Baidu Research)
- Pruning Convolutional Neural Networks for Resource Efficient Inference. (NVIDIA)
- Pruning Filters for Efficient ConvNets. (University of Maryland + NEC Labs America)
- Soft Weight-Sharing for Neural Network Compression. (University of Amsterdam, [reddit discussion](https://www.reddit.com/r/MachineLearning/comments/5u7h3l/r_compressing_nn_with_shannons_blessing/))
- Sparsely-Connected Neural Networks_Towards Efficient VLSI Implementation of Deep Neural Networks. (McGill University)
- Training Compressed Fully-Connected Networks with a Density-Diversity Penalty. (University of Washington)
- **Bayesian Compression**
   - Bayesian Sparsification of Recurrent Neural Networks
   - Bayesian Compression for Deep Learning
   - Structured Bayesian Pruning via Log-Normal Multiplicative Noise

### **Tensor Decomposition**
- Compression of Deep Convolutional Neural Networks for Fast and Low Power Mobile Applications. (Samsung, etc)
- Learning compact recurrent neural networks. (University of Southern California + Google)
- Tensorizing Neural Networks. (Skolkovo Institute of Science and Technology, etc)
- Ultimate tensorization_compressing convolutional and FC layers alike. (Moscow State University, etc)
- Efficient and Accurate Approximations of Nonlinear Convolutional Networks. (@CVPR2015)
- Exploiting Linear Structure Within Convolutional Networks for Efficient Evaluation. (New York University, etc.)
- Convolutional neural networks with low-rank regularization. (Princeton University, etc.)
- **Learning with Tensors: Why Now and How?** (Tensor-Learn Workshop @ NIPS'16)

##  **Conditional (Adaptive) Computing**
- Adaptive Computation Time for Recurrent Neural Networks. (Google DeepMind@Alex Graves)
- Variable Computation in Recurrent Neural Networks. (New York University + Facebook AI Research)
- Spatially Adaptive Computation Time for Residual Networks. ([github link](https://github.com/mfigurnov/sact), Google, etc.)
- Hierarchical Multiscale Recurrent Neural Networks. (Montréal)
- Outrageously Large Neural Networks_The Sparsely-Gated Mixture-of-Experts Layer. (Google Brain, etc.)
- Adaptive Neural Networks for Fast Test-Time Prediction. (Boston University, etc)
- Dynamic Deep Neural Networks_Optimizing Accuracy-Efficiency Trade-offs by Selective Execution. (University of Michigan)
- **Estimating or Propagating Gradients Through Stochastic Neurons for Conditional Computation**. (@Yoshua Bengio)
- Multi-Scale Dense Convolutional Networks for Efficient Prediction. (Cornell University, etc)

## **Hardware Accelerator**
### **Benchmark and Platform Analysis**
- Fathom: Reference Workloads for Modern Deep Learning Methods. (Harvard University)
- DeepBench: Open-Source Tool for benchmarking DL operations. (svail.github.io-Baidu)
- BENCHIP: Benchmarking Intelligence Processors.

### **Recurrent Neural Networks**
- FPGA-based Low-power Speech Recognition with Recurrent Neural Networks. (Seoul National University)
- Accelerating Recurrent Neural Networks in Analytics Servers: Comparison of FPGA, CPU, GPU, and ASIC. (Intel)
- ESE: Efficient Speech Recognition Engine with Compressed LSTM on FPGA. (FPGA 2017, Best Paper Award)
- DNPU: An 8.1TOPS/W Reconfigurable CNN-RNN Processor for GeneralPurpose Deep Neural Networks. (KAIST, ISSCC 2017)
- Hardware Architecture of Bidirectional Long Short-Term Memory Neural Network for Optical Character Recognition. (University of Kaiserslautern, etc)
- Efficient Hardware Mapping of Long Short-Term Memory Neural Networks for Automatic Speech Recognition. (Master Thesis@Georgios N. Evangelopoulos)
- A Fast and Power Efficient Architecture to Parallelize LSTM based RNN for Cognitive Intelligence Applications. (Tsinghua University)
- Hardware Accelerators for Recurrent Neural Networks on FPGA. (Purdue University, ISCAS 2017)
- Accelerating Recurrent Neural Networks: A Memory Efficient Approach. (Nanjing University)
- A Fast and Power Efficient Architecture to Parallelize LSTM based RNN for Cognitive Intelligence Applications.
- An Energy-Efficient Reconfigurable Architecture for RNNs Using Dynamically Adaptive Approximate Computing.
- DNPU: An 8.1TOPS/W reconfigurable CNN-RNN processor for general-purpose deep neural networks. 
- Hardware Architecture of Bidirectional Long Short-Term Memory Neural Network for Optical Character Recognition.
- A Systolically Scalable Accelerator for Near-Sensor Recurrent Neural Network Inference.

### **Convolutional Neural Networks**
- Please refer to  [Neural-Networks-on-Silicon](https://github.com/fengbintu/Neural-Networks-on-Silicon/blob/master/README.md)
## **Conference Papers**

### **NIPS 2016**
-  Dynamic Network Surgery for Efficient DNNs. (Intel Labs China)
-  Memory-Efficient Backpropagation Through Time. (Google DeepMind)
-  PerforatedCNNs: Acceleration through Elimination of Redundant Convolutions. (Moscow State University, etc.)
-  Learning Structured Sparsity in Deep Neural Networks. (University of Pittsburgh)
-  LightRNN: Memory and Computation-Efficient Recurrent Neural Networks. (Nanjing University + Microsoft Research)

### **ICASSP 2017**
-	lognet: energy-efficient neural networks using logarithmic computation. (Stanford University)
-	extended low rank plus diagonal adaptation for deep and recurrent neural networks. (Microsoft)
-	fixed-point optimization of deep neural networks with adaptive step size retraining. (Seoul National University)
-	implementation of efficient, low power deep neural networks on next-generation intel client platforms (Demos). (Intel)
-	knowledge distillation for small-footprint highway networks. (TTI-Chicago, etc)
-	automatic node selection for deep neural networks using group lasso regularization. (Doshisha University, etc)
-	accelerating deep convolutional networks using low-precision and sparsity. (Intel Labs)

### **CVPR 2017**
- Designing Energy-Efficient Convolutional Neural Networks using Energy-Aware Pruning. (MIT)
- Network Sketching: Exploiting Binary Structure in Deep CNNs. (Intel Labs China + Tsinghua University)
- Spatially Adaptive Computation Time for Residual Networks. (Google, etc)
- A Compact DNN: Approaching GoogLeNet-Level Accuracy of Classification and Domain Adaptation. (University of Pittsburgh, etc)


### **ICML 2017**
- Deep Tensor Convolution on Multicores. (MIT)
- Beyond Filters: Compact Feature Map for Portable Deep Model. (Peking University + University of Sydney)
- Combined Group and Exclusive Sparsity for Deep Neural Networks. (UNIST)
- Delta Networks for Optimized Recurrent Network Computation. (Institute of Neuroinformatics, etc)
- MEC: Memory-efficient Convolution for Deep Neural Network. (IBM Research)
- Deciding How to Decide: Dynamic Routing in Artificial Neural Networks. (California Institute of Technology)
- Training Models with End-to-End Low Precision: The Cans, the Cannots, and a Little Bit of Deep Learning. (ETH Zurich, etc)
- Analytical Guarantees on Numerical Precision of Deep Neural Networks. (University of Illinois at Urbana-Champaign)
- Variational Dropout Sparsifies Deep Neural Networks. (Skoltech, etc)
- Adaptive Neural Networks for Fast Test-Time Prediction. (Boston University, etc)
- Theoretical Properties for Neural Networks with Weight Matrices of Low Displacement Rank. (The City University of New York, etc)

### **ICCV 2017**
- Channel Pruning for Accelerating Very Deep Neural Networks. (Xi’an Jiaotong University + Megvii Inc.)
- ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression. (Nanjing University, etc)
- Learning Efficient Convolutional Networks through Network Slimming. (Intel Labs China, etc)
- Performance Guaranteed Network Acceleration via High-Order Residual Quantization. (Shanghai Jiao Tong University + Peking University)
- Coordinating Filters for Faster Deep Neural Networks. (University of Pittsburgh + Duke University, etc, [github link](https://github.com/wenwei202/caffe))

### **NIPS 2017**
- Towards Accurate Binary Convolutional Neural Network. (DJI)
- Soft-to-Hard Vector Quantization for End-to-End Learning Compressible Representations. (ETH Zurich)
- TernGrad: Ternary Gradients to Reduce Communication in Distributed Deep Learning. (Duke University, etc, [github link](https://github.com/wenwei202/terngrad))
- Flexpoint: An Adaptive Numerical Format for Efficient Training of Deep Neural Networks. (Intel)
- Bayesian Compression for Deep Learning. (University of Amsterdam, etc)
- Learning to Prune Deep Neural Networks via Layer-wise Optimal Brain Surgeon. (Nanyang Technological Univ)
- Training Quantized Nets: A Deeper Understanding. (University of Maryland)
- Structured Bayesian Pruning via Log-Normal Multiplicative Noise. (Yandex, etc)
- Runtime Neural Pruning. (Tsinghua University)
- The Reversible Residual Network: Backpropagation Without Storing Activations. (University of Toronto, [gihub link](https://github.com/renmengye/revnet-public))
- Compression-aware Training of Deep Networks. (Toyota Research Institute + EPFL)

### **ICLR 2018**
- Oral
   - Training and Inference with Integers in Deep Neural Networks. (Tsinghua University)
- Poster
   - Learning Sparse NNs Through L0 Regularization
   - Learning Intrinsic Sparse Structures within Long Short-Term Memory
   - Variantional Network Quantization
   - Alternating Multi-BIT Quantization for Recurrent Neural Networks
   - Mixed Precision Training
   - Multi-Scale Dense Networks for Resource Efficient Image Classification
   - efficient sparse-winograd CNNs
   - Compressing Wrod Embedding via Deep Compositional Code Learning
   - Mixed Precision Training of Convolutional Neural Networks using Integer Operations
   - Adaptive Quantization of Neural Networks
   - Espresso_Efficient Forward Propagation for Binary Deep Neural Networks
   - WRPN_Wide Reduced-Precision Networks
   - Deep Rewiring_Training very sparse deep networks
   - Loss-aware Weight Quantization of Deep Network
   - Learning to share_simultaneous parameter tying and sparsification in deep learning
   - Deep Gradient Compression_Reducing the Communication Bandwidth for Distributed Training
   - Large scale distributed neural network training through online distillation
   - Learning Discrete Weights Using the Local Reparameterization Trick
   - Rethinking the Smaller-Norm-Less-Informative Assumption in Channel Pruning of Convolution Layers
   - Training wide residual networks for deployment using a single bit for each weight
   - The High-Dimensional Geometry of Binary Neural Networks
- workshop
   - To Prune or Not to Prune_Exploring the Efficacy of Pruning for Model Compression
### **CVPR 2018**
- Shift: A Zero FLOP, Zero Parameter Alternative to Spatial Convolutions
- ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices
- Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference
- BlockDrop: Dynamic Inference Paths in Residual Networks
- SYQ: Learning Symmetric Quantization for Efficient Deep Neural Networks
- Two-Step Quantization for Low-Bit Neural Networks
- Towards Effective Low-Bitwidth Convolutional Neural Networks
- Explicit Loss-Error-Aware Quantization for Low-Bit Deep Neural Networks
- CLIP-Q: Deep Network Compression Learning by In-Parallel Pruning-Quantization
- “Learning-Compression” Algorithms for Neural Net Pruning
- Wide Compression: Tensor Ring Nets
- NestedNet: Learning Nested Sparse Structures in Deep Neural Networks
- Interleaved Structured Sparse Convolutional Neural Networks
- NISP: Pruning Networks Using Neuron Importance Score Propagation
- Learning Compact Recurrent Neural Networks With Block-Term Tensor Decomposition
- HydraNets: Specialized Dynamic Architectures for Efficient Inference
- Learning Time/Memory-Efficient Deep Architectures With Budgeted Super Networks
### **ECCV 2018**
- ShuffleNet V2: Practical Guidelines for Efficient CNN Architecture Design
- A Systematic DNN Weight Pruning Framework using Alternating Direction Method of Multipliers
- **Learning Compression from Limited Unlabeled Data**
- **AMC: AutoML for Model Compression and Acceleration on Mobile Devices**
- Training Binary Weight Networks via Semi-Binary Decomposition
- Clustering Convolutional Kernels to Compress Deep Neural Networks
- Bi-Real Net: Enhancing the Performance of 1-bit CNNs With Improved Representational Capability and Advanced Training Algorithm
- Data-Driven Sparse Structure Selection for Deep Neural Networks
- Coreset-Based Neural Network Compression
- Convolutional Networks with Adaptive Inference Graphs
- Value-aware Quantization for Training and Inference of Neural Networks
- LQ-Nets: Learned Quantization for Highly Accurate and Compact Deep Neural Networks
- Deep Expander Networks: Efficient Deep Networks from Graph Theory
- Extreme Network Compression via Filter Group Approximation
- Constraint-Aware Deep Neural Network Compression
### **ICML 2018**
- Compressing Neural Networks using the Variational Information Bottleneck
- DCFNet_Deep Neural Network with Decomposed Convolutional Filters
- Deep k-Means Re-Training and Parameter Sharing with Harder Cluster Assignments for Compressing Deep Convolutions
- Error Compensated Quantized SGD and its Applications to Large-scale Distributed Optimization
- High Performance Zero-Memory Overhead Direct Convolutions
- Kronecker Recurrent Units
- Learning Compact Neural Networks with Regularization
- StrassenNets_Deep Learning with a Multiplication Budge
- Weightless_Lossy weight encoding for deep neural network compression
- WSNet_Compact and Efficient Networks Through Weight Sampling

### **ICLR 2019**
- Poster:
   - SNIP: SINGLE-SHOT NETWORK PRUNING BASED ON CONNECTION SENSITIVITY
   - Rethinking the Value of Network Pruning
   - Non-vacuous Generalization Bounds at the ImageNet Scale: a PAC-Bayesian Compression Approach
   - Dynamic Channel Pruning: Feature Boosting and Suppression
   - Energy-Constrained Compression for Deep Neural Networks via Weighted Sparse Projection and Layer Input Masking
   - Slimmable Neural Networks
   - RotDCF: Decomposition of Convolutional Filters for Rotation-Equivariant Deep Networks
   - Dynamic Sparse Graph for Efficient Deep Learning
   - Big-Little Net: An Efficient Multi-Scale Feature Representation for Visual and Speech Recognition
   - Data-Dependent Coresets for Compressing Neural Networks with Applications to Generalization Bounds
   - Learning Recurrent Binary/Ternary Weights
   - Double Viterbi: Weight Encoding for High Compression Ratio and Fast On-Chip Reconstruction for Deep Neural Network
   - Relaxed Quantization for Discretized Neural Networks
   - Integer Networks for Data Compression with Latent-Variable Models
   - Minimal Random Code Learning: Getting Bits Back from Compressed Model Parameters
   - A Systematic Study of Binary Neural Networks' Optimisation
   - Analysis of Quantized Models
- Oral:
   - The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks
