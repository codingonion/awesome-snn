# Awesome-SNN
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🔥🔥🔥 This repository lists some awesome SNN(Spiking Neural Network) projects.

## Contents
- [Awesome-SNN](#awesome-SNN)
  - [Review](#review)
  - [Frameworks](#frameworks)
  - [Datasets](#datasets)
  - [Applications](#applications)
    - [Attention and Transformer](#attention-and-transformer)
    - [Object Detection](#object-detection)
    - [Object Recognition](#object-recognition)
    - [Adversarial Attack and Defense](#adversarial-attack-and-defense)
    - [Speech and Audio Field](#speech-and-audio-field)
    - [Event-Based Application](#event-based-application)
    - [Hardware Deployment](#hardware-deployment)
  - [Blogs](#blogs)

## Review

  - [uzh-rpg/event-based_vision_resources](https://github.com/uzh-rpg/event-based_vision_resources) <img src="https://img.shields.io/github/stars/uzh-rpg/event-based_vision_resources?style=social"/> : Event-based Vision Resources.

  - [XDUSPONGE/SNN_benchmark](https://github.com/XDUSPONGE/SNN_benchmark) <img src="https://img.shields.io/github/stars/XDUSPONGE/SNN_benchmark?style=social"/> : Spiking Neural Network Paper List.

  - [amirHossein-Ebrahimi/awesome-computational-neuro-science](https://github.com/amirHossein-Ebrahimi/awesome-computational-neuro-science) <img src="https://img.shields.io/github/stars/amirHossein-Ebrahimi/awesome-computational-neuro-science?style=social"/> : A curated list of awesome Go frameworks, libraries, and software + First class pure python Tutorial Series for Spiking Neural Networks 🔥.

  - [vvvityaaa/awesome-spiking-neural-networks](https://github.com/vvvityaaa/awesome-spiking-neural-networks) <img src="https://img.shields.io/github/stars/vvvityaaa/awesome-spiking-neural-networks?style=social"/> : A curated list of materials for Spiking Neural Networks, 3rd generation of artificial neural networks.

  - [TheAwesomeAndy/Awesome_SNN_Reads](https://github.com/TheAwesomeAndy/Awesome_SNN_Reads) <img src="https://img.shields.io/github/stars/TheAwesomeAndy/Awesome_SNN_Reads?style=social"/> : A list of little and big reads about SNN's.

  - [SpikingChen/SNN-Daily-Arxiv](https://github.com/SpikingChen/SNN-Daily-Arxiv) <img src="https://img.shields.io/github/stars/SpikingChen/SNN-Daily-Arxiv?style=social"/> : Update arXiv papers about Spiking Neural Networks daily.

  - [shenhaibo123/SNN_arxiv_daily](https://github.com/shenhaibo123/SNN_arxiv_daily) <img src="https://img.shields.io/github/stars/shenhaibo123/SNN_arxiv_daily?style=social"/> : SNN_arxiv_daily.

  - "Advances in spike vision". "脉冲视觉研究进展". (**[中国图象图形学报 2022](https://kns.cnki.net/kcms/detail/detail.aspx?dbcode=CJFD&dbname=CJFDAUTO&filename=ZGTB202206006&uniplatform=NZKPT&v=1SpBEdioSKuEkmX33l-qeXciGOojmZIKjTSz1zgE9as8bUPvlctiRNCrJ4biYEi8)**)


## Datasets

  - [N-Caltech101](https://www.garrickorchard.com/datasets/n-caltech101) : The Neuromorphic-Caltech101 (N-Caltech101) dataset is a spiking version of the original frame-based [Caltech101](http://www.google.com/url?q=http%3A%2F%2Fwww.vision.caltech.edu%2FImage_Datasets%2FCaltech101%2FCaltech101.html&sa=D&sntz=1&usg=AOvVaw3FAvWUY-ZpW9w-WlEVDYjk) dataset. “Converting Static Image Datasets to Spiking Neuromorphic Datasets Using Saccades". (**[Frontiers in neuroscience, 2015](https://www.frontiersin.org/articles/10.3389/fnins.2015.00437/full)**)


## Frameworks

  - [SpikingJelly | 惊蜇](https://github.com/fangwei123456/spikingjelly) <img src="https://img.shields.io/github/stars/fangwei123456/spikingjelly?style=social"/> : SpikingJelly is an open-source deep learning framework for Spiking Neural Network (SNN) based on PyTorch. SpikingJelly 是一个基于 PyTorch，使用脉冲神经网络(Spiking Neural Network, SNN)进行深度学习的框架。[spikingjelly.readthedocs.io](https://spikingjelly.readthedocs.io/zh_CN/latest/)

  - [BrainCog | 智脉](https://github.com/BrainCog-X/Brain-Cog) <img src="https://img.shields.io/github/stars/BrainCog-X/Brain-Cog?style=social"/> : BrainCog is an open source spiking neural network based brain-inspired cognitive intelligence engine for Brain-inspired Artificial Intelligence and brain simulation. More information on braincog can be found on its homepage http://www.brain-cog.network/. "BrainCog: A Spiking Neural Network based Brain-inspired Cognitive Intelligence Engine for Brain-inspired AI and Brain Simulation". (**[arXiv 2022](https://arxiv.org/abs/2207.08533)**)

  - [NCPs](https://github.com/mlech26l/ncps) <img src="https://img.shields.io/github/stars/mlech26l/ncps?style=social"/> : PyTorch and TensorFlow implementation of NCP, LTC, and CfC wired neural models. "Neural circuit policies enabling auditable autonomy". (**[Nature Machine Intelligence, 2020](https://www.nature.com/articles/s42256-020-00237-3)**)

  - [CfC](https://github.com/raminmh/CfC) <img src="https://img.shields.io/github/stars/raminmh/CfC?style=social"/> : "Closed-form continuous-time neural networks". (**[Nature Machine Intelligence, 2022](https://www.nature.com/articles/s42256-022-00556-7)**)

  - [LTCs](https://github.com/raminmh/liquid_time_constant_networks) <img src="https://img.shields.io/github/stars/raminmh/liquid_time_constant_networks?style=social"/> : "Liquid Time-constant Networks". (**[AAAI 2021](https://ojs.aaai.org/index.php/AAAI/article/view/16936)**)

  - [C. elegans](http://www.wormbook.org/chapters/www_celegansintro/celegansintro.html) : "A Transparent Window into Biology: A Primer on Caenorhabditis elegans". (**[Genetics, 2015](https://academic.oup.com/genetics/article/200/2/387/5936175?login=false)**)

  - [VOneNets](https://github.com/dicarlolab/vonenet) <img src="https://img.shields.io/github/stars/dicarlolab/vonenet?style=social"/> : "Simulating a Primary Visual Cortex at the Front of CNNs Improves Robustness to Image Perturbations". (**[NeurIPS 2020](https://proceedings.neurips.cc/paper/2020/hash/98b17f068d5d9b7668e19fb8ae470841-Abstract.html)**)

  - [BindsNET](https://github.com/BindsNET/bindsnet) <img src="https://img.shields.io/github/stars/BindsNET/bindsnet?style=social"/> : Simulation of spiking neural networks (SNNs) using PyTorch.

  - [Brian2](https://github.com/brian-team/brian2) <img src="https://img.shields.io/github/stars/brian-team/brian2?style=social"/> : Brian is a free, open source simulator for spiking neural networks. "Brian 2, an intuitive and efficient neural simulator". (**[Elife 2019](https://elifesciences.org/articles/47314)**)

  - [Brian2CUDA](https://github.com/brian-team/brian2cuda) <img src="https://img.shields.io/github/stars/brian-team/brian2cuda?style=social"/> : A brian2 extension to simulate spiking neural networks on GPUs. "Brian2CUDA: flexible and efficient simulation of spiking neural network models on GPUs". (**[Frontiers in Neuroinformatics 2022](https://www.frontiersin.org/articles/10.3389/fninf.2022.883700/abstract14)**)

  - [Spiking-Neural-Network](https://github.com/Shikhargupta/Spiking-Neural-Network) <img src="https://img.shields.io/github/stars/Shikhargupta/Spiking-Neural-Network?style=social"/> : This is the python implementation of hardware efficient spiking neural network.

  - [norse](https://github.com/norse/norse) <img src="https://img.shields.io/github/stars/norse/norse?style=social"/> : Deep learning with spiking neural networks (SNNs) in PyTorch.

  - [snntorch](https://github.com/jeshraghian/snntorch) <img src="https://img.shields.io/github/stars/jeshraghian/snntorch?style=social"/> : Deep and online learning with spiking neural networks in Python. "Training Spiking Neural Networks Using Lessons From Deep Learning". (**[arXiv 2021](https://arxiv.org/abs/2109.12894)**)

  - [snn_toolbox](https://github.com/NeuromorphicProcessorProject/snn_toolbox) <img src="https://img.shields.io/github/stars/NeuromorphicProcessorProject/snn_toolbox?style=social"/> : Toolbox for converting analog to spiking neural networks (ANN to SNN), and running them in a spiking neuron simulator.

  - [SpyTorch](https://github.com/fzenke/spytorch) <img src="https://img.shields.io/github/stars/fzenke/spytorch?style=social"/> : "Surrogate gradient learning in spiking neural networks: Bringing the power of gradient-based optimization to spiking neural networks". (**[IEEE Signal Processing Magazine 2019](https://ieeexplore.ieee.org/abstract/document/8891809)**)

  - [slayerPytorch](https://github.com/bamsumit/slayerPytorch) <img src="https://img.shields.io/github/stars/bamsumit/slayerPytorch?style=social"/> : PyTorch implementation of SLAYER for training Spiking Neural Networks . "Slayer: Spike layer error reassignment in time". (**[NeurIPS 2018](https://proceedings.neurips.cc/paper/2018/hash/82f2b308c3b01637c607ce05f52a2fed-Abstract.html)**)

  - [Spiking-Neural-Network-SNN-with-PyTorch-where-Backpropagation-engenders-STDP](https://github.com/guillaume-chevalier/Spiking-Neural-Network-SNN-with-PyTorch-where-Backpropagation-engenders-STDP) <img src="https://img.shields.io/github/stars/guillaume-chevalier/Spiking-Neural-Network-SNN-with-PyTorch-where-Backpropagation-engenders-STDP?style=social"/> : Spiking Neural Network (SNN) with PyTorch : towards bridging the gap between deep learning and the human brain.

  - [PySNN](https://github.com/BasBuller/PySNN) <img src="https://img.shields.io/github/stars/BasBuller/PySNN?style=social"/> : Efficient Spiking Neural Network framework, built on top of PyTorch for GPU acceleration.

  - [yjwu17/STBP-for-training-SpikingNN](https://github.com/yjwu17/STBP-for-training-SpikingNN) <img src="https://img.shields.io/github/stars/yjwu17/STBP-for-training-SpikingNN?style=social"/> : Spatio-temporal BP for spiking neural networks.

  - [thiswinex/STBP-simple](https://github.com/thiswinex/STBP-simple) <img src="https://img.shields.io/github/stars/thiswinex/STBP-simple?style=social"/> : A simple direct training implement for SNNs using Spatio-Temporal Backpropagation.

  - [ZLkanyo009/STBP-train-and-compression](https://github.com/ZLkanyo009/STBP-train-and-compression) <img src="https://img.shields.io/github/stars/ZLkanyo009/STBP-train-and-compression?style=social"/> : STBP is a way to train SNN with datasets by Backward propagation.Using this Repositories allows you to train SNNS with STBP and quantize SNNS with QAT to deploy to neuromorphological chips like Loihi and Tianjic.

  - [SPAIC](https://github.com/ZhejianglabNCRC/SPAIC) <img src="https://img.shields.io/github/stars/ZhejianglabNCRC/SPAIC?style=social"/> : Spike-based artificial intelligence computing platform. "Darwin-S: A Reference Software Architecture for Brain-Inspired Computers". (**[IEEE Computer 2022](https://ieeexplore.ieee.org/abstract/document/9771131)**)

  - [yhhhli/SNN_Calibration](https://github.com/yhhhli/SNN_Calibration) <img src="https://img.shields.io/github/stars/yhhhli/SNN_Calibration?style=social"/> : Pytorch Implementation of Spiking Neural Networks Calibration, ICML 2021. "A free lunch from ANN: Towards efficient, accurate spiking neural networks calibration". (**[ICML 2021](https://proceedings.mlr.press/v139/li21d.html)**).  "Converting Artificial Neural Networks to Spiking Neural Networks via Parameter Calibration". (**[arXiv 2022](https://arxiv.org/abs/2205.10121)**)

  - [gmtiddia/working_memory_spiking_network](https://github.com/gmtiddia/working_memory_spiking_network) <img src="https://img.shields.io/github/stars/gmtiddia/working_memory_spiking_network?style=social"/> : Spiking network model and analysis scripts for the preprint "Simulations of Working Memory Spiking Networks driven by Short-Term Plasticity".

  - [Brain-Cog-Lab/Conversion_Burst](https://github.com/Brain-Cog-Lab/Conversion_Burst) <img src="https://img.shields.io/github/stars/Brain-Cog-Lab/Conversion_Burst?style=social"/> : "Efficient and Accurate Conversion of Spiking Neural Network with Burst Spikes". (**[IJCAI 2022](https://arxiv.org/abs/2204.13271)**)

  - [Brain-Cog-Lab/BP-STA](https://github.com/Brain-Cog-Lab/BP-STA) <img src="https://img.shields.io/github/stars/Brain-Cog-Lab/BP-STA?style=social"/> : "Backpropagation with Biologically Plausible Spatio-Temporal Adjustment For Training Deep Spiking Neural Networks". (**[Cell Patterns 2022](https://www.sciencedirect.com/science/article/pii/S2666389922001192)**)

  - [Borzyszkowski/SNN-CMS](https://github.com/Borzyszkowski/SNN-CMS) <img src="https://img.shields.io/github/stars/Borzyszkowski/SNN-CMS?style=social"/> : Spiking Neural Networks accelerated on the Intel Loihi chips for LHC experiments, at CMS detector. Project of the European Organization for Nuclear Research (CERN) in collaboration with Intel Labs.

  - [TJXTT/SNN2ANN](https://github.com/TJXTT/SNN2ANN) <img src="https://img.shields.io/github/stars/TJXTT/SNN2ANN?style=social"/> : "SNN2ANN: A Fast and Memory-Efficient Training Framework for Spiking Neural Networks". (**[arXiv 2022](https://arxiv.org/abs/2206.09449)**)

  - [sPyMem](https://github.com/dancasmor/sPyMem) <img src="https://img.shields.io/github/stars/dancasmor/sPyMem?style=social"/> : sPyMem: spike-based bio-inspired memory models.

  - [romainzimmer/s2net](https://github.com/romainzimmer/s2net) <img src="https://img.shields.io/github/stars/romainzimmer/s2net?style=social"/> : Supervised Spiking Network.

  - [combra-lab/snn-eeg](https://github.com/combra-lab/snn-eeg) <img src="https://img.shields.io/github/stars/combra-lab/snn-eeg?style=social"/> : PyTorch and Loihi implementation of the Spiking Neural Network for decoding EEG on Neuromorphic Hardware. "PyTorch and Loihi implementation of the Spiking Neural Network for decoding EEG on Neuromorphic Hardware". (**[TMLR 2022](https://openreview.net/forum?id=ZPBJPGX3Bz)**)

  - [SpikingSIM](https://github.com/Evin-X/SpikingSIM) <img src="https://img.shields.io/github/stars/Evin-X/SpikingSIM?style=social"/> : "SpikingSIM: A Bio-inspired Spiking Simulator". (ISCAS 2022)

  - [Mathorga/behema](https://github.com/Mathorga/behema) <img src="https://img.shields.io/github/stars/Mathorga/behema?style=social"/> : Spiking neural network implementation inspired by cellular automata for efficiency.

  - [synsense/rockpool](https://github.com/synsense/rockpool) <img src="https://img.shields.io/github/stars/synsense/rockpool?style=social"/> : A machine learning library for spiking neural networks. Supports training with both torch and jax pipelines, and deployment to neuromorphic hardware.

  - [Sinabs](https://github.com/synsense/sinabs) <img src="https://img.shields.io/github/stars/synsense/sinabs?style=social"/> : Spiking neural network library based on PyTorch.

  - [MungoMeng/Spiking-Inception](https://github.com/MungoMeng/Spiking-Inception) <img src="https://img.shields.io/github/stars/MungoMeng/Spiking-Inception?style=social"/> : A Spiking Inception architecture for unsupervised Spiking Neural Networks (SNNs). "High-parallelism Inception-like Spiking Neural Networks for Unsupervised Feature Learning". (**[Neurocomputing 2021](https://www.sciencedirect.com/science/article/abs/pii/S0925231221002733)**). "Spiking Inception Module for Multi-layer Unsupervised Spiking Neural Networks". (**[IJCNN 2020](https://ieeexplore.ieee.org/abstract/document/9207161)**).

  - [BioLCNet](https://github.com/Singular-Brain/BioLCNet) <img src="https://img.shields.io/github/stars/Singular-Brain/BioLCNet?style=social"/> : "BioLCNet: Reward-modulated Locally Connected Spiking Neural Networks". (**[arXiv 2021](https://arxiv.org/abs/2109.05539)**)

  - [aggelen/Spayk](https://github.com/aggelen/Spayk) <img src="https://img.shields.io/github/stars/aggelen/Spayk?style=social"/> : An open source environment for spiking neural networks.

  - [ANNarchy](https://github.com/ANNarchy/ANNarchy) <img src="https://img.shields.io/github/stars/ANNarchy/ANNarchy?style=social"/> : "ANNarchy: a code generation approach to neural simulations on parallel hardware". (**[Frontiers in Neuroinformatics 2015](https://www.frontiersin.org/articles/10.3389/fninf.2015.00019/full)**)

  - [Real-Spike](https://github.com/yfguo91/Real-Spike) <img src="https://img.shields.io/github/stars/yfguo91/Real-Spike?style=social"/> : "Real Spike: Learning Real-valued Spikes for Spiking Neural Networks". (ECCV 2022)

  - [Spike-Element-Wise-ResNet](https://github.com/fangwei123456/Spike-Element-Wise-ResNet) <img src="https://img.shields.io/github/stars/fangwei123456/Spike-Element-Wise-ResNet?style=social"/> : "Deep residual learning in spiking neural networks". (**[NeurIPS 2021](https://proceedings.neurips.cc/paper/2021/hash/afe434653a898da20044041262b3ac74-Abstract.html)**)

  - [cuSNN](https://github.com/tudelft/cuSNN) <img src="https://img.shields.io/github/stars/tudelft/cuSNN?style=social"/> : Spiking Neural Networks in C++ with strong GPU acceleration through CUDA. "Unsupervised Learning of a Hierarchical Spiking Neural Network for Optical Flow Estimation: From Events to Global Motion Perception". (**[TPAMI 2020](https://ieeexplore.ieee.org/abstract/document/8660483/)**)

  - [nengo/pytorch-spiking](https://github.com/nengo/pytorch-spiking) <img src="https://img.shields.io/github/stars/nengo/pytorch-spiking?style=social"/> : Spiking neuron integration for PyTorch. www.nengo.ai/pytorch-spiking/.

  - [zhouyanasd/DL-NC](https://github.com/zhouyanasd/DL-NC) <img src="https://img.shields.io/github/stars/zhouyanasd/DL-NC?style=social"/> : spiking-neural-networks.

  - [ShahriarSS/Spyker](https://github.com/ShahriarSS/Spyker) <img src="https://img.shields.io/github/stars/ShahriarSS/Spyker?style=social"/> : High-performance Spiking Neural Networks Library Written From Scratch with C++ and Python Interfaces.

  - [STSC-SNN](https://github.com/Tab-ct/STSC-SNN) <img src="https://img.shields.io/github/stars/Tab-ct/STSC-SNN?style=social"/> : "STSC-SNN: Spatio-Temporal Synaptic Connection with temporal convolution and attention for spiking neural networks". (**[Frontiers in Neuroscience, 2022](https://arxiv.org/abs/2210.05241)**)

  - [michaelmelanson/spiking-neural-net](https://github.com/michaelmelanson/spiking-neural-net) <img src="https://img.shields.io/github/stars/michaelmelanson/spiking-neural-net?style=social"/> : A spiking neural network simulation library.

  - [STSC-SNN](https://github.com/INM-6/multi-area-model) <img src="https://img.shields.io/github/stars/INM-6/multi-area-model?style=social"/> : Multi-scale spiking network model of macaque visual cortex. "Multi-scale account of the network structure of macaque visual cortex". (**[Brain Structure and Function, 2018](https://link.springer.com/article/10.1007/s00429-017-1554-4)**). "A multi-scale layer-resolved spiking network model of resting-state dynamics in macaque visual cortical areas". (**[PLOS Computational Biology, 2018](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006359)**).





## Applications

  - ### Attention and Transformer

    - [Attention-SNN](https://github.com/BICLab/Attention-SNN) <img src="https://img.shields.io/github/stars/BICLab/Attention-SNN?style=social"/> : Offical implementation of "Attention Spiking Neural Networks" (**[IEEE TPAMI 2023](https://ieeexplore.ieee.org/abstract/document/10032591)**)

    - [Spike-Driven-Transformer](https://github.com/BICLab/Spike-Driven-Transformer) <img src="https://img.shields.io/github/stars/BICLab/Spike-Driven-Transformer?style=social"/> : Offical implementation of "Spike-driven Transformer" (**[NeurIPS 2023](https://openreview.net/forum?id=9FmolyOHi5)**)

    - [Spike-Driven-Transformer-V2](https://github.com/BICLab/Spike-Driven-Transformer-V2) <img src="https://img.shields.io/github/stars/BICLab/Spike-Driven-Transformer-V2?style=social"/> : Offical implementation of "Spike-driven Transformer V2: Meta Spiking Neural Network Architecture Inspiring the Design of Next-generation Neuromorphic Chips" (**[ICLR 2024](https://openreview.net/forum?id=1SIBN5Xyw7)**)




  - ### Object Detection

    - [SpikeYOLO](https://github.com/BICLab/SpikeYOLO) <img src="https://img.shields.io/github/stars/BICLab/SpikeYOLO?style=social"/> : Offical implementation of "Integer-Valued Training and Spike-Driven Inference Spiking Neural Network for High-performance and Energy-efficient Object Detection" (**[ECCV 2024 Oral](https://arxiv.org/abs/2407.20708)**)


    - [EMS-YOLO](https://github.com/BICLab/EMS-YOLO) <img src="https://img.shields.io/github/stars/BICLab/EMS-YOLO?style=social"/> : Offical implementation of "Deep Directly-Trained Spiking Neural Networks for Object Detection" (**[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/html/Su_Deep_Directly-Trained_Spiking_Neural_Networks_for_Object_Detection_ICCV_2023_paper.html)**)

    - [Attention-SNN](https://github.com/BICLab/Attention-SNN) <img src="https://img.shields.io/github/stars/BICLab/Attention-SNN?style=social"/> : Offical implementation of "Attention Spiking Neural Networks" (**[IEEE TPAMI 2023](https://ieeexplore.ieee.org/abstract/document/10032591)**)

    - [Spike-Driven-Transformer](https://github.com/BICLab/Spike-Driven-Transformer) <img src="https://img.shields.io/github/stars/BICLab/Spike-Driven-Transformer?style=social"/> : Offical implementation of "Spike-driven Transformer" (**[NeurIPS 2023](https://openreview.net/forum?id=9FmolyOHi5)**)

    - [Spike-Driven-Transformer-V2](https://github.com/BICLab/Spike-Driven-Transformer-V2) <img src="https://img.shields.io/github/stars/BICLab/Spike-Driven-Transformer-V2?style=social"/> : Offical implementation of "Spike-driven Transformer V2: Meta Spiking Neural Network Architecture Inspiring the Design of Next-generation Neuromorphic Chips" (**[ICLR 2024](https://openreview.net/forum?id=1SIBN5Xyw7)**)

    - [Spiking-YOLOv3](https://github.com/cwq159/PyTorch-Spiking-YOLOv3) <img src="https://img.shields.io/github/stars/cwq159/PyTorch-Spiking-YOLOv3?style=social"/> : A PyTorch implementation of Spiking-YOLOv3. Two branches are provided, based on two common PyTorch implementation of YOLOv3([ultralytics/yolov3](https://github.com/ultralytics/yolov3) & [eriklindernoren/PyTorch-YOLOv3](https://github.com/eriklindernoren/PyTorch-YOLOv3)), with support for Spiking-YOLOv3-Tiny at present. (**[AAAI 2020](https://ojs.aaai.org/index.php/AAAI/article/view/6787)**)

    - [fjcu-ee-islab/Spiking_Converted_YOLOv4](https://github.com/fjcu-ee-islab/Spiking_Converted_YOLOv4) <img src="https://img.shields.io/github/stars/fjcu-ee-islab/Spiking_Converted_YOLOv4?style=social"/> : Object Detection Based on Dynamic Vision Sensor with Spiking Neural Network.

    - [Zaabon/spiking_yolo](https://github.com/Zaabon/spiking_yolo) <img src="https://img.shields.io/github/stars/Zaabon/spiking_yolo?style=social"/> : This project is a combined neural network utilizing an spiking CNN with backpropagation and YOLOv3 for object detection.

    - [Dignity-ghost/PyTorch-Spiking-YOLOv3](https://github.com/Dignity-ghost/PyTorch-Spiking-YOLOv3) <img src="https://img.shields.io/github/stars/Dignity-ghost/PyTorch-Spiking-YOLOv3?style=social"/> : A modified repository based on [Spiking-YOLOv3](https://github.com/cwq159/PyTorch-Spiking-YOLOv3) and [YOLOv3](https://pjreddie.com/darknet/yolo), which makes it suitable for VOC-dataset and YOLOv2.

    - [beauty-girl-cxy/spiking-yolov5](https://github.com/beauty-girl-cxy/spiking-yolov5) <img src="https://img.shields.io/github/stars/beauty-girl-cxy/spiking-yolov5?style=social"/> : spiking-yolov5.

    - [arsalikhov/PSYCH420_final_project](https://github.com/arsalikhov/PSYCH420_final_project) <img src="https://img.shields.io/github/stars/arsalikhov/PSYCH420_final_project?style=social"/> : Goal of the project is to train an Object-Detection model using Spiking Neural Network on COCO dataset.

    - [loiccordone/object-detection-with-spiking-neural-networks](https://github.com/loiccordone/object-detection-with-spiking-neural-networks) <img src="https://img.shields.io/github/stars/loiccordone/object-detection-with-spiking-neural-networks?style=social"/> : "Object Detection with Spiking Neural Networks on Automotive Event Data". (**[IJCNN 2022](https://arxiv.org/abs/2205.04339)**)




  - ### Object Recognition

    - [freek9807/SNN-NMNIST-Object-Recognition](https://github.com/freek9807/SNN-NMNIST-Object-Recognition) <img src="https://img.shields.io/github/stars/freek9807/SNN-NMNIST-Object-Recognition?style=social"/> : An object recognition model for NMNIST larger video frame.


  - ### Adversarial Attack and Defense

    - [ssharmin/spikingNN-adversarial-attack](https://github.com/ssharmin/spikingNN-adversarial-attack) <img src="https://img.shields.io/github/stars/ssharmin/spikingNN-adversarial-attack?style=social"/> : FGSM and PGD adversarial attack on Spiking Neural Network (SNN).


  - ### Speech and Audio Field

    - [flinkerlab/neural_speech_decoding](https://github.com/flinkerlab/neural_speech_decoding) <img src="https://img.shields.io/github/stars/flinkerlab/neural_speech_decoding?style=social"/> : Neural Speech Decoding. "A neural speech decoding framework leveraging deep learning and speech synthesis". (**[Nature, 2024](https://www.nature.com/articles/s42256-024-00824-8)**). "微信公众号「量子位」《[脑电合成自然语音！LeCun转发Nature子刊新成果，代码开源](https://mp.weixin.qq.com/s/BcV3-3glmdsVF--fpPRU2g)》"。

    - [comob-project/snn-sound-localization](https://github.com/comob-project/snn-sound-localization) <img src="https://img.shields.io/github/stars/comob-project/snn-sound-localization?style=social"/> : Training spiking neural networks for sound localization.

    - [pyNAVIS](https://github.com/jpdominguez/pyNAVIS) <img src="https://img.shields.io/github/stars/jpdominguez/pyNAVIS?style=social"/> : "PyNAVIS: An open-source cross-platform software for spike-based neuromorphic audio information processing". (**[Neurocomputing, 2021](https://www.sciencedirect.com/science/article/abs/pii/S0925231221005130)**)




  - ### Event-Based Application

    - [uzh-rpg/snn_angular_velocity](https://github.com/uzh-rpg/snn_angular_velocity) <img src="https://img.shields.io/github/stars/uzh-rpg/snn_angular_velocity?style=social"/> : "Event-Based Angular Velocity Regression with Spiking Networks". (**[ICRA 2020](https://ieeexplore.ieee.org/abstract/document/9197133)**)



  - ### Hardware Deployment

    - [catalyst-neuromorphic/catalyst-benchmarks](https://github.com/catalyst-neuromorphic/catalyst-benchmarks) <img src="https://img.shields.io/github/stars/catalyst-neuromorphic/catalyst-benchmarks?style=social"/> : SNN benchmark suite for the Catalyst neuromorphic processor (128 cores, 131K neurons, FPGA). Includes SHD (90.7%), SSC (72.1%), N-MNIST (99.2%), and GSC KWS (88.0%) benchmarks with full Loihi 2 feature parity. [[Paper-N1](https://doi.org/10.5281/zenodo.18727094)][[Paper-N2](https://doi.org/10.5281/zenodo.18728256)]

    - [metr0jw/Spiking-Neural-Network-on-FPGA](https://github.com/metr0jw/Spiking-Neural-Network-on-FPGA) <img src="https://img.shields.io/github/stars/metr0jw/Spiking-Neural-Network-on-FPGA?style=social"/> : Leaky Integrate and Fire (LIF) model implementation for FPGA.





## Blogs

  - 微信公众号「智能的本质与未来」
    - [2022-07-20，类脑认知智能引擎“智脉”：全脉冲神经网络的新一代人工智能开源平台](https://mp.weixin.qq.com/s/nfF1BYIL7ktvHRKDuKBTNQ)
    - [2022-09-06，【智脉说】类脑认知智能引擎BrainCog基础 第1期 BrainCog系统部署](https://mp.weixin.qq.com/s/fX-S3fKKDfR3NV4ISAHrZg)
    - [2022-09-07，【智脉说】类脑认知智能引擎BrainCog基础 第2期 脉冲神经元计算建模](https://mp.weixin.qq.com/s/pCdlbkrdnMNHj7wcwi9D2Q)
    - [2022-09-14，【智脉说】类脑认知智能引擎BrainCog基础 第3期 高效构建脉冲神经网络](https://mp.weixin.qq.com/s/NIz7MSAOJQ79m97hkP3HVg)
    - [2022-09-20，【智脉说】类脑认知智能引擎BrainCog基础 第4期 构建脑区的认知脉冲神经网络模型](https://mp.weixin.qq.com/s/K0pY6V8TupJgYXH4WvS9jg)
    - [2022-09-30，【智脉说】类脑认知智能引擎BrainCog基础 第5期 BrainCog系统功能进阶](https://mp.weixin.qq.com/s/ywgQ5ydQxr6W7d_Y_XqC6w)
    - [2022-10-16，【智脉说】类脑认知智能引擎BrainCog基础 第6期 用BrainGog实现深度强化学习脉冲神经网络](https://mp.weixin.qq.com/s/Zt78vj_sKn5jffEyeh86Cw)
    - [2022-10-18，【智脉说】类脑认知智能引擎BrainCog基础 第7期 用BrainGog实现受量子叠加态启发的脉冲序列时空编码](https://mp.weixin.qq.com/s/YVNkwDwuF9FG-YqQyd3KTg)
    - [2022-10-26，【智脉说】类脑认知智能引擎BrainCog基础 第8期 用BrainCog实现从人工神经网络到​脉冲神经网络的转换](https://mp.weixin.qq.com/s/4g8WBoa4SOcb_VQ24wO-Xw)
    - [2022-11-03，【智脉说】类脑认知引擎Braincog基础 第9期 用Braincog实现全局反馈连接脉冲神经网络](https://mp.weixin.qq.com/s/-AS0BihlXdFwCt1hgzFx3g)
    - [2022-11-09，【智脉说】类脑认知引擎Braincog基础 第10期 用Braincog实现多脑区协同的类脑自主决策脉冲神经网络](https://mp.weixin.qq.com/s/dltOGjhUZ9yTzSssIvkhtA)
    - [2022-11-18，【智脉说】类脑认知引擎Braincog基础 第11期 用Braincog实现类脑脉冲神经网络高效时空调节训练](https://mp.weixin.qq.com/s/6ZtaWtiY9K96UhVnvhfP7w)
    - [2022-11-28，【智脉说】类脑认知引擎Braincog基础 第12期 用Braincog实现基于脉冲时序依赖可塑性的无监督脉冲神经网络](https://mp.weixin.qq.com/s/v_svhQ0N3JAYo1l8NQ1W1w)
    - [2022-12-03，【智脉说】类脑认知引擎Braincog基础 第13期 用Braincog实现基于群体编码机制启发的符号表征与推理](https://mp.weixin.qq.com/s/UXc5QDbg8tUKVU3L6dhvxw)
    - [2022-12-12，【智脉说】类脑认知引擎Braincog基础 第14期 实现基于脉冲神经网络的多感觉融合概念学习](https://mp.weixin.qq.com/s/s9gXF5NkPUGXkcFAFtsCMw)
    - [2022-12-31，【智脉说】类脑认知智能引擎BrainCog基础 第15期 用Braincog实现基于脉冲神经网络的音乐记忆与创作模型](https://mp.weixin.qq.com/s/y-t9rFEXYSmI_-rnVk_usw)
    - [2023-01-08，【智脉说】类脑认知智能引擎BrainCog基础 第16期 用Braincog实现基于脉冲神经网络的类脑身体自我感知模型](https://mp.weixin.qq.com/s/RLbS3GmhE8ScyZTKJKl_SQ)
    - [2023-01-09，【智脉说】类脑认知智能引擎BrainCog基础 第17期 类脑心理揣测模型以及其在帮助其他智能体避免安全风险任务中的应用](https://mp.weixin.qq.com/s/xzFF6IK86W4h2CMs7jt7Xw)
    - [2023-01-18，类脑认知智能引擎“智脉BrainCog”半岁了：最新研究进展与研发社区建设](https://mp.weixin.qq.com/s/NO4zFDIVtQdndvc4c01dDQ)
    - [2023-02-02，从认知脑的计算模拟到类脑人工智能](https://mp.weixin.qq.com/s/ATZ8Bjq7nUOH5E-2EE9JGQ)
    - [2023-02-03，【智脉说】类脑认知智能引擎BrainCog基础 第18期 用BrainCog实现前额叶功能柱模型在工作记忆任务中的应用](https://mp.weixin.qq.com/s/E6pb5W0Q4noK72NGf4SNGQ)
    - [2023-02-09，【智脉说】类脑认知智能引擎BrainCog基础 第19期 用BrainCog实现多脑区协同的类脑情感共情脉冲神经网络](https://mp.weixin.qq.com/s/xUnal4I5tM-Rl49fu0ZRVw)
    - [2023-02-16，【智脉说】类脑认知智能引擎BrainCog基础 第20期 用BrainCog实现发育可塑性的脉冲神经网络自适应剪枝](https://mp.weixin.qq.com/s/-F0XcIovI1WY6YyoO5P58Q)
    - [2023-02-25，【智脉说】类脑认知智能引擎BrainCog基础 第21期 用Braincog实现基于约束、剪枝和再生的脉冲神经网络动态结构发育](https://mp.weixin.qq.com/s/n1EK6lddriS0dnSgfdsa8w)
    - [2023-03-15，【智脉说】类脑认知智能引擎BrainCog基础 第22期 BrainCog数据引擎之时空序列数据N-Omniglot及其应用](https://mp.weixin.qq.com/s/VIzDb2kn_4LUyUh0qc2j4w)
    - [2023-03-23，【智脉说】类脑认知智能引擎BrainCog基础 第23期 用BrainCog实现用于目标检测和语义分割的脉冲神经网络](https://mp.weixin.qq.com/s/fyf_cbzH_i1_ZEFWTSH81Q)
    - [2023-04-14，【智脉说】类脑认知智能引擎BrainCog基础 第24期 用BrainCog实现EventMix 针对DVS数据的增强策略](https://mp.weixin.qq.com/s/BNMZ_oQK9Foui2zcnKWYgg)
  - 微信公众号「图灵人工智能」
    - [2023-05-06，神经科学的深度学习框架](https://mp.weixin.qq.com/s/EJNcVMhx63wTiCjfsT43Gg)
  - 微信公众号「蜂耘网」
    - [2024-04-19，类脑AI新时代——全球最大神经拟态系统诞生了！](https://mp.weixin.qq.com/s/I59_0WWdUSb9yyUTBup8qA)
  - 微信公众号「量子位」
    - [2024-04-17，脑电合成自然语音！LeCun转发Nature子刊新成果，代码开源](https://mp.weixin.qq.com/s/BcV3-3glmdsVF--fpPRU2g)
  - 微信公众号「AI Energy」
    - [2023-10-07，Science Advances | SpikingJelly：基于尖峰智能的开源机器学习基础平台](https://mp.weixin.qq.com/s/HZAruFdXW6uWaZGR9jUAGA)
  - 微信公众号「数据派THU」
    - [2024-06-30，「千脑计划」启动，模仿人类大脑皮层，开发全新AI，盖茨资助](https://mp.weixin.qq.com/s/m5QaD98tVRaHY_4Lc5IqIw)
  - 微信公众号「深观启元」
    - [2024-06-20，浅谈脉冲神经网络（SNN）](https://mp.weixin.qq.com/s/at7wyg5P2m7XLUlDydDFLw)
  - 微信公众号「算力猩」
    - [2022-05-09，中科院自动化所研究员李国齐：类脑计算的前世今生](https://mp.weixin.qq.com/s/AwU6qNLO2xjv5qi2PDOiSQ)
  - 微信公众号「算力猩」
    - [2023-10-19，深度学习框架重要突破！鹏城实验室田永鸿教授领衔，国产AI芯片成幕后功臣](https://mp.weixin.qq.com/s/Hdg7cEAvQEpgfHLcL-zZug)
  - 微信公众号「中国科学院自动化研究所」
    - [2023-11-21，脑科学如何启发AI，这场论坛带你全面探索「大脑网络与智能计算融合方式」](https://mp.weixin.qq.com/s/TLbVhLeKvrtBGZArSPblgA)
  - 微信公众号「北京大学计算机学院」
    - [2023-10-09，新闻丨北京大学计算机学院田永鸿课题组脉冲神经网络深度学习开源框架荣登Science子刊](https://mp.weixin.qq.com/s/Q4Qhy9SYZ34Dgo4EE7yclw)
  - 微信公众号「北京大学计算机学院」
    - [2024-03-16，科学家为脉冲神经网络引入新架构，为未来基于神经形态网络的超大模型奠定基础](https://mp.weixin.qq.com/s/nayHqKJoExYY6FQG1NGdPw)
  - 微信公众号「智源社区」
    - [2022-05-07，一文梳理类脑计算的前世今生 | 中科院自动化所研究员李国齐](https://mp.weixin.qq.com/s/9-FW5ZxJt4fthNhQI10qHA)