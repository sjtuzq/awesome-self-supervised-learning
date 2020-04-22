paperlist for self-supervised learning, keep updating...

###Pretext task
**Denoising auto-encoder**
* [Extracting and composing robust features with denoising autoencoders](https://dl.acm.org/doi/10.1145/1390156.1390294). Pascal Vincent, Hugo Larochelle, Yoshua Bengio, and Pierre-Antoine Manzagol. In ICML, 2008.

**Context auto-encoder**
* [Unsupervised visual representation learning by context prediction](https://arxiv.org/abs/1505.05192). Carl Doersch, Abhinav Gupta, and Alexei A Efros. In ICCV, 2015
* [Context encoders: Feature learning by inpainting. Deepak Pathak](https://arxiv.org/abs/1604.07379), Philipp Krahenbuhl, Jeff Donahue, Trevor Darrell, and Alexei A Efros.  In CVPR, 2016.
* [Learning representations by maximizing mutual information across views](https://arxiv.org/abs/1906.00910). Philip Bachman, R Devon Hjelm, and William Buchwalter.  arXiv:1906.00910, 2019.

**Cross-channel auto-encoder**
* [Colorful image colorization](https://arxiv.org/abs/1603.08511). Richard Zhang, Phillip Isola, and Alexei A Efros. In ECCV, 2016.
* [Split-brain autoencoders: Unsupervised learning by cross-channel prediction](https://arxiv.org/abs/1611.09842). Richard Zhang, Phillip Isola, and Alexei A Efros. In CVPR, 2017

**Exemplar image transformation**
* [Discriminative unsupervised feature learning with convolutional neural networks](https://arxiv.org/abs/1406.6909). Alexey Dosovitskiy, Jost Tobias Springenberg, Martin Riedmiller, and Thomas Brox. In NIPS, 2014.

**Patch ordering**
* [Unsupervised learning of visual representations by solving jigsaw puzzles](https://arxiv.org/abs/1603.09246). Mehdi Noroozi and Paolo Favaro. In ECCV, 2016. 

**Tracking**
* [Unsupervised learning of visual representations using videos](https://arxiv.org/abs/1505.00687). Xiaolong Wang and Abhinav Gupta. In ICCV, 2015.

**Counting**
* [Representation learning by learning to count](https://arxiv.org/abs/1708.06734). M. Noroozi, H. Pirsiavash, and P. Favaro. In ICCV, 2017.

**Instance discrimination**
* [Unsupervised feature learning via non-parametric instance discrimination](https://arxiv.org/abs/1805.01978). Zhirong Wu, Yuanjun Xiong, Stella Yu, and Dahua Lin. In CVPR, 2018.
* [Momentum contrast for unsupervised visual representation learning](https://arxiv.org/abs/1911.05722). Kaiming He, Haoqi Fan, Yuxin Wu, Saining Xie, and Ross Girshick. In arXiv 1911.05722, 2019

**Segmenting in videos**
* [Learning features by watching objects move](https://arxiv.org/abs/1612.06370). Deepak Pathak, Ross Girshick, Piotr Dollar, Trevor Darrell, and Bharath Hariharan. In CVPR, 2017

**Clustering features**
* [Deep clustering for unsupervised learning of visual features](https://arxiv.org/abs/1807.05520). Mathilde Caron, Piotr Bojanowski, Armand Joulin, and Matthijs Douze. In ECCV, 2018
* [Unsupervised pre-training of image features on non-curated data](https://arxiv.org/abs/1905.01278). Mathilde Caron, Piotr Bojanowski, Julien Mairal, and Armand Joulin.  In ICCV, 2019

**Rotation**
* [Unsupervised representation learning by predicting image rotations](https://arxiv.org/abs/1803.07728). Spyros Gidaris, Praveer Singh, and Nikos Komodakis. arXiv preprint arXiv:1803.07728, 2018.
* [Self-supervised representation learning by rotation feature decoupling](http://openaccess.thecvf.com/content_CVPR_2019/html/Feng_Self-Supervised_Representation_Learning_by_Rotation_Feature_Decoupling_CVPR_2019_paper.html). Zeyu Feng, Chang Xu, and Dacheng Tao. In CVPR, 2019.

**Warp**
* [Warpnet: Weakly supervised matching for single view reconstruction](https://arxiv.org/abs/1604.05592). Angjoo Kanazawa, David W Jacobs, and Manmohan Chandraker.  In CVPR, pages 3253–3261, 2016.
* [Self-supervised learning of geometrically stable features through probabilistic introspection](https://arxiv.org/abs/1804.01552). David Novotny, Samuel Albanie, Diane Larlus, and Andrea Vedaldi. In CVPR, pages 3637–3645, 2018

**Neighbourhood discovery**
* [Unsupervised Deep Learning by Neighbourhood Discovery](https://arxiv.org/abs/1904.11567). Jiabo Huang, Qi Dong, Shaogang Gong, Xiatian Zhu. In ICML, 2019

**Transformation prediction**
* [Aet vs. aed: Unsupervised representation learning by autoencoding transformations rather than data](https://arxiv.org/abs/1901.04596). Liheng Zhang, Guo-Jun Qi, Liqiang Wang, and Jiebo Luo. arXiv preprint arXiv:1901.04596, 2019.

**Transformation invariant**
* [Self-Supervised Learning of Pretext-Invariant Representations](https://arxiv.org/abs/1912.01991). Ishan Misra, Laurens van der Maaten. arXiv preprint arXiv:1912.01991, 2019.

**Temporal order**
* [Shuffle and learn: unsupervised learning using temporal order verification](https://arxiv.org/abs/1603.08561). Ishan Misra, C Lawrence Zitnick, and Martial Hebert. In ECCV, 2016.


###Loss functions
**Handcraft loss(predefined categories)**
* [Unsupervised visual representation learning by context prediction](https://arxiv.org/abs/1505.05192). Carl Doersch, Abhinav Gupta, and Alexei A Efros. In ICCV, 2015.
* [Colorful image colorization](https://arxiv.org/abs/1603.08511). Richard Zhang, Phillip Isola, and Alexei A Efros.  In ECCV, 2016.

**Original contrastive loss**
* [Dimensionality reduction by learning an invariant mapping](http://yann.lecun.com/exdb/publis/pdf/hadsell-chopra-lecun-06.pdf). Raia Hadsell, Sumit Chopra, and Yann LeCun. In CVPR, 2006

**NCE(noise contrastive estimation)**
* [Noise-contrastive estimation: A new estimation principle for unnormalized statistical models](http://proceedings.mlr.press/v9/gutmann10a.html). Michael Gutmann and Aapo Hyvarinen. In AISTATS, 2010
* [Unsupervised feature learning via non-parametric instance discrimination](https://arxiv.org/abs/1805.01978). Zhirong Wu, Yuanjun Xiong, Stella Yu, and Dahua Lin. In CVPR, 2018.

**CPC(contrastive predictive coding)**
* [Representation learning with contrastive predictive coding](https://arxiv.org/abs/1807.03748). Aaron van den Oord, Yazhe Li, and Oriol Vinyals.  arXiv:1807.03748, 2018
* [Data-efficient image recognition with contrastive predictive coding](https://arxiv.org/abs/1905.09272). Olivier J Henaff, Ali Razavi, Carl Doersch, SM Eslami, and Aaron van den Oord.  arXiv:1905.09272, 2019.

**CMC(contrastive multi-view coding)**
* [Contrastive multiview coding](https://arxiv.org/abs/1906.05849). Yonglong Tian, Dilip Krishnan, and Phillip Isola. arXiv:1906.05849, 2019

**MIM(mutual information maximization)**
* [Learning deep representations by mutual information estimation and maximization](https://arxiv.org/abs/1808.06670). R Devon Hjelm, Alex Fedorov, Samuel Lavoie-Marchildon, Karan Grewal, Adam Trischler, and Yoshua Bengio. In ICLR, 2019.
* [Learning representations by maximizing mutual information across views](https://arxiv.org/abs/1906.00910). Philip Bachman, R Devon Hjelm, and William Buchwalter. arXiv:1906.00910, 2019

**Local aggregation**
* [Local aggregation for unsupervised learning of visual embeddings](https://arxiv.org/abs/1903.12355). Chengxu Zhuang, Alex Lin Zhai, and Daniel Yamins.  In ICCV, 2019.

**Adversarial learning**
* [Adversarial feature learning](https://arxiv.org/abs/1605.09782). Jeff Donahue, Philipp Krahenbuhl, and Trevor Darrell. In ICLR, 2017.
* [Large scale adversarial representation learning](https://arxiv.org/abs/1907.02544). Jeff Donahue and Karen Simonyan. arXiv:1907.02544, 2019

###Predictive coding:
* [Predictive coding](https://ieeexplore.ieee.org/document/1055126) Peter Elias. IEEE Transactions on Information Theory, 1(1):16–24, 1955
* [Adaptive predictive coding of speech signals](https://ieeexplore.ieee.org/document/6769531). Bishnu S Atal and Manfred R Schroeder. The Bell System Technical Journal, 49(8):1973–1986, 1970
* [Predictive coding in the visual cortex: a functional interpretation of some extra-classical receptive-field effects](https://www.nature.com/articles/nn0199_79). Rajesh PN Rao and Dana H Ballard. Nature neuroscience, 2(1):79, 1999.
* [A theory of cortical responses](https://royalsocietypublishing.org/doi/10.1098/rstb.2005.1622). Karl Friston. Philosophical transactions of the Royal Society B: Biological sciences, 360(1456):815–836, 2005

**application in nlp**
* [Efficient estimation of word representations in vector space](https://arxiv.org/abs/1301.3781). Tomas Mikolov, Kai Chen, Greg Corrado, and Jeffrey Dean. arXiv preprint arXiv:1301.3781, 2013.
* [Skip-thought vectors](https://arxiv.org/abs/1506.06726). Ryan Kiros, Yukun Zhu, Ruslan R Salakhutdinov, Richard Zemel, Raquel Urtasun, Antonio Torralba, and Sanja Fidler. In Advances in neural information processing systems, pages 3294–3302, 2015.
* [Learning to generate reviews and discovering sentiment](https://arxiv.org/abs/1704.01444). Alec Radford, Rafal Jozefowicz, and Ilya Sutskever.  arXiv preprint arXiv:1704.01444, 2017.


###Contrastive learning:
**Triplet loss**
* [Learning a similarity metric discriminatively, with application to face verification](http://yann.lecun.com/exdb/publis/pdf/chopra-05.pdf). Sumit Chopra, Raia Hadsell, and Yann LeCun. In Computer Vision and Pattern Recognition, 2005. CVPR 2005. IEEE Computer Society Conference on, volume 1, pages 539–546. IEEE, 2005.
* [Distance metric learning for large margin nearest neighbor classification](http://jmlr.csail.mit.edu/papers/volume10/weinberger09a/weinberger09a.pdf). Kilian Q Weinberger and Lawrence K Saul. Journal of Machine Learning Research, 10(Feb):207–244, 2009.
* [Facenet: A unified embedding for face recognition and clustering](https://arxiv.org/abs/1503.03832). Florian Schroff, Dmitry Kalenichenko, and James Philbin. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 815–823, 2015.
* Time-contrastive:
* [Time-contrastive networks: Self-supervised learning from multi-view observation](https://arxiv.org/abs/1704.06888). Pierre Sermanet, Corey Lynch, Jasmine Hsu, and Sergey Levine. arXiv preprint arXiv:1704.06888, 2017.
* [Unsupervised feature extraction by time-contrastive learning and nonlinear ica](https://papers.nips.cc/paper/6395-unsupervised-feature-extraction-by-time-contrastive-learning-and-nonlinear-ica).Aapo Hyvarinen and Hiroshi Morioka. Advances in Neural Information Processing Systems 29, pages 3765–3773. Curran Associates, Inc., 2016.


###Self-supervised on videos:
**Region-level**
* [Learning correspondence from the cycle-consistency of time](https://arxiv.org/abs/1903.07593). X. Wang, A. Jabri, and A. A. Efros.  In CVPR, 2019
* [Unsupervised deep tracking](https://arxiv.org/abs/1904.01828). N. Wang, Y. Song, C. Ma, W. Zhou, W. Liu, and H. Li. In CVPR, 2019

**Pixel-level**
* [Tracking emerges by colorizing videos](https://arxiv.org/abs/1806.09594). C. Vondrick, A. Shrivastava, A. Fathi, S. Guadarrama, and K. Murphy. In ECCV, 2018.
* [Self-supervised learning for video correspondence flow](https://arxiv.org/abs/1905.00875). Z. Lai and W. Xie.  arXiv preprint arXiv:1905.00875, 2019
* [Multigrid predictive filter flow for unsupervised learning on videos](https://arxiv.org/abs/1904.01693). S. Kong and C. Fowlkes. arXiv preprint arXiv:1904.01693, 2019.

**Optical flow**
* [Sift flow: Dense correspondence across scenes and its applications](https://people.csail.mit.edu/celiu/SIFTflow/SIFTflow.pdf). C. Liu, J. Yuen, and A. Torralba. TPAMI, 2011
* [PWC-Net: CNNs for optical flow using pyramid, warping, and cost volume](https://arxiv.org/abs/1709.02371). D. Sun, X. Yang, M.-Y. Liu, and J. Kautz. In CVPR, 2018.
* [Flownet 2.0: Evolution of optical flow estimation with deep networks](https://arxiv.org/abs/1612.01925). E. Ilg, N. Mayer, T. Saikia, M. Keuper, A. Dosovitskiy, and T. Brox.  In CVPR, 2017.
* [An iterative image registration technique with an application to stereo vision](https://www.researchgate.net/publication/215458777_An_Iterative_Image_Registration_Technique_with_an_Application_to_Stereo_Vision_IJCAI). B. D. Lucas, T. Kanade, et al.  In DARPA Image Understanding Workshop. Vancouver, British Columbia, 1981

**Slow feature**
* [Slow feature analysis: Unsupervised learning of invariances](http://www.cnbc.cmu.edu/~tai/readings/learning/wiskott_sejnowski_2002.pdf). Laurenz Wiskott and Terrence J Sejnowski.  Neural computation, 14(4):715–770, 2002.

**Dense tracking**
* [Maskrnn: Instance level video object segmentation](https://arxiv.org/abs/1803.11187). Yuan-Ting Hu, Jia-Bin Huang, and Alexander G. Schwing. In NIPS, 2017
* [Videomatch: Matching based video object segmentation](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yuan-Ting_Hu_VideoMatch_Matching_based_ECCV_2018_paper.pdf). Yuan-Ting Hu, Jia-Bin Huang, and Alexander G. Schwing. In Proc. ECCV, 2018.
* [Lucid data dreaming for multiple object tracking](https://arxiv.org/abs/1703.09554). Anna Khoreva, Rodrigo Benenson, Eddy Ilg, Thomas Brox, and Bernt Schiele. In arXiv preprint arXiv: 1703.09554, 2017
* [Premvos: Proposal-generation, refinement and merging for video object segmentation](https://arxiv.org/abs/1807.09190). Jonathon Luiten, Paul Voigtlaender, and Bastian Leibe.  In Proc. ACCV, 2018
* [Feelvos: Fast end-to-end embedding learning for video object segmentation](https://arxiv.org/abs/1902.09513). Paul Voigtlaender, Yuning Chai, Florian Schroff, Hartwig Adam, Bastian Leibe, and Liang-Chieh Chen.  In Proc. CVPR, 2019.
* [One-shot video object segmentation](https://arxiv.org/abs/1611.05198). Sergi Caelles, Kevis-Kokitsi Maninis, Jordi Pont-Tuset, Laura Leal-Taixe, Daniel Cremers, and Luc Van Gool. In Proc. CVPR, 2017
* [Video object segmentation without temporal information](https://arxiv.org/abs/1709.06031). Kevis-Kokitsi Maninis, Sergi Caelles, Yuhua Chen, Jordi Pont-Tuset, Laura Leal-Taixe, Daniel Cremers, and Luc Van Gool. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2018

**Temporal ordering**
* [Self-supervised video representation learning with odd-one-out networks](https://arxiv.org/abs/1611.06646). Basura Fernando, Hakan Bilen, Efstratios Gavves, and Stephen Gould. In Proc. CVPR, 2017.
* [Shuffle and learn: Unsupervised learning using temporal order verification](https://arxiv.org/abs/1603.08561). Ishan Misra, C. Lawrence Zitnick, and Martial Hebert.  In Proc. ECCV, 2016.
* [Learning and using the arrow of time](https://ieeexplore.ieee.org/document/8578938). Donglai Wei, Joseph Lim, Andrew Zisserman, and William T. Freeman. In Proc. CVPR, 2018. 
* [Video representation learning by dense predictive coding](https://arxiv.org/abs/1909.04656). Tengda Han, Weidi Xie, and Andrew Zisserman. In 1st International Workshop on Large-scale Holistic Video Understanding, ICCV, 2019.






