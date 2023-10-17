# Geometric deep learning meets BCI to advance inter-session and -subject transfer


## Speaker
[Reinmar Kobler](https://scholar.google.at/citations?user=hE8CJYIAAAAJ):  Research Scientist, Advanced Telecommunications Research Institute International (ATR) and RIKEN Center for Advanced Intelligence Project (RIKEN AIP), Kyoto, Japan


## Abstract
Current brain-computer interfaces (BCIs) do not generalize well across domains (e.g., sessions and subjects) without expensive supervised re-calibration on small domain-specific data, which severely limits BCI utility and scalability. Fortunately, geometric deep learning offers a remedy via combining data-efficiency and invariances of Riemannian geometry aware methods with feature learning capabilities of neural nets. In this talk, I will present a geometric deep learning framework to perform unsupervised domain adaptation (UDA) on the symmetric, positive definite (SPD) manifold. The framework can be readily applied to multi-source/-target and online UDA scenarios. Using oscillatory EEG BCI datasets, we demonstrate that a simple, network architecture, which we denote TSMNet, can obtain state-of-the-art performance in inter-session and -subject transfer without compromising on neurophysiological interpretability.


## Geometric Deep Learning in the context of BCI

- [Reference implementation](https://github.com/rkobler/TSMNet ) of TSMNet ([Kobler+2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/28ef7ee7cd3e03093acc39e1272411b7-Abstract-Conference.html),*NeurIPS*)
- [Pull Request](https://github.com/braindecode/braindecode/pull/534) to include TSMNet in [braindecode](https://github.com/braindecode/braindecode)
- [Reference implementation](https://github.com/GeometricBCI/Tensor-CSPNet-and-Graph-CSPNet) of Tensor-CSPNet ([Ju+2022](https://ieeexplore.ieee.org/document/9805775),*TNNLS*) and Graph-CSPNet ([Ju+2023](https://ieeexplore.ieee.org/document/10255369),*TNNLS*)
- [Reference implementation](https://github.com/ku-milab/Deep-Efficient-Continuous-Manifold-Learning) of ([Jeong+203](https://ieeexplore.ieee.org/document/10266751/),*TPAMI*)
- [Reference implementation](https://github.com/cecnl/matt) of MAtt ([Pan+2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/c981fd12b1d5703f19bd8289da9fc996-Abstract-Conference.html),*NeurIPS*)
- [Reference implementation](https://papers.nips.cc/paper_files/paper/2019/file/6e69ebbfad976d4637bb4b39de261bf7-Supplemental.zip) of Riemannian Batch normalization ([Brooks+2019](https://papers.nips.cc/paper_files/paper/2019/hash/6e69ebbfad976d4637bb4b39de261bf7-Abstract.html),*NeurIPS*)

## Additional related literature
### Geometric Deep Learning
- Wilson Daniel, Robin Tibor Schirrmeister, Lukas Alexander Wilhelm Gemein, and Tonio Ball. 2022. “Deep Riemannian Networks for EEG Decoding.” _arXiv_. http://arxiv.org/abs/2212.10426.
### Batch Norm on the SPD manifold
- Kobler Reinmar J., Jun-ichiro Hirayama, and Motoaki Kawanabe. 2022. “Controlling The Fréchet Variance Improves Batch Normalization on the Symmetric Positive Definite Manifold.” In _IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)_, 3863–67. https://doi.org/10.1109/ICASSP43922.2022.9746629.
### Tangent Space Mapping (TSM)
- Barachant Alexandre, Stéphane Bonnet, Marco Congedo, and Christian Jutten. 2012. “Multiclass Brain-Computer Interface Classification by Riemannian Geometry.” _IEEE Transactions on Bio-Medical Engineering _59 (4): 920–28. https://doi.org/10.1109/TBME.2011.2172210.
- Sabbagh David, Pierre Ablin, Gaël Varoquaux, Alexandre Gramfort, and Denis A. Engemann. 2020. “Predictive Regression Modeling with MEG/EEG: From Source Power to Signals and Cognitive States.” _NeuroImage_ 222: 116893. https://doi.org/10.1016/j.neuroimage.2020.116893.

### Interpreting TSM models
- Kobler Reinmar J., Jun-Ichiro Hirayama, Lea Hehenberger, Catarina Lopes-Dias, Gernot Müller-Putz, and Motoaki Kawanabe. 2021. “On the Interpretation of Linear Riemannian Tangent Space Model Parameters in M/EEG.” In _43rd Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC)_. https://doi.org/10.1109/EMBC46164.2021.9630144.
- Xu Jiachen, Moritz Grosse-Wentrup, and Vinay Jayaram. 2019. “Interpretable Riemannian Classification in Brain-Computer Interfacing.” In _8th Graz Brain Computer Interface Conference_. https://doi.org/10.3217/978-3-85125-682-6-07.
### Transfer learning
- Li Siyang, Ziwei Wang, Hanbin Luo, Lieyun Ding, and Dongrui Wu. 2023. “T-TIME: Test-Time Information Maximization Ensemble for Plug-and-Play BCIs.” _IEEE Transactions on Biomedical Engineering_, 1–11. https://doi.org/10.1109/TBME.2023.3303289.
- Kobler Reinmar, Jun-ichiro Hirayama, Qibin Zhao, and Motoaki Kawanabe. 2022. “SPD Domain-Specific Batch Normalization to Crack Interpretable Unsupervised Domain Adaptation in EEG.” In _Advances in Neural Information Processing Systems_.
- Zanini Paolo, Marco Congedo, Christian Jutten, Salem Said, and Yannick Berthoumieu. 2018. “Transfer Learning: A Riemannian Geometry Framework With Applications to Brain–Computer Interfaces.”_ IEEE Transactions on Biomedical Engineering_ 65 (5): 1107–16. https://doi.org/10.1109/TBME.2017.2742541.
- Rodrigues Pedro Luiz Coelho, Christian Jutten, and Marco Congedo. 2019. “Riemannian Procrustes Analysis: Transfer Learning for Brain–Computer Interfaces.” _IEEE Transactions on Biomedical Engineering_ 66 (8): 2390–2401. https://doi.org/10.1109/TBME.2018.2889705.
- He He, and Dongrui Wu. 2020. “Transfer Learning for Brain–Computer Interfaces: A Euclidean Space Data Alignment Approach.” IEEE Transactions on Biomedical Engineering 67 (2): 399–410. https://doi.org/10.1109/TBME.2019.2913914.
- Kobler Reinmar J., and Reinhold Scherer. 2016. “Restricted Boltzmann Machines in Sensory Motor Rhythm Brain-Computer Interfacing: A Study on Inter-Subject Transfer and Co-Adaptation.” In _IEEE International Conference on Systems, Man, and Cybernetics (SMC)_, 469–74. https://doi.org/10.1109/SMC.2016.7844284.





