[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

This repository contains a collection of resources and papers on ***Diffusion Models***.

## Contents
- [Resources](#resources)
  - [Introductory Posts](#introductory-posts)
  - [Introductory Papers](#introductory-papers)
  - [Introductory Videos](#introductory-videos)
  - [Introductory Lectures](#introductory-lectures)
  - [Tutorial and Jupyter Notebook](#tutorial-and-jupyter-notebook)
- [Papers](#papers)
  - [Survey](#survey)
  - [Vision](#vision)
    - [Image Generation](#image-generation)
    - [Segmentation](#segmentation)
    - [Image-to-Image Translation](#image-to-image-translation)
    - [Super Resolution](#super-resolution)
    - [Image Inpainting](#image-inpainting)
    - [Image Editing](#image-editing)
    - [Text-to-Image](#text-to-image)
    - [Medical Imaging](#medical-imaging)
    - [Video Generation](#video-generation)
    - [Point Cloud](#point-cloud)
    - [Mesh](#mesh)
    - [3D View](#3d-view)
    - [Human Motion Synthesis](#human-motion-synthesis)
    - [Adversarial Attack](#adversarial-attack)
    - [Miscellaneous](#miscellaneous)
  - [Audio](#audio)
    - [Audio Generation](#audio-generation)
    - [Audio Conversion](#audio-conversion)
    - [Audio Enhancement](#audio-enhancement)
    - [Text-to-Speech](#text-to-speech)
    - [Music Generation](#music-generation)
    - [Separation](#separation)
  - [Natural Language](#natural-language)
    - [Natural Language Generation](#natural-language-generation)
  - [Tabular and Time Series](#tabular-and-time-series)
    - [Generation](#generation)
    - [Forecasting](#forecasting)
    - [Imputation](#imputation)
  - [Graph](#graph)
    - [Graph Generation](#graph-generation)
    - [Molecular and Material Generation](#molecular-and-material-generation)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Theory](#theory)
  - [Applications](#applications)


# Resources
## Introductory Posts

**How diffusion models work: the math from scratch** \
*Sergios Karagiannakos,Nikolas Adaloglou* \
[[Website](https://theaisummer.com/diffusion-models/?fbclid=IwAR1BIeNHqa3NtC8SL0sKXHATHklJYphNH-8IGNoO3xZhSKM_GYcvrrQgB0o)] \
24 Sep 2022

**A Path to the Variational Diffusion Loss** \
*Alex Alemi* \
[[Website](https://blog.alexalemi.com/diffusion.html)] [[Colab](https://colab.research.google.com/github/google-research/vdm/blob/main/colab/SimpleDiffusionColab.ipynb)] \
15 Sep 2022

**The Annotated Diffusion Model** \
*Niels Rogge, Kashif Rasul* \
[[Website](https://huggingface.co/blog/annotated-diffusion)] \
06 Jun 2022

**The recent rise of diffusion-based models** \
*Maciej Domagała* \
[[Website](https://maciejdomagala.github.io/generative_models/2022/06/06/The-recent-rise-of-diffusion-based-models.html)] \
06 Jun 2022

**Introduction to Diffusion Models for Machine Learning** \
*Ryan O'Connor* \
[[Website](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/)] \
12 May 2022

**Improving Diffusion Models as an Alternative To GANs** \
*Arash Vahdat and Karsten Kreis* \
[[Website-Part 1](https://developer.nvidia.com/blog/improving-diffusion-models-as-an-alternative-to-gans-part-1/)] [[Website-Part 2](https://developer.nvidia.com/blog/improving-diffusion-models-as-an-alternative-to-gans-part-2/)] \
26 Apr 2022

**An introduction to Diffusion Probabilistic Models** \
*Ayan Das* \
[[Website](https://ayandas.me/blog-tut/2021/12/04/diffusion-prob-models.html)] \
04 Dec 2021

**Introduction to deep generative modeling: Diffusion-based Deep Generative Models** \
*Jakub Tomczak* \
[[Website](https://jmtomczak.github.io/blog/10/10_ddgms_lvm_p2.html)] \
30 Aug 2021

**What are Diffusion Models?** \
*Lilian Weng* \
[[Website](https://lilianweng.github.io/lil-log/2021/07/11/diffusion-models.html)] \
11 Jul 2021

**Diffusion Models as a kind of VAE** \
*Angus Turner* \
[[Website](https://angusturner.github.io/generative_models/2021/06/29/diffusion-probabilistic-models-I.html)] \
29 June 2021

**Generative Modeling by Estimating Gradients of the Data Distribution** \
*Yang Song* \
[[Website](https://yang-song.github.io/blog/2021/score/)] \
5 May 2021

## Introductory Papers

**Understanding Diffusion Models: A Unified Perspective** \
*Calvin Luo* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.11970)] \
25 Aug 2022

**How to Train Your Energy-Based Models** \
*Yang Song, Diederik P. Kingma* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2101.03288)] \
9 Jan 2021

## Introductory Videos

**Diffusion Models | Paper Explanation | Math Explained** \
*Outlier* \
[[Video](https://www.youtube.com/watch?v=HoKDTa5jHvg)] \
Jun 6 2022

**What are Diffusion Models?** \
*Ari Seff* \
[[Video](https://www.youtube.com/watch?v=fbLgFrlTnGU&list=LL&index=2)] \
20 Apr 2022

**Diffusion models explained** \
*AI Coffee Break with Letitia* \
[[Video](https://www.youtube.com/watch?v=344w5h24-h8&ab_channel=AICoffeeBreakwithLetitia)] \
23 Mar 2022

## Introductory Lectures

**Denoising Diffusion-based Generative Modeling: Foundations and Applications** \
*Karsten Kreis, Ruiqi Gao, Arash Vahdat* \
[[Page](https://cvpr2022-tutorial-diffusion-models.github.io/)] \
19 June 2022

**Diffusion Probabilistic Models** \
*Jascha Sohl-Dickstein, MIT 6.S192 - Lecture 22* \
[[Video](https://www.youtube.com/watch?v=XCUlnHP1TNM)] \
19 April 2022

## Tutorial and Jupyter Notebook

**diffusion-for-beginners** \
*ozanciga* \
[[Github](https://github.com/ozanciga/diffusion-for-beginners)]

**Beyond Diffusion: What is Personalized Image Generation and How Can You Customize Image Synthesis?** \
*J. Rafid Siddiqui* \
[[Github](https://github.com/azad-academy/personalized-diffusion)] [[Medium](https://medium.com/mlearning-ai/beyond-diffusion-what-is-personalized-image-generation-and-how-can-you-customize-image-synthesis-26a89d5b335)]

**Diffusion_models_tutorial** \
*FilippoMB* \
[[Github](https://github.com/FilippoMB/Diffusion_models_tutorial)]

**ScoreDiffusionModel** \
*JeongJiHeon* \
[[Github](https://github.com/JeongJiHeon/ScoreDiffusionModel)]

**Minimal implementation of diffusion models** \
*VSehwag* \
[[Github](https://github.com/VSehwag/minimal-diffusion)]

**diffusion_tutorial** \
*sunlin-ai* \
[[Github](https://github.com/sunlin-ai/diffusion_tutorial)] 

**Denoising diffusion probabilistic models** \
*acids-ircam* \
[[Github](https://github.com/acids-ircam/diffusion_models)] 


**Centipede Diffusion** \
[[Notebook](https://colab.research.google.com/github/Zalring/Centipede_Diffusion/blob/main/Centipede_Diffusion.ipynb)]

**Deforum Stable Diffusion** \
[[Notebook](https://colab.research.google.com/github/deforum/stable-diffusion/blob/main/Deforum_Stable_Diffusion.ipynb)]

**Stable Diffusion Interpolation** \
[[Notebook](https://colab.research.google.com/drive/1EHZtFjQoRr-bns1It5mTcOVyZzZD9bBc?usp=sharing)]

**Keras Stable Diffusion: GPU starter example** \
[[Notebook](https://colab.research.google.com/drive/1zVTa4mLeM_w44WaFwl7utTaa6JcaH1zK)]

**Huemin Jax Diffusion** \
[[Notebook](https://colab.research.google.com/github/huemin-art/jax-guided-diffusion/blob/v2.7/Huemin_Jax_Diffusion_2_7.ipynb)]

**Disco Diffusion** \
[[Notebook](https://colab.research.google.com/github/alembics/disco-diffusion/blob/main/Disco_Diffusion.ipynb)]

**Simplified Disco Diffusion** \
[[Notebook](https://colab.research.google.com/github/entmike/disco-diffusion-1/blob/main/Simplified_Disco_Diffusion.ipynb)]

**WAS's Disco Diffusion - Portrait Generator Playground** \
[[Notebook](https://colab.research.google.com/github/WASasquatch/disco-diffusion-portrait-playground/blob/main/WAS's_Disco_Diffusion_v5_6_9_%5BPortrait_Generator_Playground%5D.ipynb)]

**Diffusers - Hugging Face** \
[[Notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/diffusers_intro.ipynb)] 


# Papers

## Survey

**Diffusion Models for Medical Image Analysis: A Comprehensive Survey** \
*Amirhossein Kazerouni, Ehsan Khodapanah Aghdam, Moein Heidari, Reza Azad, Mohsen Fayyaz, Ilker Hacihaliloglu, Dorit Merhof* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.07804)] [[Github](https://github.com/amirhossein-kz/Awesome-Diffusion-Models-in-Medical-Imaging)] \
14 Nov 2022

**Efficient Diffusion Models for Vision: A Survey** \
*Anwaar Ulhaq, Naveed Akhtar, Ganna Pogrebna* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09292)] \
7 Oct 2022

**Diffusion Models in Vision: A Survey** \
*Florinel-Alin Croitoru, Vlad Hondru, Radu Tudor Ionescu, Mubarak Shah* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.04747)] \
10 Sep 2022

**A Survey on Generative Diffusion Model** \
*Hanqun Cao, Cheng Tan, Zhangyang Gao, Guangyong Chen, Pheng-Ann Heng, Stan Z. Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.02646)] \
6 Sep 2022

**Diffusion Models: A Comprehensive Survey of Methods and Applications** \
*Ling Yang<sup>1</sup>, Zhilong Zhang<sup>1</sup>, Shenda Hong, Wentao Zhang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.00796)] \
2 Sep 2022

## Vision
### Image Generation


**Why Are Conditional Generative Models Better Than Unconditional Ones?** \
*Fan Bao, Chongxuan Li, Jiacheng Sun, Jun Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00362)] \
1 Dec 2022


**High-Fidelity Guided Image Synthesis with Latent Diffusion Models** \
*Jaskirat Singh, Stephen Gould, Liang Zheng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.17084)] [[Project](https://1jsingh.github.io/gradop)] \
30 Nov 2022


**Score-based Continuous-time Discrete Diffusion Models** \
*Haoran Sun, Lijun Yu, Bo Dai, Dale Schuurmans, Hanjun Dai* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16750)] \
30 Nov 2022

**Wavelet Diffusion Models are fast and scalable Image Generators** \
*Hao Phung, Quan Dao, Anh Tran* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16152)] \
29 Nov 2022


**Dimensionality-Varying Diffusion Process** \
*Han Zhang, Ruili Feng, Zhantao Yang, Lianghua Huang, Yu Liu, Yifei Zhang, Yujun Shen, Deli Zhao, Jingren Zhou, Fan Cheng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16032)] \
29 Nov 2022

**Refining Generative Process with Discriminator Guidance in Score-based Diffusion Models** \
*Dongjun Kim<sup>1</sup>, Yeongmin Kim<sup>1</sup>, Wanmo Kang, Il-Chul Moon* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.17091)] \
28 Nov 2022

**Fast Sampling of Diffusion Models via Operator Learning** \
*Hongkai Zheng, Weili Nie, Arash Vahdat, Kamyar Azizzadenesheli, Anima Anandkumar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13449)] \
24 Nov 2022


**SinDiffusion: Learning a Diffusion Model from a Single Natural Image** \
*Weilun Wang, Jianmin Bao, Wengang Zhou, Dongdong Chen, Dong Chen, Lu Yuan, Houqiang Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12445)] [[Github](https://github.com/WeilunWang/SinDiffusion)] \
22 Nov 2022

**Accelerating Diffusion Sampling with Classifier-based Feature Distillation** \
*Wujie Sun, Defang Chen, Can Wang, Deshi Ye, Yan Feng, Chun Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12039)] \
22 Nov 2022

**SceneComposer: Any-Level Semantic Image Synthesis** \
*Yu Zeng, Zhe Lin, Jianming Zhang, Qing Liu, John Collomosse, Jason Kuen, Vishal M. Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11742)] [[Project](https://zengyu.me/scenec/)] \
21 Nov 2022

**Diffusion-Based Scene Graph to Image Generation with Masked Contrastive Pre-Training** \
*Ling Yang<sup>1</sup>, Zhilin Huang<sup>1</sup>, Yang Song, Shenda Hong, Guohao Li, Wentao Zhang, Bin Cui, Bernard Ghanem, Ming-Hsuan Yang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11138)] \
21 Nov 2022



**SinFusion: Training Diffusion Models on a Single Image or Video** \
*Yaniv Nikankin, Niv Haim, Michal Irani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11743)] \
21 Nov 2022

**Seeing Beyond the Brain: Conditional Diffusion Model with Sparse Masked Modeling for Vision Decoding** \
*Zijiao Chen, Jiaxin Qing, Tiange Xiang, Wan Lin Yue, Juan Helen Zhou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.06956)] [[Project](https://mind-vis.github.io/)] [[Github](https://github.com/zjc062/mind-vis)] \
13 Nov 2022

**Few-shot Image Generation with Diffusion Models** \
*Jingyuan Zhu, Huimin Ma, Jiansheng Chen, Jian Yuan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.03264)] \
7 Nov 2022

**From Denoising Diffusions to Denoising Markov Models** \
*Joe Benton, Yuyang Shi, Valentin De Bortoli, George Deligiannidis, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.03595)] [[Github](https://github.com/yuyang-shi/generalized-diffusion)] \
7 Nov 2022

**An optimal control perspective on diffusion-based generative modeling** \
*Julius Berner, Lorenz Richter, Karen Ullrich* \
NeurIPS Workshop 2022. [[Paper](https://arxiv.org/abs/2211.01364)] \
2 Nov 2022

**Entropic Neural Optimal Transport via Diffusion Processes** \
*Nikita Gushchin, Alexander Kolesov, Alexander Korotin, Dmitry Vetrov, Evgeny Burnaev* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.01156)] \
2 Nov 2022

**DPM-Solver++: Fast Solver for Guided Sampling of Diffusion Probabilistic Models** \
*Cheng Lu, Yuhao Zhou, Fan Bao, Jianfei Chen, Chongxuan Li, Jun Zhu* \
NeurIPS 2022 (Oral) [[Paper](https://arxiv.org/abs/2211.01095)] [[Github](https://github.com/LuChengTHU/dpm-solver)] \
2 Nov 2022

**Score-based Denoising Diffusion with Non-Isotropic Gaussian Noise Models** \
*Vikram Voleti, Christopher Pal, Adam Oberman* \
NeurIPS Workshop 2022. [[Paper](https://arxiv.org/abs/2210.12254)] \
21 Oct 2022


**Deep Equilibrium Approaches to Diffusion Models** \
*Ashwini Pokle, Zhengyang Geng, Zico Kolter* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2210.12867)] [[Github](https://github.com/locuslab/deq-ddim)] \
23 Oct 2022

**Representation Learning with Diffusion Models** \
*Jeremias Traub* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.11058)] [[Github](https://github.com/jeremiastraub/diffusion)] \
20 Oct 2022

**Self-Guided Diffusion Models** \
*Vincent Tao Hu<sup>1</sup>, David W Zhang<sup>1</sup>, Yuki M. Asano, Gertjan J. Burghouts, Cees G. M. Snoek* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.06462)] \
12 Oct 2022

**GENIE: Higher-Order Denoising Diffusion Solvers** \
*Tim Dockhorn, Arash Vahdat, Karsten Kreis* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2210.05475)] [[Project](https://nv-tlabs.github.io/GENIE/) [[Github](https://github.com/nv-tlabs/GENIE)] \
11 Oct 2022

**f-DM: A Multi-stage Diffusion Model via Progressive Signal Transformation** \
*Jiatao Gu, Shuangfei Zhai, Yizhe Zhang, Miguel Angel Bautista, Josh Susskind* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.04955)] [[Project](http://jiataogu.me/fdm/)] \
10 Oct 2022

**On Distillation of Guided Diffusion Models** \
*Chenlin Meng, Ruiqi Gao, Diederik P. Kingma, Stefano Ermon, Jonathan Ho, Tim Salimans* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.03142)] \
6 Oct 2022

**Improving Sample Quality of Diffusion Model Using Self-Attention Guidance** \
*Susung Hong, Gyuseong Lee, Wooseok Jang, Seungryong Kim* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.00939)] [[Project](https://ku-cvlab.github.io/Self-Attention-Guidance/)] \
3 Oct 2022

**OCD: Learning to Overfit with Conditional Diffusion Models** \
*Shahar Shlomo Lutati, Lior Wolf* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.00471)] [[Github](https://github.com/ShaharLutatiPersonal/OCD)] \
2 Oct 2022

**Generated Faces in the Wild: Quantitative Comparison of Stable Diffusion, Midjourney and DALL-E 2** \
*Ali Borji* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.00586)] [[Github](https://github.com/aliborji/GFW)] \
2 Oct 2022

**Denoising MCMC for Accelerating Diffusion-Based Generative Models** \
*Beomsu Kim, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14593)] [[Github](https://github.com/1202kbs/DMCMC)] \
29 Sep 2022

**All are Worth Words: a ViT Backbone for Score-based Diffusion Models** \
*Fan Bao, Chongxuan Li, Yue Cao, Jun Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.12152)] \
25 Sep 2022


**Neural Wavelet-domain Diffusion for 3D Shape Generation** \
*Ka-Hei Hui, Ruihui Li, Jingyu Hu, Chi-Wing Fu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.08725)] \
19 Sep 2022

**Can segmentation models be trained with fully synthetically generated data?** \
*Virginia Fernandez, Walter Hugo Lopez Pinaya, Pedro Borges, Petru-Daniel Tudosiu, Mark S Graham, Tom Vercauteren, M Jorge Cardoso* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.08256)] \
17 Sep 2022

**Blurring Diffusion Models** \
*Emiel Hoogeboom, Tim Salimans* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.05557)] \
12 Sep 2022

**Soft Diffusion: Score Matching for General Corruptions** \
*Giannis Daras, Mauricio Delbracio, Hossein Talebi, Alexandros G. Dimakis, Peyman Milanfar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.05442)] \
12 Sep 2022

**Improved Masked Image Generation with Token-Critic** \
*José Lezama, Huiwen Chang, Lu Jiang, Irfan Essa* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.04439)] \
9 Sep 2022


**Let us Build Bridges: Understanding and Extending Diffusion Generative Models** \
*Xingchao Liu, Lemeng Wu, Mao Ye, Qiang Liu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.14699)] \
31 Aug 2022

**Frido: Feature Pyramid Diffusion for Complex Scene Image Synthesis** \
*Wan-Cyuan Fan, Yen-Chun Chen, DongDong Chen, Yu Cheng, Lu Yuan, Yu-Chiang Frank Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.13753)] \
29 Aug 2022

**Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise** \
*Arpit Bansal, Eitan Borgnia, Hong-Min Chu, Jie S. Li, Hamid Kazemi, Furong Huang, Micah Goldblum, Jonas Geiping, Tom Goldstein* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09392)] [[Github](https://github.com/arpitbansal297/Cold-Diffusion-Models)] \
19 Aug 2022

**Enhancing Diffusion-Based Image Synthesis with Robust Classifier Guidance** \
*Bahjat Kawar, Roy Ganz, Michael Elad* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.08664)] \
18 Aug 2022

**Your ViT is Secretly a Hybrid Discriminative-Generative Diffusion Model** \
*Xiulong Yang<sup>1</sup>, Sheng-Min Shih<sup>1</sup>, Yinlin Fu, Xiaoting Zhao, Shihao Ji* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.07791)] [[Github](https://github.com/sndnyang/Diffusion_ViT)] \
16 Aug 2022

**Applying Regularized Schrödinger-Bridge-Based Stochastic Process in Generative Modeling** \
*Ki-Ung Song* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.07131)] [[Github](https://github.com/KiUngSong/RSB)] \
15 Aug 2022

**Analog Bits: Generating Discrete Data using Diffusion Models with Self-Conditioning** \
*Ting Chen, Ruixiang Zhang, Geoffrey Hinton* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.04202)] \
8 Aug 2022


**Pyramidal Denoising Diffusion Probabilistic Models** \
*Dohoon Ryu, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.01864)] \
3 Aug 2022

**Progressive Deblurring of Diffusion Models for Coarse-to-Fine Image Synthesis** \
*Sangyun Lee, Hyungjin Chung, Jaehyeon Kim, Jong Chul Ye* \
arxiv 2022. [[Paper](https://arxiv.org/abs/2207.11192)] [[Github](https://github.com/sangyun884/blur-diffusion)] \
16 Jul 2022

**Improving Diffusion Model Efficiency Through Patching** \
*Troy Luhman, Eric Luhman* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.04316)] [[Github](https://github.com/ericl122333/PatchDiffusion-Pytorch)] \
9 Jul 2022

**Accelerating Score-based Generative Models with Preconditioned Diffusion Sampling** \
*Hengyuan Ma, Li Zhang, Xiatian Zhu, Jianfeng Feng* \
ECCV 2022. [[Paper](https://arxiv.org/abs/2207.02196)] \
5 Jul 2022

**SPI-GAN: Distilling Score-based Generative Models with Straight-Path Interpolations** \
*Jinsung Jeon, Noseong Park* \
arxiv 2022. [[Paper](https://arxiv.org/abs/2206.14464)] \
29 Jun 2022

**Entropy-driven Sampling and Training Scheme for Conditional Diffusion Generation** \
*Shengming Li, Guangcong Zheng, Hui Wang, Taiping Yao, Yang Chen, Shoudong Ding, Xi Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.11474)] \
23 Jun 2022

**Generative Modelling With Inverse Heat Dissipation** \
*Severi Rissanen, Markus Heinonen, Arno Solin* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.13397)] [[Project](https://aaltoml.github.io/generative-inverse-heat-dissipation/)] \
21 Jun 2022

**Diffusion models as plug-and-play priors** \
*Alexandros Graikos, Nikolay Malkin, Nebojsa Jojic, Dimitris Samaras* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2206.09012)] [[Github](https://github.com/alexgraikos/diffusion_priors)] \
17 June 2022

**A Flexible Diffusion Model** \
*Weitao Du, Tao Yang, He Zhang, Yuanqi Du* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.10365)] \
17 Jun 2022

**Lossy Compression with Gaussian Diffusion** \
*Lucas Theis, Tim Salimans, Matthew D. Hoffman, Fabian Mentzer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.08889)] \
17 Jun 2022

**Maximum Likelihood Training for Score-Based Diffusion ODEs by High-Order Denoising Score Matching** \
*Cheng Lu, Kaiwen Zheng, Fan Bao, Jianfei Chen, Chongxuan Li, Jun Zhu* \
ICML 2022. [[Paper](https://arxiv.org/abs/2206.08265)] [[Github](https://github.com/LuChengTHU/mle_score_ode)] \
16 Jun 2022

**Estimating the Optimal Covariance with Imperfect Mean in Diffusion Probabilistic Models** \
*Fan Bao, Chongxuan Li, Jiacheng Sun, Jun Zhu, Bo Zhang* \
ICML 2022. [[Paper](https://arxiv.org/abs/2206.07309)] [[Github](https://github.com/baofff/Extended-Analytic-DPM)] \
15 Jun 2022

**Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation** \
*Ye Zhu, Yu Wu, Kyle Olszewski, Jian Ren, Sergey Tulyakov, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07771)] [[Github](https://github.com/L-YeZhu/CDCD)] \
15 Jun 2022

**gDDIM: Generalized denoising diffusion implicit models** \
*Qinsheng Zhang, Molei Tao, Yongxin Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.05564)] [[Github](https://github.com/qsh-zh/gDDIM)] \
11 Jun 2022

**How Much is Enough? A Study on Diffusion Times in Score-based Generative Models** \
*Giulio Franzese, Simone Rossi, Lixuan Yang, Alessandro Finamore, Dario Rossi, Maurizio Filippone, Pietro Michiardi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.05173)] \
10 Jun 2022

**Image Generation with Multimodal Priors using Denoising Diffusion Probabilistic Models** \
*Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.05039)] \
10 Jun 2022

**Accelerating Score-based Generative Models for High-Resolution Image Synthesis** \
*Hengyuan Ma, Li Zhang, Xiatian Zhu, Jingfeng Zhang, Jianfeng Feng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.04029)] \
8 Jun 2022

**Diffusion-GAN: Training GANs with Diffusion** \
*Zhendong Wang, Huangjie Zheng, Pengcheng He, Weizhu Chen, Mingyuan Zhou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.02262)] \
5 Jun 2022

**DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps** \
*Cheng Lu, Yuhao Zhou, Fan Bao, Jianfei Chen, Chongxuan Li, Jun Zhu* \
NeurrIPS 2022. [[Paper](https://arxiv.org/abs/2206.00927)] [[Github](https://github.com/LuChengTHU/dpm-solver)] \
2 Jun 2022

**Elucidating the Design Space of Diffusion-Based Generative Models** \
*Tero Karras, Miika Aittala, Timo Aila, Samuli Laine* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2206.00364)] \
1 Jun 2022

**On Analyzing Generative and Denoising Capabilities of Diffusion-based Deep Generative Models** \
*Kamil Deja, Anna Kuzina, Tomasz Trzciński, Jakub M. Tomczak* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2206.00070)] \
31 May 2022

**Few-Shot Diffusion Models** \
*Giorgio Giannone, Didrik Nielsen, Ole Winther* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.15463)] \
30 May 2022

**A Continuous Time Framework for Discrete Denoising Models** \
*Andrew Campbell, Joe Benton, Valentin De Bortoli, Tom Rainforth, George Deligiannidis, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.14987)] \
30 May 2022

**Maximum Likelihood Training of Implicit Nonlinear Diffusion Models** \
*Dongjun Kim, Byeonghu Na, Se Jung Kwon, Dongsoo Lee, Wanmo Kang, Il-Chul Moon* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2205.13699)] \
27 May 2022

**Accelerating Diffusion Models via Early Stop of the Diffusion Process** \
*Zhaoyang Lyu, Xudong XU, Ceyuan Yang, Dahua Lin, Bo Dai* \
ICML 2022. [[Paper](https://arxiv.org/abs/2205.12524)] \
25 May 2022

**On Conditioning the Input Noise for Controlled Image Generation with Diffusion Models** \
*Vedant Singh<sup>1</sup>, Surgan Jandial<sup>1</sup>, Ayush Chopra, Siddharth Ramesh, Balaji Krishnamurthy, Vineeth N. Balasubramanian* \
CVPR Workshop 2022. [[Paper](https://arxiv.org/abs/2205.03859)] \
8 May 2022

**Subspace Diffusion Generative Models** \
*Bowen Jing, Gabriele Corso, Renato Berlinghieri, Tommi Jaakkola* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.01490)] [[Github](https://github.com/bjing2016/subspace-diffusion)] \
3 May 2022

**Fast Sampling of Diffusion Models with Exponential Integrator** \
*Qinsheng Zhang, Yongxin Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.13902)] \
29 Apr 2022

**Retrieval-Augmented Diffusion Models** \
*Andreas Blattmann<sup>1</sup>, Robin Rombach<sup>1</sup>, Kaan Oktay, Björn Ommer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.11824)] \
25 Apr 2022

**Perception Prioritized Training of Diffusion Models** \
*Jooyoung Choi, Jungbeom Lee, Chaehun Shin, Sungwon Kim, Hyunwoo Kim, Sungroh Yoon* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2204.00227)] [[Github](https://github.com/jychoi118/P2-weighting)] \
1 Apr 2022

**Generating High Fidelity Data from Low-density Regions using Diffusion Models** \
*Vikash Sehwag, Caner Hazirbas, Albert Gordo, Firat Ozgenel, Cristian Canton Ferrer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.17260)] \
31 Mar 2022

**Diffusion Models for Counterfactual Explanations** \
*Guillaume Jeanneret, Loïc Simon, Frédéric Jurie* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.15636)] \
29 Mar 2022

**Denoising Likelihood Score Matching for Conditional Score-based Data Generation** \
*Chen-Hao Chao, Wei-Fang Sun, Bo-Wun Cheng, Yi-Chen Lo, Chia-Che Chang, Yu-Lun Liu, Yu-Lin Chang, Chia-Ping Chen, Chun-Yi Lee* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2203.14206)] \
27 Mar 2022

**Dynamic Dual-Output Diffusion Models** \
*Yaniv Benny, Lior Wolf* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2203.04304)] \
8 Mar 2022

**Conditional Simulation Using Diffusion Schrödinger Bridges** \
*Yuyang Shi, Valentin De Bortoli, George Deligiannidis, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.13460)] \
27 Feb 2022

**Diffusion Causal Models for Counterfactual Estimation** \
*Pedro Sanchez, Sotirios A. Tsaftaris* \
PMLR 2022. [[Paper](https://arxiv.org/abs/2202.10166)] \
21 Feb 2022

**Pseudo Numerical Methods for Diffusion Models on Manifolds** \
*Luping Liu, Yi Ren, Zhijie Lin, Zhou Zhao* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2202.09778)] [[Github](https://github.com/luping-liu/PNDM)] \
20 Feb 2022

**Truncated Diffusion Probabilistic Models** \
*Huangjie Zheng, Pengcheng He, Weizhu Chen, Mingyuan Zhou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.09671)] \
19 Feb 2022

**Understanding DDPM Latent Codes Through Optimal Transport** \
*Valentin Khrulkov, Ivan Oseledets* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.07477)] \
14 Feb 2022

**Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality** \
*Daniel Watson, William Chan, Jonathan Ho, Mohammad Norouzi* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2202.05830)] \
11 Feb 2022


**Diffusion bridges vector quantized Variational AutoEncoders** \
*Max Cohen, Guillaume Quispe, Sylvain Le Corff, Charles Ollion, Eric Moulines* \
ICML 2022. [[Paper](https://arxiv.org/abs/2202.04895)] \
10 Feb 2022

**Progressive Distillation for Fast Sampling of Diffusion Models** \
*Tim Salimans, Jonathan Ho* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2202.00512)] \
1 Feb 2022

**Analytic-DPM: an Analytic Estimate of the Optimal Reverse Variance in Diffusion Probabilistic Models** \
*Fan Bao, Chongxuan Li, Jun Zhu, Bo Zhang* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2201.06503)] \
17 Jan 2022

**DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents** \
*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.00308)] [[Github](https://github.com/kpandey008/DiffuseVAE)] \
2 Jan 2022

**Itô-Taylor Sampling Scheme for Denoising Diffusion Probabilistic Models using Ideal Derivatives** \
*Hideyuki Tachibana, Mocho Go, Muneyoshi Inahara, Yotaro Katayama, Yotaro Watanabe* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.13339)] \
26 Dec 2021

**GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models** \
*Alex Nichol<sup>1</sup>, Prafulla Dhariwal<sup>1</sup>, Aditya Ramesh<sup>1</sup>, Pranav Shyam, Pamela Mishkin, Bob McGrew, Ilya Sutskever, Mark Chen* \
ICML 2021. [[Paper](https://arxiv.org/abs/2112.10741)] [[Github](https://github.com/openai/glide-text2im)] \
20 Dec 2021

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Dominik Lorenz, Patrick Esser, Björn Ommer* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.10752)] [[Github](https://github.com/CompVis/latent-diffusion)] \
20 Dec 2021

**Heavy-tailed denoising score matching** \
*Jacob Deasy, Nikola Simidjievski, Pietro Liò* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.09788)] \
17 Dec 2021

**High Fidelity Visualization of What Your Self-Supervised Representation Knows About** \
*Florian Bordes, Randall Balestriero, Pascal Vincent* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.09164)] \
16 Dec 2021

**Tackling the Generative Learning Trilemma with Denoising Diffusion GANs** \
*Zhisheng Xiao, Karsten Kreis, Arash Vahdat* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.07804)] [[Project](https://nvlabs.github.io/denoising-diffusion-gan)] \
15 Dec 2021

**Score-Based Generative Modeling with Critically-Damped Langevin Diffusion** \
*Tim Dockhorn, Arash Vahdat, Karsten Kreis* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2112.07068)] [[Project](https://nv-tlabs.github.io/CLD-SGM/)] \
14 Dec 2021

**More Control for Free! Image Synthesis with Semantic Diffusion Guidance** \
*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05744)] \
10 Dec 2021

**Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation** \
*Minghui Hu, Yujie Wang, Tat-Jen Cham, Jianfei Yang, P.N.Suganthan* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.01799)] \
3 Dec 2021

**Diffusion Autoencoders: Toward a Meaningful and Decodable Representation** \
*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2111.15640)] [[Project](https://diff-ae.github.io/)] [[Github](https://github.com/phizaz/diffae)] \
30 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] \
26 Nov 2021

**Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes** \
*Sam Bond-Taylor<sup>1</sup>, Peter Hessey<sup>1</sup>, Hiroshi Sasaki, Toby P. Breckon, Chris G. Willcocks* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.12701)] [[Github](https://github.com/samb-t/unleashing-transformers)] \
24 Nov 2021

**Diffusion Normalizing Flow** \
*Qinsheng Zhang, Yongxin Chen* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2110.07579)] [[Github](https://github.com/qsh-zh/DiffFlow)] \
14 Oct 2021

**Denoising Diffusion Gamma Models** \
*Eliya Nachmani<sup>1</sup>, Robin San Roman<sup>1</sup>, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.05948)] \
10 Oct 2021

**Score-based Generative Neural Networks for Large-Scale Optimal Transport** \
*Max Daniels, Tyler Maunu, Paul Hand* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.03237)] \
7 Oct 2021

**Score-Based Generative Classifiers** \
*Roland S. Zimmermann, Lukas Schott, Yang Song, Benjamin A. Dunn, David A. Klindt* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.00473)] \
1 Oct 2021

**Classifier-Free Diffusion Guidance** \
*Jonathan Ho, Tim Salimans* \
NeurIPS Workshop 2021. [[Paper](https://arxiv.org/abs/2207.12598)] \
28 Sep 2021


**Bilateral Denoising Diffusion Models** \
*Max W. Y. Lam, Jun Wang, Rongjie Huang, Dan Su, Dong Yu* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2108.11514)] [[Project](https://bilateral-denoising-diffusion-model.github.io)] \
26 Aug 2021

**ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis** \
*Patrick Esser<sup>1</sup>, Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Björn Ommer* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2108.08827)] [[Project](https://compvis.github.io/imagebart/)] \
19 Aug 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021

**SDEdit: Image Synthesis and Editing with Stochastic Differential Equations** \
*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* \
ICLR  2021. [[Paper](https://arxiv.org/abs/2108.01073)] [[Project](https://sde-image-editing.github.io/)] [[Github](https://github.com/ermongroup/SDEdit)] \
2 Aug 2021

**Structured Denoising Diffusion Models in Discrete State-Spaces** \
*Jacob Austin<sup>1</sup>, Daniel D. Johnson<sup>1</sup>, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2107.03006)] \
7 Jul 2021 

**Variational Diffusion Models** \
*Diederik P. Kingma<sup>1</sup>, Tim Salimans<sup>1</sup>, Ben Poole, Jonathan Ho* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2107.00630)] [[Github]](https://github.com/google-research/vdm) \
1 Jul 2021 

**Diffusion Priors In Variational Autoencoders** \
*Antoine Wehenkel<sup>1</sup>, Gilles Louppe<sup>1</sup>* \
ICML Workshop 2021. [[Paper](https://arxiv.org/abs/2106.15671)] \
29 Jun 2021

**Deep Generative Learning via Schrödinger Bridge** \
*Gefei Wang, Yuling Jiao, Qian Xu, Yang Wang, Can Yang* \
ICML 2021. [[Paper](https://arxiv.org/abs/2106.10410)] \
19 Jun 2021

**Non Gaussian Denoising Diffusion Models** \
*Eliya Nachmani<sup>1</sup>, Robin San Roman<sup>1</sup>, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.07582)] [[Project](https://enk100.github.io/Non-Gaussian-Denoising-Diffusion-Models/)] \
14 Jun 2021 

**D2C: Diffusion-Denoising Models for Few-shot Conditional Generation** \
*Abhishek Sinha<sup>1</sup>, Jiaming Song<sup>1</sup>, Chenlin Meng, Stefano Ermon* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2106.06819)] [[Project](https://d2c-model.github.io/)] [[Github](https://github.com/d2c-model/d2c-model.github.io)] \
12 Jun 2021

**Score-based Generative Modeling in Latent Space** \
*Arash Vahdat<sup>1</sup>, Karsten Kreis<sup>1</sup>, Jan Kautz* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.05931)] \
10 Jun 2021

**Learning to Efficiently Sample from Diffusion Probabilistic Models** \
*Daniel Watson, Jonathan Ho, Mohammad Norouzi, William Chan* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.03802)] \
7 Jun 2021 

**A Variational Perspective on Diffusion-Based Generative Models and Score Matching** \
*Chin-Wei Huang, Jae Hyun Lim, Aaron Courville* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2106.02808)] [[Github](https://github.com/CW-Huang/sdeflow-light)] \
5 Jun 2021 

**Soft Truncation: A Universal Training Technique of Score-based Diffusion Model for High Precision Score Estimation** \
*Dongjun Kim, Seungjae Shin, Kyungwoo Song, Wanmo Kang, Il-Chul Moon* \
ICML 2022. [[Paper](https://arxiv.org/abs/2106.05527)] \
10 Jun 2021

**Diffusion Schrödinger Bridge with Applications to Score-Based Generative Modeling** \
*Valentin De Bortoli, James Thornton, Jeremy Heng, Arnaud Doucet* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.01357)] [[Project](https://jtt94.github.io/papers/schrodinger_bridge)] [[Github](https://github.com/JTT94/diffusion_schrodinger_bridge)] \
1 Jun 2021

**On Fast Sampling of Diffusion Probabilistic Models** \
*Zhifeng Kong, Wei Ping* \
ICML Workshop 2021. [[Paper](https://arxiv.org/abs/2106.00132)] [[Github](https://github.com/FengNiMa/FastDPM_pytorch)] \
31 May 2021 

**Cascaded Diffusion Models for High Fidelity Image Generation** \
*Jonathan Ho<sup>1</sup>, Chitwan Saharia<sup>1</sup>, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans* \
JMLR 2021. [[Paper](https://arxiv.org/abs/2106.15282)] [[Project](https://cascaded-diffusion.github.io/)] \
30 May 2021 

**Gotta Go Fast When Generating Data with Score-Based Models** \
*Alexia Jolicoeur-Martineau, Ke Li, Rémi Piché-Taillefer, Tal Kachman, Ioannis Mitliagkas* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2105.14080)] [[Github](https://github.com/AlexiaJM/score_sde_fast_sampling)] \
28 May 2021

**Diffusion Models Beat GANs on Image Synthesis** \
*Prafulla Dhariwal<sup>1</sup>, Alex Nichol<sup>1</sup>* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2105.05233)] [[Github](https://github.com/openai/guided-diffusion)] \
11 May 2021 

**Image Super-Resolution via Iterative Refinement** \
*Chitwan Saharia, Jonathan Ho, William Chan, Tim Salimans, David J. Fleet, Mohammad Norouzi* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.07636)] [[Project](https://iterative-refinement.github.io/)] [[Github](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement)] \
15 Apr 2021 

**Noise Estimation for Generative Diffusion Models** \
*Robin San-Roman<sup>1</sup>, Eliya Nachmani<sup>1</sup>, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.02600)] \
6 Apr 2021 

**Improved Denoising Diffusion Probabilistic Models** \
*Alex Nichol<sup>1</sup>, Prafulla Dhariwal<sup>1</sup>* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2102.09672)] [[Github](https://github.com/openai/improved-diffusion)] \
18 Feb 2021 

**Maximum Likelihood Training of Score-Based Diffusion Models** \
*Yang Song<sup>1</sup>, Conor Durkan<sup>1</sup>, Iain Murray, Stefano Ermon* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2101.09258)] \
22 Jan 2021 

**Knowledge Distillation in Iterative Generative Models for Improved Sampling Speed** \
*Eric Luhman<sup>1</sup>, Troy Luhman<sup>1</sup>* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2101.02388)] [[Github](https://github.com/tcl9876/Denoising_Student)] \
7 Jan 2021

**Learning Energy-Based Models by Diffusion Recovery Likelihood** \
*Ruiqi Gao, Yang Song, Ben Poole, Ying Nian Wu, Diederik P. Kingma* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2012.08125)] [[Github](https://github.com/ruiqigao/recovery_likelihood)] \
15 Dec 2020 

**Score-Based Generative Modeling through Stochastic Differential Equations** \
*Yang Song, Jascha Sohl-Dickstein, Diederik P. Kingma, Abhishek Kumar, Stefano Ermon, Ben Poole* \
ICLR 2021 (Oral). [[Paper](https://arxiv.org/abs/2011.13456)] [[Github](https://github.com/yang-song/score_sde)] \
26 Nov 2020 

**Variational (Gradient) Estimate of the Score Function in Energy-based Latent Variable Models** \
*Fan Bao, Kun Xu, Chongxuan Li, Lanqing Hong, Jun Zhu, Bo Zhang* \
ICML 2021. [[Paper](https://arxiv.org/abs/2010.08258)] \
16 Oct 2020

**Denoising Diffusion Implicit Models**  \
*Jiaming Song, Chenlin Meng, Stefano Ermon* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2010.02502)] [[Github](https://github.com/ermongroup/ddim)] \
6 Oct 2020

**Adversarial score matching and improved sampling for image generation** \
*Alexia Jolicoeur-Martineau<sup>1</sup>, Rémi Piché-Taillefer<sup>1</sup>, Rémi Tachet des Combes, Ioannis Mitliagkas* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2009.05475)] [[Github](https://github.com/AlexiaJM/AdversarialConsistentScoreMatching)] \
11 Sep 2020

**Denoising Diffusion Probabilistic Models** \
*Jonathan Ho, Ajay Jain, Pieter Abbeel* \
NeurIPS 2020. [[Paper](https://arxiv.org/abs/2006.11239)] [[Github](https://github.com/hojonathanho/diffusion)] [[Github2](https://github.com/pesser/pytorch_diffusion)] \
19 Jun 2020 

**Improved Techniques for Training Score-Based Generative Models** \
*Yang Song, Stefano Ermon* \
NeurIPS 2020. [[Paper](https://arxiv.org/abs/2006.09011)] [[Github](https://github.com/ermongroup/ncsnv2)] \
16 Jun 2020 

**Generative Modeling by Estimating Gradients of the Data Distribution** \
*Yang Song, Stefano Ermon* \
NeurIPS 2019. [[Paper](https://arxiv.org/abs/1907.05600)] [[Project](https://yang-song.github.io/blog/2021/score/)] [[Github](https://github.com/ermongroup/ncsn)] \
12 Jul 2019 

**Neural Stochastic Differential Equations: Deep Latent Gaussian Models in the Diffusion Limit** \
*Belinda Tzen, Maxim Raginsky* \
arXiv 2019. [[Paper](https://arxiv.org/abs/1905.09883)] \
23 May 2019 

**Deep Unsupervised Learning using Nonequilibrium Thermodynamics** \
*Jascha Sohl-Dickstein, Eric A. Weiss, Niru Maheswaranathan, Surya Ganguli* \
ICML 2015. [[Paper](https://arxiv.org/abs/1503.03585)] [[Github](https://github.com/Sohl-Dickstein/Diffusion-Probabilistic-Models)] \
2 Mar 2015


### Segmentation

**Multi-Class Segmentation from Aerial Views using Recursive Noise Diffusion** \
*Benedikt Kolbeinsson, Krystian Mikolajczyk* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00787)] \
1 Dec 2022

**Peekaboo: Text to Image Diffusion Models are Zero-Shot Segmentors** \
*Ryan Burgert, Kanchana Ranasinghe, Xiang Li, Michael S. Ryoo* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13224)] \
23 Nov 2022

**Anatomically constrained CT image translation for heterogeneous blood vessel segmentation** \
*Giammarco La Barbera, Haithem Boussaid, Francesco Maso, Sabine Sarnacki, Laurence Rouet, Pietro Gori, Isabelle Bloch* \
BMVC 2022. [[Paper](https://arxiv.org/abs/2210.01713)] \
4 Oct 2022

**Diffusion Adversarial Representation Learning for Self-supervised Vessel Segmentation** \
*Boah Kim<sup>1</sup>, Yujin Oh<sup>1</sup>, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14566)] \
29 Sep 2022

**Can segmentation models be trained with fully synthetically generated data?** \
*Virginia Fernandez, Walter Hugo Lopez Pinaya, Pedro Borges, Petru-Daniel Tudosiu, Mark S Graham, Tom Vercauteren, M Jorge Cardoso* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.08256)] \
17 Sep 2022

**Let us Build Bridges: Understanding and Extending Diffusion Generative Models** \
*Xingchao Liu, Lemeng Wu, Mao Ye, Qiang Liu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.14699)] \
31 Aug 2022


**Semantic Image Synthesis via Diffusion Models** \
*Weilun Wang, Jianmin Bao, Wengang Zhou, Dongdong Chen, Dong Chen, Lu Yuan, Houqiang Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.00050)] \
30 Jun 2022


**Remote Sensing Change Detection (Segmentation) using Denoising Diffusion Probabilistic Models** \
*Wele Gedara Chaminda Bandara, Nithin Gopalakrishnan Nair, Vishal M. Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.11892)] [[Github](https://github.com/wgcban/ddpm-cd)] \
23 Jun 2022

**Diffusion models as plug-and-play priors** \
*Alexandros Graikos, Nikolay Malkin, Nebojsa Jojic, Dimitris Samaras* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.09012)] \
17 Jun 2022

**Decoder Denoising Pretraining for Semantic Segmentation** \
*Emmanuel Brempong Asiedu, Simon Kornblith, Ting Chen, Niki Parmar, Matthias Minderer, Mohammad Norouzi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.11423)] \
23 May 2022

**Diffusion Models for Implicit Image Segmentation Ensembles** \
*Julia Wolleb<sup>1</sup>, Robin Sandkühler<sup>1</sup>, Florentin Bieder, Philippe Valmaggia, Philippe C. Cattin* \
MIDL 2021. [[Paper](https://arxiv.org/abs/2112.03145)] \
6 Dec 2021

**Label-Efficient Semantic Segmentation with Diffusion Models** \
*Dmitry Baranchuk, Ivan Rubachev, Andrey Voynov, Valentin Khrulkov, Artem Babenko* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2112.03126)] [[Github](https://github.com/yandex-research/ddpm-segmentation)] \
6 Dec 2021

**SegDiff: Image Segmentation with Diffusion Probabilistic Models** \
*Tomer Amit, Eliya Nachmani, Tal Shaharbany, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.00390)] \
1 Dec 2021


### Image-to-Image Translation

**DiffGAR: Model-Agnostic Restoration from Generative Artifacts Using Image-to-Image Diffusion Models** \
*Yueqin Yin, Lianghua Huang, Yu Liu, Kaiqi Huang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.08573)] 
16 Oct 2022

**Unifying Diffusion Models' Latent Space, with Applications to CycleDiffusion and Guidance** \
*Chen Henry Wu, Fernando De la Torre* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05559)] [[Github-1](https://github.com/ChenWu98/cycle-diffusion)] [[Github-2](https://github.com/ChenWu98/unified-generative-zoo)] \
11 Oct 2022


**Anatomically constrained CT image translation for heterogeneous blood vessel segmentation** \
*Giammarco La Barbera, Haithem Boussaid, Francesco Maso, Sabine Sarnacki, Laurence Rouet, Pietro Gori, Isabelle Bloch* \
BMVC 2022. [[Paper](https://arxiv.org/abs/2210.01713)] \
4 Oct 2022


**Diffusion-based Image Translation using Disentangled Style and Content Representation** \
*Gihyun Kwon, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15264)] \
30 Sep 2022


**MIDMs: Matching Interleaved Diffusion Models for Exemplar-based Image Translation** \
*Junyoung Seo<sup>1</sup>, Gyuseong Lee<sup>1</sup>, Seokju Cho, Jiyoung Lee, Seungryong Kim* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.11047)] \
22 Sep 2022


