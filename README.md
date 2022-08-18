# Kmnist_Project
KMNIST Classification Problem using Multi-Layer Perceptron (MLPs) and Convolutional Neural Networks (CNNs)

This work is presented as a project for EEL6814 – Deep Learning Course. Over the last few decades, deep neural networks have proved very powerful in handling big data. In pattern recognition, particularly image problems, deep learning’s performance surpasses classical machine learning in accuracy. The Multilayer Perceptron (MLP) and the
Convolutional Neural Network (CNN) are two of the most popular deep learning architectures for classification. We present the two networks’ performance to classify the Japanese KMNIST data set. In this report, we test the performance of different MLP and CNN architectures on the data set. We further tune hyperparameters and investigate how different parameters affect the classification efficiency.

## Results
CNN Train and test results
![result1](/data/Picture1.png)

Result (includes Cnn, Different models, Different Optimizers)
![result2](/data/Picture2.png)

## Dataset
- Kuzushiji-MNIST is a drop-in replacement for the MNIST dataset (28x28 grayscale, 70,000 images), provided in the original MNIST format as well as a NumPy format. Since MNIST restricts us to 10 classes, we chose one character to represent each of the 10 rows of Hiragana when creating Kuzushiji-MNIST
- Paper: [Deep Learning for Classical Japanese Literature](https://arxiv.org/pdf/1812.01718.pdf)
- Data: [The KMNIST dataset](http://codh.rois.ac.jp/kmnist/index.html.en)
