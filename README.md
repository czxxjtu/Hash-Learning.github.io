# Table of contents
---
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
	 - [MIR-FLICKR](#mir-flickr)
	 - [FLICKR-8k](#flickr-8k)
	 - [FLICKR-25k](#flickr-25k)
	 - [NUS-WIDE](#nus-wide)
	 - [TINY](#tiny)
	 - [CIFAR](#cifar)
	 - [WIKI](#wiki)
	 - [Labelme](#labelme)
	 - [Sun-397](#sun-397)
	 - [IAPRTC12](#iaprtc12)
	 - [Imagenet](#imagenet)
	 - [SIFT-1M](#sift-1m)

# Introduction
---

# Categories
---
## Data-Independent Method
* Locality-Sensitive Hashing
	* Gionis et al.,1999. Similarity Search in High Dimensions via Hashing. \[[paper](http://www.cs.princeton.edu/courses/archive/spring13/cos598C/Gionis.pdf)\]
	* Andoni and Indyk, 2008. Near-optimal hashing algorithms for approximate nearest neighbor in high dimensions. \[[paper](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4031381)\]
	* Datar et al.,2004. Locality-Sensitive Hashing Scheme Based on p-Stable Distributions \[[paper](http://dl.acm.org/citation.cfm?id=997857)\]
* Kernelized Locality-Sensitive Hashing 	
	* Kulis and Grauman, 2009. Kernelized Locality-Sensitive Hashing for Scalable Image Search \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5459466)\]
	* Kulis et al., 2009. Fast Similarity Search for Learned Metrics. \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5204087)\]
* Shift Invariant Kernel Hashing
	* Raginsky and Lazebnik, 2009. Locality-Sensitive Binary Codes from Shift-Invariant Kernels. \[[paper](http://papers.nips.cc/paper/3749-locality-sensitive-binary-codes-from-shift-invariant-kernels)\]

## Data-Dependent Method

### Unsupervised Hashing
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
* Locality Linear Hashing (LLH) \[[paper](http://www.ee.columbia.edu/~xmwu/publications.html)\]\[[supplementary](http://www.ee.columbia.edu/~xmwu/publications.html)\]
	* Irie et al. Locality Linear Hashing for Extracting Non-Linear Manifolds [*CVPR*], 2014
* Scalable Graph Hashing (SGH) \[[paper](http://cs.nju.edu.cn/lwj/paper/IJCAI15_SGH.pdf))\]\[[code](http://cs.nju.edu.cn/lwj/code/SGH.rar)\]
	* Jiang and Li. Scalable Graph Hashing with Feature Transformation [*IJCAI*], 2015

### Supervised Hashing

### Ranking-based Hashing

* Hamming Distance Metric Learning (HDML) \[[paper](http://papers.nips.cc/paper/4808-hamming-distance-metric-learning.pdf)\] \[[code](https://github.com/norouzi/hdml)\]
	* Mohammad Norouzi, David J. Fleet, Ruslan Salakhutdinov. [*NIPS*], 2012
* Learning Hash Functions Using Column Generation (CGH)  \[[paper](http://www.jmlr.org/proceedings/papers/v28/li13a.pdf)\]\[[code](https://bitbucket.org/ningche001/column-generation-hashing/src/8d1c53f219cfc2b2f38e407079776e4f62c3dc89/CGHash/?at=master)\]
	* Xi Li, Guosheng Lin,Chunhua Shen,Anton van den Hengel,Anthony Dick. [*ICML*], 2013
* Order preserving Hashing for Approximate Nearest Neighbor Search (OPH) \[[paper](http://research.microsoft.com/en-us/um/people/jingdw/pubs%5CACMMM13-OrderPreservingHashing.pdf)\]
	* Jianfeng Wang, Jingdong Wang, and Nenghai Yu,Shipeng Li. [*ACM MM*], 2013
* Learning Hash Codes with Listwise Supervision (RSH) \[[paper](http://www.ee.columbia.edu/~wliu/ICCV13_rankhash.pdf)\]
	* Jun Wang, Wei Liu,Andy X. Sun,Yu-Gang Jiang. [*ICCV*], 2013
* Optimizing Ranking Measures for Compact Binary Code Learning (StructHash) \[[paper](http://link.springer.com/chapter/10.1007%2F978-3-319-10578-9_40)\]
	* Guosheng Lin, Chunhua Shen, Jianxin Wu. [*ECCV*], 2014	
* Ranking Preserving Hashing for Fast Similarity Search (RPH) \[[paper](http://ijcai.org/papers15/Papers/IJCAI15-549.pdf)\]
	* Qifan Wang,  Zhiwei Zhang,Luo Si. [*IJCAI*], 2015	

### Multimodal Hashing
* Composite Hashing (CHMIS-AW) \[[paper](https://www.cs.purdue.edu/homes/lsi/SIGIR_2011B.pdf)\]
	* Zhang et al. Composite Hashing with Multiple Information Sources [*ACM SIGIR*], 2011
* Cross View Hashing (CVH) \[[paper](http://research.microsoft.com/pubs/151205/ijcai11.pdf)\]
	* Kumar and Udupa. Learning hash functions for cross-view similarity search [*IJCAI*], 2011
* Co-Regularized Hashing (CRH) \[[paper](http://papers.nips.cc/paper/4793-co-regularized-hashing-for-multimodal-data.pdf)\]
	* Zhen and Yeung. Co-Regularized Hashing for Multimodal Data [*NIPS*], 2012
* Inter-Media Hashing (IMH) \[[paper](http://dl.acm.org/citation.cfm?id=2465274)\]
	* Song et al. Inter-Media Hashing for Large-Scale Retrieval from Heterogeneous Data Sources. [*SIGMOD*], 2013
* Relation-aware Heterogeneous Hashing (RaHH) \[[paper](http://media.cs.tsinghua.edu.cn/~multimedia/cuipeng/papers/HeterogeneousHashing.pdf)\] 
	* Ou et al. Comparing apples to oranges: a scalable solution with heterogeneous hashing [*KDD*], 2013
* Semantic Correlation Maximization (SCM) \[[paper](http://cs.nju.edu.cn/lwj/paper/AAAI14_SCM.pdf)\]\[[code](http://cs.nju.edu.cn/lwj/code/SCMHash_Release.zip)\]
	* Zhang and Li. Large-scale supervised multimodal hashing with semantic correlation maximization [*AAAI*], 2014
* Collective Matrix Factorization Hashing (CMFH) \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6909664&tag=1)\]
	* Ding et al. Collective Matrix Factorization Hashing for Multimodal data [*CVPR*], 2014
* Quantized Correlation Hashing (QCH) \[[paper](http://ijcai.org/papers15/Papers/IJCAI15-554.pdf)\]
	* Wu et al. Quantized correlation hashing for fast cross-modal search [*IJCAI*], 2015
* Semantic Topic Multimodal Hashing (STMH) \[[paper](http://ijcai.org/papers15/Papers/IJCAI15-546.pdf)\]
	* Wang et al. Semantic Topic Multimodal Hashing for Cross-Media Retrieval [*IJCAI*], 2015
* Semantics-Preserving Hashing (SePH) \[[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Lin_Semantics-Preserving_Hashing_for_2015_CVPR_paper.pdf)\]
	* Lin et al. Semantics-Preserving Hashing for Cross-View Retrieval [*CVPR*], 2015
	
### Deep Hashing
* Supervised Hashing via Image Representation Learning(CNNH) \[[paper](http://ss.sysu.edu.cn/~py/papers/AAAI-CNNH.pdf)\]\[[code](http://ss.sysu.edu.cn/~py/CNNH/cnnh.html)\]\[[slide](http://ss.sysu.edu.cn/~py/CNNH-slides.pdf)]
	* Rongkai Xia , Yan Pan, Hanjiang Lai, Cong Liu, and Shuicheng Yan. [*AAAI*], 2014
* Bit-Scalable Deep Hashing With Regularized Similarity Learning for Image Retrieval and Person Re-Identification(DRSCH) \[[paper](http://arxiv.org/pdf/1508.04535v2.pdf)\]\[[code](https://github.com/ruixuejianfei/BitScalableDeepHash)\]
	* Ruimao Zhang, Liang Lin, Rui Zhang, Wangmeng Zuo, and Lei Zhang. [*TIP*], 2015
* Convolutional Neural Networks for Text Hashing(THC) \[[paper](http://ijcai.org/papers15/Papers/IJCAI15-197.pdf)\]
	* Jiaming Xu, PengWang, Guanhua Tian, Bo Xu, Jun Zhao, Fangyuan Wang, Hongwei Hao. [IJCAI], 2015
* Simultaneous Feature Learning and Hash Coding with Deep Neural Networks(NINH) \[[paper](http://arxiv.org/pdf/1504.03410v1.pdf)\]
	* Hanjiang Lai, Yan Pan, Ye Liu, and Shuicheng Yan. [*CVPR*], 2015
* Deep Semantic Ranking Based Hashing for Multi-Label Image Retrieval(DSRH) \[[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Zhao_Deep_Semantic_Ranking_2015_CVPR_paper.pdf)\]\[[code](https://github.com/zhaofang0627/cuda-convnet-for-hashing)\]
	* Fang Zhao, Yongzhen Huang, Liang Wang, and Tieniu Tan. [*CVPR*], 2015
* Deep Hashing for Compact Binary Codes Learning(DH) \[[paper](https://sites.google.com/site/elujiwen/CVPR15b.pdf?attredirects=0&d=1)\]
	* Venice Erin Liong, Jiwen Lu, Gang Wang, Pierre Moulin, and Jie Zhou. [*CVPR*], 2015
* Deep Learning of Binary Hash Codes for Fast Image Retrieval(HDS) \[[paper](http://www.iis.sinica.edu.tw/~kevinlin311.tw/cvprw15.pdf)\]\[[code](https://github.com/kevinlin311tw/caffe-cvprw15)\]\[[questions](http://www.iis.sinica.edu.tw/~kevinlin311.tw/deephash_questions.txt)\]
	* Kevin Lin, Huei-Fang Yang, Jen-Hao Hsiao, and Chu-Song Chen. [*CVPRW*], 2015

### Online Hashing

* Online Hashing (OKH) \[[paper](http://ijcai.org/papers13/Papers/IJCAI13-213.pdf)\]
	* Huang et al. Online Hashing [*IJCAI*], 2013
* Online Sketching Hashing (OSH) \[[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Leng_Online_Sketching_Hashing_2015_CVPR_paper.pdf)\]
	* Leng et al. Online Sketching Hashing [*CVPR*], 2015

### Quantization

* Double-Bit Quantization for Hashing (DBQ) \[[paper](http://cs.nju.edu.cn/lwj/paper/AAAI12_DBQ.pdf)\] \[[code](http://cs.nju.edu.cn/lwj/code/DBQ.rar)\]
	* Weihao Kong, Wu-Jun Li. [*AAAI*], 2012
* Manhattan hashing for large-scale image retrieval (MQ) \[[paper](http://cs.nju.edu.cn/lwj/paper/SIGIR12_MH.pdf)\] \[[code](http://cs.nju.edu.cn/lwj/code/MH.rar)\]
	* Weihao Kong, Wu-Jun Li,Minyi Guo. [*SIGIR*], 2012
* Variable Bit Quantisation for LSH \[[paper](http://homepages.inf.ed.ac.uk/miles/papers/acl13.pdf)\] 
	* Sean Moran, Victor Lavrenko,Miles Osborne. [*ACL*], 2013
* Hamming Compatible Quantization for Hashing  \[[paper](http://ijcai.org/papers15/Papers/IJCAI15-325.pdf)\] 
	* Wang et al. Hamming Compatible Quantization for Hashing [*IJCAI*], 2015

# Dataset
---

## MIR-FLICKR 
* \[[dataset](http://press.liacs.nl/mirflickr/mirdownload.html)\]

## FLICKR-8k
* \[[dataset]()\]

## FLICKR-25k
* \[[dataset]()\]

## NUS-WIDE  
* \[[dataset](http://lms.comp.nus.edu.sg/research/NUS-WIDE.htm)\]

## TINY 
* \[[dataset](http://groups.csail.mit.edu/vision/TinyImages/)\]

## CIFAR  
* \[[dataset](https://www.cs.toronto.edu/~kriz/cifar.html)\]

## WIKI
* \[[dataset](http://www.svcl.ucsd.edu/projects/crossmodal/)\]

## MNIST
* \[[dataset](http://yann.lecun.com/exdb/mnist/)\]

## Labelme
* \[[dataset](http://labelme.csail.mit.edu/Release3.0/browserTools/php/dataset.php)\]

## Sun-397
* \[[dataset](http://groups.csail.mit.edu/vision/SUN/)\]

## IAPRTC12
* \[[dataset](http://imageclef.org/SIAPRdata)\]

## Imagenet
* \[[dataset](http://www.image-net.org/)\]

## SIFT-1M
* \[[dataset]()\]




