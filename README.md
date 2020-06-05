# Semi-supervised Manifold Regularization via Subnetwork-based Representation Learning Model

## Abstract:
Semi-supervised classification (SSC) with very limited labeled training samples is a challenging task in the area of data mining. Manifold regularization (MR) is a widely used technique in tackling SSC task. However, the existing MR algorithms focus on fully-connected fashion, models with local connections have not attracted much research attention. In this paper, a new semi-supervised multilayer subnet-based neural network termed SS-MSNN is introduced. The key contributions of this paper are as follows: 1) A novel MR model with partially-connected network topology diagram is introduced. The subnetwork structure is utilized to iteratively enrich the latent space representations. 2) A single framework training process in order to learn the discriminative encoding is provided. Similar to end-to-end learning, SS-MSNN optimizes parameters by considering the input raw images and output targets directly, accepting input from one end and producing output at the other end. 3) The proposed SS-MSNN is successfully utilized in real-world radar signal domain, which provides a new perspective for handling practical vessel target localization task. Experiments on semi-supervised classification and radar signal processing domains show that SS-MSNN achieves superior performance among the state-of-the-art comparison algorithms on different datasets, takes on fast inference speed and better generalization ability.

## Contributions:
* 1) A manifold regularization framework named SS-MSNN with novel connection fashion is introduced. In particular, the abovementioned subnetwork is partially-connected instead of fully connected to its former layer and latter layer. Also, the learnt hidden space features are gradually learnt through the add of subnetworks. 

* 2) In this paper, a one-shoot learning algorithm is provided instead of stacking separate learning blocks. We consider that it is better for us to classifier and categorize the patterns through the combination of feature representation and final pattern recognition. Furthermore, we can learn the global-level representations. 

* 3) Comparison experiments ranging from semi-supervised classification and radar object recognition showed that the proposed SS-MSNN provides superior performance among other state-of-the-art comparison frameworks. 

## Learning Structure:

<img src="https://github.com/wandongzhang/Wi-HSNN/blob/master/2.jpg" width="550" height="430" />

<img src="https://github.com/wandongzhang/Wi-HSNN/blob/master/1.jpg" width="1200" height="400" />

## Downloads:
### Scene-15
* Fine-tuned ResNet-50 features: [Res50_S15](https://drive.google.com/open?id=1Jb_xdmA9StQLUme3LG_e3_EjlNIM3hiH)
* Fine-tuned InceptionNet-v3 features: [Incv3_S15](https://drive.google.com/open?id=1ku7huEzJ8I99qYKT5gtCG803puMz9kxe)
* Source code for Scene-15: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-101
* Caltech-101 dataset: [Caltech-101](http://www.vision.caltech.edu/Image_Datasets/Caltech101/#Download)
* Fine-tuned ResNet-50 features: [Res50_C101](https://drive.google.com/open?id=1F5BUPCQkzR1OmTlx2aID-E-Is6PrWHRZ)
* Fine-tuned InceptionNet-v3 features: [Incv3_C101](https://drive.google.com/open?id=1pFeL9kC8vs9ljmB4JYOxTznSj0MxM6DF)
* Source code for Caltech-101: The file will be made public after acceptance of the manuscript (if decided so).
### Caltech-256
* Caltech-256 dataset: [Caltech-256](http://www.vision.caltech.edu/Image_Datasets/Caltech256/)
* Fine-tuned ResNet-50 features: [Res50_C256](https://drive.google.com/open?id=104hhcvC20s4sp0J7TYRRM6VK51a6d83v)
* Fine-tuned InceptionNet-v3 features: [Incv3_C256](https://drive.google.com/open?id=1XIHncWSHRH97TDtxCj2-QvR2KjubMXNh)
* Source code for Caltech-256: The file will be made public after acceptance of the manuscript (if decided so).
