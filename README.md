**Cheetah Lion Classification**

This project implements a machine learning model to classify images of animals into two categories: cheetah and lion. The model is trained on a dataset of labeled images, and it uses convolutional neural networks (CNNs) to extract features and make predictions.

**Dataset**

The dataset used for this project is the "Cheetah vs Lion" dataset from Kaggle (https://www.kaggle.com/datasets/mikoajfish99/lions-or-cheetahs-image-classification)). It consists of 100 images of cheetahs and 100 images of lions, however, some of the images provided could be considered as junk images.

**Model**

ResNet18 is a relatively small version of the ResNet architecture, with only 18 layers. It consists of several stages, each of which contains a number of residual blocks. The residual block is the key innovation of the ResNet architecture, which allows the network to be much deeper than previous architectures without suffering from the problem of vanishing gradients.

In a residual block, the input is passed through two or more convolutional layers, and then added to the output of the block. This allows the network to learn residual mappings, which capture the difference between the input and the desired output. By stacking many residual blocks together, the network can learn very deep representations of the input data.

ResNet18 also uses other techniques to improve performance, such as batch normalization, ReLU activation functions, and max pooling. The architecture has been widely used for image classification tasks and has achieved state-of-the-art results on several benchmark datasets, including ImageNet.

**Credits**

This project was created by Stanford Renald Rodrigues as part of my research into finding better techniques for classification. The model architecture and training code were adapted from [source], and the "Cheetah vs Lion" dataset was downloaded from Kaggle (https://www.kaggle.com/datasets/mikoajfish99/lions-or-cheetahs-image-classification)).
