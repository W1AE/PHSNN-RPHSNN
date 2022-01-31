# Progressive Learning Model for Big Data Analysis Using Subnetwork and Moore-Penrose Inverse
## Abstract:

The multilayer Moore-Penrose inverse-based representation learning algorithms play an important role in image classification and big data analysis. However, these algorithms have several limitations such as large number of hyper-parameters and ineffectiveness of feature encoding. In this paper, we developed two representation learning algorithms using the Moore-Penrose inverse strategy to solve these two limitations. Firstly, a progressive learning method called P-HSNN is developed that can gradually learn the representations of the latent space. Here, the hidden layer representation is gradually learned by adding new subnet nodes and subspaces. Following that, a robust learning algorithm named RP-HSNN is proposed to learn the more discriminative features. Specifically, the manifold regularization is used to project the raw data to the subspace. Experimental result on different application domains verified the effectiveness of the proposed models. Here, experiments on image classification and other real-world application domains with varying number of training samples show that the proposed feature representation network gets stronger testing performance compared with other multilayer one-class classification  frameworks.


## Contributions:
* I. Architecture side - Two novel analytic learning algorithms called P-HSNN and RP-HSNN are proposed. Specifically, i) to enhance the discriminitively of the latent space features, the manifold regularization strategy is used. ii) the global-level representations of input pattern are generated through the proposed strategy, and iii) the latent space is genertated through the concatenation of the subnet-based subspace.

* II. Application side - The key contribution of this paper in terms of its application is the usage of P-HSNN and RP-HSNN, which harnesses high-level abstract features to handle large-scale datasets with more than 500 K samples. Furthermore, the cross-domain validations verify the effectiveness of the proposed methods. 


## Learning Structure:

<img src="https://github.com/1027051515/PHSNN-RPHSNN/blob/main/graph.png" width="1050" height="430" />

## Related Work:

[1] Zhang, W. (2022). Progressive Learning Model for Big Data Analysis Using Subnetwork and Moore-Penrose Inverse. IEEE Transactions on Cybernetics.

### Caltech-101 (Visual Image Classification Domain)
* Caltech-101 dataset: [Caltech-101 DATASET](http://yann.lecun.com/exdb/mnist/)
* Caltech-101 features: [Caltech-101 (GoogLe Drive)](https://drive.google.com/file/d/1kWEMoIbtR8TKJq0X8btXrFqSetzOyHWH/view?usp=sharing) or [Caltech-101 (GitHub)](https://github.com/W1AE/OCC/blob/main/M_2.mat)
* Source code for Caltech-101: [Caltech-101](https://github.com/W1AE/OCC/blob/main/Demo_MNIST.zip)

### Misinformation detection (Extended Domain)
* Misinformation dataset (Data collected from three major news agencies): [RUMOR DATASET](https://github.com/1027051515/PHSNN-RPHSNN/blob/main/BL.csv)

### Text-pattern Categorization (Extended Domain)
* Text-pattern dataset (Data collected from three major news agencies): [Text-pattern DATASET](https://github.com/W1AE/OCC/blob/main/BL.csv)

## Dependancies
* Matlab version 2020a,
* A workstation with a 256GB memory and an E5-2650 processor.

## Reproduce the Experimental Results

Run script "Coding_PHSNN.m" for original P-HSNN algorithm, run script "Coding_MCOCSNN.m" for the improved RP-HSNN algorithm.

#The code is released in content-obscured version (p files). After acceptance of the manuscript (if decided so), the source code will be made public.
