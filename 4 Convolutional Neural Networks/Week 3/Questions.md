## Questions

**Deep convolutional models**

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
