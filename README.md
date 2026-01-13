<h1 align="center">Hi 👋, I'm Ramshankar</h1>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=ramshankar07&label=Profile%20views&color=0e75b6&style=flat" alt="ramshankar07" /> </p>

**ML Systems Engineer | GPU Optimization Researcher**

I build high-performance machine learning systems with a focus on GPU optimization, model compression, and distributed training. My work spans custom CUDA kernel development, cross-platform GPU programming (NVIDIA CUDA, AMD ROCm/HIP, Apple Metal), and automated neural architecture optimization.

## Research Interests

- GPU kernel optimization and low-level performance engineering
- Model quantization and precision-efficient inference
- Automated model optimization using reinforcement learning and tree search
- Distributed training systems and parallelization strategies
- Efficient neural network compression (pruning, knowledge distillation, early exit)

## Selected Work

### ModelOpt

An automated neural network optimization framework that treats model compression as a sequential decision-making problem. Uses Monte Carlo Tree Search to navigate the combinatorial space of compression configurations, discovering optimal quantization and pruning strategies without requiring gradient-based fine-tuning. Achieves 98.1% accuracy retention with 3.0× compression ratios, outperforming baseline search strategies by 13-201% across benchmark models. The MCTS formulation enables efficient exploration of the optimization landscape through learned value estimates and UCB-based action selection.

### BitSkip: Quantization × Early Exit Composition

Empirical analysis of composing quantization with early exit strategies for efficient inference. Investigates how reduced numerical precision interacts with adaptive computation depth—whether aggressive quantization degrades the confidence estimates that early exit relies on, and how to jointly optimize both techniques. Explores the Pareto frontier of latency, memory, and accuracy trade-offs.

### Cross-Platform GPU Optimization

Custom kernel implementations achieving 8.8x RMSNorm speedup and 79-83% memory bandwidth utilization on distributed 8-GPU A100 systems. Experience porting optimizations across CUDA, ROCm/HIP, and Metal backends, with focus on memory coalescing, warp-level primitives, and minimizing kernel launch overhead.

## Technical Depth

### Model Quantization

Experience with post-training quantization (PTQ) and quantization-aware training (QAT) across INT8, INT4, and mixed-precision schemes. Familiar with techniques including symmetric/asymmetric quantization, per-channel vs per-tensor scaling, and handling outlier activations. Research focus on automating quantization configuration search rather than relying on manual sensitivity analysis.

### Model Optimization

Work spans structured and unstructured pruning, knowledge distillation pipelines, and neural architecture search. Particular interest in framing optimization as a search problem—using RL and tree search methods to discover compression strategies that manual approaches miss. Implemented distillation pipelines for production OCR models achieving 98% accuracy with significantly reduced parameter counts.

## Experience

**AI Engineer @ BulkBeings** (Summer 2025)  
Developed distributed LLM training pipelines for 8B-70B parameter models using FSDP across A100 clusters. Built custom CUDA kernels achieving 42% training speedup. Implemented hybrid SFT-DPO training workflows combining supervised fine-tuning with direct preference optimization for alignment.

**Teaching Assistant, High-Performance Computing @ Northeastern University**  
Led TA teams supporting students with parallel computing, SLURM job scheduling, and multiprocessing on the Discovery supercomputing cluster.

## Education

**M.S. Information Systems** — Northeastern University (December 2025)  
Thesis: *ModelOpt: Research Framework for Zero-Shot Computer Vision Model Optimization with Tree Search and Federated Knowledge Sharing*  
Advisor: Professor Handan Liu

## Technical Skills

**GPU Programming:** CUDA, ROCm/HIP, Metal, Triton  
**ML Frameworks:** PyTorch, DeepSpeed, FSDP, Hugging Face Transformers  
**Quantization Tools:** bitsandbytes, GPTQ, AWQ  
**Languages:** Python, C++, CUDA C  
**Infrastructure:** Distributed training, SLURM, multi-node clusters


## 💻 Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![R](https://img.shields.io/badge/R-Programming-green) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) 

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![Langchain Library](https://img.shields.io/badge/Langchain%20Library-Python-blue) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Transformers-orange)

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-11.2-76B900.svg)	![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)

]