**T2V-DDPM: Thermal to Visible Face Translation using Denoising Diffusion Probabilistic Models** \
*Nithin Gopalakrishnan Nair, Vishal M. Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.08814)] \
19 Sep 2022

**Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models** \
*Ozan Özdenizci, Robert Legenstein* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.14626)] \
29 Jul 2022

**Non-Uniform Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.09786)] \
20 Jul 2022

**Unsupervised Medical Image Translation with Adversarial Diffusion Models** \
*Muzaffer Özbey, Salman UH Dar, Hasan A Bedel, Onat Dalmaz, Şaban Özturk, Alper Güngör, Tolga Çukur* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.08208)] \
17 Jul 2022

**EGSDE: Unpaired Image-to-Image Translation via Energy-Guided Stochastic Differential Equations** \
*Min Zhao, Fan Bao, Chongxuan Li, Jun Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.06635)] \
14 Jul 2022

**Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation** \
*Ye Zhu, Yu Wu, Kyle Olszewski, Jian Ren, Sergey Tulyakov, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07771)] [[Github](https://github.com/L-YeZhu/CDCD)] \
15 Jun 2022

**SAR Despeckling using a Denoising Diffusion Probabilistic Model** \
*Malsha V. Perera, Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M. Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.04514)] \
9 Jun 2022

**Pretraining is All You Need for Image-to-Image Translation** \
*Tengfei Wang, Ting Zhang, Bo Zhang, Hao Ouyang, Dong Chen, Qifeng Chen, Fang Wen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.12952)] [[Project](https://tengfei-wang.github.io/PITI/index.html)] [[Github](https://github.com/PITI-Synthesis/PITI)] \
25 May 2022

**VQBB: Image-to-image Translation with Vector Quantized Brownian Bridge** \
*Bo Li, Kaitao Xue, Bin Liu, Yu-Kun Lai* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.07680)] \
16 May 2022

