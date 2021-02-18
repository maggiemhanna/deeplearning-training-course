# Deep Learning Training

The objective of this training is to allow you to grasp the essential concepts that help you get started with Deep Learning.
This training covers the vast majority of ideas and concepts that you should encounter when solving a deep learning problem.
The main framework used in this training is Tensorflow 2.

Please follow the order of folders and files the way they are sorted and numbered.

The package versions used in this training have been freezed to requirements.txt

Here is the outline of the training:

* Introduction to Deep Learning 
    * What is AI, Machine Learning, and Deep Learning
    * Components of Machine Learning
        * Data
        * Features
        * Algorithms
    * Defining Machine Learning Type
        * Supervised Learning
        * Unsupervised Learning
    * ML Model Representation 
        * Simple linear regression
            * Model Representation
            * Model Cost Function
        * Multi variate linear regression
            * Model Representation
        * Logistic Regression
            * Model Representation: Sigmoid activation function
            * Cost function: Cross Entropy
            * Multi-output logistic regression
                * One-vs-All
                * SoftMax Logistic Regression
    * Model Optimization
        * OLS
        * Gradient Descent
            
* Deep Feedforward Networks 
    * Why is Deep Learning Taking off
    * The Neural Network
        * Biological Neuron
        * The perceptron
        * Multi-layer perceptron
    * Neural Network Representation
    * Activation Functions
        * Activation Functions in Tensorflow
    * Output Layers for Regression & Classification
        * Regression: linear activation
        * Binary Classification: Sigmoid or tanh activation
        * Multiclass classificaiton: softmax activation
    * Cost Functions for Regression & Classification
        * Cost functions in Tensorflow
    * Gradient Descent for Neural Networks
        * Forward & Backpropagation
    * Applications: 
        * Implementing Deep Feedforward Networks with TensorFlow & Keras
        * Options to load data to TF Keras
            * Numpy array
            * Tf Dataset
        
* Practical Aspects Deep Learning 
    * Data Splitting
    * Bias / Variance Diagnosis & Correction
        * Plot history log with tfdocs
        * Tensorboard
        * Notebook: Overfitting and Underfitting
    * Regularization
        * L1/L2 
        * Dropout regularization
    * Improving Neural Networks
        * Input Normalization
        * Batch Normalization
        * Vanishing / exploding gradients
        * Weight Initialization
    * Optimization Algorithms
        * Mini-batch gradient descent
        * Gradient Descent with Momentum
        * RMSprop
        * Adam optimization
        * Learning rate decay
    * Hyperparameter Tuning
        * Grid Search, Random Search, Bayesian Optimisation, Hyperband
        * Options to do HT with Tensorflow
            * Keras Tuner 
            * Hparams
    * Feature Engineering 
        * Tf keras processing layers
        * Tf Feature Columns
        
* Convolutional Neural Networks 
    * CNNs foundations
        * Convolutions
        * Pooling
        * Fully Connected
    * Popular CNNs architectures:
        * LeNet
        * AlexNet
        * ResNets
        * Inception Networks
        * MobileNet
    * Data Augmentation
        * ImageDataGenerators
        * Keras preprocessing layers
        * Tf.image
    * Embeddings
    * Transfer Learning
    * Object Detection
        * Image Classification
        * Classification & Localization
        * Landmark Detection
        * YOLO Algorithm
    * Face Recognition
        * One Shot Learning 
        * Siamese Network 
        * Triple Loss
    * Use Case: Implementing Image Classification with TensorFlow & Keras
    
* Sequence Models 
    * Recurrent Neural Networks
    * Bidirectional RNNs
    * Encoder-Decoder Sequence-to-Sequence Architectures
    * Gated Recurrent Unit (GRU)
    * Long Short Term Memory (LSTM)
    * Natural Language Processing & Word Embeddings
    * Sentiment Classification
    * Implementation with TensorFlow & Keras
    * Embeddings
        * Pretrained embeddings
            * Word2vec