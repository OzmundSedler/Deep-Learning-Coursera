## Questions

**Basics of ConvNets**

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

**From quiz**
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
