# Table of contents
 - [Introduction](#introduction) 
 - [Categories](#categories)	
	 - [Data-Independent Method](#data-independent-method)	 
	 - [Data-Dependent Method](#data-dependent-method)
		- [Unsupervised Hashing](#unsupervised-hashing)
		- [Supervised Hashing](#supervised-hashing)
		- [Ranking-based Hashing](#ranking-based-hashing)
		- [Multimodal Hashing](#multimodal-hashing)
		- [Deep Hashing](#deep-hashing)
		- [Online Hashing](#online-hashing)
		- [Quantization](#quantization)
 - [Dataset](#dataset)
	 - [MIR-FLICKR](#mirflickr)
	 - [NUS-WIDE](#nus-wide)
	 - [TINY](#tiny)
	 - [CIFAR](#cifar)
	 - [WIKI](#wiki)

## Introduction
---

## Categories
---
### Data-Independent Method
* Locality-Sensitive Hashing
	* Gionis et al.,1999. Similarity Search in High Dimensions via Hashing. \[[paper](http://www.cs.princeton.edu/courses/archive/spring13/cos598C/Gionis.pdf)\]
	* Andoni and Indyk, 2008. Near-optimal hashing algorithms for approximate nearest neighbor in high dimensions. \[[paper](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4031381)\]
	* Datar et al.,2004. Locality-Sensitive Hashing Scheme Based on p-Stable Distributions \[[paper](http://dl.acm.org/citation.cfm?id=997857)\]
* Kernelized Locality-Sensitive Hashing 	
	* Kulis and Grauman, 2009. Kernelized Locality-Sensitive Hashing for Scalable Image Search \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5459466)\]
	* Kulis et al., 2009. Fast Similarity Search for Learned Metrics. \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5204087)\]
* Shift Invariant Kernel Hashing
	* Raginsky and Lazebnik, 2009. Locality-Sensitive Binary Codes from Shift-Invariant Kernels. \[[paper](http://papers.nips.cc/paper/3749-locality-sensitive-binary-codes-from-shift-invariant-kernels)\]

### Data-Dependent Method

#### Unsupervised Hashing
* Spectral Hashing (SH) \[[paper](http://people.csail.mit.edu/torralba/publications/spectralhashing.pdf)\]\[[code](http://www.cs.huji.ac.il/~yweiss/SpectralHashing/sh.zip)\]
	* Weiss et al. Spectral Hashing. [*NIPS*], 2008
* Anchor Graph Hashing (AGH) \[[paper](http://www.ee.columbia.edu/~wliu/ICML11_AGH.pdf)\]\[[code](http://www.ee.columbia.edu/~wliu/)\]
	* Liu et al. Hashing with Graphs [*ICML*], 2010
* Iterative Quantization (ITQ) \[[paper](http://www.unc.edu/~yunchao/papers/CVPR11_a.pdf)\]\[[code](http://www.unc.edu/~yunchao/code/smallcode.zip)\] 
	* Gong and Lazebnik. Iterative quantization: A procerustean approach to learning binary codes. [*CVPR*], 2011
* Isotropic Hashing (IsoHash) \[[paper](http://cs.nju.edu.cn/lwj/paper/NIPS12-IsoHash.pdf)\]\[[code](http://cs.nju.edu.cn/lwj/code/IsoHash.zip)\] 
	* Kong and Li. Isotropic Hashing [*NIPS*], 2012
* Spherical Hashing (SPH) \[[paper](http://sglab.kaist.ac.kr/Spherical_Hashing/Spherical_Hashing.pdf)\]\[[C++ code](http://sglab.kaist.ac.kr/projects/Spherical_Hashing/static/media/uploads/Spherical_Hashing_Src_CPP.zip)\]\[[matlab code](http://sglab.kaist.ac.kr/projects/Spherical_Hashing/static/media/uploads/Spherical_Hashing_Src_Matlab.zip)\]\[[slide](http://sglab.kaist.ac.kr/Spherical_Hashing/SphericalHashing_Slide.pdf)\]
	* Jae-Pil Heo et al. Spherical Hashing [*CVPR*], 2012
* Harmonious Hashing (HamH) \[[paper](http://ijcai.org/papers13/Papers/IJCAI13-269.pdf)\] 
	* Xu et al. Harmonious Hashing [*IJCAI*], 2013
* Complementary Projection Hashing (CPH) \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6751141)\]
	* Jin et al. Comlementary Projection Hashing [*ICCV*], 2013
* Inductive Hashing on Manifolds \[[paper](https://sites.google.com/site/shenfumin/)\]\[[supplementary](https://sites.google.com/site/shenfumin/)\]\[[code](https://sites.google.com/site/shenfumin/)\]\[[poster](https://sites.google.com/site/shenfumin/)\]
	* Shen et al. Inductive Hashing on Manifolds [*CVPR*], 2013
* Bilinear Projection-based Binary Codes (BPBC) \[[paper](http://www.unc.edu/~yunchao/papers/CVPR13.pdf)\]\[[code](http://www.unc.edu/~yunchao/bpbc.htm)\]
	* Gong et al. Learning Binary Codes for High-Dimensional Data Using Bilinear Projections [*CVPR*], 2013
* Discrete Graph Hashing (DGH) \[[paper](http://www.ee.columbia.edu/~wliu/NIPS14_dgh.pdf)\]
	* Liu et al. Discrete Graph Hashing [*NIPS*], 2014
* Circulant Binary Embedding (CBE) \[[paper](http://www.felixyu.org/cbe.html)\]\[[code](http://www.felixyu.org/cbe.html)\]\[[slide](http://www.felixyu.org/cbe.html)\]
	* Yu et al. Circulant Binary Embedding [*ICML*], 2014
* Locality Linear Hashing (LLH) \[[paper](http://www.ee.columbia.edu/~xmwu/publications.html)\]\[[supplemental](http://www.ee.columbia.edu/~xmwu/publications.html)\]
	* Irie et al. Locality Linear Hashing for Extracting Non-Linear Manifolds [*CVPR*],2014
* Scalable Graph Hashing (SGH) \[[paper](http://cs.nju.edu.cn/lwj/paper/IJCAI15_SGH.pdf))\]\[[code](http://cs.nju.edu.cn/lwj/code/SGH.rar)\]
	* Jiang and Li. Scalable Graph Hashing with Feature Transformation [*IJCAI*], 2015

#### Supervised Hashing

#### Ranking-based Hashing

#### Multimodal Hashing

#### Deep Hashing

#### Online Hashing

#### Quantization

## Dataset
---

### MIR-FLICKR

### NUS-WIDE 

### TINY

### CIFAR

### WIKI

### MNIST

