# DCGAN
This is an abstract implementation of a DCGAN architecture proposed in [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks). The model is developed in pytorch and trained on CelebA face dataset.

## Prerequisites
The architecture has been implemented using the following:
- Python 3.5
- Torchvision
- Tensorflow 1.7.0
- Tensorboard

Tensorflow and Tensorboard are used for visualization and monitoring purposes, thus they are not mandatory.

## Running the code
To start training the dcgan model use:
```
python main.py --dataPath /path/to/celebA
```

The ```logger.py``` file is used to create and update the model's instance for Tensorboard. To monitor the training process use:
```
tensorboard --logdir='./logs' --port 6006
```
and use your browser to access the localhost at the specified port.

## Acknowledgement
This work is based on the PyTorch examples. The Tensorboard support is provided from [yunjey](https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/04-utils/tensorboard).


