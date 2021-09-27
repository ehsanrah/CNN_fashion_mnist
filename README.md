This repository implements a CNN to classify fashion articles from the Fashion-MNIST dataset according to the
following specifications:

• Input layer: a 28x28x1 image (the 1 specifies a grayscale image)
• First hidden layer: a 2-dimensional convolutional layer with 256 feature maps and a 3x3
filter size
• Second hidden layer: a 2x2 max-pooling layer
• Third hidden layer: a 2-dimensional convolutional layerwith 128 featuremaps and a 3x3
filter size
• Fourth hidden layer: a 2x2 max-pooling layer
• Fifth hidden layer: a layer to flatten the data
• Sixth hidden layer: A dense (fully-connected) layer consisting of 100 perceptrons
• Seventh hidden layer: A dense (fully-connected) layer consisting of 100 perceptrons
• Output layer (classification probabilites): 10 perceptrons
• Model is trained using 100 epochs.