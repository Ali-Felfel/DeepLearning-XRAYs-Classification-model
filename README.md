# DeepLearning
CNN Classification model

The goal or task of this project is to use Convolutional Neural Networks on chest x-ray images to
determine and distinguish normal healthy patients from those with pneumonia. However,
successfully training CNNs requires a large amount of data. The Chest X-Ray Images dataset
that was used for this project only contains 5,856 images. This was not enough to generalize
the network effectively. For this reason a data augmentation technique was needed in order to
improve the generalizability of the neural network. There are four approaches for this image
classification. First a simple Convolutional Neural Network (CNN) was applied to the existing
data in the dataset. Second, we attempt to optimize the CNN through parameters.Third, deep
convolutional generative adversarial networks (DCGANs) were used in an attempt to improve
the training of CNNs by artiffitialy generating new data. And lastly, the newly generated images
were applied again for all six CNN models and used for original test data prediction.
