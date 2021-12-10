# Transfer-Learning-on-CIFAR-10-dataset-using-pytorch
Transfer Learning on CIFAR-10 dataset using pytorch and pretrained Alex-Net
– Download the CIFAR10 Train and Test Datasets (you need to choose an appropriate
transform!);
– Take the first 10000 elements in the Train Dataset and the 2000 elements in the
Test Dataset, and make DataLoaders over them;
– Load the AlexNet network, change the Classifier part to the following architecture:
* Linear Layer with 128 outputs, with ReLU AF;
* Dropout Layer with rate 0.5;
* Linear Output Layer to Classify CIFAR10 Images;
* LogSoftMax AF at the Output Layer;
– Take Negative Log-Likelihood Loss;
– Take Adam Optimizer with Learning Rate 0.001;
– Train on a GPU with 5 epochs, only newly created layers parameters (weights/biases);
– Calculate Test Accuracy of the obtained model.
