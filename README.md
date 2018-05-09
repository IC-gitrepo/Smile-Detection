# Smile-Detection
Deep Neural Networks and Convolutional Neural Networks for distinguishing between smiling and non smiling faces. Dataset was taken from https://github.com/hromi/SMILEsmileD

Dependencies- Python v3.6.3, NumPy v1.14.0, TensorFlow v1.4.0, scikit-learn v0.19.1, matplotlib v2.1.0, OpenCV v3.3.1

Binary classification task; dataset consists of images with smiling faces and images with non smiling faces. DNNs and CNNs were trained to solve the problem, after reducing dimentionality of the images using Principle Component Analysis. Models were regularized by dropout, L1 and L2 regularization tehcniques. Class imbalance was dealt with by scaling logits of the network. 