**The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models** \
*Julia Wolleb<sup>1</sup>, Robin Sandkühler<sup>1</sup>, Florentin Bieder, Philippe C. Cattin* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.02641)] \
6 Apr 2022

**Dual Diffusion Implicit Bridges for Image-to-Image Translation** \
*Xuan Su, Jiaming Song, Chenlin Meng, Stefano Ermon* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.08382)] \
16 Mar 2022

**Denoising Diffusion Restoration Models** \
*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2201.11793)] \
27 Jan 2022

**DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models** \
*Boah Kim, Inhwa Han, Jong Chul Ye* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05149)] \
9 Dec 2021

**Diffusion Autoencoders: Toward a Meaningful and Decodable Representation** \
*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.15640)] [[Project](https://diff-ae.github.io/)] \
30 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] \
26 Nov 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021

**UNIT-DDPM: UNpaired Image Translation with Denoising Diffusion Probabilistic Models**  \
*Hiroshi Sasaki, Chris G. Willcocks, Toby P. Breckon* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.05358)] \
12 Apr 2021

### Super Resolution


**Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model** \
*Yinhuai Wang<sup>1</sup>, Jiwen Yu<sup>1</sup>, Jian Zhang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00490)] [[Github](https://github.com/wyhuai/DDNM)] \
1 Dec 2022


**FREDSR: Fourier Residual Efficient Diffusive GAN for Single Image Super Resolution** \
*Kyoungwan Woo<sup>1</sup>, Achyuta Rajaram<sup>1</sup>* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16678)] \
30 Nov 2022

**CHIMLE: Conditional Hierarchical IMLE for Multimodal Conditional Image Synthesis** \
*Shichong Peng, Alireza Moazeni, Ke Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14286)] \
25 Nov 2022

**Superresolution Reconstruction of Single Image for Latent features** \
*Xin Wang, Jing-Ke Yan, Jing-Ye Cai, Jian-Hua Deng, Qin Qin, Qin Wang, Heng Xiao, Yao Cheng, Peng-Fei Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12845)] \
16 Nov 2022

**Diffusion Model Based Posterior Sampling for Noisy Linear Inverse Problems** \
*Xiangming Meng, Yoshiyuki Kabashima* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12343)] [[Github](https://github.com/mengxiangming/dmps)] \
20 Nov 2022

**Conffusion: Confidence Intervals for Diffusion Models** \
*Eliahu Horwitz, Yedid Hoshen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09795)] \
17 Nov 2022


**From Denoising Diffusions to Denoising Markov Models** \
*Joe Benton, Yuyang Shi, Valentin De Bortoli, George Deligiannidis, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.03595)] [[Github](https://github.com/yuyang-shi/generalized-diffusion)] \
7 Nov 2022

**Diffusion Posterior Sampling for General Noisy Inverse Problems** \
*Hyungjin Chung<sup>1</sup>, Jeongsol Kim<sup>1</sup>, Michael T. Mccann, Marc L. Klasky, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14687)] [[Github](https://github.com/DPS2022/diffusion-posterior-sampling)] \
29 Sep 2022

**Face Super-Resolution Using Stochastic Differential Equations** \
*Marcelo dos Santos<sup>1</sup>, Rayson Laroca<sup>1</sup>, Rafael O. Ribeiro, João Neves, Hugo Proença, David Menotti* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.12064)] [[Github](https://github.com/marcelowds/sr-sde)] \
24 Sep 2022

**Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise** \
*Arpit Bansal, Eitan Borgnia, Hong-Min Chu, Jie S. Li, Hamid Kazemi, Furong Huang, Micah Goldblum, Jonas Geiping, Tom Goldstein* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09392)] [[Github](https://github.com/arpitbansal297/Cold-Diffusion-Models)] \
19 Aug 2022

**Non-Uniform Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.09786)] \
20 Jul 2022

**Denoising Diffusion Restoration Models** \
*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song* \
ICLR 2022 Workshop (Oral). [[Paper](https://arxiv.org/abs/2201.11793)] \
27 Jan 2022

**DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents** \
*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.00308)] [[Github](https://github.com/kpandey008/DiffuseVAE)] \
2 Jan 2022

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Dominik Lorenz, Patrick Esser, Björn Ommer* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2112.10752)] [[Github](https://github.com/CompVis/latent-diffusion)] \
20 Dec 2021

**Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction** \
*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2112.05146)] \
9 Dec 2021

**Deblurring via Stochastic Refinement** \
*Jay Whang, Mauricio Delbracio, Hossein Talebi, Chitwan Saharia, Alexandros G. Dimakis, Peyman Milanfar* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2112.02475)]  \
5 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] \
26 Nov 2021

**S3RP: Self-Supervised Super-Resolution and Prediction for Advection-Diffusion Process** \
*Chulin Wang, Kyongmin Yeo, Xiao Jin, Andres Codas, Levente J. Klein, Bruce Elmegreen* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2111.04639)] \
8 Nov 2021

**Autoregressive Diffusion Models** \
*Emiel Hoogeboom, Alexey A. Gritsenko, Jasmijn Bastings, Ben Poole, Rianne van den Berg, Tim Salimans* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2110.02037)] \
5 Oct 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021 

**Cascaded Diffusion Models for High Fidelity Image Generation**  \
*Jonathan Ho<sup>1</sup>, Chitwan Saharia<sup>1</sup>, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.15282)] [[Project](https://cascaded-diffusion.github.io/)] \
30 May 2021

**SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models** \
*Haoying Li, Yifan Yang, Meng Chang, Huajun Feng, Zhihai Xu, Qi Li, Yueting Chen* \
ACM 2022. [[Paper](https://arxiv.org/abs/2104.14951)] \
30 Apr 2021

**Image Super-Resolution via Iterative Refinement**  \
*Chitwan Saharia, Jonathan Ho, William Chan, Tim Salimans, David J. Fleet, Mohammad Norouzi* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.07636)] [[Project](https://iterative-refinement.github.io/)] [[Github](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement)] \
15 Apr 2021

### Image Inpainting

**Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model** \
*Yinhuai Wang<sup>1</sup>, Jiwen Yu<sup>1</sup>, Jian Zhang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00490)] [[Github](https://github.com/wyhuai/DDNM)] \
1 Dec 2022

**A Structure-Guided Diffusion Model for Large-Hole Diverse Image Completion** \
*Daichi Horita, Jiaolong Yang, Dong Chen, Yuki Koyama, Kiyoharu Aizawa* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10437)] \
18 Nov 2022

**Conffusion: Confidence Intervals for Diffusion Models** \
*Eliahu Horwitz, Yedid Hoshen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09795)] \
17 Nov 2022

**From Denoising Diffusions to Denoising Markov Models** \
*Joe Benton, Yuyang Shi, Valentin De Bortoli, George Deligiannidis, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.03595)] [[Github](https://github.com/yuyang-shi/generalized-diffusion)] \
7 Nov 2022

**Intelligent Painter: Picture Composition With Resampling Diffusion Model** \
*Wing-Fung Ku, Wan-Chi Siu, Xi Cheng, H. Anthony Chan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.17106)] \
31 Oct 2022

**Delving Globally into Texture and Structure for Image Inpainting** \
*Haipeng Liu, Yang Wang, Meng Wang, Yong Rui* \
ACM 2022. [[Paper](https://arxiv.org/abs/2209.08217)] [[Github](https://github.com/htyjers/DGTS-Inpainting)] \
17 Sep 2022

**Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise** \
*Arpit Bansal, Eitan Borgnia, Hong-Min Chu, Jie S. Li, Hamid Kazemi, Furong Huang, Micah Goldblum, Jonas Geiping, Tom Goldstein* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09392)] [[Github](https://github.com/arpitbansal297/Cold-Diffusion-Models)] \
19 Aug 2022

**Non-Uniform Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.09786)] \
20 Jul 2022

**Improving Diffusion Models for Inverse Problems using Manifold Constraints** \
*Hyungjin Chung<sup>1</sup>, Byeongsu Sim<sup>1</sup>, Dohoon Ryu, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00941)] \
2 Jun 2022

**Denoising Diffusion Restoration Models** \
*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song* \
ICLR 2022 Workshop (Oral). [[Paper](https://arxiv.org/abs/2201.11793)] \
27 Jan 2022

**RePaint: Inpainting using Denoising Diffusion Probabilistic Models** \
*Andreas Lugmayr, Martin Danelljan, Andres Romero, Fisher Yu, Radu Timofte, Luc Van Gool* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2201.09865)] [[Github](https://github.com/andreas128/RePaint)] \
24 Jan 2022

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Dominik Lorenz, Patrick Esser, Björn Ommer* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2112.10752)] [[Github](https://github.com/CompVis/latent-diffusion)] \
20 Dec 2021

**Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction** \
*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2112.05146)] \
9 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] [[Github](https://github.com/GBATZOLIS/conditional_score_diffusion)] \
26 Nov 2021

**Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes** \
*Sam Bond-Taylor<sup>1</sup>, Peter Hessey<sup>1</sup>, Hiroshi Sasaki, Toby P. Breckon, Chris G. Willcocks* \
ECCV 2022. [[Paper](https://arxiv.org/abs/2111.12701)] [[Github](https://github.com/samb-t/unleashing-transformers)] \
24 Nov 2021

### Image Editing


**SinDDM: A Single Image Denoising Diffusion Model** \
*Vladimir Kulikov, Shahar Yadin, Matan Kleiner, Tomer Michaeli* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16582)] [[Project](https://matankleiner.github.io/sinddm/)] \
29 Nov 2022



**Shape-Guided Diffusion with Inside-Outside Attention** \
*Dong Huk Park<sup>1</sup>, Grace Luo<sup>1</sup>, Clayton Toste, Samaneh Azadi, Xihui Liu, Maka Karalashvili, Anna Rohrbach, Trevor Darrell* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00210)] [[Project](https://shape-guided-diffusion.github.io/)] \
1 Dec 2022


**3DDesigner: Towards Photorealistic 3D Object Generation and Editing with Text-guided Diffusion Models** \
*Gang Li, Heliang Zheng, Chaoyue Wang, Chang Li, Changwen Zheng, Dacheng Tao* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14108)] \
25 Nov 2022


**SpaText: Spatio-Textual Representation for Controllable Image Generation** \
*Omri Avrahami, Thomas Hayes, Oran Gafni, Sonal Gupta, Yaniv Taigman, Devi Parikh, Dani Lischinski, Ohad Fried, Xi Yin* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14305)] [[Project](https://omriavrahami.com/spatext/)] \
25 Nov 2022


**Paint by Example: Exemplar-based Image Editing with Diffusion Models** \
*Binxin Yang, Shuyang Gu, Bo Zhang, Ting Zhang, Xuejin Chen, Xiaoyan Sun, Dong Chen, Fang Wen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13227)] \
23 Nov 2022


**Paint by Example: Exemplar-based Image Editing with Diffusion Models** \
*Binxin Yang, Shuyang Gu, Bo Zhang, Ting Zhang, Xuejin Chen, Xiaoyan Sun, Dong Chen, Fang Wen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13227)] \
23 Nov 2022


**EDICT: Exact Diffusion Inversion via Coupled Transformations** \
*Bram Wallace, Akash Gokul, Nikhil Naik* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12446)] \
22 Nov 2022


**SinDiffusion: Learning a Diffusion Model from a Single Natural Image** \
*Weilun Wang, Jianmin Bao, Wengang Zhou, Dongdong Chen, Dong Chen, Lu Yuan, Houqiang Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12445)] [[Github](https://github.com/WeilunWang/SinDiffusion)] \
22 Nov 2022

**SinFusion: Training Diffusion Models on a Single Image or Video** \
*Yaniv Nikankin, Niv Haim, Michal Irani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11743)] \
21 Nov 2022



