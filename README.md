# Semi-supervised Manifold Regularization via Subnetwork-based Representation Learning Model

## Abstract:
High dimensional data classification with very limited labeled training data is a challenging task in the area of data mining. Manifold regularization strategies are widely used in processing semi-supervised classification. However, the state-of-the-art manifold regularization structures can only recognize the patterns directly, without any process on representation learning and feature coding.
Therefore, current manifold regularization structure cannot work well on complex semi-supervised datasets. In this paper, we propose a novel semi-supervised algorithm SS-MSNN that use feature representation structures to refine and reinforce the hidden space features. The advantages of this structure are: 1) We introduce a semi-supervised structure with new network connection topology. 2) We provide a novel learning fashion. The hidden space features are generated iteratively. In each iteration, a subnetwork is included. 3) The proposed SS-MSNN can be considered as an extension of SS-ELM. In other words, the proposed SS-MSNN, SS-ELM, and ELM can actually be put into a unified framework. This provides new perspectives for understanding the mechanism of random feature mapping, which is the key concept in ELM theory. Empirical study on a wide range of data sets demonstrates that the proposed algorithms are competitive with the state-ofthe-art semi-supervised or unsupervised learning algorithms in terms of accuracy and efficiency.

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
