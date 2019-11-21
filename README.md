# EIP4

## Assignment for Week 1

## Accuracy Score - (0.9912)

### Convolution:

       1. Convolution is the representation of a function that is produced by combining two functions.
       2. Convolution in images work by extracting pixel information 
       from two or more pixel and producing third pixel information, 
       the input function can be of different sizes. (Eg. 1x1, 3x3, 5x5, 7x7)


### Filters/Kernels:
        
       1. These are also called feature extractor, conv matrices.
       2. Kernels are represented as 2D array of matrices and these kernels help images to be altered 
    by multiplying the colours of the image and the matrix that is given as input.
       3. These kernels determine the relevant features and combines them as it moves through each layers to get the output
       4. For example : Consider we have 4x4 image and to this we apply 3x3 kernel by which it convolves and 
    extracts relevant features and passes it to top layer which is 2x2, relevant features in the sense,
    the method that we want to use such as edge detector, line detector, blurring, sharpening etc.
    
### Epochs:

       1. Epochs represent the number of iterations that you want your model to trained for.
       2. We must use epochs for training our model at optimum rate,
       as it can also lead to overfitting, therefore reducing our model's accuracy.
       3. It goes through your dataset every time according to your epochs.

### 1x1 Convolution:
       
       1. 1x1 Convolutions are mostly used to reduce the number of channels.
       2. It is the least convolution that is possible, which is 
       less expensive and also it is a slow process for large images.
       3. It combines the channels that are having contextual link to each other.
       
       
### 3x3 Convolution:
       
       1. It is the most commonly used convolutions over an image 
       as it more efficient and less expensive when compared to other filters.
       (5x5, 7x7)
       2. It convolves over 27 values and combines the relevent features and 
       produces 1 single channel.

### Activation Function:
       
       1. Activation function lets us decide whether a neuron should be activated or not.
       2. ReLu is considered as the best activation function, as it
       does not accomodate vanishing gradient problem(zero gradient).
       3. It is a mathematical function that decides whether the input is 
       relevent to model's prediction so that if it is relevent, it will be
       activated.
       
### Receptive Field:

       1. It is the part of the image that is visible from one filter.
       2. Receptive field is the output view of a convolution layer 
       when we are convolving on an image.
       
 
       
