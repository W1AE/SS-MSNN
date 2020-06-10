# Semi-supervised Manifold Regularization via Subnetwork-based Representation Learning Model

## Abstract:
High dimensional data classification with very limited labeled training data is a challenging task in the area of data mining. Manifold regularization strategies are widely used in processing semi-supervised classification. However, the state-of-the-art manifold regularization structures can only recognize the patterns directly, without any process on representation learning and feature coding.
Therefore, current manifold regularization structure cannot work well on complex semi-supervised datasets. In this paper, we propose a novel semi-supervised algorithm SS-MSNN that use feature representation structures to refine and reinforce the hidden space features. The advantages of this structure are: 1) We introduce a semi-supervised structure with new network connection topology. 2) We provide a novel learning fashion. The hidden space features are generated iteratively. In each iteration, a subnetwork is included. 3) The proposed SS-MSNN can be considered as an extension of SS-ELM. In other words, the proposed SS-MSNN, SS-ELM, and ELM can actually be put into a unified framework. This provides new perspectives for understanding the mechanism of random feature mapping, which is the key concept in ELM theory. Empirical study on a wide range of data sets demonstrates that the proposed algorithms are competitive with the state-ofthe-art semi-supervised or unsupervised learning algorithms in terms of accuracy and efficiency.

## Contributions:
* 1) A manifold regularization framework named SS-MSNN with novel connection fashion is introduced. In particular, the abovementioned subnetwork is partially-connected instead of fully connected to its former layer and latter layer. Also, the learnt hidden space features are gradually learnt through the add of subnetworks. 

* 2) In this paper, a one-shoot learning algorithm is provided instead of stacking separate learning blocks. We consider that it is better for us to classifier and categorize the patterns through the combination of feature representation and final pattern recognition. Furthermore, we can learn the global-level representations. 

* 3) Comparison experiments ranging from semi-supervised classification and radar object recognition showed that the proposed SS-MSNN provides superior performance among other state-of-the-art comparison frameworks. 

## Learning Structure:

<img src="https://github.com/wandongzhang/SS-MSNN/blob/master/1.png" width="1200" height="430" />

<img src="https://github.com/wandongzhang/SS-MSNN/blob/master/2.png" width="1200" height="400" />

## Downloads:
### Semi-Supervised Classification
### G50c
* Dataset: [G50c](https://drive.google.com/open?id=1BHjJ1TBgqHVYOs4Ar7MNjUNcba8a79hV)
* Source code for G50c: The file will be made public after acceptance of the manuscript (if decided so).

### Coil-20
* Dataset: [Coil-20](https://drive.google.com/open?id=1PaQdvhdfm19v699huslKt1MS5zSurZsd)
* Source code for Coil-20: The file will be made public after acceptance of the manuscript (if decided so).
### Text Classification
### WeaRe
* Dataset: [WeaRe](https://drive.google.com/open?id=1PaQdvhdfm19v699huslKt1MS5zSurZsd)
* Source code for Wea-Re: The file will be made public after acceptance of the manuscript (if decided so).

