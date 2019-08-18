# Read-MNIST
A program on reading the MNIST data

Since the MNIST data is too large, I can only submit an RAR. The [MNIST_Data.rar](https://github.com/Gaiss/Read-MNIST/blob/master/MNIST_Data.rar) package consists of the following four files. You can also download them from the [Office Website](http://yann.lecun.com/exdb/mnist/).
* train-images.idx3-ubyte
> The 60000 images of the training sets. (Each 28*28 in size)

* train-labels.idx1-ubyte
> The 60000 labels of the training sets. (Each is a integer values from 0~9)

* t10k-images.idx3-ubyte
> The 10000 images of the testing sets. (Each 28*28 in size)

* t10k-labels.idx1-ubyte
> The 10000 labels of the testing sets. (Each is a integer values from 0~9)

* [read_mnist.m](https://github.com/Gaiss/Read-MNIST/blob/master/read_mnist.m)
> The function written in MATLAB to read the above four files. Your will get four variables separately save the above four data sets in order(See the picture below). Each image is straightened and saved as a column vector and all the images in one data sets make up a large matrix. The vectors which save the labels are also two column vectors.
![](https://github.com/Gaiss/Read-MNIST/blob/master/Variables.png)

> The code has Chinese annotations.