**Invariant Learning via Diffusion Dreamed Distribution Shifts** \
*Priyatham Kattakinda, Alexander Levine, Soheil Feizi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10370)] \
18 Nov 2022

**Null-text Inversion for Editing Real Images using Guided Diffusion Models**\
*Ron Mokady, Amir Hertz, Kfir Aberman, Yael Pritch, Daniel Cohen-Or* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09794)] \
17 Nov 2022

**InstructPix2Pix: Learning to Follow Image Editing Instructions** \
*Tim Brooks, Aleksander Holynski, Alexei A. Efros* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09800)] \
17 Nov 2022

**Versatile Diffusion: Text, Images and Variations All in One Diffusion Model** \
*Xingqian Xu, Zhangyang Wang, Eric Zhang, Kai Wang, Humphrey Shi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08332)] [[Github](https://github.com/SHI-Labs/Versatile-Diffusion)] \
15 Nov 2022

**Direct Inversion: Optimization-Free Text-Driven Real Image Editing with Diffusion Models** \
*Adham Elarabawy, Harish Kamath, Samuel Denton* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.07825)] \
15 Nov 2022

**Efficient Spatially Sparse Inference for Conditional GANs and Diffusion Models** \
*Muyang Li, Ji Lin, Chenlin Meng, Stefano Ermon, Song Han, Jun-Yan Zhu* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2211.02048)] [[Github](https://github.com/lmxyy/sige)] \
4 Nov 2022

**High-Resolution Image Editing via Multi-Stage Blended Diffusion** \
*Johannes Ackermann, Minjun Li* \
NeurIPS Workshop 2022. [[Paper](https://arxiv.org/abs/2210.12965)] [[Github](https://github.com/pfnet-research/multi-stage-blended-diffusion)] \
24 Oct 2022


**DiffEdit: Diffusion-based semantic image editing with mask guidance** \
*Guillaume Couairon, Jakob Verbeek, Holger Schwenk, Matthieu Cord* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.11427)] \
20 Oct 2022

**Imagic: Text-Based Real Image Editing with Diffusion Models** \
*Bahjat Kawar<sup>1</sup>, Shiran Zada<sup>1</sup>, Oran Lang, Omer Tov, Huiwen Chang, Tali Dekel, Inbar Mosseri, Michal Irani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09276)] \
17 Oct 2022

**Leveraging Off-the-shelf Diffusion Model for Multi-attribute Fashion Image Manipulation** \
*Chaerin Kong, DongHyeon Jeon, Ohjoon Kwon, Nojun Kwak* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05872)] \
12 Oct 2022

**Adaptively-Realistic Image Generation from Stroke and Sketch with Diffusion Model** \
*Shin-I Cheng<sup>1</sup>, Yu-Jie Chen<sup>1</sup>, Wei-Chen Chiu, Hsin-Ying Lee, Hung-Yu Tseng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.12675)] [[Project](https://cyj407.github.io/DiSS/)] \
26 Aug 2022

**Blended Latent Diffusion** \
*Omri Avrahami, Ohad Fried, Dani Lischinski* \
ACM 2022. [[Paper](https://arxiv.org/abs/2206.02779)] [[Project](https://omriavrahami.com/blended-latent-diffusion-page/)] [[Github](https://github.com/omriav/blended-latent-diffusion)] \
6 Jun 2022

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Dominik Lorenz, Patrick Esser, Björn Ommer* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2112.10752)] [[Github](https://github.com/CompVis/latent-diffusion)] \
20 Dec 2021

**Tackling the Generative Learning Trilemma with Denoising Diffusion GANs** \
*Zhisheng Xiao, Karsten Kreis, Arash Vahdat* \
ICLR 2022 (Spotlight). [[Paper](https://arxiv.org/abs/2112.07804)] [[Project](https://nvlabs.github.io/denoising-diffusion-gan)] \
15 Dec 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021

**SDEdit: Image Synthesis and Editing with Stochastic Differential Equations**  \
*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2108.01073)] [[Project](https://sde-image-editing.github.io/)] [[Github](https://github.com/ermongroup/SDEdit)] \
2 Aug 2021

### Text-to-Image


**Unite and Conquer: Cross Dataset Multimodal Synthesis using Diffusion Models** \
*Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M. Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00793)] [[Project](https://nithin-gk.github.io/projectpages/Multidiff/index.html)] \
1 Dec 2022

**DATID-3D: Diversity-Preserved Domain Adaptation Using Text-to-Image Diffusion for 3D Generative Model** \
*Gwanghyun Kim, Se Young Chun* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16374)] [[Github](https://datid-3d.github.io/)] \
29 Nov 2022


**Unified Discrete Diffusion for Simultaneous Vision-Language Generation** \
*Minghui Hu, Chuanxia Zheng, Heliang Zheng, Tat-Jen Cham, Chaoyue Wang, Zuopeng Yang, Dacheng Tao, Ponnuthurai N. Suganthan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14842)] \
27 Nov 2022


**3DDesigner: Towards Photorealistic 3D Object Generation and Editing with Text-guided Diffusion Models** \
*Gang Li, Heliang Zheng, Chaoyue Wang, Chang Li, Changwen Zheng, Dacheng Tao* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14108)] \
25 Nov 2022

**SpaText: Spatio-Textual Representation for Controllable Image Generation** \
*Omri Avrahami, Thomas Hayes, Oran Gafni, Sonal Gupta, Yaniv Taigman, Devi Parikh, Dani Lischinski, Ohad Fried, Xi Yin* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14305)] [[Project](https://omriavrahami.com/spatext/)] \
25 Nov 2022

**Shifted Diffusion for Text-to-image Generation** \
*Yufan Zhou, Bingchen Liu, Yizhe Zhu, Xiao Yang, Changyou Chen, Jinhui Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.15388)] \
24 Nov 2022


**Sketch-Guided Text-to-Image Diffusion Models** \
*Andrey Voynov, Kfir Aberman, Daniel Cohen-Or* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13752)] [[Project](https://sketch-guided-diffusion.github.io/)] \
24 Nov 2022

**EDICT: Exact Diffusion Inversion via Coupled Transformations** \
*Bram Wallace, Akash Gokul, Nikhil Naik* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12446)] \
22 Nov 2022


**SinDiffusion: Learning a Diffusion Model from a Single Natural Image** \
*Weilun Wang, Jianmin Bao, Wengang Zhou, Dongdong Chen, Dong Chen, Lu Yuan, Houqiang Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12445)] [[Github](https://github.com/WeilunWang/SinDiffusion)] \
22 Nov 2022

**Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation** \
*Narek Tumanyan<sup>1</sup>, Michal Geyer<sup>1</sup>, Shai Bagon, Tali Dekel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12572)] \
22 Nov 2022

**Human Evaluation of Text-to-Image Models on a Multi-Task Benchmark** \
*Vitali Petsiuk, Alexander E. Siemenn, Saisamrit Surbehera, Zad Chin, Keith Tyser, Gregory Hunter, Arvind Raghavan, Yann Hicke, Bryan A. Plummer, Ori Kerret, Tonio Buonassisi, Kate Saenko, Armando Solar-Lezama, Iddo Drori* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2211.12112)] \
22 Nov 2022

**Investigating Prompt Engineering in Diffusion Models** \
*Sam Witteveen, Martin Andrews* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.15462)] \
21 Nov 2022

**VectorFusion: Text-to-SVG by Abstracting Pixel-Based Diffusion Models** \
*Ajay Jain<sup>1</sup>, Amber Xie<sup>1</sup>, Pieter Abbeel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11319)] [[Project](https://ajayj.com/vectorfusion)] \
21 Nov 2022

**DiffStyler: Controllable Dual Diffusion for Text-Driven Image Stylization** \
*Nisha Huang, Yuxin Zhang, Fan Tang, Chongyang Ma, Haibin Huang, Yong Zhang, Weiming Dong, Changsheng Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10682)] \
19 Nov 2022


**Magic3D: High-Resolution Text-to-3D Content Creation** \
*Chen-Hsuan Lin<sup>1</sup>, Jun Gao<sup>1</sup>, Luming Tang<sup>1</sup>, Towaki Takikawa<sup>1</sup>, Xiaohui Zeng<sup>1</sup>, Xun Huang, Karsten Kreis, Sanja Fidler, Ming-Yu Liu, Tsung-Yi Lin* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10440)] [[Project](https://deepimagination.cc/Magic3D/)] \
18 Nov 2022



**Invariant Learning via Diffusion Dreamed Distribution Shifts** \
*Priyatham Kattakinda, Alexander Levine, Soheil Feizi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10370)] \
18 Nov 2022

**Null-text Inversion for Editing Real Images using Guided Diffusion Models**\
*Ron Mokady, Amir Hertz, Kfir Aberman, Yael Pritch, Daniel Cohen-Or* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09794)] \
17 Nov 2022

**InstructPix2Pix: Learning to Follow Image Editing Instructions** \
*Tim Brooks, Aleksander Holynski, Alexei A. Efros* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09800)] \
17 Nov 2022


**Versatile Diffusion: Text, Images and Variations All in One Diffusion Model** \
*Xingqian Xu, Zhangyang Wang, Eric Zhang, Kai Wang, Humphrey Shi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08332)] [[Github](https://github.com/SHI-Labs/Versatile-Diffusion)] \
15 Nov 2022

**Arbitrary Style Guidance for Enhanced Diffusion-Based Text-to-Image Generation** \
*Zhihong Pan, Xin Zhou, Hao Tian* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.07751)] \
14 Nov 2022


**Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models** \
*Patrick Schramowski, Manuel Brack, Björn Deiseroth, Kristian Kersting* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.05105)] [[Github](https://github.com/ml-research/safe-latent-diffusion)] \
9 Nov 2022

**Rickrolling the Artist: Injecting Invisible Backdoors into Text-Guided Image Generation Models** \
*Lukas Struppek, Dominik Hintersdorf, Kristian Kersting* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.02408)] [[Github](https://github.com/LukasStruppek/Rickrolling-the-Artist)] \
4 Nov 2022

**eDiffi: Text-to-Image Diffusion Models with an Ensemble of Expert Denoisers** \
*Yogesh Balaji, Seungjun Nah, Xun Huang, Arash Vahdat, Jiaming Song, Karsten Kreis, Miika Aittala, Timo Aila, Samuli Laine, Bryan Catanzaro, Tero Karras, Ming-Yu Liu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.01324)] [[Github](https://deepimagination.cc/eDiffi/)] \
2 Nov 2022

**MagicMix: Semantic Mixing with Diffusion Models** \
*Jun Hao Liew, Hanshu Yan, Daquan Zhou, Jiashi Feng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.16056)] [[Project](https://magicmix.github.io/)] \
28 Oct 2022

**UPainting: Unified Text-to-Image Diffusion Generation with Cross-modal Guidance** \
*Wei Li, Xue Xu, Xinyan Xiao, Jiachen Liu, Hu Yang, Guohao Li, Zhanpeng Wang, Zhifan Feng, Qiaoqiao She, Yajuan Lyu, Hua Wu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.16031)] \
28 Oct 2022

**How well can Text-to-Image Generative Models understand Ethical Natural Language Interventions?** \
*Hritik Bansal<sup>1</sup>, Da Yin<sup>1</sup>, Masoud Monajatipoor, Kai-Wei Chang* \
EMNLP 2022. [[Paper(https://arxiv.org/abs/2210.15230)] [[Github](https://github.com/Hritikbansal/entigen_emnlp)] \
27 Oct 2022

**ERNIE-ViLG 2.0: Improving Text-to-Image Diffusion Model with Knowledge-Enhanced Mixture-of-Denoising-Experts** \
*Zhida Feng<sup>1</sup>, Zhenyu Zhang<sup>1</sup>, Xintong Yu<sup>1</sup>, Yewei Fang, Lanxin Li, Xuyi Chen, Yuxiang Lu, Jiaxiang Liu, Weichong Yin, Shikun Feng, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.15257)] \
27 Oct 2022


**DiffusionDB: A Large-scale Prompt Gallery Dataset for Text-to-Image Generative Models** \
*Zijie J. Wang, Evan Montoya, David Munechika, Haoyang Yang, Benjamin Hoover, Duen Horng Chau* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.14896)] [[Project](https://poloclub.github.io/diffusiondb/)] \
26 Oct 2022

**Lafite2: Few-shot Text-to-Image Generation** \
*Yufan Zhou, Chunyuan Li, Changyou Chen, Jianfeng Gao, Jinhui Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.14124)] \
25 Oct 2022

**Conditional Diffusion with Less Explicit Guidance via Model Predictive Control** \
*Max W. Shen, Ehsan Hajiramezanali, Gabriele Scalia, Alex Tseng, Nathaniel Diamant, Tommaso Biancalani, Andreas Loukas* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.12192)] \
21 Oct 2022

**A Visual Tour Of Current Challenges In Multimodal Language Models** \
*Shashank Sonkar, Naiming Liu, Richard G. Baraniuk* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.12565)] \
22 Oct 2022

**Diffusion Models already have a Semantic Latent Space** \
*Mingi Kwon, Jaeseok Jeong, Youngjung Uh* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.10960)] [[Project](https://kwonminki.github.io/Asyrp/)] \
20 Oct 2022

**DiffEdit: Diffusion-based semantic image editing with mask guidance** \
*Guillaume Couairon, Jakob Verbeek, Holger Schwenk, Matthieu Cord* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.11427)] \
20 Oct 2022

**UniTune: Text-Driven Image Editing by Fine Tuning an Image Generation Model on a Single Image** \
*Dani Valevski, Matan Kalman, Yossi Matias, Yaniv Leviathan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09477)] \
18 Oct 2022

**Swinv2-Imagen: Hierarchical Vision Transformer Diffusion Models for Text-to-Image Generation** \
*Ruijun Li, Weihua Li, Yi Yang, Hanyu Wei, Jianhua Jiang, Quan Bai* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09549)] \
18 Oct 2022

**Imagic: Text-Based Real Image Editing with Diffusion Models** \
*Bahjat Kawar<sup>1</sup>, Shiran Zada<sup>1</sup>, Oran Lang, Omer Tov, Huiwen Chang, Tali Dekel, Inbar Mosseri, Michal Irani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09276)] \
17 Oct 2022

**Unifying Diffusion Models' Latent Space, with Applications to CycleDiffusion and Guidance** \
*Chen Henry Wu, Fernando De la Torre* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05559)] [[Github-1](https://github.com/ChenWu98/cycle-diffusion)] [[Github-2](https://github.com/ChenWu98/unified-generative-zoo)] \
11 Oct 2022


**LDEdit: Towards Generalized Text Guided Image Manipulation via Latent Diffusion Models** \
*Paramanand Chandramouli, Kanchana Vaishnavi Gandikota* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.02249)] \
5 Oct 2022

**clip2latent: Text driven sampling of a pre-trained StyleGAN using denoising diffusion and CLIP** \
*Justin N. M. Pinkney, Chuan Li* \
BMVC 2022. [[Paper](https://arxiv.org/abs/2210.02347)] [[Github](https://github.com/justinpinkney/clip2latent)] \
5 Oct 2022

**Membership Inference Attacks Against Text-to-image Generation Models** \
*Yixin Wu, Ning Yu, Zheng Li, Michael Backes, Yang Zhang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.00968)] \
3 Oct 2022

**DreamFusion: Text-to-3D using 2D Diffusion** \
*Ben Poole, Ajay Jain, Jonathan T. Barron, Ben Mildenhall* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14988)] [[Github](https://dreamfusion3d.github.io/)] \
29 Sep 2022

**Re-Imagen: Retrieval-Augmented Text-to-Image Generator** \
*Wenhu Chen, Hexiang Hu, Chitwan Saharia, William W. Cohen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14491)] \
29 Sep 2022

**Creative Painting with Latent Diffusion Models** \
*Xianchao Wu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14697)] \
29 Sep 2022

**Draw Your Art Dream: Diverse Digital Art Synthesis with Multimodal Guided Diffusion** \
*Nisha Huang, Fan Tang, Weiming Dong, Changsheng Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.13360)] [[Github](https://github.com/haha-lisa/MGAD-multimodal-guided-artwork-diffusion)] \
27 Sep 2022

**Personalizing Text-to-Image Generation via Aesthetic Gradients** \
*Victor Gallego* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.12330)] [[Github](https://github.com/vicgalle/stable-diffusion-aesthetic-gradients)] \
25 Sep 2022

**Best Prompts for Text-to-Image Models and How to Find Them** \
*Nikita Pavlichenko, Dmitry Ustalov* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.11711)] \
23 Sep 2022

**The Biased Artist: Exploiting Cultural Biases via Homoglyphs in Text-Guided Image Generation Models** \
*Lukas Struppek, Dominik Hintersdorf, Kristian Kersting* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.08891)]  [[Github](https://github.com/LukasStruppek/The-Biased-Artist)] \
19 Sep 2022

**Generative Visual Prompt: Unifying Distributional Control of Pre-Trained Generative Models** \
*Chen Henry Wu, Saman Motamed, Shaunak Srivastava, Fernando De la Torre* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.06970)] [[Github](https://github.com/ChenWu98/Generative-Visual-Prompt)] \
14 Sep 2022

**DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation** \
*Nataniel Ruiz, Yuanzhen Li, Varun Jampani, Yael Pritch, Michael Rubinstein, Kfir Aberman* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.12242)] [[Project](https://dreambooth.github.io/)] [[Github](https://github.com/Victarry/stable-dreambooth)] \
25 Aug 2022

**Text-Guided Synthesis of Artistic Images with Retrieval-Augmented Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Björn Ommer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.13038)] [[Github](https://github.com/CompVis/latent-diffusion)] \
26 Jul 2022

**Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation** \
*Ye Zhu, Yu Wu, Kyle Olszewski, Jian Ren, Sergey Tulyakov, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07771)] [[Github](https://github.com/L-YeZhu/CDCD)] \
15 Jun 2022

**Blended Latent Diffusion** \
*Omri Avrahami, Ohad Fried, Dani Lischinski* \
ACM 2022. [[Paper](https://arxiv.org/abs/2206.02779)] [[Project](https://omriavrahami.com/blended-latent-diffusion-page/)] [[Github](https://github.com/omriav/blended-latent-diffusion)] \
6 Jun 2022

**Compositional Visual Generation with Composable Diffusion Models** \
*Nan Liu<sup>1</sup>, Shuang Li<sup>1</sup>, Yilun Du<sup>1</sup>, Antonio Torralba, Joshua B. Tenenbaum* \
ECCV 2022. [[Paper](https://arxiv.org/abs/2206.01714)] [[Project](https://energy-based-model.github.io/Compositional-Visual-Generation-with-Composable-Diffusion-Models/)] [[Github](https://github.com/energy-based-model/Compositional-Visual-Generation-with-Composable-Diffusion-Models-PyTorch)] \
3 Jun 2022

**DiVAE: Photorealistic Images Synthesis with Denoising Diffusion Decoder** \
*Jie Shi<sup>1</sup>, Chenfei Wu<sup>1</sup>, Jian Liang, Xiang Liu, Nan Duan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00386)] \
1 Jun 2022

**Improved Vector Quantized Diffusion Models** \
*Zhicong Tang, Shuyang Gu, Jianmin Bao, Dong Chen, Fang Wen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.16007)] [[Github](https://github.com/microsoft/VQ-Diffusion)] \
31 May 2022

**Text2Human: Text-Driven Controllable Human Image Generation** \
*Yuming Jiang, Shuai Yang, Haonan Qiu, Wayne Wu, Chen Change Loy, Ziwei Liu* \
ACM 2022. [[Paper](https://arxiv.org/abs/2205.15996)] \
31 May 2022

**Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding** \
*Chitwan Saharia<sup>1</sup>, William Chan<sup>1</sup>, Saurabh Saxena, Lala Li, Jay Whang, Emily Denton, Seyed Kamyar Seyed Ghasemipour, Burcu Karagol Ayan, S. Sara Mahdavi, Rapha Gontijo Lopes, Tim Salimans, Jonathan Ho, David J Fleet, Mohammad Norouzi* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2205.11487)] [[Github](https://github.com/lucidrains/imagen-pytorch)]  \
23 May 2022

**Retrieval-Augmented Diffusion Models** \
*Andreas Blattmann<sup>1</sup>, Robin Rombach<sup>1</sup>, Kaan Oktay, Björn Ommer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.11824)] [[Github](https://github.com/lucidrains/retrieval-augmented-ddpm)] \
25 Apr 2022

**Hierarchical Text-Conditional Image Generation with CLIP Latents** \
*Aditya Ramesh, Prafulla Dhariwal, Alex Nichol, Casey Chu, Mark Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.06125)] [[Github](https://github.com/lucidrains/DALLE2-pytorch)] \
13 Apr 2022


**KNN-Diffusion: Image Generation via Large-Scale Retrieval** \
*Oron Ashual, Shelly Sheynin, Adam Polyak, Uriel Singer, Oran Gafni, Eliya Nachmani, Yaniv Taigman* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.02849)] \
6 Apr 2022

**More Control for Free! Image Synthesis with Semantic Diffusion Guidance** \
*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05744)] [[Github](https://xh-liu.github.io/sdg/)] \
10 Dec 2021

**Vector Quantized Diffusion Model for Text-to-Image Synthesis** \
*Shuyang Gu, Dong Chen, Jianmin Bao, Fang Wen, Bo Zhang, Dongdong Chen, Lu Yuan, Baining Guo* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2111.14822)] [[Github](https://github.com/microsoft/VQ-Diffusion)] \
29 Nov 2021

**Blended Diffusion for Text-driven Editing of Natural Images** \
*Omri Avrahami, Dani Lischinski, Ohad Fried* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2111.14818)] [[Project](https://omriavrahami.com/blended-diffusion-page/)] [[Github](https://github.com/omriav/blended-diffusion)] \
29 Nov 2021

**DiffusionCLIP: Text-guided Image Manipulation Using Diffusion Models** \
*Gwanghyun Kim, Jong Chul Ye* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2110.02711)] \
6 Oct 2021

### Medical Imaging

**Improving dermatology classifiers across populations using images generated by large diffusion models** \
*Luke W. Sagers<sup>1</sup>, James A. Diao<sup>1</sup>, Matthew Groh, Pranav Rajpurkar, Adewole S. Adamson, Arjun K. Manrai* \
NeurIPS Workshop 2022. [[Paper](https://arxiv.org/abs/2211.13352)] \
23 Nov 2022

**RoentGen: Vision-Language Foundation Model for Chest X-ray Generation** \
*Pierre Chambon<sup>1</sup>, Christian Bluethgen<sup>1</sup>, Jean-Benoit Delbrouck, Rogier Van der Sluijs, Małgorzata Połacin, Juan Manuel Zambrano Chaves, Tanishq Mathew Abraham, Shivanshu Purohit, Curtis P. Langlotz, Akshay Chaudhari* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12737)] \
23 Nov 2022

**DOLCE: A Model-Based Probabilistic Diffusion Framework for Limited-Angle CT Reconstruction** \
*Jiaming Liu, Rushil Anirudh, Jayaraman J. Thiagarajan, Stewart He, K. Aditya Mohan, Ulugbek S. Kamilov, Hyojin Kim* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12340)] \
22 Nov 2022


