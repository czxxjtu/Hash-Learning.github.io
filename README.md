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
	 - [NUS-WIDE](#nus-wide)
	 - [TINY](#tiny)
	 - [CIFAR](#cifar)
	 - [WIKI](#wiki)
	 - [Labelme](#labelme)
	 - [Sun-397](#sun-397)
	 - [IAPRTC12](#iaprtc12)
	 - [Imagenet](#imagenet)

# Introduction
---

# Categories
---
## Data-Independent Method
* Similarity Search in High Dimensions via Hashing \[[paper](http://www.cs.princeton.edu/courses/archive/spring13/cos598C/Gionis.pdf)\]
	* Aristides Gionis, Piotr Indyk and Rajeev Motwani. [*VLDB*], 1999. 
*  Near-optimal hashing algorithms for approximate nearest neighbor in high dimensions. \[[paper](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4031381)\]
	*  Alexandr Andoni and Piotr Indyk. [*ACM*] 2008.
*  Locality-Sensitive Hashing Scheme Based on p-Stable Distributions \[[paper](http://dl.acm.org/citation.cfm?id=997857)\]
	*  Datar et al. [*ACM*], 2004.
* Kernelized Locality-Sensitive Hashing for Scalable Image Search \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5459466)\]
	* Brian Kulis and Kristen Grauman. [*ICCV*], 2009. 
* Fast Similarity Search for Learned Metrics \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=5204087)\]
	* Prateek Jain, Brian Kulis and Kristen Grauman. [*TPAMI*], 2009. 
* Locality-Sensitive Binary Codes from Shift-Invariant Kernels \[[paper](http://papers.nips.cc/paper/3749-locality-sensitive-binary-codes-from-shift-invariant-kernels)\]
	* Maxim Raginsky and Svetlana Lazebnik. [*NIPS*], 2009. 

## Data-Dependent Method

### Unsupervised Hashing
* Spectral Hashing (SH) \[[paper](http://people.csail.mit.edu/torralba/publications/spectralhashing.pdf)\]\[[code](http://www.cs.huji.ac.il/~yweiss/SpectralHashing/sh.zip)\]
	* Yair Weiss, Antonio Torralba and Rob Fergus. [*NIPS*], 2008
* Hashing with Graphs (AGH) \[[paper](http://www.ee.columbia.edu/~wliu/ICML11_AGH.pdf)\]\[[code](http://www.ee.columbia.edu/~wliu/)\]
	* Wei Liu, Jun Wang, Sanjiv Kumar and Shih-Fu Chang. [*ICML*], 2010
* Iterative quantization: A procerustean approach to learning binary codes (ITQ) \[[paper](http://www.unc.edu/~yunchao/papers/CVPR11_a.pdf)\]\[[code](http://www.unc.edu/~yunchao/code/smallcode.zip)\] 
	* Yunchao Gong and Svetlana Lazebnik. . [*CVPR*], 2011
* Isotropic Hashing (IsoHash) \[[paper](http://cs.nju.edu.cn/lwj/paper/NIPS12-IsoHash.pdf)\]\[[code](http://cs.nju.edu.cn/lwj/code/IsoHash.zip)\] 
	* Weihao Kong and Wu-Jun Li. [*NIPS*], 2012
* Spherical Hashing (SPH) \[[paper](http://sglab.kaist.ac.kr/Spherical_Hashing/Spherical_Hashing.pdf)\]\[[C++ code](http://sglab.kaist.ac.kr/projects/Spherical_Hashing/static/media/uploads/Spherical_Hashing_Src_CPP.zip)\]\[[matlab code](http://sglab.kaist.ac.kr/projects/Spherical_Hashing/static/media/uploads/Spherical_Hashing_Src_Matlab.zip)\]\[[slide](http://sglab.kaist.ac.kr/Spherical_Hashing/SphericalHashing_Slide.pdf)\]
	* Jae-Pil Heo, Youngwoon Lee, Junfeng He, Shih-Fu Chang and Sung-Eui Yoon. [*CVPR*], 2012
* Harmonious Hashing (HamH) \[[paper](http://ijcai.org/papers13/Papers/IJCAI13-269.pdf)\] 
	* Bin Xu, Jiajun Bu, Yue Lin Chun Chen, Xiaofei He and Deng Cai. [*IJCAI*], 2013
* Complementary Projection Hashing (CPH) \[[paper](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6751141)\]
	* Zhongming Jin, Yao Hu, Yue Lin, Debing Zhang, Shiding Lin, Deng Cai and Xuelong Li. [*ICCV*], 2013
* Inductive Hashing on Manifolds \[[paper](https://sites.google.com/site/shenfumin/)\]\[[supplementary](https://sites.google.com/site/shenfumin/)\]\[[code](https://sites.google.com/site/shenfumin/)\]\[[poster](https://sites.google.com/site/shenfumin/)\]
	* Fumin Shen, Chunhua Shen, Qinfeng Shi, Anton van den Hengel and Zhenmin Tang. [*CVPR*], 2013
* Learning Binary Codes for High-Dimensional Data Using Bilinear Projections  (BPBC) \[[paper](http://www.unc.edu/~yunchao/papers/CVPR13.pdf)\]\[[code](http://www.unc.edu/~yunchao/bpbc.htm)\]
	* Yunchao Gong, Sanjiv Kumar, Henry A. Rowley and Svetlana Lazebnik. [*CVPR*], 2013
* Discrete Graph Hashing (DGH) \[[paper](http://www.ee.columbia.edu/~wliu/NIPS14_dgh.pdf)\]
	* Wei Liu, Cun Mu, Sanjiv Kumar and Shih-Fu Chang. [*NIPS*], 2014
* Circulant Binary Embedding (CBE) \[[paper](http://www.felixyu.org/cbe.html)\]\[[code](http://www.felixyu.org/cbe.html)\]\[[slide](http://www.felixyu.org/cbe.html)\]
	* Felix Xu, Sanjiv Kumar, Yunchao Gong and Shih-Fu Chang. [*ICML*], 2014
* Locality Linear Hashing for Extracting Non-Linear Manifolds (LLH) \[[paper](http://www.ee.columbia.edu/~xmwu/publications.html)\]\[[supplementary](http://www.ee.columbia.edu/~xmwu/publications.html)\]
	* Go Irie, Zhenguo Li and Xiao-Ming Wu and Shih-Fu Chang. [*CVPR*], 2014
*  Scalable Graph Hashing with Feature Transformation (SGH) \[[paper](http://cs.nju.edu.cn/lwj/paper/IJCAI15_SGH.pdf))\]\[[code](http://cs.nju.edu.cn/lwj/code/SGH.rar)\]
	* Qing-Yuan Jiang and Wu-Jun Li. [*IJCAI*], 2015

### Supervised Hashing

* Semi-supervised hashing for scalable image retrieval (SSH)[[paper]](http://www.ee.columbia.edu/ln/dvmm/publications/10/SSH_CVPR2010.pdf)
	* Jun Wang, Sanjiv Kumar, and Shih-Fu Chang. [*CVPR*], 2010
* Minimal loss hashing for compact binary codes (MLH) [[paper]](http://www.cs.toronto.edu/%7Enorouzi/research/papers/min_loss_hash.pdf) [[code]](http://www.cs.toronto.edu/%7Enorouzi/research/mlh/)
	* Mohammad Norouzi and David M. Blei. [*ICML*], 2011
* Supervised hashing with kernels (KSH) [[paper]](http://www.ee.columbia.edu/%7Ewliu/CVPR12_ksh.pdf)[[code]](http://www.ee.columbia.edu/%7Ewliu/ksh_code.zip)
	* Wei Liu, Jun Wang, Rongrong Ji, Yu-Gang Jiang, and Shih-Fu Chang.[*CVPR*], 2012
* LDAHash: Improved matching with smaller descriptors [[paper]](http://wiki.epfl.ch/edicpublic/documents/Candidacy%20exam/LDAHash.pdf) [[code]](http://cvlab.epfl.ch/research/detect/ldahash)
	* Christoph Strecha, Alexander M. Bronstein, Michael M. Bronstein, and Pascal Fua. [*TPAMI*], 2012
* A general two-step approach to learning-based hashing (TSH) [[paper]](http://dx.doi.org/10.1109/ICCV.2013.317) [[code]](https://bitbucket.org/guosheng/two-step-hashing)
	* Guosheng Lin, Chunhua Shen, David Suter, and Anton van den Hengel.  [*ICCV*], 2013
* Supervised binary hash code learning with jensen shannon divergence (JSD) [[paper]](http://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Fan_Supervised_Binary_Hash_2013_ICCV_paper.pdf)
	* Lixin Fan. [*ICCV*], 2013
* The power of asymmetry in binary hashing (ASH) [[paper]](http://ttic.uchicago.edu/~yury/papers/nips2013_asym.pdf) [[code]](http://ttic.uchicago.edu/~bneyshabur/papers/asymmetric_codes_v1.0.tar)
	* Behnam Neyshabur, Nati Srebro, Ruslan R. Salakhutdinov, Yury Makarychev, and Payman Yadollahpour. [*NIPS*], 2012
* Graph cuts for supervised binary coding (GCC) [[paper]](http://research.microsoft.com/en-us/um/people/kahe/publications/eccv14gcc.pdf)
	* Tiezheng Ge, Kaiming He, and Jian Sun. [*ECCV*], 2014
* Fast supervised hashing with decision trees for high-dimensional data [[paper]](https://bitbucket.org/chhshen/fasthash/src) [[code]](https://bitbucket.org/chhshen/fasthash/)
	* Guosheng Lin, Chunhua Shen, Qinfeng Shi, Anton van den Hengel, and David Suter. [*CVPR*], 2014
* Supervised hashing with latent factor models (LFH) [[paper]](http://cs.nju.edu.cn/lwj/paper/SIGIR14_LFH.pdf) [[code]](http://cs.nju.edu.cn/lwj/code/LFH.rar)
	* Peichao Zhang, Wei Zhang, Wu-Jun Li, and Minyi Guo. [*SIGIR*], 2014
* Supervised Discrete Hashing (SDH) [[paper]](http://bmc.uestc.edu.cn/~fshen/SDH.pdf) [[code]](https://github.com/bd622/DiscretHashing)
	* Fumin Shen, Chunhua Shen, Wei Liu, and Heng Tao Shen. Supervised Discrete Hashing. [*CVPR*], 2015
* COSDISH
	* Wang-Cheng Kang, Wu-Jun Li and Zhi-Hua Zhou. Column sampling based discrete supervised hashing. [*AAAI*], 2016

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
* Composite Hashing with Multiple Information Sources (CHMIS-AW) \[[paper](https://www.cs.purdue.edu/homes/lsi/SIGIR_2011B.pdf)\]
	* Dan Zhang, Fei Wang, Luo Si. [*ACM SIGIR*], 2011
* Learning hash functions for cross-view similarity search (CVH) \[[paper](http://research.microsoft.com/pubs/151205/ijcai11.pdf)\]
	* Shaishav Kumar and Raghavendra Udupa. [*IJCAI*], 2011
* Co-Regularized Hashing for Multimodal Data (CRH) \[[paper](http://papers.nips.cc/paper/4793-co-regularized-hashing-for-multimodal-data.pdf)\]
	* Yi Zhen and Dit-Yan Yeung. [*NIPS*], 2012
* Inter-Media Hashing for Large-Scale Retrieval from Heterogeneous Data Sources (IMH) \[[paper](http://dl.acm.org/citation.cfm?id=2465274)\]
	* Jingkuan Song, Yang Yang, Yi Yang, Zi Huang and Heng Tao Shen. [*SIGMOD*], 2013
* Comparing apples to oranges: a scalable solution with heterogeneous hashing (RaHH) \[[paper](http://media.cs.tsinghua.edu.cn/~multimedia/cuipeng/papers/HeterogeneousHashing.pdf)\] 
	* Mingdong Ou, Peng Cui, Fei Wang, Jun Wang, Wenwu Zhu, Shiqiang Yang. [*KDD*], 2013
* Large-scale supervised multimodal hashing with semantic correlation maximization (SCM) \[[paper](http://cs.nju.edu.cn/lwj/paper/AAAI14_SCM.pdf)\]\[[code](http://cs.nju.edu.cn/lwj/code/SCMHash_Release.zip)\]
	* Dongqing Zhang and Wu-Jun Li. [*AAAI*], 2014
* Collective Matrix Factorization Hashing for Multimodal data (CMFH) \[[paper](http://ise.thss.tsinghua.edu.cn/MIG/CVPR2014%20Collective%20Matrix%20Factorization%20Hashing%20for%20Multimodal%20Data.pdf)\]
	* Guiguang Ding, Yuchen Guo and Jile Zhou.[*CVPR*], 2014
* Quantized correlation hashing for fast cross-modal search (QCH) \[[paper](http://ijcai.org/papers15/Papers/IJCAI15-554.pdf)\]
	* Botong Wu, Qiang Yang, Wei-Shi Zheng, Yizhou Wang and Jingdong Wang.[*IJCAI*], 2015
* Semantic Topic Multimodal Hashing for Cross-Media Retrieval (STMH) \[[paper](http://ijcai.org/papers15/Papers/IJCAI15-546.pdf)\]
	* Wang et al.[*IJCAI*], 2015
* Semantics-Preserving Hashing for Cross-View Retrieval  (SePH) \[[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Lin_Semantics-Preserving_Hashing_for_2015_CVPR_paper.pdf)\]
	* Zijia Lin, Guiguang Ding, Mingqing Hu and Jianmin Wang. [*CVPR*], 2015
	
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
	* Long-kai Huang, Qiang Yang and Wei-Shi Zheng. [*IJCAI*], 2013
* Online Sketching Hashing (OSH) \[[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Leng_Online_Sketching_Hashing_2015_CVPR_paper.pdf)\]
	* Cong Leng, Jiaxiang Wu, Jian Cheng, Xiao Bai and Hangqing Lu. [*CVPR*], 2015

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




