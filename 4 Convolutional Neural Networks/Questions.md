## Week 1 - Basics of ConvNets

1. What is Computer Vision in general?
2. What is elementary filter to detect vertical/horizontal edges? Write an example.
3. What is the output shape of a matrix (nxn) with filter (fxf) applied?
4. Padding? What problems does it solve?
5. What is the output shape of a matrix (nxn) with filter (fxf) and padding p applied?
6. What the padding value must be to output be the same as input? 
7. What is stride ? What is output size formula for a matrix (nxn) with filter (fxf), padding (p) and stride (s)
8. Tell an example to build one layer of a convolutional network:
![layer](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/4%20Convolutional%20Neural%20Networks/Week%201/images/FBC755B2-BDC0-4DB2-85AA-04305E16B42C.png)
9. If you have 10 filters 3x3x3, how many parameters will you have in one layer?
10. You can replace any number with ? and ask questions:
![CNN](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/4%20Convolutional%20Neural%20Networks/Week%201/images/82AEF6B0-78B2-4FB6-88BA-E05DC9AEA60E.png)
11. Pooling layer. What is the purpose of it? What are the hyperparameters of pooling ?
12. Demonstrate max pooling with the given matrix.
13. What is the average pooling?
14. Any questions you want on simple CNN example:
![CNN](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/4%20Convolutional%20Neural%20Networks/Week%201/images/606B6069-8235-4DD6-990A-F83DA218AB05.png)
![CNN](https://github.com/OzmundSedler/Deep-Learning-Coursera/blob/master/4%20Convolutional%20Neural%20Networks/Week%201/images/A80419E1-7DA7-4EE5-9909-22C2A7DCCB86.png)

**More from the quiz**
1. What do you think applying this filter to a grayscale image will do?

| 0 | 1 | -1 | 0  |
|---|---|----|----|
| 1 | 3 | -3 | -1 |
| 0 | 1 | -1 | 0  |

2. Suppose your input is a 300 by 300 color (RGB) image, and you are not using a convolutional network. If the first hidden layer has 100 neurons, each one fully connected to the input, how many parameters does this hidden layer have (including the bias parameters)?
3. Suppose your input is a 300 by 300 color (RGB) image, and you use a convolutional layer with 100 filters that are each 5x5. How many parameters does this hidden layer have (including the bias parameters)?
4. You have an input volume that is 63x63x16, and convolve it with 32 filters that are each 7x7, using a stride of 2 and no padding. What is the output volume?
5. You have an input volume that is 15x15x8, and pad it using “pad=2.” What is the dimension of the resulting volume (after padding)?
6. You have an input volume that is 63x63x16, and convolve it with 32 filters that are each 7x7, and stride of 1. You want to use a “same” convolution. What is the padding?
7. You have an input volume that is 32x32x16, and apply max pooling with a stride of 2 and a filter size of 2. What is the output volume?

## Week 2 - Deep convolutional models

1. Residual NN. What is it? What is the idea behind it?  
2. ResNet block - Describe it, write the activation function. Explain.
3. Name the pros and cons of skip-connection.
4. Inception NN. What is it? What is the idea behind it?
5. Describe typical single inception block.
6. 1x1 Convolutions and its purpose. Suppose you have an input volume of dimension 64x64x16. How many parameters would a single 1x1 convolutional filter have (including the bias)?
7. What changes in nH, nW and nC do you typically see as you move to deeper layers in a ConvNet?
8. What is the typical order of blocks in a ConvNet?

## Week 3 - Object detection

1. What are localization and detection?
2. What are Net outputs for simple classification with localization (3 classes for example)?
3. What is landmark detection? How does it work?
4. What is sliding window detection? How does it work?
5. Convolution implementation of sliding windows. How does it work?
6. YOLO algorithm. How does it work?
7. What is Intersection Over Union (IoU)? What is its purpose?
8. What is Non-max suppression? Describe how does it work.
9. What is Anchor Boxes? Describe the idea and how it works.
10. What is R-CNN
11. Suppose you are applying a sliding windows classifier (non-convolutional implementation). Increasing the stride would tend to increase accuracy, but decrease computational cost. Is it True?
12. In the YOLO algorithm, at training time, only one cell ---the one containing the center/midpoint of an object--- is responsible for detecting this object. Is it True?
13. Suppose you are using YOLO on a 19x19 grid, on a detection problem with 20 classes, and with 5 anchor boxes. During training, for each image you will need to construct an output volume y as the target value for the neural network; this corresponds to the last layer of the neural network. (y may include some “?”, or “don’t cares”). What is the dimension of this output volume?

## Week 4 - Face recognition & Neural style transfer

1. What is Face recognition?
2. What is One Shot Learning? 
3. Triplet Loss - how does it work? What is a formula for triplet loss? How do you suppose to choose triplets? 
4. How does learning the similarity function happens? 
5. What is neural style transfer? 
6. What a deep ConvNets are actually learning in each layer? 
7. The cost function for the Neural Style Transfer. Content Cost Function. Style Cost function.
8. Face verification requires comparing a new picture against one person’s face, whereas face recognition requires comparing a new picture against K person’s faces.
9. In order to train the parameters of a face recognition system, it would be reasonable to use a training set comprising 100,000 pictures of 100,000 different persons. Is it true ?
10. You train a ConvNet on a dataset with 100 different classes. You wonder if you can find a hidden unit which responds strongly to pictures of cats. (I.e., a neuron so that, of all the input/training images that strongly activate that neuron, the majority are cat pictures.) You are more likely to find this unit in layer 4 of the network than in layer 1. Is it true ?
11. Neural style transfer is trained as a supervised learning task in which the goal is to input two images (x), and train a network to output a new, synthesized image (y). Is it true ?
12. In the deeper layers of a ConvNet, each channel corresponds to a different feature detector. The style matrix G[l] measures the degree to which the activations of different feature detectors in layer l vary (or correlate) together with each other. Is it true ?
13. In neural style transfer, what is updated in each iteration of the optimization algorithm?