**Patch-Based Denoising Diffusion Probabilistic Model for Sparse-View CT Reconstruction** \
*Wenjun Xia, Wenxiang Cong, Ge Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10388)] \
18 Nov 2022


**Brain PET Synthesis from MRI Using Joint Probability Distribution of Diffusion Model at Ultrahigh Fields** \
*Xie Taofeng<sup>1</sup>, Cao Chentao<sup>1</sup>, Cui Zhuoxu, Li Fanshi, Wei Zidong, Zhu Yanjie, Li Ye, Liang Dong, Jin Qiyu, Chen Guoqing, Wang Haifeng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08901)] \
16 Nov 2022

**Improved HER2 Tumor Segmentation with Subtype Balancing using Deep Generative Networks** \
*Mathias Öttl, Jana Mönius, Matthias Rübner, Carol I. Geppert, Jingna Qiu, Frauke Wilm, Arndt Hartmann, Matthias W. Beckmann, Peter A. Fasching, Andreas Maier, Ramona Erber, Katharina Breininger* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.06150)] \
11 Nov 2022



**An unobtrusive quality supervision approach for medical image annotation** \
*Sonja Kunzmann, Mathias Öttl, Prathmesh Madhu, Felix Denzinger, Andreas Maier* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.06146)] \
11 Nov 2022


**Medical Diffusion -- Denoising Diffusion Probabilistic Models for 3D Medical Image Generation** \
*Firas Khader, Gustav Mueller-Franzes, Soroosh Tayebi Arasteh, Tianyu Han, Christoph Haarburger, Maximilian Schulze-Hagen, Philipp Schad, Sandy Engelhardt, Bettina Baessler, Sebastian Foersch, Johannes Stegmaier, Christiane Kuhl, Sven Nebelung, Jakob Nikolas Kather, Daniel Truhn* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.03364)] \
7 Nov 2022

**Generation of Anonymous Chest Radiographs Using Latent Diffusion Models for Training Thoracic Abnormality Classification Systems** \
*Kai Packhäuser, Lukas Folle, Florian Thamm, Andreas Maier* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.01323)] \
2 Nov 2022

**Spot the fake lungs: Generating Synthetic Medical Images using Neural Diffusion Models** \
*Hazrat Ali, Shafaq Murad, Zubair Shah* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.00902)] [[Project](https://www.kaggle.com/datasets/hazrat/awesomelungs)] \
2 Nov 2022

**MedSegDiff: Medical Image Segmentation with Diffusion Probabilistic Model** \
*Junde Wu, Huihui Fang, Yu Zhang, Yehui Yang, Yanwu Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.00611)] \
1 Nov 2022

**Accelerating Diffusion Models via Pre-segmentation Diffusion Sampling for Medical Image Segmentation** \
*Xutao Guo, Yanwu Yang, Chenfei Ye, Shang Lu, Yang Xiang, Ting Ma* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.17408)] \
27 Oct 2022

**Multitask Brain Tumor Inpainting with Diffusion Models: A Methodological Report** \
*Pouria Rouzrokh<sup>1</sup>, Bardia Khosravi<sup>1</sup>, Shahriar Faghani, Mana Moassefi, Sanaz Vahdati, Bradley J. Erickson* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.12113)] [[Github](https://github.com/Mayo-Radiology-Informatics-Lab/MBTI)] \
21 Oct 2022

**Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains** \
*Pierre Chambon<sup>1</sup>, Christian Bluethgen<sup>1</sup>, Curtis P. Langlotz, Akshay Chaudhari* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.04133)] \
9 Oct 2022

**Anatomically constrained CT image translation for heterogeneous blood vessel segmentation** \
*Giammarco La Barbera, Haithem Boussaid, Francesco Maso, Sabine Sarnacki, Laurence Rouet, Pietro Gori, Isabelle Bloch* \
BMVC 2022. [[Paper](https://arxiv.org/abs/2210.01713)] \
4 Oct 2022

**Low-Dose CT Using Denoising Diffusion Probabilistic Model for 20× Speedup** \
*Wenjun Xia, Qing Lyu, Ge Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15136)] \
29 Sep 2022

**Diffusion Adversarial Representation Learning for Self-supervised Vessel Segmentation** \
*Boah Kim<sup>1</sup>, Yujin Oh<sup>1</sup>, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14566)] \
29 Sep 2022

**Conversion Between CT and MRI Images Using Diffusion and Score-Matching Models** \
*Qing Lyu, Ge Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.12104)] \
24 Sep 2022

**Brain Imaging Generation with Latent Diffusion Models** \
*Walter H. L. Pinaya<sup>1</sup>, Petru-Daniel Tudosiu<sup>1</sup>, Jessica Dafflon, Pedro F da Costa, Virginia Fernandez, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardoso* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.07162)] \
15 Sep 2022

**PET image denoising based on denoising diffusion probabilistic models** \
*Kuang Gong, Keith A. Johnson, Georges El Fakhri, Quanzheng Li, Tinsu Pan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.06167)] \
13 Sep 2022

**Self-Score: Self-Supervised Learning on Score-Based Models for MRI Reconstruction** \
*Zhuo-Xu Cui, Chentao Cao, Shaonan Liu, Qingyong Zhu, Jing Cheng, Haifeng Wang, Yanjie Zhu, Dong Liang* \
IEEE TMI 2022. [[Paper](https://arxiv.org/abs/2209.00835)] \
2 Sep 2022

**High-Frequency Space Diffusion Models for Accelerated MRI** \
*Chentao Cao, Zhuo-Xu Cui, Shaonan Liu, Dong Liang, Yanjie Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.05481)] \
10 Aug 2022

**What is Healthy? Generative Counterfactual Diffusion for Lesion Localization** \
*Pedro Sanchez, Antanas Kascenas, Xiao Liu, Alison Q. O'Neil, Sotirios A. Tsaftaris* \
MICCAI 2022. [[Paper](https://arxiv.org/abs/2207.12268)] [[Github](https://github.com/vios-s/Diff-SCM)] \
25 Jul 2022


**Unsupervised Medical Image Translation with Adversarial Diffusion Models** \
*Muzaffer Özbey, Salman UH Dar, Hasan A Bedel, Onat Dalmaz, Şaban Özturk, Alper Güngör, Tolga Çukur* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.08208)] \
17 Jul 2022

**Adaptive Diffusion Priors for Accelerated MRI Reconstruction** \
*Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Gokberk Elmas, Muzaffer Özbey, Alper Güngör, Tolga Çukur* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.05876)] \
12 Jul 2022

**A Novel Unified Conditional Score-based Generative Framework for Multi-modal Medical Image Completion** \
*Xiangxi Meng, Yuning Gu, Yongsheng Pan, Nizhuan Wang, Peng Xue, Mengkang Lu, Xuming He, Yiqiang Zhan, Dinggang Shen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.03430)] \
7 Jul 2022

**Cross-Modal Transformer GAN: A Brain Structure-Function Deep Fusing Framework for Alzheimer's Disease** \
*Junren Pan, Shuqiang Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.13393)] \
20 Jun 2022

**Diffusion Deformable Model for 4D Temporal Medical Image Generation** \
*Boah Kim, Jong Chul Ye* \
MICCAI 2022. [[Paper](https://arxiv.org/abs/2206.13295)] [[Github](https://github.com/torchddm/ddm)] \
27 Jun 2022


**Fast Unsupervised Brain Anomaly Detection and Segmentation with Diffusion Models** \
*Walter H. L. Pinaya, Mark S. Graham, Robert Gray, Pedro F Da Costa, Petru-Daniel Tudosiu, Paul Wright, Yee H. Mah, Andrew D. MacKinnon, James T. Teo, Rolf Jager, David Werring, Geraint Rees, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardos* \
MICCAI 2022. [[Paper](https://arxiv.org/abs/2206.03461)] \
7 Jun 2022

**Improving Diffusion Models for Inverse Problems using Manifold Constraints** \
*Hyungjin Chung<sup>1</sup>, Byeongsu Sim<sup>1</sup>, Dohoon Ryu, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00941)] \
2 Jun 2022

**AnoDDPM: Anomaly Detection with Denoising Diffusion Probabilistic Models using Simplex Noise** \
*Julian Wyatt, Adam Leach, Sebastian M. Schmon, Chris G. Willcocks* \
CVPR Workshop 2022. [[Paper](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Wyatt_AnoDDPM_Anomaly_Detection_With_Denoising_Diffusion_Probabilistic_Models_Using_Simplex_CVPRW_2022_paper.pdf)] [[Github](https://github.com/Julian-Wyatt/AnoDDPM)] \
1 Jun 2022

**The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models** \
*Julia Wolleb<sup>1</sup>, Robin Sandkühler<sup>1</sup>, Florentin Bieder, Philippe C. Cattin* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.02641)] \
6 Apr 2022

**MR Image Denoising and Super-Resolution Using Regularized Reverse Diffusion** \
*Hyungjin Chung, Eun Sun Lee, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.12621)] \
23 Mar 2022

**Diffusion Models for Medical Anomaly Detection** \
*Julia Wolleb, Florentin Bieder, Robin Sandkühler, Philippe C. Cattin* \
MICCAI 2022. [[Paper](https://arxiv.org/abs/2203.04306)] [[Github](https://github.com/JuliaWolleb/diffusion-anomaly)] \
8 Mar 2022

**Towards performant and reliable undersampled MR reconstruction via diffusion model sampling** \
*Cheng Peng, Pengfei Guo, S. Kevin Zhou, Vishal Patel, Rama Chellappa* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.04292)] [[Github](https://github.com/cpeng93/diffuserecon)] \
8 Mar 2022

**Measurement-conditioned Denoising Diffusion Probabilistic Model for Under-sampled Medical Image Reconstruction** \
*Yutong Xie, Quanzheng Li* \
MICCAI 2022. [[Paper](https://arxiv.org/abs/2203.03623)] [[Github](https://github.com/Theodore-PKU/MC-DDPM)] \
5 Mar 2022

**MRI Reconstruction via Data Driven Markov Chain with Joint Uncertainty Estimation** \
*Guanxiong Luo, Martin Heide, Martin Uecker* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.01479)] [[Github](https://github.com/mrirecon/spreco)] \
3 Feb 2022

**Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model** \
*Dewei Hu, Yuankai K. Tao, Ipek Oguz* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.11760)] [[Github](https://github.com/DeweiHu/OCT_DDPM)] \
27 Jan 2022

**Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction** \
*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye* \
CVPR 2021. [[Paper](https://arxiv.org/abs/2112.05146)] \
9 Dec 2021

**Solving Inverse Problems in Medical Imaging with Score-Based Generative Models** \
*Yang Song<sup>1</sup>, Liyue Shen<sup>1</sup>, Lei Xing, Stefano Ermon* \
NeurIPS Workshop 2021. [[Paper](https://arxiv.org/abs/2111.08005)] [[Github](https://github.com/yang-song/score_inverse_problems)] \
15 Nov 2021

**Score-based diffusion models for accelerated MRI** \
*Hyungjin Chung, Jong chul Ye* \
MIA 2021. [[Paper](https://arxiv.org/abs/2110.05243)] [[Github](https://github.com/HJ-harry/score-MRI)] \
8 Oct 2021


### Video Generation

**VIDM: Video Implicit Diffusion Models** \
*Kangfu Mei, Vishal M. Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00235)] [[Project](https://kfmei.page/vidm/)] \
1 Dec 2022

**Latent Video Diffusion Models for High-Fidelity Video Generation with Arbitrary Lengths** \
*Yingqing He, Tianyu Yang, Yong Zhang, Ying Shan, Qifeng Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13221)] \
23 Nov 2022


**SinFusion: Training Diffusion Models on a Single Image or Video** \
*Yaniv Nikankin, Niv Haim, Michal Irani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11743)] \
21 Nov 2022

**MagicVideo: Efficient Video Generation With Latent Diffusion Models** \
*Daquan Zhou<sup>1</sup>, Weimin Wang<sup>1</sup>, Hanshu Yan, Weiwei Lv, Yizhe Zhu, Jiashi Feng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11018)] [[Project](https://magicvideo.github.io/)] \
20 Nov 2022

**Imagen Video: High Definition Video Generation with Diffusion Models** \
*Jonathan Ho<sup>1</sup>, William Chan<sup>1</sup>, Chitwan Saharia<sup>1</sup>, Jay Whang<sup>1</sup>, Ruiqi Gao, Alexey Gritsenko, Diederik P. Kingma, Ben Poole, Mohammad Norouzi, David J. Fleet, Tim Salimans* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.02303)] \
5 Oct 2022

**Make-A-Video: Text-to-Video Generation without Text-Video Data** \
*Uriel Singer, Adam Polyak, Thomas Hayes, Xi Yin, Jie An, Songyang Zhang, Qiyuan Hu, Harry Yang, Oron Ashual, Oran Gafni, Devi Parikh, Sonal Gupta, Yaniv Taigman* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14792)] \
29 Sep 2022

**Diffusion Models for Video Prediction and Infilling** \
*Tobias Höppe, Arash Mehrjou, Stefan Bauer, Didrik Nielsen, Andrea Dittadi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07696)] \
15 Jun 2022

**Flexible Diffusion Modeling of Long Videos** \
*William Harvey, Saeid Naderiparizi, Vaden Masrani, Christian Weilbach, Frank Wood* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.11495)] [[Github](https://github.com/plai-group/flexible-video-diffusion-modeling)] \
23 May 2022

**MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation** \
*Vikram Voleti<sup>1</sup>, Alexia Jolicoeur-Martineau<sup>1</sup>, Christopher Pal* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2205.09853)] [[Github](https://github.com/voletiv/mcvd-pytorch)] \
19 May 2022

**Video Diffusion Models** \
*Jonathan Ho<sup>1</sup>, Tim Salimans<sup>1</sup>, Alexey Gritsenko, William Chan, Mohammad Norouzi, David J. Fleet* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2204.03458)] \
7 Apr 2022

**Diffusion Probabilistic Modeling for Video Generation** \
*Ruihan Yang, Prakhar Srivastava, Stephan Mandt* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.09481)] [[Github](https://github.com/buggyyang/rvd)] \
16 Mar 2022


### Point Cloud

**Ada3Diff: Defending against 3D Adversarial Point Clouds via Adaptive Diffusion** \
*Kui Zhang, Hang Zhou, Jie Zhang, Qidong Huang, Weiming Zhang, Nenghai Yu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16247)] \
29 Nov 2022

**DiffusionSDF: Conditional Generative Modeling of Signed Distance Functions** \
*Gene Chou, Yuval Bahat, Felix Heide* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13757)] \
24 Nov 2022

**Tetrahedral Diffusion Models for 3D Shape Generation** \
*Nikolai Kalischek, Torben Peters, Jan D. Wegner, Konrad Schindler* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13220)] \
23 Nov 2022


**LION: Latent Point Diffusion Models for 3D Shape Generation** \
*Xiaohui Zeng, Arash Vahdat, Francis Williams, Zan Gojcic, Or Litany, Sanja Fidler, Karsten Kreis* \
NeurIPS 2022. [[Paper](https://arxiv.org/pdf/2210.06978.pdf)] [[Project](https://nv-tlabs.github.io/LION/)] \
12 Oct 2022

**First Hitting Diffusion Models** \
*Mao Ye, Lemeng Wu, Qiang Liu* \
NeruIPS 2022. [[Paper](https://arxiv.org/abs/2209.01170)] \
2 Sep 2022

**Let us Build Bridges: Understanding and Extending Diffusion Generative Models** \
*Xingchao Liu, Lemeng Wu, Mao Ye, Qiang Liu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.14699)] \
31 Aug 2022

**PointDP: Diffusion-driven Purification against Adversarial Attacks on 3D Point Cloud Recognition** \
*Jiachen Sun, Weili Nie, Zhiding Yu, Z. Morley Mao, Chaowei Xiao* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09801)] \
21 Aug 2022

**A Conditional Point Diffusion-Refinement Paradigm for 3D Point Cloud Completion** \
*Zhaoyang Lyu, Zhifeng Kong, Xudong Xu, Liang Pan, Dahua Lin* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2112.03530)] [[Github](https://github.com/zhaoyanglyu/point_diffusion_refinement)] \
7 Dec 2021

**Score-Based Point Cloud Denoising** \
*Shitong Luo, Wei Hu*\
ICCV 2021. [[Paper](https://arxiv.org/abs/2107.10981)] [[Github](https://github.com/luost26/score-denoise)] \
23 Jul 2021

**3D Shape Generation and Completion through Point-Voxel Diffusion** \
*Linqi Zhou, Yilun Du, Jiajun Wu* \
ICCV 2021. [[Paper](https://arxiv.org/abs/2104.03670)] [[Project](https://alexzhou907.github.io/pvd)] \
8 Apr 2021

**Diffusion Probabilistic Models for 3D Point Cloud Generation** \
*Shitong Luo, Wei Hu* \
CVPR 2021. [[Paper](https://arxiv.org/abs/2103.01458)] [[Github](https://github.com/luost26/diffusion-point-cloud)] \
2 Mar 2021 

### Mesh


**3D Neural Field Generation using Triplane Diffusion** \
*J. Ryan Shue, Eric Ryan Chan, Ryan Po, Zachary Ankner, Jiajun Wu, Gordon Wetzstein* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16677)] [[Project](https://jryanshue.com/nfd/)] \
30 Nov 2022

**IC3D: Image-Conditioned 3D Diffusion for Shape Generation** \
*Cristian Sbrolli, Paolo Cudrano, Matteo Frosi, Matteo Matteucci* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10865)] \
20 Nov 2022

**Neural Volumetric Mesh Generator** \
*Yan Zheng, Lemeng Wu, Xingchao Liu, Zhen Chen, Qiang Liu, Qixing Huang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.03158)] \
6 Oct 2022

### 3D View


**NeuralLift-360: Lifting An In-the-wild 2D Photo to A 3D Object with 360° Views** \
*Dejia Xu, Yifan Jiang, Peihao Wang, Zhiwen Fan, Yi Wang, Zhangyang Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16431)] [[Project](https://vita-group.github.io/NeuralLift-360/)] \
29 Nov 2022

**SparseFusion: Distilling View-conditioned Diffusion for 3D Reconstruction** \
*Zhizhuo Zhou, Shubham Tulsiani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00792)] [[Github](https://sparsefusion.github.io/)] \
1 Dec 2022

**Score Jacobian Chaining: Lifting Pretrained 2D Diffusion Models for 3D Generation** \
*Haochen Wang<sup>1</sup>, Xiaodan Du<sup>1</sup>, Jiahao Li<sup>1</sup>, Raymond A. Yeh, Greg Shakhnarovich* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2212.00774)] \
1 Dec 2022


**3DDesigner: Towards Photorealistic 3D Object Generation and Editing with Text-guided Diffusion Models** \
*Gang Li, Heliang Zheng, Chaoyue Wang, Chang Li, Changwen Zheng, Dacheng Tao* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14108)] \
25 Nov 2022


