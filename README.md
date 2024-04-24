# Object-Detection-using-CNN
Convolutional neural network (CNN) model that perform object detection using CIFAR-10 dataset
# Architectur
The model has 6 convolution layers 2 of them with 16 filters, 2 of them with 32 filters, and the last two with 64 filters. The activation function of all of the convolution layers is the Rectified function (ReLU) function. I use ReLU as an activation function because it proves its efficiency since its performance is better than the other functions. All convolution layers are used to extract the input image feature. The model also has 2 max pooling layers used to reduce the dimensions of the output volume. The last two layers are the flattened layer which is used to convert the matrix to vector, and the dense layer with softmax as an activation function which is used to classify the input into one of the ten classes.

The accuracy of last epoch was 0.8535 
