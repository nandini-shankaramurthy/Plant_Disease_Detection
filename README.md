# Plant_Disease_Detection
Plant diseases are a major source of worry for farmers and the agricultural business. We hope to create a system that can assist in identifying and controlling these diseases more efficiently by leveraging the capabilities of deep learning.

We have used the following models:

DenseNet-121:
DenseNet, which stands for Densely Connected Convolutional Networks, is a CNN architecture developed by Facebook AI Research (FAIR) researchers in 2017. The 121 in DenseNet-121 refers to the number of network layers.
The concept of dense connections between layers is introduced by DenseNet. Unlike standard CNNs, in DenseNet, each layer takes input from all preceding levels. This dense connectivity enhances gradient flow and assists with feature reuse, making the network more parameter efficient.
Advantages: DenseNet outperforms typical CNN designs in terms of accuracy and parameter efficiency.
![image](https://github.com/nandini-shankaramurthy/Plant_Disease_Detection/assets/160645954/5cd2c95d-052d-403a-9076-984db236f6c5)



EfficientNet:
EfficientNet is a convolutional neural network family developed to address the trade-off between model size and accuracy. In 2019, Google researchers proposed it.
The basic idea of EfficientNet is to grow the network's depth, width, and resolution in a balanced fashion. Rather than modifying each dimension independently, the authors devised a compound scaling method that equally scales all dimensions by a given factor.
Advantages: When compared to other models, EfficientNet has demonstrated state-of-the-art performance on several picture classification tasks while being more computationally efficient.



Inception (Google Net):
Inception, commonly known as GoogLeNet, is a CNN architecture created by Google in 2014. It was one of the 2014 ImageNet Large Scale Visual Recognition Competition (ILSVRC) winners.
The use of "inception modules," which comprise of numerous convolutional filters of various sizes (1x1, 3x3, 5x5) and pooling processes, is the major breakthrough in Inception. These various filters capture characteristics at various scales, allowing the network to learn both fine-grained and coarse-grained features.
Advantages: Inception architecture is noted for its ability to successfully collect diverse features at multiple scales, resulting in increased performance.
![image](https://github.com/nandini-shankaramurthy/Plant_Disease_Detection/assets/160645954/a9771da1-1d31-4744-86e8-93b5645704d3)

