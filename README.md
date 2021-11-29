# Implementation of SOTA Deep Anomaly Detection Methods
In this repository, we provide a continuously updated collection of implementation of SOTA deep anomaly detection methods in the literature. This list was originally collected and presented in our CSUR survey paper on deep anomaly detection. This repository is created to serve as an extension to that list. You may cite the survey paper below to acknolwedge our contribution. 
```bibtex
@article{pang2021deep,
  title={Deep learning for anomaly detection: A review},
  author={Pang, Guansong and Shen, Chunhua and Cao, Longbing and Hengel, Anton Van Den},
  journal={ACM Computing Surveys (CSUR)},
  volume={54},
  number={2},
  pages={1--38},
  year={2021},
  publisher={ACM New York, NY, USA}
}
```

## Algorithms and Source Codes


| Method | Publication Venue | Year | API | Link | Supervision*|Data|
| :----------- | :-----------: | :-----------: | :-----------: | :----------- |:----------- |:----------- |
|RDA|KDD| 2017|	Tensorflow|	https://git.io/JfYG5 | Semi-supervised|Image|
|AnoGAN| IPMI|2017|	Tensorflow|	https://git.io/JfGgc |Semi-supervised|Image|
|Fast AntoGAN|Medical Image Analysis|2019|	Tensorflow|	https://git.io/JfZRn |Semi-supervised|Image|
|EBGAN|arXiv|2018|	Keras|	https://git.io/JfGgG |Semi-supervised|Image|
|ALAD	|ICDM|2018|	Keras|	https://git.io/JfZ8v |Semi-supervised|Image|
|GANomaly|ACCV|2018|	PyTorch|	https://git.io/JfGgn |Semi-supervised|Image|
|FFP|CVPR|2018|Tensorflow|	https://git.io/Jf4pc |Semi-supervised|Video|
|LSA| CVPR|2019|	Torch|	https://git.io/Jf4pW |Semi-supervised|Image|
|GT| NeurIPS|2018|	Keras|	https://git.io/JfZRW |Semi-supervised|Image|
|E3Outlier| NeurIPS|2019|	PyTorch|	https://git.io/Jf4pl |Unsupervised|Image|
|REPEN	|KDD|2018|	Keras|	https://git.io/JfZRg |Unsupervised|Tabular|
|RDP| IJCAI| 2020|PyTorch|	https://git.io/RDP |Unsupervised|Tabular|
|AE-1SVM	|ECML-PKDD|2018|	Tensorflow	|https://git.io/JfGgl |Unsupervised|Tabular|
|OC-NN| arXiv|2018|	Keras|	https://git.io/JfGgZ |Semi-supervised|Image|
|Deep SVDD| ICML|2018|	Tensorflow	|https://git.io/JfZRR |Semi-supervised|Image|
|Deep SAD	|ICLR|2020|	PyTorch	|https://git.io/JfOkr |Weakly-supervised|Image|
|DAGMM	|ICLR|2018|	PyTorch|	https://git.io/JfZR0 |Unsupervised|Image|
|MIL| CVPR|2018|	Keras	|https://git.io/JfZRz |Weakly-supervised|Video|
|DevNet| KDD|2019|	Keras|	https://git.io/JfZRw |Weakly-supervised|Tabular|
|ALOCC	|CVPR|2018|	Tensorflow|	https://git.io/Jf4p4 |Semi-supervised|Image|
|OCAN	|AAAI|2019|	Tensorflow|	https://git.io/JfYGb |Semi-supervised|Sequential|
|FenceGAN|arXiv|2019|	Keras|	https://git.io/Jf4pR |Semi-supervised|Image&Tabular|
|OCGAN|CVPR|2019|	MXNet|	https://git.io/Jf4p0 |Semi-supervised|Image|
|RTFM|ICCV|2021|PyTorch|https://git.io/JKnE6| Weakly-supervised|Video|
|CCD|MICCAI|2021|PyTorch|https://git.io/JKnEM|Semi-supervised|Image|
|MemAE|ICCV|2019|PyTorch|https://git.io/JVnlz|Semi-supervised|Image&Video|
|GCN-AE|SDM|2019|PyTorch|https://git.io/JVn43|Unsupervised|Graph|
|DevNet|arXiv|2021|PyTorch|https://git.io/DevNet|Weakly-supervised|Image|
|GCLNC|CVPR|2019|PyTorch|https://git.io/JwoHS|Weakly-supervised|Video|
|OmniAnomaly|KDD|2019|Tensorflow|https://git.io/JKnu4|Unsupervised|Time series|
|RWAD|CVPR|2018|Keras|https://git.io/JfZRz| Weakly-supervised|Video|
|A3|ECMLPKDD|2020|Keras|https://github.com/Fraunhofer-AISEC/A3|Semi-supervised|Tabular|



\* In the supervision column, 'semi-supervised' indicates that the specific methods are trained on exclusively normal data, 'unsupervised' indicates that they are trained on fully unlabeled data (mostly normal data), while `weakly-supervised' indicates that the methods use some form of weak supervision, e.g., coarse class labels, or partially observed anomaly class labels