**RenderDiffusion: Image Diffusion for 3D Reconstruction, Inpainting and Generation** \
*Titas Anciukevičius, Zexiang Xu, Matthew Fisher, Paul Henderson, Hakan Bilen, Niloy J. Mitra, Paul Guerrero* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09869)] \
17 Nov 2022

**Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures** \
*Gal Metzer<sup>1</sup>, Elad Richardson<sup>1</sup>, Or Patashnik, Raja Giryes, Daniel Cohen-Or* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.07600)] [[Github](https://github.com/eladrich/latent-nerf)] \
14 Nov 2022

**LION: Latent Point Diffusion Models for 3D Shape Generation** \
*Xiaohui Zeng, Arash Vahdat, Francis Williams, Zan Gojcic, Or Litany, Sanja Fidler, Karsten Kreis* \
NeurIPS 2022. [[Paper](https://arxiv.org/pdf/2210.06978.pdf)] [[Project](https://nv-tlabs.github.io/LION/)] \
12 Oct 2022

**Novel View Synthesis with Diffusion Models** \
*Daniel Watson, William Chan, Ricardo Martin-Brualla, Jonathan Ho, Andrea Tagliasacchi, Mohammad Norouzi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.04628)] \
6 Oct 2022


**A Diffusion Model Predicts 3D Shapes from 2D Microscopy Images** \
*Dominik J. E. Waibel, Ernst Röell, Bastian Rieck, Raja Giryes, Carsten Marr* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.14125)] \
30 Aug 2022

### Human Motion Synthesis

**UDE: A Unified Driving Engine for Human Motion Generation** \
*Zixiang Zhou, Baoyuan Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16016)] [[Project](https://zixiangzhou916.github.io/UDE/)] [[Github](https://github.com/zixiangzhou916/UDE/)] \
29 Nov 2022

**Listen, denoise, action! Audio-driven motion synthesis with diffusion models** \
*Simon Alexanderson, Rajmund Nagy, Jonas Beskow, Gustav Eje Henter* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09707)] [[Github](https://www.speech.kth.se/research/listen-denoise-action/)] \
17 Nov 2022

**ReFu: Refine and Fuse the Unobserved View for Detail-Preserving Single-Image 3D Human Reconstruction** \
*Gyumin Shim<sup>1</sup>, Minsoo Lee<sup>1</sup>, Jaegul Choo* \
ACM 2022. [[Paper](https://arxiv.org/abs/2211.04753)] \
9 Nov 2022

**Diffusion Motion: Generate Text-Guided 3D Human Motion by Diffusion Model** \
*Zhiyuan Ren, Zhihong Pan, Xin Zhou, Le Kang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.12315)] \
22 Oct 2022

**Denoising Diffusion Probabilistic Models for Styled Walking Synthesis** \
*Edmund J. C. Findlay, Haozheng Zhang, Ziyi Chang, Hubert P. H. Shum* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14828)] \
29 Sep 2022

**Human Motion Diffusion Model** \
*Guy Tevet, Sigal Raab, Brian Gordon, Yonatan Shafir, Amit H. Bermano, Daniel Cohen-Or* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14916)] [[Project](https://guytevet.github.io/mdm-page/)] \
29 Sep 2022

**SE(3)-DiffusionFields: Learning cost functions for joint grasp and motion optimization through diffusion** \
*Julen Urain, Niklas Funk, Georgia Chalvatzaki, Jan Peters* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.03855)] [[Github](https://github.com/TheCamusean/grasp_diffusion)] \
8 Sep 2022


**FLAME: Free-form Language-based Motion Synthesis & Editing** \
*Jihoon Kim, Jiseob Kim, Sungjoon Choi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.00349)] \
1 Sep 2022

**MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model** \
*Mingyuan Zhang, Zhongang Cai, Liang Pan, Fangzhou Hong, Xinying Guo, Lei Yang, Ziwei Liu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.15001)] [[Project](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)] \
31 Aug 2022

**Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion** \
*Tianpei Gu<sup>1</sup>, Guangyi Chen<sup>1</sup>, Junlong Li, Chunze Lin, Yongming Rao, Jie Zhou, Jiwen Lu*\
CVPR 2022. [[Paper](https://arxiv.org/abs/2203.13777)] [[Github](https://github.com/gutianpei/MID)] \
25 Mar 2022


**DiffuStereo: High Quality Human Reconstruction via Diffusion-based Stereo Using Sparse Cameras** \
*Ruizhi Shao, Zerong Zheng, Hongwen Zhang, Jingxiang Sun, Yebin Liu* \
ECCV 2022. [[Paper](https://arxiv.org/abs/2207.08000)] [[Project](http://liuyebin.com/diffustereo/diffustereo.html)] [[Github](https://github.com/DSaurus/DiffuStereo)] \
16 Jul 2022


### Adversarial Attack

**Fight Fire With Fire: Reversing Skin Adversarial Examples by Multiscale Diffusive and Denoising Aggregation Mechanism** \
*Yongwei Wang<sup>1</sup>, Yuan Li<sup>1</sup>, Zhiqi Shen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.10373)] \
22 Aug 2022

**DensePure: Understanding Diffusion Models towards Adversarial Robustness** \
*Chaowei Xiao<sup>1</sup>, Zhongzhu Chen<sup>1</sup>, Kun Jin<sup>1</sup>, Jiongxiao Wang<sup>1</sup>, Weili Nie, Mingyan Liu, Anima Anandkumar, Bo Li, Dawn Song* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2211.00322)] \
1 Nov 2022

**Improving Adversarial Robustness by Contrastive Guided Diffusion Process** \
*Yidong Ouyang, Liyan Xie, Guang Cheng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09643)] \
18 Oct 2022

**Differentially Private Diffusion Models** \
*Tim Dockhorn, Tianshi Cao, Arash Vahdat, Karsten Kreis* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09929)] [[Project](https://nv-tlabs.github.io/DPDM/)] \
18 Oct 2022

**PointDP: Diffusion-driven Purification against Adversarial Attacks on 3D Point Cloud Recognition** \
*Jiachen Sun, Weili Nie, Zhiding Yu, Z. Morley Mao, Chaowei Xiao* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09801)] \
21 Aug 2022


**Threat Model-Agnostic Adversarial Defense using Diffusion Models** \
*Tsachi Blau, Roy Ganz, Bahjat Kawar, Alex Bronstein, Michael Elad* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.08089)] \
17 Jul 2022

**Back to the Source: Diffusion-Driven Test-Time Adaptation** \
*Jin Gao<sup>1</sup>, Jialing Zhang<sup>1</sup>, Xihui Liu, Trevor Darrell, Evan Shelhamer, Dequan Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.03442)] \
7 Jul 2022

**Guided Diffusion Model for Adversarial Purification from Random Noise** \
*Quanlin Wu, Hang Ye, Yuntian Gu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.10875)] \
17 Jun 2022

**(Certified!!) Adversarial Robustness for Free!** \
*Nicholas Carlini, Florian Tramer, Krishnamurthy (Dj)Dvijotham, J. Zico Kolter* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.10550)] \
21 Jun 2022

**Guided Diffusion Model for Adversarial Purification** \
*Jinyi Wang<sup>1</sup>, Zhaoyang Lyu<sup>1</sup>, Dahua Lin, Bo Dai, Hongfei Fu* \
ICML 2022. [[Paper](https://arxiv.org/abs/2205.14969)] [[Github](https://github.com/jinyiw/guideddiffusionpur)] \
30 May 2022

**Diffusion Models for Adversarial Purification** \
*Weili Nie, Brandon Guo, Yujia Huang, Chaowei Xiao, Arash Vahdat, Anima Anandkumar* \
ICML 2022. [[Paper](https://arxiv.org/abs/2205.07460)] [[Project](https://diffpure.github.io/)] [[Github](https://github.com/NVlabs/DiffPure)] \
16 May 2022

**TFDPM: Attack detection for cyber-physical systems with diffusion probabilistic models** \
*Tijin Yan, Tong Zhou, Yufeng Zhan, Yuanqing Xia* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.10774)] \
20 Dec 2021

**Adversarial purification with Score-based generative models** \
*Jongmin Yoon, Sung Ju Hwang, Juho Lee* \
ICML 2021. [[Paper](https://arxiv.org/abs/2106.06041)] [[Github](https://github.com/jmyoon1/adp)] \
11 Jun 2021

### Miscellaneous

**DiffPose: Toward More Reliable 3D Pose Estimation** \
*Jia Gong<sup>1</sup>, Lin Geng Foo<sup>1</sup>, Zhipeng Fan, Qiuhong Ke, Hossein Rahmani, Jun Liu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16940)] \
30 Nov 2022

**DiffPose: Multi-hypothesis Human Pose Estimation using Diffusion models** \
*Karl Holmquist, Bastian Wandt* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.16487)] \
29 Nov 2022

**Post-training Quantization on Diffusion Models** \
*Yuzhang Shang<sup>1</sup>, Zhihang Yuan<sup>1</sup>, Bin Xie<sup>1</sup>, Bingzhe Wu, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.15736)] \
28 Nov 2022

**Refined Semantic Enhancement towards Frequency Diffusion for Video Captioning** \
*Xian Zhong, Zipeng Li, Shuqin Chen, Kui Jiang, Chen Chen, Mang Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.15076)] [[Github](https://github.com/lzp870/RSFD)] \
28 Nov 2022

**Diffusion Probabilistic Model Made Slim** \
*Xingyi Yang, Daquan Zhou, Jiashi Feng, Xinchao Wang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.17106)] \
27 Nov 2022


**BeLFusion: Latent Diffusion for Behavior-Driven Human Motion Prediction** \
*German Barquero, Sergio Escalera, Cristina Palmero* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.14304)] \
25 Nov 2022

**JigsawPlan: Room Layout Jigsaw Puzzle Extreme Structure from Motion using Diffusion Models** \
*Sepidehsadat Hosseini, Mohammad Amin Shabani, Saghar Irandoust, Yasutaka Furukawa* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13785)] [[Project](https://sepidsh.github.io/JigsawPlan/index.html)] \
24 Nov 2022


**HouseDiffusion: Vector Floorplan Generation via a Diffusion Model with Discrete and Continuous Denoising** \
*Mohammad Amin Shabani, Sepidehsadat Hosseini, Yasutaka Furukawa* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13287)] [[Project](https://aminshabani.github.io/housediffusion/)] \
23 Nov 2022

**Make-A-Story: Visual Memory Conditioned Consistent Story Generation** \
*Tanzila Rahman, Hsin-Ying Lee, Jian Ren, Sergey Tulyakov, Shweta Mahajan, Leonid Sigal* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13319)] \
23 Nov 2022



**Inversion-Based Creativity Transfer with Diffusion Models** \
*Yuxin Zhang, Nisha Huang, Fan Tang, Haibin Huang, Chongyang Ma, Weiming Dong, Changsheng Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13203)] \
23 Nov 2022

**Schrödinger's Bat: Diffusion Models Sometimes Generate Polysemous Words in Superposition** \
*Jennifer C. White, Ryan Cotterell* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13095)] \
23 Nov 2022

**DiffDreamer: Consistent Single-view Perpetual View Generation with Conditional Diffusion Models** \
*Shengqu Cai, Eric Ryan Chan, Songyou Peng, Mohamad Shahbazi, Anton Obukhov, Luc Van Gool, Gordon Wetzstein* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12131)] [[Project](https://primecai.github.io/diffdreamer)] \
22 Nov 2022

**Person Image Synthesis via Denoising Diffusion Model** \
*Ankan Kumar Bhunia, Salman Khan, Hisham Cholakkal, Rao Muhammad Anwer, Jorma Laaksonen, Mubarak Shah, Fahad Shahbaz Khan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12500)] \
22 Nov 2022


**Diffusion Denoising Process for Perceptron Bias in Out-of-distribution Detection** \
*Luping Liu, Yi Ren, Xize Cheng, Zhou Zhao* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11255)] [[Github](https://github.com/luping-liu/DiffOOD)] \
21 Nov 2022

**Exploring Discrete Diffusion Models for Image Captioning** \
*Zixin Zhu, Yixuan Wei, Jianfeng Wang, Zhe Gan, Zheng Zhang, Le Wang, Gang Hua, Lijuan Wang, Zicheng Liu, Han Hu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11694)] [[Github](https://github.com/buxiangzhiren/DDCap)] \
21 Nov 2022


**Synthesizing Coherent Story with Auto-Regressive Latent Diffusion Models** \
*Xichen Pan, Pengda Qin, Yuhong Li, Hui Xue, Wenhu Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10950)] \
20 Nov 2022

**DiffusionDet: Diffusion Model for Object Detection** \
*Shoufa Chen, Peize Sun, Yibing Song, Ping Luo* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09788)] [[Github](https://github.com/ShoufaChen/DiffusionDet)] \
17 Nov 2022


**Learning to Kindle the Starlight** \
*Yu Yuan, Jiaqi Wu, Lindong Wang, Zhongliang Jing, Henry Leung, Shuyuan Zhu, Han Pan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09206)] \
16 Nov 2022


**CaDM: Codec-aware Diffusion Modeling for Neural-enhanced Video Streaming** \
*Qihua Zhou, Ruibin Li, Song Guo, Yi Liu, Jingcai Guo, Zhenda Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08428)] \
15 Nov 2022


**ShadowDiffusion: Diffusion-based Shadow Removal using Classifier-driven Attention and Structure Preservation** \
*Yeying Jin, Wenhan Yang, Wei Ye, Yuan Yuan, Robby T. Tan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08089)] \
15 Nov 2022

**Extreme Generative Image Compression by Learning Text Embedding from Diffusion Models** \
*Zhihong Pan, Xin Zhou, Hao Tian* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.07793)] \
14 Nov 2022


**Denoising Diffusion Models for Out-of-Distribution Detection** \
*Mark S. Graham, Walter H.L. Pinaya, Petru-Daniel Tudosiu, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardoso* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.07740)] \
14 Nov 2022


**DriftRec: Adapting diffusion models to blind image restoration tasks** \
*Simon Welker, Henry N. Chapman, Timo Gerkmann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.06757)] \
12 Nov 2022

**Evaluating a Synthetic Image Dataset Generated with Stable Diffusion** \
*Andreas Stöckl* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.01777)] \
3 Nov 2022


**Quantized Compressed Sensing with Score-Based Generative Models** \
*Xiangming Meng, Yoshiyuki Kabashima* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.13006)] [[Github](https://github.com/mengxiangming/QCS-SGM)] \
2 Nov 2022

**On the detection of synthetic images generated by diffusion models** \
*Riccardo Corvi, Davide Cozzolino, Giada Zingarini, Giovanni Poggi, Koki Nagano, Luisa Verdoliva* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.00680)] \
1 Nov 2022

**DOLPH: Diffusion Models for Phase Retrieval** \
*Shirin Shoushtari<sup>1</sup>, Jiaming Liu<sup>1</sup>, Ulugbek S. Kamilov* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.00529)] \
1 Nov 2022

**A simple, efficient and scalable contrastive masked autoencoder for learning visual representations** \
*Shlok Mishra, Joshua Robinson, Huiwen Chang, David Jacobs, Aaron Sarna, Aaron Maschinot, Dilip Krishnan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.16870)] \
30 Oct 2022

**Towards the Detection of Diffusion Model Deepfakes** \
*Jonas Ricker, Simon Damm, Thorsten Holz, Asja Fischer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.14571)] \
26 Oct 2022


**Boomerang: Local sampling on image manifolds using diffusion models** \
*Lorenzo Luzi, Ali Siahkoohi, Paul M Mayer, Josue Casco-Rodriguez, Richard Baraniuk* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.12100)] [[Colab](https://colab.research.google.com/drive/1PV5Z6b14HYZNx1lHCaEVhId-Y4baKXwt)] \
21 Oct 2022

**Deep Data Augmentation for Weed Recognition Enhancement: A Diffusion Probabilistic Model and Transfer Learning Based Approach** \
*Dong Chen, Xinda Qi, Yu Zheng, Yuzhen Lu, Zhaojian Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.09509)] [[Github](https://github.com/DongChen06/DMWeeds)] \
18 Oct 2022

**Meta-Learning via Classifier(-free) Guidance** \
*Elvis Nava<sup>1</sup>, Seijin Kobayashi<sup>1</sup>, Yifei Yin, Robert K. Katzschmann, Benjamin F. Grewe* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.08942)] \
17 Oct 2022

**DE-FAKE: Detection and Attribution of Fake Images Generated by Text-to-Image Diffusion Models** \
*Zeyang Sha, Zheng Li, Ning Yu, Yang Zhang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.06998)] \
13 Oct 2022

**Markup-to-Image Diffusion Models with Scheduled Sampling** \
*Yuntian Deng, Noriyuki Kojima, Alexander M. Rush* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05147)] \
11 Oct 2022

**What the DAAM: Interpreting Stable Diffusion Using Cross Attention** \
*Raphael Tang, Akshat Pandey, Zhiying Jiang, Gefei Yang, Karun Kumar, Jimmy Lin, Ferhan Ture* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.04885)] [[Github](https://github.com/castorini/daam)] \
10 Oct 2022

**CLIP-Diffusion-LM: Apply Diffusion Model on Image Captioning** \
*Shitong Xu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.04559)] [[Github](https://github.com/xu-shitong/diffusion-image-captioning)] \
10 Oct 2022

**JPEG Artifact Correction using Denoising Diffusion Restoration Models** \
*Bahjat Kawar<sup>1</sup>, Jiaming Song<sup>1</sup>, Stefano Ermon, Michael Elad* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.11888)] \
23 Sep 2022


**AT-DDPM: Restoring Faces degraded by Atmospheric Turbulence using Denoising Diffusion Probabilistic Models** \
*Nithin Gopalakrishnan Nair, Kangfu Mei, Vishal M Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.11284)] \
24 Aug 2022

**Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models** \
*Ozan Özdenizci, Robert Legenstein* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.14626)] [[Github](https://github.com/IGITUGraz/WeatherDiffusion)] \
29 Jul 2022


**Deep Diffusion Models for Seismic Processing** \
*Ricard Durall, Ammar Ghanim, Mario Fernandez, Norman Ettrich, Janis Keuper* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.10451)] \
21 Jul 2022

**Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions** \
*Emiel Hoogeboom, Didrik Nielsen, Priyank Jaini, Patrick Forré, Max Welling* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2102.05379)] \
10 Feb 2021


## Audio
### Audio Generation

**SDMuse: Stochastic Differential Music Editing and Generation via Hybrid Representation** \
*Chen Zhang, Yi Ren, Kejun Zhang, Shuicheng Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.00222)] [[Project](https://sdmuse.github.io/posts/sdmuse/)] \
1 Nov 2022

**Full-band General Audio Synthesis with Score-based Diffusion** \
*Santiago Pascual, Gautam Bhattacharya, Chunghsin Yeh, Jordi Pons, Joan Serrà* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.14661)] \
26 Oct 2022

**Hierarchical Diffusion Models for Singing Voice Neural Vocoder** \
*Naoya Takahashi, Mayank Kumar, Singh, Yuki Mitsufuji* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.07508)] \
14 Oct 2022

**DDSP-based Singing Vocoders: A New Subtractive-based Synthesizer and A Comprehensive Evaluation** \
*Da-Yi Wu<sup>1</sup>, Wen-Yi Hsiao<sup>1</sup>, Fu-Rong Yang, Oscar Friedman, Warren Jackson, Scott Bruzenak, Yi-Wen Liu, Yi-Hsuan Yang* \
ISMIR 2022. [[Paper](https://arxiv.org/abs/2208.04756)] [[Github](https://github.com/YatingMusic/ddsp-singing-vocoders/)] \
9 Aug 2022

**ProDiff: Progressive Fast Diffusion Model For High-Quality Text-to-Speech** \
*Rongjie Huang<sup>1</sup>, Zhou Zhao, Huadai Liu<sup>1</sup>, Jinglin Liu, Chenye Cui, Yi Ren* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.06389)] [[Project](https://prodiff.github.io/)] \
13 Jul 2022

**Adversarial Audio Synthesis with Complex-valued Polynomial Networks** \
*Yongtao Wu, Grigorios G Chrysos, Volkan Cevher* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.06811)] \
14 Jun 2022

