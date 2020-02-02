# An-Experimental-Study-of-Data-Transformation-for-Better-Learning-in-Neural-Networks

We know that different Artifical Neural Networks (ANNs) are good for different problems. For examlple, Convolutional Neural Networks (CNNs) are used frequently for image classification. Recurrent Neural Networks (RNNs) are better with text and time series analysis. 

Furthermore, it is imperative to know that ANNs heavily relies on the representation of data it receives as input.

In this project, we followed the hypothesis that CNNs are better than MLP 
when it comes to spatial feature learning and learning multiple features together.

We tried experimenting with the data representation and its effects on the performance
of these two ANNs. 
So we build two types of models:
1) MLP - Uses original data
2) CNN - uses image format (2-D array) data

With 4 different architectures:
1) MLP - Uses original data
2) CNN - uses image format (2-D array) data
3) Siamese MLP - Uses original data
4) Siamese CNN - uses image format (2-D array) data

More details on Siamese Netwroks can be found in the below research paper by G Koch et al. :
Siamese Netowrks [ G. Koch, R. Zemel, and R. Salakhutdinov. Siamese neural networks for one-shot image
recognition. In ICML deep learning workshop, volume 2, 2015. ]

