# PW-360IQA
Code of the [PW-360IQA](https://doi.org/10.3390/s23094242) model published under "PW-360IQA: Perceptually-Weighted Multichannel CNN for Blind 360-Degree Image Quality Assessment"

## Abstract
Image quality assessment of 360-degree images is still in its early stages, especially when it comes to solutions that rely on machine learning. There are many challenges to be addressed related to training strategies and model architecture. In this paper, we propose a perceptually weighted multichannel convolutional neural network (CNN) using a weight-sharing strategy for 360-degree IQA (PW-360IQA). Our approach involves extracting visually important viewports based on several visual scan-path predictions, which are then fed to a multichannel CNN using DenseNet-121 as the backbone. In addition, we account for users’ exploration behavior and human visual system (HVS) properties by using information regarding visual trajectory and distortion probability maps. The inter-observer variability is integrated by leveraging different visual scan-paths to enrich the training data. PW-360IQA is designed to learn the local quality of each viewport and its contribution to the overall quality. We validate our model on two publicly available datasets, CVIQ and OIQA, and demonstrate that it performs robustly. Furthermore, the adopted strategy considerably decreases the complexity when compared to the state-of-the-art, enabling the model to attain comparable, if not better, results while requiring less computational complexity.

## Authors
* Abderrezzaq Sendjasni, Ph.D.   [(abderrezzaq.sendjasni@univ-poitiers.fr)](mailto:abderrezzaq.sendjasni@univ-poitiers.fr)  
* Chaker Larabi, Prof.   [(chaker.larabi@univ-poitiers.fr)](mailto:chaker.larabi@univ-poitiers.fr)

## How to cite
```
  @Article{s23094242,
      AUTHOR = {Sendjasni, Abderrezzaq and Larabi, Mohamed-Chaker},
      TITLE = {PW-360IQA: Perceptually-Weighted Multichannel CNN for Blind 360-Degree Image Quality Assessment},
      JOURNAL = {Sensors},
      VOLUME = {23},
      YEAR = {2023},
      NUMBER = {9},
      ARTICLE-NUMBER = {4242},
      PubMedID = {37177446},
      ISSN = {1424-8220}
}
```
