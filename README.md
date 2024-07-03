# CNN-Feature-Extraction

We usually use a classic CNN as a feature extractor, since the classic CNN with the parameters pre-trained under ImageNet is available publicly. Given a user provided image, we can extract a feature from some layer in the classic CNN, and then, leverage the feature in different down stream applications.

 

1.Choose a dataset (FashionMNIST or CIFAR-10) and choose a classic CNN (VGG, Alex, ResNet…).

2.Choose a feature and extract this feature from each image in the dataset. You need to decide which feature (one or multiple channel in a conv layer, or the neurons in a FC layer, etc.)

3.Visualize the extracted features from all images using TSNE.

4.Quantify the intra-class and inter-class variances of your chosen feature.

Notes:
  - Images in FashionMNIST have only one channel, you can repeat the one channel into a 3-channel image.
  - You may need to resize the input images.
