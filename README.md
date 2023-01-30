# Dogs-and-cats
CNN binary classification and explanation
This project is about basic convolutional neural networks which helps to classify between dogs and cats. for this CNN i used dogs and cats dataset and which is 
already labeled dataset.
for this python program i used Imagedatagenerator class to rescale the image size and then flow_from_directory to fetch the dataset from directory and initialize as 
a training set.
neural network is divided into
1. Convolution layer : conv2D class helps to add this layer in neural network and define kernel or filter size.
2. Pooling : down-sampling operation that reduce the dimensionality of feature map.
3. Flattening : helps to convert 2D array from pooled feature map into single long continuous linear vector.
4. fully connected layer : dense function used to define activation function and units( for multiclass more than 1 units and for binary class units = 1)
then compiler functions helps to define optimizer and loss ( for binary classification loss='binary_crossentropy' and more than 2 categorical classification 
loss='categorical_crossentropy')