**BinauralGrad: A Two-Stage Conditional Diffusion Probabilistic Model for Binaural Audio Synthesis** \
*Yichong Leng, Zehua Chen, Junliang Guo, Haohe Liu, Jiawei Chen, Xu Tan, Danilo Mandic, Lei He, Xiang-Yang Li, Tao Qin, Sheng Zhao, Tie-Yan Liu* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2205.14807)] [[Github](https://speechresearch.github.io/binauralgrad/)] \
30 May 2022

**FastDiff: A Fast Conditional Diffusion Model for High-Quality Speech Synthesis** \
*Rongjie Huang<sup>1</sup>, Max W. Y. Lam<sup>1</sup>, Jun Wang, Dan Su, Dong Yu, Yi Ren, Zhou Zhao* \
IJCAI 2022. [[Paper](https://arxiv.org/abs/2204.09934)] [[Project](https://fastdiff.github.io/)] [[Github](https://github.com/Rongjiehuang/FastDiff)] \
21 Apr 2022

**SpecGrad: Diffusion Probabilistic Model based Neural Vocoder with Adaptive Noise Spectral Shaping** \
*Yuma Koizumi, Heiga Zen, Kohei Yatabe, Nanxin Chen, Michiel Bacchiani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.16749)] \
31 Mar 2022

**BDDM: Bilateral Denoising Diffusion Models for Fast and High-Quality Speech Synthesis** \
*Max W. Y. Lam, Jun Wang, Dan Su, Dong Yu* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2203.13508)] [[Github](https://github.com/tencent-ailab/bddm)] \
25 Mar 2022

**ItôWave: Itô Stochastic Differential Equation Is All You Need For Wave Generation** \
*Shoule Wu<sup>1</sup>, Ziqiang Shi<sup>1</sup>* \
CoRR 2022. [[Paper](https://arxiv.org/abs/2201.12519)] [[Project](https://wushoule.github.io/ItoAudio/)] \
29 Jan 2022

**Itô-Taylor Sampling Scheme for Denoising Diffusion Probabilistic Models using Ideal Derivatives** \
*Hideyuki Tachibana, Mocho Go, Muneyoshi Inahara, Yotaro Katayama, Yotaro Watanabe* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.13339)] \
26 Dec 2021

**Denoising Diffusion Gamma Models** \
*Eliya Nachmani<sup>1</sup>, Robin San Roman<sup>1</sup>, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.05948)] \
10 Oct 2021

**Variational Diffusion Models** \
*Diederik P. Kingma, Tim Salimans, Ben Poole, Jonathan Ho* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2107.00630)] [[Github](https://github.com/revsic/jax-variational-diffwave)] \
1 Jul 2021 

**CRASH: Raw Audio Score-based Generative Modeling for Controllable High-resolution Drum Sound Synthesis** \
*Simon Rouard<sup>1</sup>, Gaëtan Hadjeres<sup>1</sup>* \
ISMIR 2021. [[Paper](https://arxiv.org/abs/2106.07431)] [[Project](https://crash-diffusion.github.io/crash/)] \
14 Jun 2021

**PriorGrad: Improving Conditional Denoising Diffusion Models with Data-Driven Adaptive Prior** \
*Sang-gil Lee, Heeseung Kim, Chaehun Shin, Xu Tan, Chang Liu, Qi Meng, Tao Qin, Wei Chen, Sungroh Yoon, Tie-Yan Liu* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2106.06406)] [[Project](https://speechresearch.github.io/priorgrad/)] \
11 Jun 2021 

**ItôTTS and ItôWave: Linear Stochastic Differential Equation Is All You Need For Audio Generation** \
*Shoule Wu<sup>1</sup>, Ziqiang Shi<sup>1</sup>* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2105.07583)] [[Project](https://wushoule.github.io/ItoAudio/)] \
17 May 2021

**DiffSinger: Singing Voice Synthesis via Shallow Diffusion Mechanism** \
*Jinglin Liu<sup>1</sup>, Chengxi Li<sup>1</sup>, Yi Ren<sup>1</sup>, Feiyang Chen, Peng Liu, Zhou Zhao* \
AAAI 2022. [[Paper](https://arxiv.org/abs/2105.02446)] [[Project](https://diffsinger.github.io/)] [[Github](https://github.com/keonlee9420/DiffSinger)] \
6 May 2021

**Symbolic Music Generation with Diffusion Models** \
*Gautam Mittal, Jesse Engel, Curtis Hawthorne, Ian Simon* \
ISMIR 2021. [[Paper](https://arxiv.org/abs/2103.16091)] [[Github](https://github.com/magenta/symbolic-music-diffusion)] \
30 Mar 2021 

**DiffWave: A Versatile Diffusion Model for Audio Synthesis** \
*Zhifeng Kong, Wei Ping, Jiaji Huang, Kexin Zhao, Bryan Catanzaro* \
ICLR 2021 [[Paper](https://arxiv.org/abs/2009.09761)] [[Github](https://diffwave-demo.github.io/)] \
21 Sep 2020 

**WaveGrad: Estimating Gradients for Waveform Generation** \
*Nanxin Chen, Yu Zhang, Heiga Zen, Ron J. Weiss, Mohammad Norouzi, William Chan*\
ICLR 2021. [[Paper](https://arxiv.org/abs/2009.00713)] [[Project](https://wavegrad.github.io/)] [[Github](https://github.com/ivanvovk/WaveGrad)] \
2 Sep 2020 


### Audio Conversion

**DiffSVC: A Diffusion Probabilistic Model for Singing Voice Conversion**  \
*Songxiang Liu<sup>1</sup>, Yuewen Cao<sup>1</sup>, Dan Su, Helen Meng* \
IEEE 2021. [[Paper](https://arxiv.org/abs/2105.13871)] [[Github](https://github.com/liusongxiang/diffsvc)] \
28 May 2021

**Diffusion-Based Voice Conversion with Fast Maximum Likelihood Sampling Scheme** \
*Vadim Popov, Ivan Vovk, Vladimir Gogoryan, Tasnima Sadekova, Mikhail Kudinov, Jiansheng Wei* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2109.13821)] [[Project](https://diffvc-fast-ml-solver.github.io/)] \
28 Sep 2021

### Audio Enhancement


**Unsupervised vocal dereverberation with diffusion-based generative models** \
*Koichi Saito, Naoki Murata, Toshimitsu Uesaka, Chieh-Hsin Lai, Yuhta Takida, Takao Fukui, Yuki Mitsufuji* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.04124)] \
8 Nov 2022

**DiffPhase: Generative Diffusion-based STFT Phase Retrieval** \
*Tal Peer, Simon Welker, Timo Gerkmann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.04332)] \
8 Nov 2022


**Cold Diffusion for Speech Enhancement** \
*Hao Yen, François G. Germain, Gordon Wichern, Jonathan Le Roux* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.02527)] \
4 Nov 2022


**Analysing Diffusion-based Generative Approaches versus Discriminative Approaches for Speech Restoration** \
*Jean-Marie Lemercier, Julius Richter, Simon Welker, Timo Gerkmann* \
ICASSP [[Paper](https://arxiv.org/abs/2211.02397)] [[Project](https://www.inf.uni-hamburg.de/en/inst/ab/sp/publications/sgmse-multitask.html)] [[Github](https://github.com/sp-uhh/sgmse)] \
4 Nov 2022

**SRTNet: Time Domain Speech Enhancement Via Stochastic Refinement** \
*Zhibin Qiu, Mengfan Fu, Yinfeng Yu, LiLi Yin, Fuchun Sun, Hao Huang* \
ICASSP 2022. [[Paper](https://arxiv.org/abs/2210.16805)] [[Github](https://github.com/zhibinQiu/SRTNet)] \
30 Oct 2022

**A Versatile Diffusion-based Generative Refiner for Speech Enhancement** \
*Ryosuke Sawata, Naoki Murata, Yuhta Takida, Toshimitsu Uesaka, Takashi Shibuya, Shusuke Takahashi, Yuki Mitsufuji* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.17287)] \
27 Oct 2022

**Conditioning and Sampling in Variational Diffusion Models for Speech Super-resolution** \
*Chin-Yun Yu, Sung-Lin Yeh, György Fazekas, Hao Tang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.15793)] [[Project](https://yoyololicon.github.io/diffwave-sr/)] [[Github](https://github.com/yoyololicon/diffwave-sr)] \
27 Oct 2022

**Solving Audio Inverse Problems with a Diffusion Model** \
*Eloi Moliner, Jaakko Lehtinen, Vesa Välimäki* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.15228)] \
27 Oct 2022

**Speech Enhancement and Dereverberation with Diffusion-based Generative Models** \
*Julius Richter, Simon Welker, Jean-Marie Lemercier, Bunlong Lay, Timo Gerkmann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.05830)] [[Project](https://www.inf.uni-hamburg.de/en/inst/ab/sp/publications/sgmse)] [[Github](https://github.com/sp-uhh/sgmse)] \
11 Aug 2022

**NU-Wave 2: A General Neural Audio Upsampling Model for Various Sampling Rates** \
*Seungu Han, Junhyeok Lee* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.08545)] [[Project](https://mindslab-ai.github.io/nuwave2/)] \
17 Jun 2022

**Universal Speech Enhancement with Score-based Diffusion** \
*Joan Serrà, Santiago Pascual, Jordi Pons, R. Oguz Araz, Davide Scaini* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.03065)] \
7 Jun 2022

**Speech Enhancement with Score-Based Generative Models in the Complex STFT Domain** \
*Simon Welker, Julius Richter, Timo Gerkmann* \
InterSpeech 2022. [[Paper](https://arxiv.org/abs/2203.17004)]  [[Github](https://github.com/sp-uhh/sgmse)] \
31 Mar 2022

**Conditional Diffusion Probabilistic Model for Speech Enhancement** \
*Yen-Ju Lu, Zhong-Qiu Wang, Shinji Watanabe, Alexander Richard, Cheng Yu, Yu Tsao* \
IEEE 2022. [[Paper](https://arxiv.org/abs/2202.05256)] [[Github](https://github.com/neillu23/cdiffuse)] \
10 Feb 2022

**A Study on Speech Enhancement Based on Diffusion Probabilistic Model** \
*Yen-Ju Lu<sup>1</sup>, Yu Tsao<sup>1</sup>, Shinji Watanabe* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2107.11876)] \
25 Jul 2021


**Restoring degraded speech via a modified diffusion model** \
*Jianwei Zhang, Suren Jayasuriya, Visar Berisha* \
Interspeech 2021. [[Paper](https://arxiv.org/abs/2104.11347)] \
22 Apr 2021

**NU-Wave: A Diffusion Probabilistic Model for Neural Audio Upsampling**  \
*Junhyeok Lee, Seungu Han* \
Interspeech 2021. [[Paper](https://arxiv.org/abs/2104.02321)] [[Project](https://mindslab-ai.github.io/nuwave/)] [[Github](https://github.com/mindslab-ai/nuwave)] \
6 Apr 2021


### Text-to-Speech

**Any-speaker Adaptive Text-To-Speech Synthesis with Diffusion Models** \
*Minki Kang, Dongchan Min, Sung Ju Hwang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09383)] [[Project](https://nardien.github.io/grad-stylespeech-demo/)] \
17 Nov 2022

**EmoDiff: Intensity Controllable Emotional Text-to-Speech with Soft-Label Guidance** \
*Yiwei Guo, Chenpeng Du, Xie Chen, Kai Yu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09496)] [[Project](https://cantabile-kwok.github.io/EmoDiff-intensity-ctrl/)] \
17 Nov 2022

**NoreSpeech: Knowledge Distillation based Conditional Diffusion Model for Noise-robust Expressive TTS** \
*Dongchao Yang, Songxiang Liu, Jianwei Yu, Helin Wang, Chao Weng, Yuexian Zou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.02448)] \
4 Nov 2022

**WaveFit: An Iterative and Non-autoregressive Neural Vocoder based on Fixed-Point Iteration** \
*Yuma Koizumi, Kohei Yatabe, Heiga Zen, Michiel Bacchiani* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.01029)] [[Project](https://google.github.io/df-conformer/wavefit/)] \
3 Oct 2022

**Diffsound: Discrete Diffusion Model for Text-to-sound Generation** \
*Dongchao Yang, Jianwei Yu, Helin Wang, Wen Wang, Chao Weng, Yuexian Zou, Dong Yu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.09983)] [[Project](http://dongchaoyang.top/text-to-sound-synthesis-demo/)] \
20 Jul 2022


**Zero-Shot Voice Conditioning for Denoising Diffusion TTS Models** \
*Alon Levkovitch, Eliya Nachmani, Lior Wolf* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.02246)] [[Project](https://alonlevko.github.io/ilvr-tts-diff)] \
5 Jun 2022

**Guided-TTS 2: A Diffusion Model for High-quality Adaptive Text-to-Speech with Untranscribed Data** \
*Sungwon Kim<sup>1</sup>, Heeseung Kim<sup>1</sup>, Sungroh Yoon* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.15370)] [[Project](https://ksw0306.github.io/guided-tts2-demo/)] \
30 May 2022

**InferGrad: Improving Diffusion Models for Vocoder by Considering Inference in Training** \
*Zehua Chen, Xu Tan, Ke Wang, Shifeng Pan, Danilo Mandic, Lei He, Sheng Zhao* \
ICASSP 2022. [[Paper](https://arxiv.org/abs/2202.03751)] \
8 Feb 2022

**DiffGAN-TTS: High-Fidelity and Efficient Text-to-Speech with Denoising Diffusion GANs** \
*Songxiang Liu, Dan Su, Dong Yu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.11972)] [[Github](https://github.com/keonlee9420/DiffGAN-TTS)] \
28 Jan 2022

**Guided-TTS:Text-to-Speech with Untranscribed Speech** \
*Heeseung Kim, Sungwon Kim, Sungroh Yoon* \
ICML 2021. [[Paper](https://arxiv.org/abs/2111.11755)] \
32 Nov 2021



**EdiTTS: Score-based Editing for Controllable Text-to-Speech** \
*Jaesung Tae<sup>1</sup>, Hyeongju Kim<sup>1</sup>, Taesu Kim* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.02584)] [[Project](https://editts.github.io/)] [[Github](https://github.com/neosapience/EdiTTS)] \
6 Oct 2021

**WaveGrad 2: Iterative Refinement for Text-to-Speech Synthesis** \
*Nanxin Chen, Yu Zhang, Heiga Zen, Ron J. Weiss, Mohammad Norouzi, Najim Dehak, William Chan* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.09660)] [[Project](https://mindslab-ai.github.io/wavegrad2/)] [[Github](https://github.com/keonlee9420/WaveGrad2)] [[Github2](https://github.com/mindslab-ai/wavegrad2)] \
17 Jun 2021 

**Grad-TTS: A Diffusion Probabilistic Model for Text-to-Speech** \
*Vadim Popov<sup>1</sup>, Ivan Vovk<sup>1</sup>, Vladimir Gogoryan, Tasnima Sadekova, Mikhail Kudinov* \
ICML 2021. [[Paper](https://arxiv.org/abs/2105.06337)] [[Project](https://grad-tts.github.io/)] [[Github](https://github.com/huawei-noah/Speech-Backbones/tree/main/Grad-TTS)] \
13 May 2021

**DiffSinger: Singing Voice Synthesis via Shallow Diffusion Mechanism** \
*Jinglin Liu<sup>1</sup>, Chengxi Li<sup>1</sup>, Yi Ren<sup>1</sup>, Feiyang Chen, Peng Liu, Zhou Zhao* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2105.02446)] [[Project](https://diffsinger.github.io/)] [[Github](https://github.com/keonlee9420/DiffSinger)] \
6 May 2021

**Diff-TTS: A Denoising Diffusion Model for Text-to-Speech**  \
*Myeonghun Jeong, Hyeongju Kim, Sung Jun Cheon, Byoung Jin Choi, Nam Soo Kim* \
Interspeech 2021. [[Paper](https://arxiv.org/abs/2104.01409)] \
3 Apr 2021

### Music Generation

**Mandarin Singing Voice Synthesis with Denoising Diffusion Probabilistic Wasserstein GAN** \
*Yin-Ping Cho, Yu Tsao, Hsin-Min Wang, Yi-Wen Liu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.10446)] [[Project](https://yinping-cho.github.io/diffwgansvs.github.io/)] \
21 Sep 2022


**Multi-instrument Music Synthesis with Spectrogram Diffusion** \
*Curtis Hawthorne, Ian Simon, Adam Roberts, Neil Zeghidour, Josh Gardner, Ethan Manilow, Jesse Engel* \
ISMIR 2022. [[Paper](https://arxiv.org/abs/2206.05408)] \
11 Jun 2022

### Separation
**Diffusion-based Generative Speech Source Separation** \
*Robin Scheibler, Youna Ji, Soo-Whan Chung, Jaeuk Byun, Soyeon Choe, Min-Seok Choi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.17327)] \
31 Oct 2022

**Instrument Separation of Symbolic Music by Explicitly Guided Diffusion Model** \
*Sangjun Han, Hyeongrae Ihm, DaeHan Ahn, Woohyung Lim* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.02696)] \
5 Sep 2022


## Natural Language

### Natural Language Generation

**DiffusionBERT: Improving Generative Masked Language Models with Diffusion Models** \
*Zhengfu He<sup>1</sup>, Tianxiang Sun<sup>1</sup>, Kuanning Wang, Xuanjing Huang, Xipeng Qiu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.15029)] [[Github](https://github.com/Hzfinfdu/Diffusion-BERT)] \
28 Nov 2022

**Continuous diffusion for categorical data** \
*Sander Dieleman, Laurent Sartran, Arman Roshannai, Nikolay Savinov, Yaroslav Ganin, Pierre H. Richemond, Arnaud Doucet, Robin Strudel, Chris Dyer, Conor Durkan, Curtis Hawthorne, Rémi Leblond, Will Grathwohl, Jonas Adler* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.15089)] \
28 Nov 2022


**Self-conditioned Embedding Diffusion for Text Generation** \
*Robin Strudel, Corentin Tallec, Florent Altché, Yilun Du, Yaroslav Ganin, Arthur Mensch, Will Grathwohl, Nikolay Savinov, Sander Dieleman, Laurent Sifre, Rémi Leblond* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.04236)] \
8 Nov 2022

**DiffusER: Discrete Diffusion via Edit-based Reconstruction** \
*Machel Reid, Vincent J. Hellendoorn, Graham Neubig* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.16886)] \
30 Oct 2022

**SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control** \
*Xiaochuang Han, Sachin Kumar, Yulia Tsvetkov* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.17432)] \
31 Oct 2022


**DiffuSeq: Sequence to Sequence Text Generation with Diffusion Models** \
*Shansan Gong<sup>1</sup>, Mukai Li<sup>1</sup>, Jiangtao Feng, Zhiyong Wu, LingPeng Kong* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.08933)] \
17 Oct 2022

**Composable Text Controls in Latent Space with ODEs** \
*Guangyi Liu, Zeyu Feng, Yuan Gao, Zichao Yang, Xiaodan Liang, Junwei Bao, Xiaodong He, Shuguang Cui, Zhen Li, Zhiting Hu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.00638)] [[Github](https://github.com/guangyliu/LatentOps)] \
1 Aug 2022


**Structured Denoising Diffusion Models in Discrete State-Spaces** \
*Jacob Austin<sup>1</sup>, Daniel D. Johnson<sup>1</sup>, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2107.03006)] \
7 Jul 2021 

**Latent Diffusion Energy-Based Model for Interpretable Text Modeling** \
*Peiyu Yu, Sirui Xie, Xiaojian Ma, Baoxiong Jia, Bo Pang, Ruigi Gao, Yixin Zhu, Song-Chun Zhu, Ying Nian Wu* \
ICML 2022. [[Paper](https://arxiv.org/abs/2206.05895)] [[Github](https://github.com/yuPeiyu98/LDEBM)] \
13 Jun 2022

**Diffusion-LM Improves Controllable Text Generation** \
*Xiang Lisa Li, John Thickstun, Ishaan Gulrajani, Percy Liang, Tatsunori B. Hashimoto* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2205.14217)] [[Github](https://github.com/XiangLi1999/Diffusion-LM)] \
27 May 2022


**Step-unrolled Denoising Autoencoders for Text Generation** \
*Nikolay Savinov, Junyoung Chung, Mikolaj Binkowski, Erich Elsen, Aaron van den Oord* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2112.06749)] [[Github](https://github.com/vvvm23/sundae)] \
13 Dec 2021


**Zero-Shot Translation using Diffusion Models** \
*Eliya Nachmani<sup>1</sup>, Shaked Dovrat<sup>1</sup>* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.01471)] \
2 Nov 2021

## Tabular and Time Series

### Generation

**TabDDPM: Modelling Tabular Data with Diffusion Models** \
*Akim Kotelnikov, Dmitry Baranchuk, Ivan Rubachev, Artem Babenko* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15421)] [[Github](https://github.com/rotot0/tab-ddpm)] \
30 Sep 2022

### Forecasting

**Modeling Temporal Data as Continuous Functions with Process Diffusion** \
*Marin Biloš, Kashif Rasul, Anderson Schneider, Yuriy Nevmyvaka, Stephan Günnemann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.02590)] \
4 Nov 2022

**Diffusion-based Time Series Imputation and Forecasting with Structured State Space Models** \
*Juan Miguel Lopez Alcaraz, Nils Strodthoff* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09399)] [[Github](https://github.com/AI4HealthUOL/SSSD)] \
19 Aug 2022

**ScoreGrad: Multivariate Probabilistic Time Series Forecasting with Continuous Energy-based Generative Models** \
*Tijin Yan, Hongwei Zhang, Tong Zhou, Yufeng Zhan, Yuanqing Xia* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.10121)] [[Github](https://github.com/yantijin/ScoreGradPred)] \
18 Jun 2021

**Autoregressive Denoising Diffusion Models for Multivariate Probabilistic Time Series Forecasting** \
*Kashif Rasul, Calvin Seward, Ingmar Schuster, Roland Vollgraf* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2101.12072)] [[Github](https://github.com/zalandoresearch/pytorch-ts)] \
2 Feb 2021 

### Imputation


**Modeling Temporal Data as Continuous Functions with Process Diffusion** \
*Marin Biloš, Kashif Rasul, Anderson Schneider, Yuriy Nevmyvaka, Stephan Günnemann* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.02590)] \
4 Nov 2022

