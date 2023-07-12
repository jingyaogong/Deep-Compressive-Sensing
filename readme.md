# Deep Compressive Sensing 
Collection of source code for deep learning-based compressive sensing (DCS). Links for source code, pdf, doi are available. 
Related works are classified based on the sampling matrix type (frame-based/block-based), sampling scale (single scale, multi-scale), and deep learning platform. 

Code for other than sampling, reconstruction of image/video are given in the Other section. 

P/s: If you know any source code please let me know. 


## Block-based DCS
### Single-Scale Sensing
* TCS-NET:[[code]](https://github.com/ICSResearch/TCS-Net)
  * H. Gan et al., From Patch to Pixel: A Transformer-based Hierarchical Framework for Compressive Image Sensing, TCI 2023
* TransCS: [[code]](https://github.com/ICSResearch/TransCS)
  * M. Shen et al., TransCS: A Transformer-Based Hybrid Architecture for Image Compressed Sensing, IEEE Trans Image Process, 2022. 
* TCS: [[code]](https://github.com/uqmarlonbran/TCS)
  * M. B. Lorenzana et al., Transfomer compressed sensing via global image tokens, IEEE International Conference on Image Processing, ICIP 2022.
* IBM_CS: [[code]](https://github.com/bksain/IBM_CS)
  * B. Lee et al., Information Bottleneck Measurement for Compressed Sensing Image Reconstruction, IEEE Signal Processing Letter 2022. 
* RK-CSNet: [[code]](https://github.com/rkteddy/RK-CCSNet) [Pytorch]
  * R. Zheng et al, "Runge-Kutta Convolutional Compressed Sensing Network," ECCV 2022.
* TDCN: [[code]](https://github.com/UHADS/TDCN) [Pytorch]
  * R. Lu and K. Ye, "Tree-structured Dilated Convolutional Networks for Image Compressed Sensing," IEEE Access, 2022.
* MTC-CSNET: [[code]](https://github.com/EchoSPLab/MTC-CSNet) [Pytorch]
  * MTC-CSNet: Marrying Transformer and Convolution for Image Compressed Sensing, 2022. 
* CASNet: [[code]](https://github.com/Guaishou74851/CASNet) [Pytorch]
  * B. Chen and J. Zhang, "Content-aware Scalable Deep Compressed Sensing," IEEE Trans. Image Processing, 2022. 
* NL-CSNet: [[code]](https://github.com/WenxueCui/NL-CSNet-Pytorch) [PyTorch]
  * W. Cui et al, Image Compressed Sensing Using Non-local Neural Network, Transaction on Multimedia, 2022.
* MADUN: [[code]](https://github.com/songjiechong/MADUN-ACMMM2021) [PyTorch]
  * J. Song et al. Memory-Augmented Deep Unfolding Network for Compressive Sensing (ACM MM 2021)
* SP_DCS: Single pixel DCS [[code]](https://github.com/Jeremy-jia2021/deep-compressive-sensing) [PyTorch]
  * Mengyu Jia et al . Single pixel imaging via unsupervised deep compressive sensing with collaborative sparsity in discretized feature space, Journal of Bio photonic, 2022.
* AMPD-Net:[[Code]](https://github.com/ZhonghaoZ/AMP-Net_TIP) [PyTorch]
  * Z. Zhang, Y. Liu, J. Liu, F. Wen, C. Zhu, "AMP-Net: Denoising based Deep Unfolding for Compressive Image Sensing," IEEE Transaction on Image Processing, 2021. 

* DRCS-SR [[code]](https://github.com/HossamMKasem/DRCS-SR-Deep-Robust-Compressed-Sensing-for-Single-Image-Super-Resolution)
  * H. Kasem, M. Selim, E. Mohamed, A. Hussein, "DRCS-SR-Deep-Robust-Compressed-Sensing-for-Single-Image-Super-Resolution," IEEE Access, 2020.
 
* OPINE-Net [[Code]](https://github.com/jianzhangcs/OPINE-Net) [Pytorch]
  * Jian Zhang, Chen Zhao, Wen Gao "Optimization-Inspired Compact Deep Compressive Sensing", IEEE Journal of Selected Topics in Signal Processing (JSTSP), vol. 14, no. 4, pp. 765-774, May 2020. [pdf]

* DUF-WL1:[[Code]](https://github.com/cyskyvein/Deep-Unfolding-Weighted-L1-Minimization)
  * J. Zhang, Y. Li, Z. Yu, Z. Gu, Y. Cheng, H. Gong, "Deep Unfolding With Weighted ℓ₂ Minimization for Compressive Sensing," IEEE Internet of Thing Journal, 2020.
  
* TGDOF [[Code]](https://github.com/dlut-dimt/TGDOF)[Matlab]
  * R. Liu, Y. ZHang, S. Cheng, X. Fan, Z. Luo, "A theoretically guaranteed optimization framework for robust compressive sensing MRI," Proceeding of the AAAI Conference on Artifical Intelligence, 2019. 
  
* DNN-CS-STM32-MCU [[Code]](https://github.com/flasonil/Deep-Neural-Network-for-CS-based-signal-reconstruction-on-STM32-MCU-board) [Tensorflow]
  * Lab. of Statistical Signal Processing - Deep Neural Network for CS based signal reconstruction on STM32 MCU board

* TIP-CSNet  [[DOI]](https://ieeexplore.ieee.org/document/8765626/) [[Code]](https://github.com/wzhshi/TIP-CSNet)[Matconvnet] [[Code]](https://github.com/WenxueCui/CSNet-Pytorch) [Pytorch]
  * W. Shi et al., Image Compressed Sensing using Convolutional Neural Network, IEEE Trans. Image Process, 2019. 
  
* LapCSNet [[PDF]](https://arxiv.org/abs/1804.04970) [[Code]](https://github.com/WenxueCui/LapCSNet)[Matconvnet]
  * Wenxue Cui, Heyao Xu, Xinwei Gao, Shengping Zhang, Feng Jiang, Debin Zhao, "An efficient deep convolutional laplacian pyramid architecture for CS reconstruction at low sampling ratios," 2018. 
  
* Perceptual-CS [[Code]] (https://github.com/jiang-du/Perceptual-CS) [[DOI]](https://link.springer.com/chapter/10.1007/978-3-030-03338-5_23) [Caffe]
  * J. Du, X. Xie, C. Wang, and G. Shi, "Perceptual Compressive Sensing," Chinese Conference on Pattern Recognition and Computer Vision (PRCV), pp. 268 - 279, 2018. 
  
* ISTA-Net [[Code]](https://github.com/jianzhangcs/ISTA-Net) [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_ISTA-Net_Interpretable_Optimization-Inspired_CVPR_2018_paper.pdf) [Tensorflow]
  * Z. Jian and G. Bernard, "ISTA-Net: Interpretable Optimization-Inspired Deep Network for Image Compressive Sensing", IEEE International Conference on Computer Vision and Pattern Recognition, 2018. 

* CSNet [[Code]](https://github.com/wzhshi/CSNet) [[Code-ReImp]](https://github.com/AtenaKid/CSNet) [[PDF]](https://arxiv.org/abs/1707.07119) [[DOI]](https://doi.org/10.1109/ICME.2017.8019428) [Matconvnet] [[Code-ReImp-Pytorch]](https://github.com/liujiawei2333/Compressed-sensing-CSNet)
  * W. Shi, F. Jaing, S. Zhang, and D. Zhao, "Deep networks for compressed image sensing", IEEE International Conference on Multimedia and Expo (ICME), 2017.   

* DeepInv [[Code-ReImp]](https://github.com/y0umu/DeepInverse-Reimplementation) [[PDF]](https://arxiv.org/pdf/1701.03891.pdf) [[DOI]](https://doi.org/10.1109/ICASSP.2017.7952561) 
  * A. Mousavi, R. G. Baraniuk et al., "Learning to invert: Signal recovery via Deep Convolutional Networks," IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2017. 

* DBCS [[Code]](http://www.cs.technion.ac.il/~adleram/BCS_DNN_2016.zip) [[PDF]](https://arxiv.org/pdf/1606.01519.pdf) [[DOI]](https://doi.org/10.1109/MMSP.2017.8122281) [Matlab]
  * A. Adler, D.Boublil, and M. Zibulevsky, "Block-based compressed sensing of images via deep learning,", IEEE International Workshop on Multimedia Signal Processing (MMSP), 2017.

* DR2Net [[Code]](https://github.com/coldrainyht/caffe_dr2) [[Code]](https://github.com/AtenaKid/Caffe-DCS) [[PDF]](https://arxiv.org/abs/1702.05743) [Caffe]
  * H. Yao, F. Dai, D. Zhang, Y. Ma, S. Zhang, Y. Zhang, and Q. Tian, "DR2-net: Deep residual reconstruction network for image compressive sensing", arXiv:1702.05743, 2017. 

* CS-CAE [[Code]](https://github.com/stes/compressed_sensing/tree/master/code) [[PDF]](https://github.com/stes/compressed_sensing/blob/master/report/report.pdf) [Theanos]
  * S. Schneider, "A deep learning approach to compressive sensing with convolutional autoencoders," tech. report, 2016. 

* ReconNet [[Code]](https://github.com/KuldeepKulkarni/ReconNet) [[Code]](https://github.com/AtenaKid/Caffe-DCS) [[PDF]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Kulkarni_ReconNet_Non-Iterative_Reconstruction_CVPR_2016_paper.pdf) [[DOI]](https://doi.org/10.1109/CVPR.2016.55) [Caffe]
  * K. Kulkarni, S. Lohi, P. Turaga, R. Kerviche, A. Ashok, "ReconNet: Non-Iterative Reconstruction of Images from Compressively Sensed
Measurements," IEEE International Conference on Computer Vision and Pattern Recognition (CVPR), 2016. 

### Multi-Scale Sensing
* STDIP: [[code]](https://github.com/zhang-chenxu/STDIP)
  * Y. Zhong et al, Image Compressed Sensing Reconstruction via Deep Image Prior With Structure-Texture Decomposition, IEEE Signal Processing Letter 2023.
* AMS-NET: [[code]](https://github.com/RedamancyAY/AMS-Net) [Python]
  * AMS-Net: Adaptive Multi-Scale Network for Image Compressive Sensing, IEEE Transaction on Multimedia, 2022. 
* MS-DCI [[DOI]]() [[PDF]](https://arxiv.org/abs/2008.00802) [[Code]](https://github.com/ngcthuong/MS-DCI/blob/master/README.md)[Matconvnet]
  * T. N. Canh et al., Multi-scale Deep Compressive Imaging, arxiv 2020. 

* Scalable Compressed Sensing Network (SCSNet) [[DOI]]() [[PDF]]() [[Code]](https://github.com/wzhshi/SCSNet)[Matconvnet]
  * W. Shi et al.,  Scalable Convolutional Neural Network for Image Compressed Sensing, CVPR 2019. 

* DoC-DCS [[Code]](https://github.com/AtenaKid/DoC-DCS) [[PDF]]( ) [MatcovnNet]
  * T. N. Canh and B. Jeon, "Difference of Convolution for Deep Compressive Sensing," IEEE International Conference on Imave Processing (ICIP), 2019.
 
* DCSNet [[Code]](https://github.com/AtenaKid/MS-DCSNet-Release) [[PDF]](https://arxiv.org/abs/1809.05717) [MatcovnNet]
  * T. N. Canh and B. Jeon, "Multi-Scale Deep Compressive Sensing Network," IEEE International Conference on Visual Communication and Imave Processing (VCIP), 2018.

* MS-CSNet [[Code]](https://github.com/wzhshi/MS-CSNet) [[DOI]](https://doi.org/10.1109/ICIP.2018.8451352) [MatconvNet]
  * W. Shi, F. Jiang, S. Liu, D. Zhao, "Multi-Scale Deep Networks for Image Compressed Sensing," IEEE International Conference on Image Processing (ICIP), 2018. 

* LAPRAN [[Code]](https://github.com/PSCLab-ASU/LAPRAN-PyTorch) [[PDF]](https://arxiv.org/abs/1807.09388) [PyTorch]
  * K. Xu, Z. Zhang, and  F. Ren, "LAPRAN: A Scalable Laplacian Pyramid Reconstructive Adversarial Network for Flexible Compressive Sensing Reconstruction," arXiv:1807.09388. 

## Adaptive Sensing 
* AMS-NET: [[code]](https://github.com/RedamancyAY/AMS-Net) [Python]
  * AMS-Net: Adaptive Multi-Scale Network for Image Compressive Sensing, IEEE Transaction on Multimedia, 2022. 
* ACSNet [[Code]](https://github.com/jirong0214/ACSNet-Code)
  * L. Zhong, S. Wan and L. Xie, "Adaptive Compressed Sensing imaging algorithm based on Deep Neural Network", Journal of Pysics Conference. 

## Frame-based DCS
* DeepFlatCam[[Code]](https://github.com/ngcthuong/DeepFlatCam) [[PDF]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/LCI/Canh_Deep_Compressive_Sensing_for_Visual_Privacy_Protection_in_FlatCam_Imaging_ICCVW_2019_paper.pdf)
  * Thuong Nguyen Canh and Hajime Nagahara, "Deep Compressive Sensing for Visual Privacy Protection in FlatCam Imaging," IEEE the International Conference on Computer Vision Workshop, 2019.)

* MD-Recon-Net[[Code]](https://github.com/Deep-Imaging-Group/MD-Recon-Net) [[PDF]]()
  * Maosong Ran, Wenjun Xia, Yongqiang Huang, Zexin Lu, Peng Bao, Yan Liu, Huaiqiang Sun, Jiliu Zhou, and Yi Zhang, "MD-Recon-Net: a parallel dual-domain convolutional neural network for compressed sensing MRI," IEEE Transactions on Radiation and Plasma Medical Sciences, DOI: 10.1109/TRPMS.2020.2991877, online, 2020.
  
* CS-MRI-GAN[[Code]](https://github.com/puneesh00/cs-mri-gan) [[PDF]](https://arxiv.org/abs/1910.06067)
  * P. Deora, B. Váudeva, S. Bhattacharya, P. M. Pradhan, "Structure Preserving Compressive Sensing MRI Reconstruction using Generative Adversarial Networks," IEEE Computer Vision and Pattern Recognition Workshop, 2020.

* Tensor-ADMM-Net-CSI[[Code]](https://github.com/Phoenix-V/tensor-admm-net-sci) [Tensorflow]
  * Jiawei Ma, Xiao-Yang Liu, Zheng Shou, Xin Yuan, "Deep Tensor ADMM-Net for Snapshot Compressive Imaging," IEEE ICCV, Nov. 2019.

* ADMM-CSNet[[Code]](https://github.com/yangyan92/ADMM-CSNet)
  * Yan Yang, Jian Sun, Huibin Li, Zongben Xu, "ADMM-CSNet: A Deep Learning Approach for Image Compressive Sensing," IEEE Transaction on Pattern Recognition and Machine Intelligence, 2019.

* DCS-GAN [[Code]](https://github.com/deepmind/deepmind-research/tree/master/cs_gan)[[Pdf]](https://arxiv.org/pdf/1905.06723.pdf) - Available Soon from DeepMind
  * Yan Wu, Mihaela Rosca, Timothy Lillicrap, Deep Compressive Sensing, Arxiv 2019. 
  
* F-CSRG [[Code]](https://github.com/sihan-zeng/f-csrg) [[PDF]](https://arxiv.org/abs/1902.06913) [Tensorflow]
  * Shaojie Xu, Sihan Zeng, Justin Romberg, "Fast Compressive Sensing Recovery Using Generative Models with Structured Latent Variables
," arXiv:1806.10175, 2019.

* L1AE [[Code]](https://github.com/wushanshan/L1AE) [[PDF]](https://arxiv.org/abs/1806.10175) [Tensorflow]
  * Shanshan Wu, Alexandros G. Dimakis, Sujay Sanghavi, Felix X. Yu, Daniel Holtmann-Rice, Dmitry Storcheus, Afshin Rostamizadeh, Sanjiv Kumar, "Learning a Compressed Sensing Measurement Matrix via Gradient Unrolling," arXiv:1806.10175, 2018.
  
* DIP [[Code]](https://github.com/davevanveen/compsensing_dip) [[PDF]](https://arxiv.org/pdf/1806.06438.pdf) [Torch]
  * David Van Veen; Ajil Jalal, Eric Price; Sriram Vishwanath; Alexandros G. Dimakis, "Compressed Sensing with Deep Image Prior and Learned Regularization," arXiv:1806.06438, 2018. 
  
* Deep-ADMM-Net [[Code]](https://github.com/yangyan92/Deep-ADMM-Net) [[DOI]](https://doi.org/10.1109/TPAMI.2018.2883941) [MatconvNet]
  * Yan Yang ; Jian Sun ; HUIBIN LI ; Zongben Xu, "ADMM-CSNet: A Deep Learning Approach for Image Compressive Sensing," IEEE Transaction on Pattern Recognition and Machine Intelligence, 2018. 

* VAR-MSI [[Code]](https://github.com/VLOGroup/mri-variationalnetwork) [[PDF]] [[DOI]](https://doi.org/10.1002/mrm.26977) [Tensorflow]
  * H. Kerstin et al., "Learning a variational network for reconstruction of accelerated MRI data," Magnetic Resonance in Medicine, vol. 79, no. 6, 2018. 

* CSMRI [[Code]](https://github.com/mseitzer/csmri-refinement) [[PDF]](https://arxiv.org/abs/1806.11216) [PyTorch]
  * M. Seitzer et al., "Adversarial and Perceptual Refinement Compressed Sensing MRI Reconstruction," MICCAI 2018. 

* KCS-Net [[Code]](https://github.com/AtenaKid/KCS-Net) [[PDF]](https://www.researchgate.net/publication/324969818_Deep_Learning-Based_Kronecker_Compressive_Imaging) [MatconvNet]
  * T. N. Canh and B. Jeon, "Deep Learning-Based Kronecker Compressive Imaging", IEEE International Conference on Consumer Electronic Asia, 2018

* DAGAN [[Code]](https://github.com/nebulaV/DAGAN) [[PDF]](http://discovery.ucl.ac.uk/10048154/1/08233175.pdf) [[DOI]](https://doi.org/10.1109/TMI.2017.2785879) [Tensorflow]
  * G. Yang et al., "DAGAN: Deep De-Aliasing Generative Adversarial Networks for Fast Compressed Sensing MRI Reconstruction," IEEE Transaction on Medical Imaging, vol. 37, no. 6, 2018. 

* SADN [[Code]](https://github.com/yqx7150/SADN)[[Doi]](https://ieeexplore.ieee.org/document/8296620?reload=true) [Matlab]
  * Qiegen Liu and Henry Leung, Synthesis-analysis deconvolutional network for compressed sensing, IEEE International Conference on Image Processing, 2017. 
* CSGM [[Code]](https://github.com/AshishBora/csgm) [[PDF]](https://arxiv.org/abs/1703.03208) [Tensorflow]
  * A. Bora, A. Jalal, A. G. Dimakis, "Compressed sensing using Generative Models," arXiv:1703.03208, 2017. 

* Learned D-AMP [[Code]](https://github.com/ricedsp/D-AMP_Toolbox) [[PDF]](https://arxiv.org/abs/1704.06625) [Tensorflow]
  * C. A. Metzler et al., "Learned D-AMP: Principled Neural Network based Compressive Image Recovery," Advances in Neural Information Processing Systems, 2017.

* Deep-Ternary [[Code]](https://github.com/nmduc/deep-ternary) [[PDF]](https://arxiv.org/abs/1708.08311) [Tensorflow] 
  * D. M. Nguyen, E. Tsiligianni and N. Deligiannis, "Deep learning sparse ternary projections for compressed sensing of images," IEEE Global Conference on Signal and Information Processing (GlobalSIP), 2017.

* GANCS [[Code]](https://github.com/gongenhao/GANCS) [[PDF]](https://www.nature.com/articles/s41592-018-0233-6) [Tensorflow]
  * M. Mardani et al., "Compressed Sensing MRI based on Deep Generative Adversarial Network", arXiv:1706.00051, 2017.

## Video Compressive Sensing
* DL-CACTI [[Code]](https://github.com/mq0829/DL-CACTI) [Tensorflow]
  * M. Qiao, Z. Meng, J. Ma, X. Yuan, "Deep Learning for Video Compressive Sensing", APL Photonic 5, 2020.

* DeepVideoCS [[Web]](http://users.eecs.northwestern.edu/~mif365/deep_cs_project.html) [[Code]](https://github.com/miliadis/DeepVideoCS) [[PDF]](http://users.eecs.northwestern.edu/~mif365/papers/Deep_Video_CS.pdf) [[DOI]](https://doi.org/10.1016/j.dsp.2017.09.010) [PyTorch]
  * M. Illiasdis, L. Spinoulas, A. K. Katsaggelos, "Deep fully-connected networks for video compressive sensing," Elsevier Digital Signal Processing, vol. 72, 2018.  

* CSVideoNet [[Code]](https://github.com/PSCLab-ASU/CSVideoNet) [[PDF]](https://arxiv.org/pdf/1612.05203.pdf) [Caffe] [Matlab]
  * K. Xu and F. Ren, "SVideoNet: A Recurrent Convolutional Neural Network for Compressive Sensing Video Reconstruction," arXiv:162.05203, 2018. 
  

## Other 
* CSNN [[Code]](https://github.com/ayonar/csnn) [[DOI]](https://arxiv.org/abs/1904.10136) [Matlab][Tensorflow]
  * Yonar and Lee et. al., A Compressed Sensing Framework for Efficient Dissection of Neural Circuits." (2019) Nature Methods 16, pages126–133.

* LIS-DL [[Code]](https://github.com/Abdelrahman-Taha/LIS-DeepLearning) [[PDF]](https://arxiv.org/abs/1904.10136) [Matlab]
  * Abdelrahman Taha, Muhammad Alrabeiah, Ahmed Alkhateeb, "Enabling Large Intelligent Surfaces with Compressive Sensing and Deep Learning," arXiv:1904.10136, Apr 2019.   

* VAE-GANs [[Code]](https://github.com/MortezaMardani/GAN-Hallucination/tree/vae) [[PDF]](https://arxiv.org/pdf/1901.11228.pdf) [Python]
  * Vineet Edupuganti, Morteza Mardani, Joseph Cheng, Shreyas Vasanawala, John Pauly, "VAE-GANs for Probabilistic Compressive Image Recovery: Uncertainty Analysis," arxiv1901.1128, 2019.   

* Sparse-Gen [[Code]](https://github.com/ermongroup/sparse_gen) [[[PDF]](https://arxiv.org/abs/1807.01442) [Tensorflow]
  * Manik Dhar, Aditya Grover, Stefano Ermon, "Modeling Sparse Deviations for Compressed Sensing using Generative Models," International Conference on Machine Learning (ICML), 2018
 
* Super-LiDAR [[Code]](https://github.com/nchodosh/Super-LiDAR) [[PDF]](https://arxiv.org/abs/1803.08949) [Tensorflow]
  * Nathaniel Chodosh, Chaoyang Wang, Simon Lucey, "Deep Convolutional Compressed Sensing for LiDAR Depth Completion," arXiv:1803.08949, 2018. 

* Unpaired-GANCS [[Code]](https://github.com/MortezaMardani/Unpaired-GANCS) [Tensorflow] 
  * Reconstruct under sampled MRI image

* CSGAN [[Code]](https://github.com/po0ya/csgan) [[PDF]](https://arxiv.org/abs/1802.01284) [Tensorflow]
  * M. Kabkab, P. Samangouei, and R. Chellappa, "Task-Aware Compressed Sensing with Generative Adversarial Networks," AAAI Conference on Artificial Intelligence, 2018

* DL-CSI [[Code]](https://github.com/sydney222/Python_CsiNet) [[PDF]](https://arxiv.org/abs/1706.01215) [Tensorflow][Keras
  * Chao-Kai Wen, Wan-Ting Shih, and Shi Jin, “Deep learning for massive MIMO CSI feedback,” IEEE Wireless Communications Letters, 2018. 

* US-CS [[Code]](https://github.com/dperdios/us-rawdata-sda) [[PDF]](https://infoscience.epfl.ch/record/230991/files/ius2017_sda_preprint.pdf) [[DOI]](https://doi.org/10.1109/ULTSYM.2017.8092746) [Tensorflow]
  * D. Perdios, A. Besson, M. Arditi, and J. Thiran, "A Deep Learning Approach to Ultrasound Image Recovery", IEEE International Ultranosics Symposium, 2017. 

* DeepIoT [[Code-ReImplement]](https://github.com/po0ya/csgan) [[PDF]](https://arxiv.org/abs/1706.01215) [Tensorflow]
  * Shuochao Yao, Yiran Zhao, Aston Zhang, Lu Su, Tarek Abdelzaher, "DeepIoT: Compressing Deep Neural Network Structures for Sensing Systems with a Compressor-Critic Framework," AAAI Conference on Artificial Intelligence, 2018

* LSTM_CS [[Code]](https://github.com/yscacaca/DeepIoT) [[PDF]](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/02/LSTM_CS_TSP.pdf) [[DOI]](https://doi.org/10.110910.1109/TSP.2016.2557301) [Matlab]
  * H. Palangi, R. Ward, and L. Deng, "Distributed Compressive Sensing: A Deep Learning Approach," IEEE Transaction on Signal Processing, vol. 64, no. 17, 2016.



  


