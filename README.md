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
       
 
# Assignment for Week 2


## Accuracy Score - (0.9941)


### Model Training

#### Params:
       Params = Total params: 14,060
       Trainable params: 13,848
       Non-trainable params: 212

#### Training:
       Train on 60000 samples, validate on 10000 samples
       Epoch 1/20

       Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
       60000/60000 [==============================] - 11s 181us/step - loss: 0.5167 - acc: 0.8569 - val_loss: 0.0952 - val_acc: 0.9801
       Epoch 2/20

       Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
       60000/60000 [==============================] - 6s 96us/step - loss: 0.2531 - acc: 0.9233 - val_loss: 0.0751 - val_acc: 0.9836
       Epoch 3/20

       Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
       60000/60000 [==============================] - 6s 97us/step - loss: 0.1954 - acc: 0.9413 - val_loss: 0.0424 - val_acc: 0.9907
       Epoch 4/20

       Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.1715 - acc: 0.9459 - val_loss: 0.0398 - val_acc: 0.9912
       Epoch 5/20

       Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
       60000/60000 [==============================] - 6s 97us/step - loss: 0.1516 - acc: 0.9500 - val_loss: 0.0343 - val_acc: 0.9907
       Epoch 6/20

       Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
       60000/60000 [==============================] - 6s 96us/step - loss: 0.1383 - acc: 0.9522 - val_loss: 0.0356 - val_acc: 0.9904
       Epoch 7/20

       Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.1306 - acc: 0.9514 - val_loss: 0.0273 - val_acc: 0.9922
       Epoch 8/20

       Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.1255 - acc: 0.9531 - val_loss: 0.0240 - val_acc: 0.9934
       Epoch 9/20

       Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.1187 - acc: 0.9539 - val_loss: 0.0251 - val_acc: 0.9937
       Epoch 10/20

       Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
       60000/60000 [==============================] - 6s 98us/step - loss: 0.1133 - acc: 0.9546 - val_loss: 0.0223 - val_acc: 0.9945
       Epoch 11/20

       Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
       60000/60000 [==============================] - 6s 98us/step - loss: 0.1102 - acc: 0.9558 - val_loss: 0.0247 - val_acc: 0.9933
       Epoch 12/20

       Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.1063 - acc: 0.9557 - val_loss: 0.0230 - val_acc: 0.9940
       Epoch 13/20

       Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.1024 - acc: 0.9567 - val_loss: 0.0234 - val_acc: 0.9937
       Epoch 14/20

       Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
       60000/60000 [==============================] - 6s 96us/step - loss: 0.1023 - acc: 0.9570 - val_loss: 0.0206 - val_acc: 0.9945
       Epoch 15/20

       Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.0975 - acc: 0.9576 - val_loss: 0.0198 - val_acc: 0.9941
       Epoch 16/20

       Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
       60000/60000 [==============================] - 6s 96us/step - loss: 0.0997 - acc: 0.9560 - val_loss: 0.0277 - val_acc: 0.9922
       Epoch 17/20

       Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
       60000/60000 [==============================] - 6s 96us/step - loss: 0.0972 - acc: 0.9568 - val_loss: 0.0224 - val_acc: 0.9944
       Epoch 18/20

       Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.0937 - acc: 0.9580 - val_loss: 0.0199 - val_acc: 0.9944
       Epoch 19/20

       Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
       60000/60000 [==============================] - 6s 95us/step - loss: 0.0950 - acc: 0.9567 - val_loss: 0.0215 - val_acc: 0.9947
       Epoch 20/20

       Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
       60000/60000 [==============================] - 6s 97us/step - loss: 0.0901 - acc: 0.9581 - val_loss: 0.0200 - val_acc: 0.9941
       
       
#### Evaluation:
       [0.020006473675835877, 0.9941]
       
#### Steps:
       Reduced the size of params to less than 15k.
       