**Diffusion models for missing value imputation in tabular data** \
*Shuhan Zheng, Nontawat Charoenphakdee* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2210.17128)] \
31 Oct 2022

**Neural Markov Controlled SDE: Stochastic Optimization for Continuous-Time Data** \
*Sung Woo Park, Kyungjae Lee, Junseok Kwon* \
ICLR 2022. [[Paper](https://openreview.net/forum?id=7DI6op61AY)] \
29 Sep 2021

**Diffusion-based Time Series Imputation and Forecasting with Structured State Space Models** \
*Juan Miguel Lopez Alcaraz, Nils Strodthoff* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09399)] [[Github](https://github.com/AI4HealthUOL/SSSD)] \
19 Aug 2022

**CSDI: Conditional Score-based Diffusion Models for Probabilistic Time Series Imputation** \
*Yusuke Tashiro, Jiaming Song, Yang Song, Stefano Ermon* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2107.03502)] [[Github](https://github.com/ermongroup/csdi)]\
7 Jul 2021 


## Graph

### Graph Generation

**NVDiff: Graph Generation through the Diffusion of Node Vectors** \
*Cristian Sbrolli, Paolo Cudrano, Matteo Frosi, Matteo Matteucci* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.10794)] \
20 Nov 2022

**Fast Graph Generative Model via Spectral Diffusion** \
*Tianze Luo, Zhanfeng Mo, Sinno Jialin Pan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08892)] \
16 Nov 2022

**Diffusion Models for Graphs Benefit From Discrete State Spaces** \
*Kilian Konstantin Haefeli, Karolis Martinkus, Nathanaël Perraudin, Roger Wattenhofer* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2210.01549)] \
4 Oct 2022

**DiGress: Discrete Denoising diffusion for graph generation** \
*Clement Vignac<sup>1</sup>, Igor Krawczuk<sup>1</sup>, Antoine Siraudin, Bohan Wang, Volkan Cevher, Pascal Frossard* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14734)] \
29 Sep 2022

**Permutation Invariant Graph Generation via Score-Based Generative Modeling** \
*Chenhao Niu, Yang Song, Jiaming Song, Shengjia Zhao, Aditya Grover, Stefano Ermon* \
AISTATS 2021. [[Paper](https://arxiv.org/abs/2003.00638)] [[Github](https://github.com/ermongroup/GraphScoreMatching)] \
2 Mar 2020

### Molecular and Material Generation

**DiffBP: Generative Diffusion of 3D Molecules for Target Protein Binding** \
*Haitao Lin<sup>1</sup>, Yufei Huang<sup>1</sup>, Meng Liu, Xuanjing Li, Shuiwang Ji, Stan Z. Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.11214)] \
21 Nov 2022

**ParticleGrid: Enabling Deep Learning using 3D Representation of Materials** \
*Shehtab Zaman, Ethan Ferguson, Cecile Pereira, Denis Akhiyarov, Mauricio Araya-Polo, Kenneth Chiu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.08506)] \
15 Nov 2022

**Structure-based Drug Design with Equivariant Diffusion Models** \
*Arne Schneuing<sup>1</sup>, Yuanqi Du<sup>1</sup>, Charles Harris, Arian Jamasb, Ilia Igashov, Weitao Du, Tom Blundell, Pietro Lió, Carla Gomes, Max Welling, Michael Bronstein, Bruno Correia* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.13695)] \
24 Oct 2022

**Protein Sequence and Structure Co-Design with Equivariant Translation** \
*Chence Shi, Chuanrui Wang, Jiarui Lu, Bozitao Zhong, Jian Tang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.08761)] \
17 Oct 2022

**Equivariant 3D-Conditional Diffusion Models for Molecular Linker Design** \
*Ilia Igashov, Hannes Stärk, Clément Vignac, Victor Garcia Satorras, Pascal Frossard, Max Welling, Michael Bronstein, Bruno Correia* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05274)] \
11 Oct 2022

**Dynamic-Backbone Protein-Ligand Structure Prediction with Multiscale Generative Diffusion Models** \
*Zhuoran Qiao, Weili Nie, Arash Vahdat, Thomas F. Miller III, Anima Anandkumar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15171)] \
30 Sep 2022

**Equivariant Energy-Guided SDE for Inverse Molecular Design** \
*Fan Bao<sup>1</sup>, Min Zhao<sup>1</sup>, Zhongkai Hao, Peiyao Li, Chongxuan Li, Jun Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15408)] \
30 Sep 2022

**Protein structure generation via folding diffusion** \
*Kevin E. Wu, Kevin K. Yang, Rianne van den Berg, James Y. Zou, Alex X. Lu, Ava P. Amini* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15611)] \
30 Sep 2022

**MDM: Molecular Diffusion Model for 3D Molecule Generation** \
*Lei Huang, Hengtong Zhang, Tingyang Xu, Ka-Chun Wong* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.05710)] \
13 Sep 2022

**Diffusion-based Molecule Generation with Informative Prior Bridges** \
*Lemeng Wu<sup>1</sup>, Chengyue Gong<sup>1</sup>, Xingchao Liu, Mao Ye, Qiang Liu* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.00865)] \
2 Sep 2022


**Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models** \
*Shitong Luo<sup>1</sup>, Yufeng Su<sup>1</sup>, Xingang Peng, Sheng Wang, Jian Peng, Jianzhu Ma* \
BioRXiv 2022. [[Paper](https://www.biorxiv.org/content/10.1101/2022.07.10.499510v1)] \
11 July 2022

**Data-driven discovery of novel 2D materials by deep generative models** \
*Peder Lyngby, Kristian Sommer Thygesen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.12159)] \
24 Jun 2022

**Score-based Generative Models for Calorimeter Shower Simulation** \
*Vinicius Mikuni, Benjamin Nachman* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.11898)] \
17 Jun 2022

**Diffusion probabilistic modeling of protein backbones in 3D for the motif-scaffolding problem** \
*Brian L. Trippe<sup>1</sup>, Jason Yim<sup>1</sup>, Doug Tischer, Tamara Broderick, David Baker, Regina Barzilay, Tommi Jaakkola* \
CoRR 2022. [[Paper](https://arxiv.org/abs/2206.04119)] \
8 Jun 2022'

**Torsional Diffusion for Molecular Conformer Generation** \
*Bowen Jing, Gabriele Corso, Regina Barzilay, Tommi S. Jaakkola* \
ICLR Workshop 2022. [[Paper](https://arxiv.org/abs/2206.01729)] [[Github](https://github.com/gcorso/torsional-diffusion)] \
1 Jun 2022

**Protein Structure and Sequence Generation with Equivariant Denoising Diffusion Probabilistic Models** \
*Namrata Anand, Tudor Achim* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.15019)] [[Project](https://nanand2.github.io/proteins/)] [[Github](https://github.com/lucidrains/ddpm-ipa-protein-generation)] \
26 May 2022

**A Score-based Geometric Model for Molecular Dynamics Simulations** \
*Fang Wu<sup>1</sup>, Qiang Zhang<sup>1</sup>, Xurui Jin, Yinghui Jiang, Stan Z. Li* \
CoRR 2022. [[Paper](https://arxiv.org/abs/2204.08672)] \
19 Apr 2022

**Equivariant Diffusion for Molecule Generation in 3D** \
*Emiel Hoogeboom<sup>1</sup>, Victor Garcia Satorras<sup>1</sup>, Clément Vignac, Max Welling* \
ICML 2022. [[Paper](https://arxiv.org/abs/2203.17003)] [[Github](https://github.com/ehoogeboom/e3_diffusion_for_molecules)] \
31 Mar 2022

**GeoDiff: a Geometric Diffusion Model for Molecular Conformation Generation** \
*Minkai Xu, Lantao Yu, Yang Song, Chence Shi, Stefano Ermon, Jian Tang* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2203.02923)] [[Github](https://github.com/MinkaiXu/GeoDiff)] \
6 Mar 2022


**Crystal Diffusion Variational Autoencoder for Periodic Material Generation** \
*Tian Xie<sup>1</sup>, Xiang Fu<sup>1</sup>, Octavian-Eugen Ganea<sup>1</sup>, Regina Barzilay, Tommi Jaakkola*\
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2110.06197)] [[Github](https://github.com/txie-93/cdvae)] \
12 Oct 2021


**Predicting Molecular Conformation via Dynamic Graph Score Matching** \
*Shitong Luo, Chence Shi, Minkai Xu, Jian Tang* \
NeurIPS 2021. [[Paper](https://proceedings.neurips.cc/paper/2021/hash/a45a1d12ee0fb7f1f872ab91da18f899-Abstract.html)] \
22 May 2021

## Reinforcement Learning

**Is Conditional Generative Modeling all you need for Decision-Making?** \
*Anurag Ajay<sup>1</sup>, Yilun Du<sup>1</sup>, Abhi Gupta<sup>1</sup>, Joshua Tenenbaum, Tommi Jaakkola, Pulkit Agrawal* \
arXiv 2022. [[Paper]()] \
28 Nov 2022

**LAD: Language Augmented Diffusion for Reinforcement Learning** \
*Edwin Zhang, Yujie Lu, William Wang, Amy Zhang* \
NeurIPS Workshop 2022. [[Paper](https://arxiv.org/abs/2210.15629)] \
27 Oct 2022



**Diffusion Policies as an Expressive Policy Class for Offline Reinforcement Learning** \
*Zhendong Wang, Jonathan J Hunt, Mingyuan Zhou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.06193)] [[Github](https://github.com/zhendong-wang/diffusion-policies-for-offline-rl)] \
12 Oct 2022


**Offline Reinforcement Learning via High-Fidelity Generative Behavior Modeling** \
*Huayu Chen, Cheng Lu, Chengyang Ying, Hang Su, Jun Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14548)] \
29 Sep 2022



**Planning with Diffusion for Flexible Behavior Synthesis** \
*Michael Janner, Yilun Du, Joshua B. Tenenbaum, Sergey Levine* \
ICML 2022. [[Paper](https://arxiv.org/abs/2205.09991)] [[Github](https://github.com/jannerm/diffuser)] \
20 May 2022


## Theory

**Neural Langevin Dynamics: towards interpretable Neural Stochastic Differential Equations** \
*Simon M. Koop, Mark A. Peletier, Jacobus W. Portegies, Vlado Menkovski* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09537)] \
17 Nov 2022

**Improved Analysis of Score-based Generative Modeling: User-Friendly Bounds under Minimal Smoothness Assumptions** \
*Hongrui Chen, Holden Lee, Jianfeng Lu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.01916)] \
3 Nov 2022

**Diffusion Models for Causal Discovery via Topological Ordering** \
*Pedro Sanchez, Xiao Liu, Alison Q O'Neil, Sotirios A. Tsaftaris* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.06201)] [[Github](https://github.com/vios-s/DiffAN)] \
12 Oct 2022

**Regularizing Score-based Models with Score Fokker-Planck Equations** \
*Chieh-Hsin Lai, Yuhta Takida, Naoki Murata, Toshimitsu Uesaka, Yuki Mitsufuji, Stefano Ermon* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.04296)] \
9 Oct 2022

**Sequential Neural Score Estimation: Likelihood-Free Inference with Conditional Score Based Diffusion Models** \
*Louis Sharrock, Jack Simons, Song Liu, Mark Beaumont* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.04872)] \
10 Oct 2022

**Analyzing Diffusion as Serial Reproduction** \
*Raja Marjieh, Ilia Sucholutsky, Thomas A. Langlois, Nori Jacoby, Thomas L. Griffiths* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.14821)] \
29 Sep 2022

**Convergence of score-based generative modeling for general data distributions** \
*Holden Lee, Jianfeng Lu, Yixin Tan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.12381)] \
26 Sep 2022

**Sampling is as easy as learning the score: theory for diffusion models with minimal data assumptions** \
*Sitan Chen, Sinho Chewi, Jerry Li, Yuanzhi Li, Adil Salim, Anru R. Zhang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.11215)] \
22 Sep 2022

**Riemannian Diffusion Models** \
*Chin-Wei Huang, Milad Aghajohari, Avishek Joey Bose, Prakash Panangaden, Aaron Courville* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2208.07949)] \
16 Aug 2022

**Convergence of denoising diffusion models under the manifold hypothesis** \
*Valentin De Bortoli* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.05314)] \
10 Aug 2022

**Theory and Algorithms for Diffusion Processes on Riemannian Manifolds** \
*Bowen Jing, Gabriele Corso, Jeffrey Chang, Regina Barzilay, Tommi Jaakkola* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.01729)] [[Github](https://github.com/gcorso/torsional-diffusion)] \
1 Jun 2022

**Riemannian Score-Based Generative Modeling** \
*Valentin De Bortoli<sup>1</sup>, Emile Mathieu<sup>1</sup>, Michael Hutchinson, James Thornton, Yee Whye Teh, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.02763)] \
6 Feb 2022

**Interpreting diffusion score matching using normalizing flow** \
*Wenbo Gong<sup>1</sup>, Yingzhen Li<sup>1</sup>* \
ICML Workshop 2021. [[Paper](https://arxiv.org/abs/2107.10072)] \
21 Jul 2021

**A Connection Between Score Matching and Denoising Autoencoders** \
*Pascal Vincent* \
Neural Computation 2011. [[Paper](http://www.iro.umontreal.ca/~vincentp/Publications/smdae_techreport.pdf)] \
7 Jul 2011

**Bayesian Learning via Stochastic Gradient Langevin Dynamics** \
*Max Welling, Yee Whye Teh* \
ICML 2011. [[Paper](https://www.stats.ox.ac.uk/~teh/research/compstats/WelTeh2011a.pdf)] [[Github](https://github.com/JavierAntoran/Bayesian-Neural-Networks#stochastic-gradient-langevin-dynamics-sgld)] \
20 Apr 2022

## Applications

**Denoising Diffusion for Sampling SAT Solutions** \
*Karlis Freivalds, Sergejs Kozlovics* \
NeurIPS Workshop 2022. [[Paper](https://arxiv.org/abs/2212.00121)] \
30 Nov 2022

**Can denoising diffusion probabilistic models generate realistic astrophysical fields?** \
*Nayantara Mudur, Douglas P. Finkbeiner* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.12444)] \
22 Nov 2022

**StructDiffusion: Object-Centric Diffusion for Semantic Rearrangement of Novel Objects** \
*Weiyu Liu, Tucker Hermans, Sonia Chernova, Chris Paxton* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.04604)] \
8 Nov 2022

**Categorical SDEs with Simplex Diffusion** \
*Pierre H. Richemond, Sander Dieleman, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.14784)] \
26 Oct 2022

**From Points to Functions: Infinite-dimensional Representations in Diffusion Models** \
*Sarthak Mittal, Guillaume Lajoie, Stefan Bauer, Arash Mehrjou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.13774)] [[Github](https://github.com/sarthmit/traj_drl)] \
25 Oct 2022

**Graphically Structured Diffusion Models** \
*Christian Weilbach, William Harvey, Frank Wood* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.11633)] \
20 Oct 2022

**TransFusion: Transcribing Speech with Multinomial Diffusion** \
*Matthew Baas, Kevin Eloff, Herman Kamper* \
SACAIR 2022. [[Paper](https://arxiv.org/abs/2210.07677)] [[Github](https://github.com/RF5/transfusion-asr)] \
14 Oct 2022

**Human Joint Kinematics Diffusion-Refinement for Stochastic Motion Prediction** \
*Dong Wei, Huaijiang Sun, Bin Li, Jianfeng Lu, Weiqing Li, Xiaoning Sun, Shengxiang Hu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05976)] \
12 Oct 2022


**A generic diffusion-based approach for 3D human pose prediction in the wild** \
*Saeed Saadatnejad, Ali Rasekh, Mohammadreza Mofayezi, Yasamin Medghalchi, Sara Rajabzadeh, Taylor Mordan, Alexandre Alahi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05669)] \
11 Oct 2022


**DALL-E-Bot: Introducing Web-Scale Diffusion Models to Robotics** \
*Ivan Kapelyukh, Vitalis Vosylius, Edward Johns* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2210.02438)] \
5 Oct 2022


**Denoising Diffusion Error Correction Codes** \
*Yoni Choukroun, Lior Wolf* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2209.13533)] \
16 Sep 2022


**Vector Quantized Diffusion Model with CodeUnet for Text-to-Sign Pose Sequences Generation** \
*Pan Xie, Qipeng Zhang, Zexian Li, Hao Tang, Yao Du, Xiaohui Hu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09141)] \
19 Aug 2022

**TopoDiff: A Performance and Constraint-Guided Diffusion Model for Topology Optimization** \
*François Mazé, Faez Ahmed* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.09591)] \
20 Aug 2022

**DeScoD-ECG: Deep Score-Based Diffusion Model for ECG Baseline Wander and Noise Removal** \
*Huayu Li, Gregory Ditzler, Janet Roveda, Ao Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.00542)] \
31 Jul 2022

**Recommendation via Collaborative Diffusion Generative Model** \
*Joojo Walker, Ting Zhong, Fengli Zhang, Qiang Gao, Fan Zhou* \
KSEM 2022. [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-10989-8_47)] \
19 Jul 2022

**Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation** \
*Ye Zhu, Yu Wu, Kyle Olszewski, Jian Ren, Sergey Tulyakov, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07771)] [[Project](https://l-yezhu.github.io/CDCD/)] [[Github](https://github.com/L-YeZhu/CDCD)] \
15 Jun 2022

**CARD: Classification and Regression Diffusion Models** \
*Xizewen Han<sup>1</sup>, Huangjie Zheng<sup>1</sup>, Mingyuan Zhou* \
NeurIPS 2022. [[Paper](https://arxiv.org/abs/2206.07275)]  \
15 Jun 2022

**Neural Diffusion Processes** \
*Vincent Dutordoir, Alan Saul, Zoubin Ghahramani, Fergus Simpson* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.03992)] \
8 Jun 2022

**Deep Diffusion Models for Robust Channel Estimation** \
*Marius Arvinte, Jonathan I Tamir* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.08177)] [[Github](https://github.com/utcsilab/diffusion-channels)] \
16 Nov 2021

**Realistic galaxy image simulation via score-based generative models** \
*Michael J. Smith (Hertfordshire), James E. Geach, Ryan A. Jackson, Nikhil Arora, Connor Stone, Stéphane Courteau* \
MNRAS 2022. [[Paper](https://arxiv.org/abs/2111.01713)] \
2 Nov 2021

**Diffusion models for Handwriting Generation** \
*Troy Luhman<sup>1</sup>, Eric Luhman<sup>1</sup>* \
arXiv 2020. [[Paper](https://arxiv.org/abs/2011.06704)] [[Github](https://github.com/tcl9876/Diffusion-Handwriting-Generation)] \
13 Nov 2020 
