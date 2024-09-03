# CNN_Breast_Cancer
A CNN model to classify breast ultrasound images into benign, normal and malignant cases. 

The CNN model consists of 4 convolution layers, which use the relu activation function and kernel size of (5,5). The 4 max pooling layers have pool size of (2,2). There is also 1 fully connected dense layer with 1024 units with relu activation, 3 dropout layers with a rate of 0.5. Lastly, an output layer with 3 units, one for each class, with the softmax activation function. To compile the model, I used the Adam optimizer and the categorical cross-entropy loss function. 

